FROM ubuntu:20.04
LABEL maintainer="Rafael Bernabeu"

# --- GLOBAL CONFIG ---
RUN sed 's/main$/main universe/' -i /etc/apt/sources.list
RUN apt-get update && apt-get upgrade -y

RUN apt-get install openjdk-11-jdk-headless maven -y

WORKDIR /opt/project