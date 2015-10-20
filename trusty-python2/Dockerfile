FROM ubuntu:trusty

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update -y && apt-get upgrade -y
RUN apt-get install -y python-setuptools && easy_install virtualenv pip wheel \
    pytest pytest-cov
RUN apt-get install -y git

LABEL description="Ubuntu Trusty, Python 2, virtualenv, pip, wheel"
