# Student_information_management_system

1、因为后台使用的mysql数据库，请自行安装mysql5.7

2、安装完数据库，请创建数据库用于回复数据库

进入数据库的命令行模式

create database if not exists college charset =utf8;

3、在系统命令行模式下进入到项目的根目录下，将数据库恢复

(注意：我这里的mysql账号密码是 root/123456，建议修改成和我一致的)

mysqldump -uroot -p123456 college < college.sql

4、进入到项目的根目录下，运行项目

python manage.py runserver 0.0.0.0:8222

6、打开浏览器，访问http://127.0.0.1:8222

7、选择用管理员身份登陆，账号密码：20180000、abcdef
