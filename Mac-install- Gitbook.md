---
title: Mac 环境下 GitBook 安装教程
---

## 安装 node.js

[下载链接](https://nodejs.org/en/)

一般选左边的就行，左边是用的最多的稳定版，右边是当前最新版，不急，用稳定版足够

![下载选项](https://cdn.ljk.cool/202201172331693.png)

下载完成后打开就继续继续继续就好了

![继续](https://cdn.ljk.cool/202201172332412.png)



安装完成后，在【终端】页面，输入

```
npm -v
```

查看版本

![版本](https://cdn.ljk.cool/202201172334916.png)

下一步就是安装 GitBook

在这里敲下一行代码：

```
sudo npm install gitbook-cli -g
```

需要输入你的开机密码，系统会自动安装，安装完成之后输入 ``gitbook -V`` 来查看 GitBook 版本，注意，这里的【V】是大写。

查询完成后，退出用 ``control``+ ``C`` .