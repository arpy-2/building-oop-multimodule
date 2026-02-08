ARG JAR_FILE
FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/${JAR_FILE} /app/app.jar
ENTRYPOINT ["java","-jar","/app/app.jar"]