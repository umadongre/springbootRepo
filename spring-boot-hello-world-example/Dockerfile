FROM openjdk:8
EXPOSE 8080
ADD target/springBoot-docker.jar springBoot-dockerImage.jar
ENTRYPOINT ["java", "-jar", "/springBoot-dockerImage.jar"]
