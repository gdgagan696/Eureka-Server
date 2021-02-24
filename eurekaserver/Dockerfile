FROM openjdk:8-jdk-alpine
LABEL maintainer="Gagan Dhand"
EXPOSE 8161
ADD ./target/eurekaserver-0.0.1-SNAPSHOT.jar /
ENTRYPOINT ["java","-jar","eurekaserver-0.0.1-SNAPSHOT.jar"]
