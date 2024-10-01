FROM wordpress:latest

# Mettre à jour et installer PHP-FPM
RUN apt-get update && apt-get install -y php-fpm

# Copier la configuration PHP-FPM
COPY www.conf /etc/php/8.2/fpm/pool.d/
COPY www.conf /usr/local/etc/php-fpm.d/

# Démarrer PHP-FPM
CMD ["php-fpm8.2", "-F"]
