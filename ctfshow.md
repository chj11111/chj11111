ubuntu替换源
```
sed -i 's/http:\/\/us.archive.ubuntu.com\/ubuntu\//http:\/\/mirrors.163.com\/ubuntu\//g' /etc/apt/sources.list

apt-get update
```
#安装php开发环境
```
apt-get install nginx

```

#查询nginx状态 绿色代表正常
```
service nginx status

```
php下载对应版本就行
```
apt-cache search php-fpm

apt-get install php8.1-fpm

service php8.1-fpm status
``` 
nginx的默认根目录为```/var/www/html```

查看版本 ```php -v```

修改nginx配置 ```在/etc/nginx/sites-avail...```
查看配置是否成功 ```nginx -t```

nginx软重启 ```nginx -s reload``` 

还有问题的话就看下面这个网址```https://www.bilibili.com/video/BV17o4y1E7GK/?p=2&spm_id_from=pageDriver```
