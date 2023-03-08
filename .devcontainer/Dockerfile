FROM ubuntu:bionic

USER root

# install dependencies
RUN apt update && \
    apt -y upgrade && \
    apt install -y sudo gawk wget git diffstat unzip bash curl nano \
        flex bison bc texinfo gcc-multilib build-essential chrpath socat \
        libssl-dev libsdl1.2-dev xterm ncurses-dev lzop libelf-dev make && \
    apt install -y gcc binutils
