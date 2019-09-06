FROM phpdockerio/php72-fpm:latest
WORKDIR "/application"

# Install git
RUN apt-get update \
    && apt-get -y install git php7.2-mysql \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
