# Use the official Java runtime image for running the application
FROM openjdk:17-jdk

# Set the working directory
WORKDIR /app

# Copy the built jar file from the Maven build stage
COPY --from=0 target/SpringAPI-0.0.1-SNAPSHOT.jar /app/SpringAPI.jar

# Define the command to run the application
CMD ["java", "-jar", "SpringAPI.jar"]
