FROM ubuntu:latest
MAINTAINER Scotty B "businge.scott@andela.com"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
ADD . /todo
WORKDIR /todo
RUN pip install --upgrade pip
RUN pip install Flask pymongo
RUN pip freeze > requirements.txt
