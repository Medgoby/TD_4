FROM alpine:3.15.0

LABEL version="1.0.0" maintainer="Mohamed BARRY" os="linux"

ENV CONTAINER_USER='BARRY'

#RUN echo $CONTAINER_USER > ./BARRY
RUN unset CONTAINER_USER
RUN adduser -S Barry
#CMD echo hello-alpine, je suis Mohamed et c est mon premier container depuis ma première image alpine

CMD echo "hello-alpine, I'm $CONTAINER_USER and this is a container for my first image”
