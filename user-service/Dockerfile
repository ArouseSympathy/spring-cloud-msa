FROM openjdk:8-jdk-alpine
EXPOSE 64412
COPY build/libs/user-service-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]