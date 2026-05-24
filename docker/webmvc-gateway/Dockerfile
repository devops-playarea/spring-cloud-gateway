FROM eclipse-temurin:17-jre

WORKDIR /app

ARG APP_MODULE=gateway-webmvc-app
ARG JAR_FILE=${APP_MODULE}/target/app.jar

COPY ${JAR_FILE} app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "/app/app.jar"]
