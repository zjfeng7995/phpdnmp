##### PHPDNMP（Docker + Nginx + MySQL + PHP）是一款全功能的DNMP一键安装程序。

##### 本地需提前安装好git、docker和docker-compose。
### 1.快速使用
```php模式 
1.下载phpdnmp：
$ git clone https://github.com/Tim-AutumnWind/phpdnmp.git
2.进入目录
$ cd phpdnmp
3.构建
$ docker-compose up
``` 
就三部曲，没有了 ！！！ 就是如此简单！！！
注意：Windows安装360安全卫士的同学，请先将其退出，不然安装过程中可能Docker创建账号过程可能被拦截，导致启动时文件共享失败；

###   2.访问在浏览器中访问：
*   http://localhost/： 默认站点
*   http://localhost:8080/： phpMyAdmin

#### docker-compose常用命令
```php模式 
docker-compose up    # 构建
docker-compose stop  # 停止
docker-compose rm    # 删除
$ docker-compose build php72    # 重建单个服务
$ docker-compose build          # 重建全部服务
``` 

#### mysql信息
```
地址:localhost
账户:root
密码:phpdnmp
``` 




