# Use official OpenJDK runtime as base image
FROM eclipse-temurin:17-jdk-jammy
# Set working directory inside container
WORKDIR /app
# Copy packaged JAR file from build target
COPY target/*.jar app.jar
# Expose application port
EXPOSE 8080
# Command to execute the application
ENTRYPOINT ["java", "-jar", "app.jar"]
