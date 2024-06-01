# Use the official OpenJDK image as the base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the application's jar file into the container
COPY target/service2-0.0.1-SNAPSHOT.jar /app/service2-0.0.1-SNAPSHOT.jar

# Expose the port the application runs on
EXPOSE 9002

# Set the entry point to run the jar file
ENTRYPOINT ["java", "-jar", "/app/service2-0.0.1-SNAPSHOT.jar"]
