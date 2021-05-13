FROM php:8.0.6-fpm-alpine

RUN docker-php-ext-install \
    pdo \
    pdo_mysql

######## Composer.phar ########
RUN curl -s https://getcomposer.org/installer | php \
  # move composer into a bin directory you control:
  && mv composer.phar /usr/local/bin/composer \
  # double check composer works
  && composer about