# music

#### 介绍
郑大音乐

#### 软件架构
软件架构说明
1. renren-common为公共模块，其他模块以jar包的形式引入进去，主要提供些工具类，以及renren-admin、renren-api模块公共的entity、mapper、dao、service服务，防止一个功能重复多次编写代码。
2. renren-admin为后台模块，也是系统的核心，用来开发后台管理系统，可以打包成jar，部署到服务器上运行，或者打包成war，放到Tomcat8.5+容器里运行。
3. renren-api为接口模块，主要是APP提供接口支持，可以打包成jar，部署到服务器上运行
4. renren-generator为代码生成器模块，只需在MySQL数据库里，创建好表结构，就可以生成新增、修改、删除、查询、导出等操作的代码，包括entity、mapper、dao、service、controller、页面等所有代码，项目开发神器。

#### 安装教程

1.  idea导入项目
2.  执行数据库脚本,renren-admin/db下面的music
3.  修改application-dev.yml，更改数据库账号和密码

#### 使用说明

1.  admin管理后台的默认用户名密码是admin admin




