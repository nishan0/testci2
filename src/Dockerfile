FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY target/*.jar gitTest-1.0-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/gitTest-1.0-SNAPSHOT"]
