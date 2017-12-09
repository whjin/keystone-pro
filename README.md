# Keystone

> 以`Express`和`MongoDB`为基础搭建的`Node.js` CMS和web应用程序平台。

项目地址：[KeystoneJS](http://keystonejs.com/zh/)

## 安装步骤： ##

1、提前安装好 **Node.js**和**MongoDB**，推荐安装最新版本，这样可以使用最新功能和依赖库。

2、**安装生成器**

在根目录运行：

    npm install -g generator-keystone

进入新创建的文件夹，运行生成器：

    yo keystone

根据自己的需要配置功能项。

3、运行MongoDB

在 `MongoDB` 安装目录下新建数据存储目录 `data`，运行数据库：

    mongod --dbpath c:\mongodb\data

4、运行keystone项目

    node keystone

然后在浏览器打开[http://localhost:3000](http://localhost:3000/)查看运行情况



