FROM openjdk:17
EXPOSE 8080
ADD target/springboot-demo-0.0.1-SNAPSHOT.jar kubernetes
ENTRYPOINT ["java", "-jar", "/springboot-demo-0.0.1-SNAPSHOT.jar"]