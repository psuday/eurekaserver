FROM openjdk:8-jdk-alpine
RUN apk update && apk upgrade && apk add netcat-openbsd
RUN mkdir -p /usr/local/eurekaserver
ADD eurekaserver-1.0-snapshot.jar /usr/local/eurekaserver
CMD java -jar /usr/local/eurekaserver/eurekaserver-1.0-snapshot.jar 