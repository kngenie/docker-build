FROM ubuntu:trusty

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update -y && apt-get upgrade -y \
    apt-get install -y git curl libjpeg8 libpng12-0
RUN apt-get install -y python3-setuptools && easy_install3 pip && \
    pip install virtualenv wheel pytest pytest-cov

LABEL description="Ubuntu Trusty, Python 3, virtualenv, pip, wheel"
