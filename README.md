#APTTools

本程序简化了apt-get常用命令的使用。
本程序遵循GPL v3协议开源。

本程序优点：
1：极大方便了网络和linux开发人员；
2：小巧玲珑，易于使用。

安装方法：克隆或下载tar.gz文件解压后运行./atinst即可。

使用方法：
ai [包名] : 等效于apt-get install [包名] -y
am [包名] : 等效于apt-get remove [包名]
amy [包名] : 用于清除卸载程序后其依赖，等效与apt autoremove
au : 等效与apt-get update
aup : 升级系统程序，等效于apt-get upgrade -y!
[例如：](https://git.oschina.net/uploads/images/2017/0507/154301_6d0d4079_1256194.png "例子")
