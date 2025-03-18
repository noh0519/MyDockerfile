FROM ubuntu:24.04

RUN apt-get update
RUN apt-get install -y locales
RUN localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
RUN apt-get install -y net-tools

ENV LANG=en_US.utf8
