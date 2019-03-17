# lambda php bin

Contains Lambda Php Binary

## php7.2.16 binary 

upload binary to Layers, and will be accessible on `/opt/bin` as binary or `/opt/lambda/` as content

### Binary
- php-fpm
- php (cli)
- php-cgi

### extension

- redis
- imagick
- pdo_pgsql
- imagick
- amazon-elasticache-cluster-client
- mongodb
- pthreads
- opcache
- igbinary

### NOTE

Pthreads does not support on CGI-fpm. Please remove pthreads.ini on lambda/etc/php/conf.d/
