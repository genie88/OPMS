# OPMS
OPMS项目+OA管理系统

http://opms.milu365.cn/

手册文档：http://opms.docs.milu365.cn/

在线体验：http://opms.demo.milu365.cn/

加QQ群（451420312）获取用户名和密码


### 安装部署
修改配置文件里先完成下面工作 /conf/app.conf
```
mysqluser = "root"
mysqlpass = ""
mysqlurls = "127.0.0.1"
mysqldb = "aiopms"
mysqlpre = "pms_"
mysqlport = "3306"  
```

2 建立数据库名称：aiopms，再直接运行数据库文件即可。如下：
```
create database aiopms;
use aiopms;
source aiopms.sql;
```

3 安装依赖
go get

3 生成
go build main.go

5 运行
./main


