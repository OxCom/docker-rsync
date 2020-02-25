FROM alpine

ENV TERM=xterm \
    LANG=en_US.UTF-8 \
    LANGUAGE=en_US.UTF-8 \
    LC_CTYPE=en_US.UTF-8 \
    LC_ALL=en_US.UTF-8

RUN apk update \
    && apk upgrade \
    && apk add rsync openssl \
    && rm -rf /tmp/* /var/cache/apk/* \
    && mkdir -p /var/project/

WORKDIR /var/project/

