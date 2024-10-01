FROM debian:latest

RUN apt update && apt upgrade && apt install -y nginx php-fpm

COPY default.conf /etc/nginx/conf.d/default.conf
# COPY default.conf /etc/nginx/nginx.conf
COPY fastcgi_params /etc/nginx/fastcgi_params

CMD ["nginx", "-g", "daemon off;"]