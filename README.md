# docker
## nginx:latest+php:5.6-fpm+mariadb:latest
- clone this repo
- docker-compose up

после развертывания, добавить в /etc/NetworkManager/dnsmasq.d/local-development.conf записи вида 
address=/php71/ip_контейнера
address=/php56/ip_контейнера