FROM openjdk:17
EXPOSE 8761
ADD target/config-service.jar config-service.jar
ENTRYPOINT ["java","-jar","/config-service.jar"]