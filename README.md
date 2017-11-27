项目介绍
=======
微信PC Hook工具 PHP-SDK 

Composer 安装
------------
```bash
新建composer.json文件，引入包如下：
 
{
  "require-dev": {
    "fastgoo/wechat-hook-phpsdk": "dev-master"
  }
} 

composer install
```

依赖扩展
-------
1、日志系统依赖 Redis扩展 和 Redis服务器

项目结构
-------

```bash
src/
    
    WxHook.php  核心管理器，管理Core、Receive
    Core.php 核心类 HTTP请求、功能接口
    Receive.php 接受数据，请求安全数据过滤，以及数据格式化
```

文档地址
-------

https://github.com/fastgoo/wechat-hook-phpsdk/wiki


作者
-------
QQ：773729704 记得备注github

微信：huoniaojugege  记得备注github

需要做维系机器人管理系统的可以联系我