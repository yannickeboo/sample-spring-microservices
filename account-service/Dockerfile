FROM  openjdk:8-jdk-alpine
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
COPY target/account-service.jar account-service.jar
ENTRYPOINT ["java", "-jar", "/account-service.jar"]
EXPOSE 2222
