# Jekyll Base Image
FROM ubuntu:14.04
MAINTAINER abel <greatabel1@126.com>

RUN apt-get -yqq update
RUN apt-get -yqq install ruby ruby-dev make nodejs
#RUN gem sources --remove http://rubygems.org/
#RUN gem sources -a http://ruby.taobao.org/
#RUN gem sources -l
#RUN gem install rack
#RUN gem sources --remove https://rubygems.org/
#RUN gem sources -a http://rubygems.org/
RUN gem install --no-rdoc --no-ri jekyll

VOLUME /data
VOLUME /var/www/html
WORKDIR /data

ENTRYPOINT [ "jekyll", "build", "--destination=/var/www/html" ]
