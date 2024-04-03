# Use the official OpenJDK 11 image as base
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /app

# Copy the Spring Boot application JAR file from the Jenkins workspace into the container
COPY target/springbootapp.jar /app/springbootapp.jar

# Expose the port your application listens on
EXPOSE 8080

# Specify the command to run your application
ENTRYPOINT ["java", "-jar", "springbootapp.jar"]
