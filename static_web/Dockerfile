# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER great abel "greatabel1@126.com"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hi, I am your container'\
    >/usr/share/nginx/html/index.html
EXPOSE 80
