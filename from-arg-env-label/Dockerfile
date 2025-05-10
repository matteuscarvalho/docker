ARG TAG=latest

FROM alpine:$TAG

ARG CONTAINER_NAME_ARG

ENV CONTAINER_NAME_ENV=${CONTAINER_NAME_ARG:-"Container A"}

LABEL maintainer="Mateus Carvalho"

# $ docker image build -t alpine:cursor-docker-2.0 --build-arg TAG=3.13 --build-arg CONTAINER_NAME_ARG="Container B" .