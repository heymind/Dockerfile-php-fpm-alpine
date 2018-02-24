FROM php:5-fpm-alpine

RUN apk --update add \
    php5-ctype \
    php5-curl \
    php5-dom \
    php5-gd \
    php5-iconv \
    php5-json \
    php5-mcrypt \
    php5-openssl \
    php5-posix \
    php5-sockets \
    php5-xml \
    php5-xmlreader \
    php5-zip

EXPOSE 9000
CMD ["php-fpm"]