# syntax=docker/dockerfile:1
FROM shinyay/docker-mvn-jdk8:3.6.3
WORKDIR /code
COPY . .
RUN mvn install
RUN mvn clean compile
CMD [ "mvn", "spring-boot:run" ]