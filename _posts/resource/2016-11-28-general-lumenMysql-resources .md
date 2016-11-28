---
layout: post
title:  lumen项目 migrate Mysql
category: 资源
tags:lumen mysql
keywords: mysql lumen
description: 
---
#lumen项目 migrate Mysql
===
1. 登录MySql 创建一个名字和lumen项目目录下.env文件里DB_DATABASE 名字一样的数据库.
2. 执行```php artisan migrate```
3. 进行填充,执行```php artisan db:seed```