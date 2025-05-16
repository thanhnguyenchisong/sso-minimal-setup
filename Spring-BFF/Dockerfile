#Should build your java image - which is match with your openjdk development
FROM eclipse-temurin:17

WORKDIR /app

COPY --chown=1001:0 target/spring-bff*.jar spring-bff.jar

EXPOSE 8080

ENTRYPOINT["java", "-jar", "spring-bff.jar"]

