FROM centos:6

MAINTAINER yubang

RUN yum groupinstall "Development tools" -y
RUN yum install wget tar -y

ADD install.sh /tmp/install.sh
ADD start.sh /tmp/start.sh
RUN /bin/bash /tmp/install.sh
