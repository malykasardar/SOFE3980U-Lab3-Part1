FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY target/BinaryCalculatorWebapp-1.0-SNAPSHOT.war /app.war
ENTRYPOINT ["java","-jar","/app.war"]
