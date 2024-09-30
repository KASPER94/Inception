FROM debian:latest

RUN apt-get update && apt-get upgrade && apt install php-fpm -y

COPY www.conf /etc/php/8.2/fpm/pool.d/
COPY www.conf /usr/local/etc/php-fpm.d/

CMD ["php-fpm8.2", "-F"]