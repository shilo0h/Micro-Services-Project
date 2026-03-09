# Use an official OpenJDK 17 slim image
FROM eclipse-temurin:17-jdk
# Copy the built jar into the container
COPY target/*.jar app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "/app.jar"]