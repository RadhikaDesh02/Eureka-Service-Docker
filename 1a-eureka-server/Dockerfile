
FROM openjdk:17-jdk-alpine
EXPOSE 7000
COPY ./target/EurekaService.jar EurekaService.jar
ENTRYPOINT ["java","-jar","EurekaService.jar"]