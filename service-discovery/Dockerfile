# Use the official OpenJDK image as the base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the application's jar file into the container
COPY target/service-discovery-0.0.1-SNAPSHOT.jar /app/service-discovery-0.0.1-SNAPSHOT.jar

# Expose the port the application runs on
EXPOSE 8761

# Set the entry point to run the jar file
ENTRYPOINT ["java", "-jar", "/app/service-discovery-0.0.1-SNAPSHOT.jar"]
