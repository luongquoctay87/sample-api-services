FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/hystrix-dashboard

COPY ${JAR_FILE} /opt/hystrix-dashboard/hystrix-dashboard-1.0-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","/opt/hystrix-dashboard/hystrix-dashboard-1.0-SNAPSHOT.jar"]
