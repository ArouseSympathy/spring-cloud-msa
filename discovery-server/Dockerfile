FROM openjdk:8-jdk-alpine
EXPOSE 8761
COPY build/libs/discovery-server-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]