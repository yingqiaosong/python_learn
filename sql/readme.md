# 学习记录3
熟悉了基本运用之后，尝试进行pycharm与本地MySQL连接

1. 安装mysql（我用的xampp内置mysql）

2. 创建数据库testdb，数据表employee（跟着菜鸟跑的hh）

3. 注册一个用户，创建数据库testdb，然后授予该数据库所有权限。

4. 新建pycharm项目sql_demo,在settings-project-python interpreter中添加 PyMySQL

   ![QQ截图20220429111033](https://github.com/yingqiaosong/python_learn/blob/main/image/QQ%E6%88%AA%E5%9B%BE20220429111033.png)

5. 尝试在py代码中输入import pymysql,无异常则连接成功

6. 学习pymysql基本使用方法，通过python进行简单的增，删，查操作和事务处理

###### 命令行指令：

登录mysql：mysql -h 主机ip -u 用户名 -p 数据库名 //如果本机，-h 主机ip 可不写

增加用户：grant 权限 on 数据库.关系 to 用户名@登录主机 identified by "密码"

###### 
