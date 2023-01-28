FROM openjdk:8-jdk-alpine
EXPOSE 8080
ADD target/*.jar springboot-docker.jar
ENTRYPOINT ["java","-jar","/springboot-docker.jar"]