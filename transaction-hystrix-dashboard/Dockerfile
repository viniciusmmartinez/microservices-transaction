FROM openjdk:jdk-11.0.8_10-alpine
VOLUME /tmp
ADD /target/transaction-hystrix-dashboard-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]