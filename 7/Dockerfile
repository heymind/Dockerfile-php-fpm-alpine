FROM php:7-fpm-alpine

RUN apk --update add \
    php7-ctype \
    php7-curl \
    php7-dom \
    php7-gd \
    php7-iconv \
    php7-json \
    php7-mcrypt \
    php7-openssl \
    php7-posix \
    php7-sockets \
    php7-xml \
    php7-xmlreader \
    php7-zip

EXPOSE 9000
CMD ["php-fpm"]