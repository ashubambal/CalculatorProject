# Use the official OpenJDK 11 image as the base image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the built JAR file into the container
COPY target/calculator-java.jar .

# Specify the command to run the JAR file
CMD ["java", "-jar", "calculator-java.jar"]

