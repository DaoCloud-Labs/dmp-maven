# maven
使用阿里的缓存

# Version
* JDK: OpenJDK-8
* Maven: 3.6.0

# Usage
docker run -it --rm --name my-maven-project -v "$PWD":/usr/src/mymaven -w /usr/src/mymaven grissomsh/maven:latest mvn package
