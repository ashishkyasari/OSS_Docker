FROM ubuntu:16.04

RUN apt update

RUN apt install default-jdk -y

COPY . .

RUN javac Main.java

CMD [ "java","Main" ]