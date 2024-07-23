FROM ubuntu:latest

RUN useradd --user-group --uid 2000 minecraft

RUN apt -y update 

RUN apt -y upgrade

RUN apt -y install openjdk-21-jre-headless

USER minecraft

EXPOSE 25565/tcp 
