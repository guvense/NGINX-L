# NGINX-L
This repo consist of nginx configuration file 
Download source code

Dependecies
```
sudo apt-get install libpcre3 libpcre3-dev zlib1g zlib1g-dev libssl-dev
```


configure like below

```
./configure --sbin-path=/usr/bin/nginx --conf-path=/etc/nginx/nginx.conf --error-log-path=/var/log/nginx/error.log 
--http-log-path=/var/log/nginx/access.log --with-pcre --pid-path=/var/run/nginx.pid --with-http_ssl_module 
--modules-path=/etc/nginx/modules --with-http_v2_module

```
make and make install
