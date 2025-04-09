FROM php:8.2-fpm-alpine

WORKDIR /var/www/html

# Instalar extensoes PH necessarias (mysq pdo_mysql)
RUN docker-php-ext-install mysql pdo pdo_mysql

# Copiar o codigo em PHP para o conteiner
COPY ./index.php .

EXPOSE 9000