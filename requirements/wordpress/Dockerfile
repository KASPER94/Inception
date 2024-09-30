FROM debian:latest

RUN apt-get update && apt-get upgrade && apt install php-fpm -y

CMD ["php-fpm8.2", "-F"]