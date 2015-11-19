FROM php:fpm
MAINTAINER tess@deninet.com

RUN apt-get update && apt-get install -y \
            libfreetype6-dev \
            libjpeg62-turbo-dev \
            libmcrypt-dev \
            libpng12-dev \
            libicu-dev \
            php5-imagick php5-imap \
            php5-mcrypt php5-curl php5-cli php5-gd \
            php5-sqlite php5-common php-apc php-pear \
            php5-json php5-memcache php5-intl

RUN docker-php-ext-install gd json intl pdo pdo_mysql mbstring
