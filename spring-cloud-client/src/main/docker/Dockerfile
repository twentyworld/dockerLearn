FROM openjdk:8-jdk-alpine
VOLUME /tmp
add dockerLearn-1.0-SNAPSHOT.jar SpringCloudClientApplication.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/SpringCloudClientApplication.jar"]



# FROM frolvlad/alpine-oraclejdk8:slim
# VOLUME /tmp
# ARG JAR_FILE
# ADD ${JAR_FILE} app.jar
# ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]