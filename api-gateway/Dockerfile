FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar api-gateway.jar
ENTRYPOINT ["java","-jar","/api-gateway.jar"]