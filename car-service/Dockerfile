FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/car-service-0.0.1-SNAPSHOT.jar car-service.jar
ENTRYPOINT ["java","-jar","/car-service.jar"]