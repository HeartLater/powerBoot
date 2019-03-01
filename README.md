# powerBoot
1、修改jdk地址
2、修改启动命令
3、将文件加入到/etc/rc.d/init.d目录下，
   cd /etc/rc.d/init.d/
   chmod +x logmonitor
4. 添加脚本到开机自动启动项目中

   chkconfig --add logmonitor
   chkconfig logmonitor on
