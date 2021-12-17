FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} ConsultSprint-1.0.jar
ENTRYPOINT ["java","-jar","ConsultSprint-1.0.jar"]
