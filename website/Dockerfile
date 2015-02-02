FROM ubuntu:14.04
MAINTAINER great abel "greatabel1@126.com"
ENV REFRESH_AT 2015-02-02

RUN apt-get update
RUN apt-get -y -q install ngix

RUN mkdir -p /var/www/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/

EXPOSE 80
