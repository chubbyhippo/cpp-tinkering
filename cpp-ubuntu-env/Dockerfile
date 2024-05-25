FROM ubuntu:22.04

RUN apt-get update
RUN DEBIAN_FRONTEND="noninteractive" apt-get upgrade -y
RUN apt-get install -y build-essential
RUN apt-get install -y gdb
RUN apt-get install -y clang
RUN apt-get install -y ninja-build
RUN apt-get install -y cmake
RUN apt-get install -y autoconf
RUN apt-get install -y automake
RUN apt-get install -y libtool
RUN apt-get install -y valgrind
RUN apt-get install -y locales-all
RUN apt-get install -y dos2unix
RUN apt-get install -y rsync
RUN apt-get install -y tar
RUN apt-get install -y python3
RUN apt-get autoremove -y
RUN apt-get clean
