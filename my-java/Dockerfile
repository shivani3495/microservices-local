# Use the official OpenJDK 11 base image
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /usr/app

# Copy the Java source code into the container
COPY . .

# Compile the Java source code
RUN javac my.java

# Expose port 8000
EXPOSE 8000

# Command to run the Java program
CMD ["java", "my"]