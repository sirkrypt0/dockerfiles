FROM phusion/baseimage:master
MAINTAINER openHPI team <openhpi-info@hpi.de>

RUN apt-get update && apt-get upgrade -y -o Dpkg::Options::="--force-confold"
RUN apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

VOLUME /workspace
WORKDIR /workspace

ENV TERM=ansi
ENV COLUMNS=10000
ENV CODEOCEAN=true

CMD ["/bin/bash"]
