FROM php:7.1-fpm-alpine
RUN apk update && apk add \
        # nproc
        coreutils \
    && docker-php-ext-install -j$(nproc) mysqli pdo_mysql
