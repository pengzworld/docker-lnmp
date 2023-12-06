
## 常用命令

```shell

sudo docker-compose up -d

docker-compose logs -f

sudo docker exec -it docker-lnmp_php_1 /bin/bash

sudo docker exec -it docker-lnmp_web_1 /bin/bash

docker cp docker-nginx-php-mysql-php-1:/usr/local/etc/php-fpm.d/www.conf  /Users/pengz/Sync/github.com/docker-nginx-php-mysql/etc/php


docker-compose down -v


docker run --rm --interactive --tty \
  --volume $PWD:/var/www/html/energy-biz \
  composer update


```