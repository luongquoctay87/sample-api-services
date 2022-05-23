FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/service-registry

COPY ${JAR_FILE} /opt/service-registry/service-registry-1.0-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/opt/service-registry/service-registry-1.0-SNAPSHOT.jar"]
