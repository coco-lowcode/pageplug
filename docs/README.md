```shell
# jdk 11
sudo docker pull maven:3.8.6-openjdk-11
sudo docker run -it --rm --name my-maven-project -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven maven:3.3-jdk-8 mvn clean install
sudo docker run -it --rm -v "$PWD":/usr/src/mymaven -v "$HOME/.m2":/root/.m2 -v "$PWD/target:/usr/src/mymaven/target" -w /usr/src/mymaven maven mvn clean package

sudo docker run -it --rm -v "$HOME/.m2":/root/.m2 -v "$PWD:/pageplug" maven:3.8.6-openjdk-11 bash

cd app/server
mvn clean package

cd docs/appsmith

sudo docker-compose up -d
sudo docker-compose down

cd docs
./install.sh

mongo
root
root

http://49.232.6.131:8102/
admin@7otech.com
test2020
```

```shell
https://docs.appsmith.com/v/v1.2.1/troubleshooting-guide/deployment-errors
```