FROM quay.io/bitrix24/php:8.2.29-fpm-v1-alpine

USER root

# Установка SOAP
RUN apk add --no-cache libxml2-dev && docker-php-ext-install soap

# Проверяем стандартную конфигурацию

USER 1000