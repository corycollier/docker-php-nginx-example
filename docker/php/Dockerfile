FROM php:7.4-fpm
MAINTAINER your@mom.com

RUN apt update -y \
    && apt upgrade -y \
    && apt install -y \
        nginx


COPY docker/php/nginx.conf /etc/nginx/conf.d/default.conf
