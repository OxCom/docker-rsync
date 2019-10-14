FROM debian:stable-slim

ENV TERM=xterm \
    DEBIAN_FRONTEND=noninteractive \
    INITRD No \
    LANG en_US.utf8

RUN apt-get update \ 
    && apt-get install -y --no-install-recommends rsync openssl \
    && mkdir -p /var/www/project/ \
    && rm -rf /tmp/* /var/tmp/* \
              /var/lib/apt/lists/* \
              /var/cache/apt/archives/*.deb \
              /var/cache/apt/archives/partial/*.deb \ 
              /var/cache/apt/*.bin

WORKDIR /var/www/project/
