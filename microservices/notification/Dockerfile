FROM openjdk:17
EXPOSE 8084
ADD target/notification-0.0.1-SNAPSHOT.jar notification.jar
ENTRYPOINT ["java", "-jar", "notification.jar"]