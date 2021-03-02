# docker-nginx-php7.4
    -=nginx=- 
    configuration  path:
        site conf = /etc/nginx/conf.d/default.conf"
        ssl conf = "/etc/ssl"
        public site = "/var/www/html"
        site tamplate =  "/etc/nginx/conf.d/default.template"
        ports:
            "80","443"

    -=php-fpm=-
    configuration  path:
        php conf = "/usr/local/etc/php/conf.d/php.ini"
        php site public = "/var/www/html"