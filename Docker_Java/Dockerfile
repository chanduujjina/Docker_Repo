# Use Eclipse Temurin JDK 17
FROM eclipse-temurin:17

WORKDIR /app

# Copy source file into container
COPY HelloDocker.java .

# Compile inside container
RUN javac HelloDocker.java

# Run program
CMD ["java", "HelloDocker"]