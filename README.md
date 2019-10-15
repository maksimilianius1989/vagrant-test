# Поднятие базовой конфигурации серыера на Vagrant

## Стек технологий в образе
* php 7.3 (php7.3-common php7.3-fpm php7.3-mysqlnd php7.3-mysql php7.3-xml php7.3-xmlrpc php7.3-curl php7.3-gd php7.3-imagick php7.3-cli php7.3-dev php7.3-imap php7.3-mbstring php7.3-opcache php7.3-soap php7.3-zip php7.3-intl)
* ubuntu 18.04
* nginx/1.14.0
* mysql 5.7
* java 8
* redis
* ElasticSearch
* supervisor

## Deployment
```vagrant up```

## SSH
```vagrant ssh```

## Remove
```vagrant destroy```

## Host
http://vagrant.test.loc/