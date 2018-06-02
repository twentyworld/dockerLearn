FROM openjdk:8-jdk-alpine
VOLUME /tmp
add dockerLearn-1.0-SNAPSHOT.jar SpringCloudEurekaServerApplication.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/SpringCloudEurekaServerApplication.jar"]