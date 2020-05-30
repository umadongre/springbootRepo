FROM openjdk:8
EXPOSE 8080
ADD target/springBoot-docker.jar springBoot-dockerImage.jar
ENTRYPOINT ["java", "-jar", "spring-boot-hello-world-example/springBoot-dockerImage.jar"]
