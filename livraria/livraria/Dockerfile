
FROM openjdk:21-jdk-slim


WORKDIR /app


COPY target/livraria-0.0.1-SNAPSHOT.jar /app/livraria.jar


EXPOSE 8080


ENTRYPOINT ["java", "-jar", "livraria.jar"]
