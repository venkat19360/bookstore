FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/bookStore-0.0.1-SNAPSHOT.jar /app/bookStore.jar

EXPOSE 1001

CMD ["java", "-jar", "bookStore.jar"]
