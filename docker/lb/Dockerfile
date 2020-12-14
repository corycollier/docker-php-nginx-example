FROM nginx:stable
MAINTAINER your@dad.com

RUN apt update -y \
    && apt upgrade -y \
    && apt install -y \
        vim

COPY docker/lb/nginx.conf /etc/nginx/conf.d/default.conf
