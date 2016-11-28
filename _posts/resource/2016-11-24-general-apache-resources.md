---
layout: post
title: Apache 命令 和lumenMysql
category: 资源
tags: jQuery
keywords: jQuery
description: 
---
##Apache 3个常用命令
===================

 - 开启Apache: ``` sudo apachectl start ```
 
 - 关闭Apache: ``` sudo apachectl stop ```
 
 - 重启Apache: ``` sudo apachectl restart ```  

##lumen项目 migrate Mysql
===
1. 登录MySql 创建一个名字和lumen项目目录下.env文件里DB_DATABASE 名字一样的数据库.
2. 执行```php artisan migrate```
3. 进行填充,执行```php artisan db:seed```