# Use a base Java image
FROM openjdk:17-jdk-slim

# Set the working directory
WORKDIR /app

# Copy the jar file built by Maven into the image
COPY target/*.jar app.jar

# Expose port (Spring Boot default)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
