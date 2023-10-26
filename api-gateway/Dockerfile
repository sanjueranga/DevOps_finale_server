
FROM openjdk:11
WORKDIR /app
COPY target/api-gateway.jar /app/api-gateway.jar
EXPOSE 9004
CMD ["java", "-jar", "api-gateway.jar"]
