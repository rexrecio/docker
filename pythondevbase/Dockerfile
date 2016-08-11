FROM ubuntu:16.04
MAINTAINER Rex Recio <rexrecio@gmail.com>
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt install -y \
    git \
    python3-pip \
    vim
RUN pip3 install virtualenv
CMD /bin/bash
