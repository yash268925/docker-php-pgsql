FROM php:8.0-fpm-alpine

RUN apk --no-cache add postgresql-dev libpq oniguruma-dev \
 && docker-php-ext-install pdo pdo_pgsql pgsql mbstring
