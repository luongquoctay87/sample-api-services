FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/cloud-config-server

COPY ${JAR_FILE} /opt/cloud-config-server/cloud-config-server-1.0-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/opt/cloud-config-server/cloud-config-server-1.0-SNAPSHOT.jar"]
