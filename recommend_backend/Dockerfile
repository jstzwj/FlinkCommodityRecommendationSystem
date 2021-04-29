# syntax=docker/dockerfile:1
FROM maven:3.8.1-jdk-8
WORKDIR /code
COPY . .
RUN mvn install
RUN mvn spring-boot:run