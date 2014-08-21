# version: 0.1

FROM ubuntu:14.04
MAINTAINER IMAD JERRA "smartshader@gmail.com"
ENV REFRESHED_AT "Mon 18 Aug 2014 00:00:54 EDT"

RUN apt-get update
RUN apt-get -y -q install nginx

RUN mkdir -p /var/www/html/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/

EXPOSE 80
