FROM php:7.4-fpm

RUN docker-php-ext-install pdo pdo_mysql

WORKDIR /app

ADD . /app

CMD ["php", "-S", "0.0.0.0:9000"]