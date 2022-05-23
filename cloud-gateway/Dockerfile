FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/cloud-gateway

COPY ${JAR_FILE} /opt/cloud-gateway/cloud-gateway-1.0-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/opt/cloud-gateway/cloud-gateway-1.0-SNAPSHOT.jar"]
