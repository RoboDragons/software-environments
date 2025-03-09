FROM robocupssl/ubuntu-vnc:latest

USER root

RUN apt update \
    && apt install -y \
        #build-essential ruby libjpeg-dev protobuf-compiler make libgsl0-dev libprotobuf-dev libpng-dev freeglut3-dev
        build-essential ruby g++ g++-7 libfltk1.1-dev libjpeg-dev protobuf-compiler make libgsl-dev libprotobuf-dev libpng-dev freeglut3-dev net-tools clang-format

RUN apt update && apt install -y \
    ca-certificates \
    git \
    openssh-client \
    tmux \
    emacs \
    vim \
    iputils-ping \
    net-tools \
    dnsutils \
    # sudo

RUN echo "default    ALL=(ALL)   NOPASSWD:    ALL" >> /etc/sudoers

USER default