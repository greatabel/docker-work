# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER great abel "greatabel1@126.com"
CMD ["/bin/bash"]
ONBUILD ADD . /abel
VOLUME ["/abel/test","abel/testA"]
ADD test.txt /opt/Application/test.txt
ADD test1.txt.tar.gz /root/abel/
COPY test2.txt /root/abel/

EXPOSE 80
