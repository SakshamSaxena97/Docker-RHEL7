FROM centos:latest
MAINTAINER Saksham

RUN yum -y update;
RUN yum -y install mongodb-server; yum clean all
RUN mkdir -p /data/db

EXPOSE 27017
ENTRYPOINT ["/usr/bin/mongod"]

