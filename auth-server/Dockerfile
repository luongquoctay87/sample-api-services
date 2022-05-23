FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/auth-server

COPY ${JAR_FILE} /opt/auth-server/auth-server-1.0-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/opt/auth-server/auth-server-1.0-SNAPSHOT.jar"]
