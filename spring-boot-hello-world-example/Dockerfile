FROM openjdk:8
EXPOSE 8080
ADD spring-boot-hello-world-example/target/springBoot-docker.jar springBoot-dockerImage.jar
ENTRYPOINT ["java", "-jar", "/springBoot-dockerImage.jar"]
