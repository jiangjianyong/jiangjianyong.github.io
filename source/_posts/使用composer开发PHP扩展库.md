---
title: 使用composer开发PHP扩展库
date: 2018-02-10 23:33:43
tags:
---

### 已完成的扩展库

| 序号 | 库名 | 地址 | 描述 | 
| - | - | :-: | -: | 
| 1 | phprush/demo | https://github.com/phprush/demo.git | 演示库 | 
| 2 | phprush/websocket | https://github.com/phprush/websocket.git | php websocket 客户端库 |
| 3 | phprush/wechat-applet | https://github.com/phprush/wechat-applet.git | 微信小程序SDK封装(laravel使用) |
| 4 | phprush/simple-encrypt | https://github.com/phprush/simple-encrypt.git | 一个简单的加密库 |
| 5 | phprush/requests | https://github.com/phprush/requests.git | 一个简单的http请求库 |

### 库的开发方式
* composer init
* composer.json 中使用psr-4规范配置autoload
* src中开发代码
* github/packagist中发布代码
