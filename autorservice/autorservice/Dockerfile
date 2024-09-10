
FROM openjdk:21-jdk-slim


WORKDIR /app


COPY target/autorservice-0.0.1-SNAPSHOT.jar /app/autorservice.jar


EXPOSE 8081


ENTRYPOINT ["java", "-jar", "autorservice.jar"]
