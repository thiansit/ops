FROM openjdk:21-jdk-slim
VOLUME /tmp
COPY target/user-service-1.0-SNAPSHOT.jar user-service.jar
ENTRYPOINT ["java", "-jar", "/user-service.jar"]
