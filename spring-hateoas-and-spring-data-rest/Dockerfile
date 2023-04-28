# Based on https://spring.io/guides/topicals/spring-boot-docker/

FROM eclipse-temurin:8u372-b07-jre-alpine

COPY target/*.jar app.jar

ENTRYPOINT ["java","-jar","/app.jar"]