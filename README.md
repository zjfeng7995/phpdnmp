##### PHPDNMP（Docker + Nginx + MySQL + PHP）是一款全功能的DNMP一键安装程序。
##### 使用过程中如有问题，请反馈谢谢 [留言地址]（https://www.jianshu.com/p/b9a957390baa）
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




