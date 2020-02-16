FROM openjdk:8-jdk-alpine
# Just for information to outside world
EXPOSE 8080
#ADD target/hello-world-rest-api.jar hello-world-rest-api.jar
# Create a generic docker file
ADD target/*.jar app.jar
ENTRYPOINT ["sh", "-c", "java -jar /app.jar"]