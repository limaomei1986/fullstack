# 准备工作

开始学习之前，事先应该做好以下准备工作。

## 知识准备

- 掌握 HTML、CSS、JS 的基本用法
- 掌握命令行的基本用法

## 安装 Git

请到官网 [git-scm.com](https://git-scm.com/) 或国内的下载站，下载安装包。

## 安装 Node

请到 Node 官网[nodejs.org](https://nodejs.org)，或者国内镜像[npm.taobao.org/mirrors/node](https://npm.taobao.org/mirrors/node)，下载安装包。推荐安装最新的稳定版，目前是v6.x。

安装完成后，命令行执行下面的命令，确认是否安装成功。

```bash
$ node -v
v6.9.4
```

Node 的模块管理器 npm 会一起安装好。由于 Node 的官方模块仓库网速太慢，模块仓库需要切换到阿里的源。

```bash
$ npm config set registry https://registry.npm.taobao.org/
```

执行下面的命令，确认是否切换成功。

```bash
$ npm config get registry
```

另外可以使用nrm管理npm的源，全局安装nrm：

```bash
$ npm install nrm -g
```

nrm常用命令:

```
$ nrm ls #查看当前 nrm 内置的几个 npm 源的地址
$ nrm user taobao 切换npm源
```

## 安装 Postman

Postman 是一个 HTTP 通信测试工具，REST API 的练习会用到它。

请到官网 [GetPostman.com](https://www.getpostman.com/) 下载独立安装包；也可以参考这篇文章[www.cnblogs.com/mafly/p/postman.html](http://www.cnblogs.com/mafly/p/postman.html)，下载 Chrome 浏览器的插件，它们的效果一样。