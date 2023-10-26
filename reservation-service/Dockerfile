FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar reservation-service.jar
ENTRYPOINT ["java","-jar","/reservation-service.jar"]