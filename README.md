# docker集成【多语言版基础配置管理系统】spring微服务镜像

   很久没玩技术了，花了几天时间，学习了一下docker的基础知识，然后把关于
多语言版基础管理系统展示[es6版]-入门配置篇(https://www.iteye.com/blog/fmfl-2432773)
里面提到的程序发布到docker上，操作系统使用的是最新的centos镜像，安装了mysql，java，httpd，redis，已设置开机自启动
 
步骤：
    1.启动前配置好端口映射[-p 8089:8089 -p 8769:8769 -p 8761:8761 -p 6379:6379 -p 8086:8086 -p 8082:8082]
    2.本地系统配置一个假域名(例如test.back.com)
    3. 访问路径：http://test.back.com:8769
   
    集成的镜像文件比较大，已上传到百度网盘和docker hub，匆忙做的集成镜像，难免有不足，有兴趣到可以下载来看看
    docker hub: https://hub.docker.com/repository/docker/minn394286006/minnautocentos 
    百度网盘：链接:https://pan.baidu.com/s/1i0SGS7HDXM0b2a36VMd9eg  密码:5u05
