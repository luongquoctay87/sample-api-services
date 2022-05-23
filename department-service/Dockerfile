FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/department-service

COPY ${JAR_FILE} /opt/department-service/department-service-1.0-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/opt/department-service/department-service-1.0-SNAPSHOT.jar"]