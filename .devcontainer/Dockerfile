FROM ubuntu:bionic

USER root

RUN apt update && \
    apt -y upgrade && \
    apt install -y gawk wget git diffstat unzip bash curl nano \
        flex bison texinfo gcc-multilib build-essential chrpath socat \
        libsdl1.2-dev xterm ncurses-dev lzop libelf-dev make && \
    apt install gcc binutils
