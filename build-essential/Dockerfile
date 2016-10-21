FROM ubuntu:latest

MAINTAINER liuzhiyi <liuzhiyi@gmail.com>

ENV DEBIAN_FRONTEND noninteractive

# Install dependencies
RUN apt-get -qq update && \
    apt-get -qqy install --no-install-recommends \
       build-essential \
       autotools-dev  \
       cmake  &&\
     rm -rf /var/lib/apt/lists/*
