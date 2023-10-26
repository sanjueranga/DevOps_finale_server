FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar car-service.jar
ENTRYPOINT ["java","-jar","/car-service.jar"]