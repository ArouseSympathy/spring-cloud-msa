FROM openjdk:8-jdk-alpine
EXPOSE 54412
COPY build/libs/order-service-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]