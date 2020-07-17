# Container image that runs your code
#FROM alpine:3.10
FROM ubuntu:bionic

ENV http_proxy "http://internet.ford.com:83/"
ENV https_proxy "http://internet.ford.com:83/"
ENV no_proxy "localhost,127.0.0.1,*.ford.com,.ford.com"

# Copies your code file from your action repository to the filesystem path `/` of the container
COPY entrypoint.sh /entrypoint.sh

# Code file to execute when the docker container starts up (`entrypoint.sh`)
ENTRYPOINT ["/entrypoint.sh"]
