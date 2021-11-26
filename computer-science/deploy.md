# Deploy 上線環境

### XAMPP

### Apache 2.4
#### apache2 -v 看版本
```sh
apache2 -v

# 2.4.51
```
#### httpd.conf
- DocumentRoot - 設定 webapp 路徑  
  http://httpd.apache.org/docs/2.4/getting-started.html#content

### PHP
#### phpversion(); 看版本
```php
<?
echo phpversion(); // 7.4.3
?>
```
#### php -v 看版本
*特別注意：這個指令看的是 "cli 版本"，"cli 版本"不見得跟 "網站版本" 相同*
```sh
php -v

# 7.4.3
```

### MySQL / MariaDB
#### mysql -V 看版本
```sh
mysql -V

# MariaDB-10.6.4
```
