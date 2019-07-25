FROM php:fpm
RUN pecl install xdebug
RUN docker-php-ext-enable xdebug
COPY php/php.ini /usr/local/etc/php/