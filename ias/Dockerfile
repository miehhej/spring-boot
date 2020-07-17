FROM openjdk:8-jdk-alpine

ARG JAR_FILE=./spring-boot-sample-web-ui-2.1.16.BUILD-SNAPSHOT.jar

WORKDIR /opt/java_app

COPY ${JAR_FILE} ./app.jar

ENTRYPOINT ["java","-jar","app.jar", "--server.port=8080"]

#EXPOSE 8082
