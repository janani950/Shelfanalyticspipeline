FROM ubuntu:latest


RUN apt update
RUN apt install python3 -y

#WORKDIR /home/ckpl/Downloads/docker

COPY sample.py ./

CMD [ "python3", "./sample.py"]


