#Dockerfile contains all the commands with which
#Docker can build images reading the instructions.

FROM openjdk:11

ADD ./target/consumer-service-0.0.1-SNAPSHOT.jar /usr/src/consumer-service-0.0.1-SNAPSHOT.jar

WORKDIR usr/src

ENTRYPOINT ["java","-jar", "consumer-service-0.0.1-SNAPSHOT.jar"]