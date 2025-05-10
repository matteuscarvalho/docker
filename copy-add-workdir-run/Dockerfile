FROM ubuntu:18.04

WORKDIR /copy

COPY host-file .

WORKDIR /ADD

ADD add-files.tar.gz .
ADD https://www.docker.com/app/uploads/2023/08/logo-guide-logos-1.svg .

RUN apt-get update && apt-get install -y \
  net-tools \ 
  curl \
  nginx \
  && rm -rf /var/lib/apt/lists/*


# docker container run -it --name ubuntu-dockerfile ubuntu:cursor-docker-1.0