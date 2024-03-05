FROM php:7.1.2-apache 
RUN docker-php-ext-install mysqli
# Install pdo is you need to use PHP PDO
RUN docker-php-ext-install pdo pdo_mysql
# Run docker-php-ext-enable command to activate mysqli
RUN docker-php-ext-enable mysqli
