FROM ubuntu:lastest AS build

RUN apt-get update
RUN apt-get install openjdk-17-jdk -y 

COPY . .

RUN apt-get iinstall maven -y
RUN mvn clean install 