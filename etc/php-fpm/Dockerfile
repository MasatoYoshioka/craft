FROM php:7.4-fpm-alpine

RUN apk add zlib-dev libpng-dev libzip-dev \
 && /usr/local/bin/docker-php-ext-install mysqli pdo pdo_mysql gd zip
