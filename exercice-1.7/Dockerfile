FROM ubuntu:22.04

RUN apt update && apt upgrade

RUN apt install curl -y

WORKDIR /usr/scr/app/

COPY script.sh .

RUN chmod +x script.sh

CMD ./script.sh 