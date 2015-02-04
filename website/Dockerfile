FROM ubuntu:14.04
MAINTAINER greatabel "greatabel1@126.com"
ENV REFRESHED_AT 2015-02-04

RUN apt-get update
RUN apt-get -y -q install nginx

RUN mkdir -p /var/www/html/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/

EXPOSE 80
