```shell
# jdk 11
sudo docker pull maven:3.8.6-openjdk-11
sudo docker run -it --rm --name my-maven-project -v "$(pwd)":/usr/src/mymaven -w /usr/src/mymaven maven:3.3-jdk-8 mvn clean install
docker run -it --rm -v "$PWD":/usr/src/mymaven -v "$HOME/.m2":/root/.m2 -v "$PWD/target:/usr/src/mymaven/target" -w /usr/src/mymaven maven mvn clean package

cd app/server
mvn clean package

cd docs
./install.sh

mongo
root
root
```

```shell
https://docs.appsmith.com/v/v1.2.1/troubleshooting-guide/deployment-errors
```