FROM maven:3.8.3-openjdk-8 AS build
WORKDIR /home

ENV PORT 8080
EXPOSE 8080

COPY target/*.jar /home/app.jar

ENTRYPOINT exec java $JAVA_OPTS -jar app.jar
