FROM ubuntu:18.04

ENV DEBCONF_NOWARNINGS yes

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    build-essential ruby g++ libfltk1.1-dev libjpeg-dev protobuf-compiler make libgsl0-dev libprotobuf-dev libpng-dev freeglut3-dev
