FROM openjdk:8
MAINTAINER elizabeth.a.weber@vanderbilt.edu
WORKDIR /app/jhipster-project
ADD ./jhipsterapp.war .
EXPOSE 8080

CMD java -jar jhipsterapp.war --spring.profiles.active=dev,swagger
