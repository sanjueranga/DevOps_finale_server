FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar discovery-service.jar
ENTRYPOINT ["java","-jar","/discovery-service.jar"]