FROM openjdk:22-jdk
WORKDIR /app
ADD target/*.jar app.jar
EXPOSE 8083
ENTRYPOINT ["java", "-jar", "app.jar"]