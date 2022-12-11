FROM ubuntu:22.04

WORKDIR /workspace

RUN DEBIAN_FRONTEND=noninteractive && \
    apt-get update -y && \
    apt-get install -y \
    cmake make gcc g++ openssl \
    bison pkg-config build-essential \
    cmake wget curl libncurses5-dev libssl-dev \
    gdb gdbserver \
    clang-14 clangd-14 libclang-14-dev libclang-cpp14-dev

RUN DEBIAN_FRONTEND=noninteractive && \
    apt-get install -y \
    cmake-curses-gui ninja-build libtool \
    iputils-ping bsdmainutils iproute2 net-tools dstat htop

RUN DEBIAN_FRONTEND=noninteractive && \
    apt-get install -y \
    mysql-client
