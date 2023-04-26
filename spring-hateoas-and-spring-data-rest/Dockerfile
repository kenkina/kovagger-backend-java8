# Based on https://spring.io/guides/topicals/spring-boot-docker/

FROM maven:3.9.1-eclipse-temurin-8-alpine
COPY target/*.jar app.jar

ENTRYPOINT ["java","-jar","/app.jar"]