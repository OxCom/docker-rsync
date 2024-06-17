FROM alpine

ENV TERM=xterm \
    LANG=en_US.UTF-8 \
    LANGUAGE=en_US.UTF-8 \
    LC_CTYPE=en_US.UTF-8 \
    LC_ALL=en_US.UTF-8

RUN apk --no-cache upgrade \
    && apk --no-cache add rsync openssl \
    && mkdir -p /var/project/

WORKDIR /var/project/

