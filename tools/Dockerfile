FROM debian:jessie

RUN apt-get update && apt-get install -y php5 php5-curl curl
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
