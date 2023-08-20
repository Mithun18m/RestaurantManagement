FROM openjdk:8
EXPOSE 8080
ADD target/OrderManagement-0.0.1-SNAPSHOT.jar order-docker.jar
ENTRYPOINT ["java","-jar","/order-docker.jar"]