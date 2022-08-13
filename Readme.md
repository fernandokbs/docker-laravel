* Execute docker compose up -d
* Every projects must be on this folder
* If you need another PHP version, enter to app container (docker exec -it app bash) and execute the folllowing code, 
    *  apt install phpVERSION-{bcmath,dev,xml,imap,readline,msgpack,igbinary,gmp,fpm,mysql,zip,intl,ldap,gd,cli,bz2,curl,mbstring,memcached,pgsql,sqlite3,opcache,soap,cgi} -y
    * Replace VERSION with the version required, ej apt install php7.2-{bcmath, ...}