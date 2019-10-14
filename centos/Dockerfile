FROM centos:8

RUN yum -y update \
    && yum install rsync -y \
    && yum install openssl -y \
    && yum clean all \
    && mkdir -p /var/www/project/

WORKDIR /var/www/project/

