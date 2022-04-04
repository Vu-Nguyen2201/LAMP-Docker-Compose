# FROM php:7.4-fpm
FROM php:7.4-fpm-alpine

RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN docker-php-ext-enable pdo_mysql

WORKDIR /home/sites