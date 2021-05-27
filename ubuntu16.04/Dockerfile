FROM ubuntu:16.04

ENV DEBCONF_NOWARNINGS yes

RUN apt-get update \
    && apt-get install -y --no-install-recommend \
    ruby g++ libgsl0-dev libfltk1.1-dev libjpeg-dev libpng12-dev protobuf-compiler libprotobuf-dev make freeglut3-dev
