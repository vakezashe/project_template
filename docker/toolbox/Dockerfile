FROM ubuntu:18.04

RUN apt-get update && \
    apt-get install python3 python3-pip -y \
    && pip3 install --upgrade pip && \
    pip3 install pytest && pip3 install selenium
    hostname
# CMD tail -f /var/log/syslog

# FROM alpine
# RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py-pip && \
#     pip install awscli
# RUN apk --purge -v del py-pip
# CMD tail -f /dev/null

