FROM ubuntu:20.04

run apt update -y
run apt upgrade -y
run apt install wget php-cli php-zip unzip curl -y
run curl -sS https://getcomposer.org/installer |php
run mv composer.phar /usr/local/bin/composer
run curl -sL https://deb.nodesource.com/setup_12.x
run apt install nodejs -y
run apt install tasksel -y
run tasksel install lamp-server