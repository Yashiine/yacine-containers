FROM alpine:3.15.0

LABEL maintainer="yacine" os="alpine" distro="Alpine 3.15.0"

ENV CONTAINER_USER="yacine"

RUN adduser $CONTAINER_USER --disabled-password && mkdir "/home/yacine/receipts"

CMD echo "hello-alpine, I'm $CONTAINER_USER and this is a container from my first image"

