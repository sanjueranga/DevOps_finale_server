FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/reservation-service-0.0.1-SNAPSHOT.jar reservation-service.jar
ENTRYPOINT ["java","-jar","/reservation-service.jar"]