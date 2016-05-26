FROM nginx:latest

MAINTAINER Shafiul Bashar <shafiul.bashar@widespace.com>

ADD nginx.conf /etc/nginx/

RUN usermod -u 1000 www-data

CMD ["nginx"]

EXPOSE 80 443
