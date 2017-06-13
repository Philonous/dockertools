# @IMAGE toolbox
# @VERSION 20170613-1

FROM ubuntu

RUN echo "dependencies v1" && \
    export DEBIAN_FRONTEND=noninteractive && \
    apt-get update && \
    apt-get install -y --no-install-recommends  \
      curl \
      dnsutils \
      emacs-nox \
      git \
      locales \
      mc \
      openssl \
      postgresql-client \
      ssh \
      wget \
    && \
    rm -rf /var/lib/apt/lists/* && \
    localedef -i en_US -c -f UTF-8 -A /usr/share/locale/locale.alias en_US.UTF-8
