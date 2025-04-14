FROM openjdk:21-jdk-slim

ARG BUILD_LIB_DIR
ARG ARTIFACTORY_FILE

WORKDIR /app

COPY ${BUILD_LIB_DIR}/${ARTIFACTORY_FILE} /app/app.jar

EXPOSE 8080

CMD ["java", "-jar", "/app/app.jar"]
