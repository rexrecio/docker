FROM ubuntu:16.04
VOLUME /source
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt install -y \
    apt-utils \
    nodejs \
    nodejs-legacy \
    npm \
    python3-pip
RUN npm install -g blockchain-wallet-service \
    bip39 \
    es6-promise \
    isomorphic-fetch \
    sjcl \
    unorm
RUN pip3 install virtualenv
