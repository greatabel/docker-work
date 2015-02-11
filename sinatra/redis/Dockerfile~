FROM ubuntu:14.04
MAINTAINER greatabel "greatabel1@126.com"
ENV REFRESHED_AT 2015-02-04

RUN apt-get update
RUN apt-get -y install redis-server redis-tools

EXPOSE 6379

ENTRYPOINT ["/usr/bin/redis-server"]
CMD []
