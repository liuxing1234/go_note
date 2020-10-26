# 环境准备

## 1. go环境搭建

下载地址: https://studygolang.com/dl

我的环境是win10, 所以直接点击的msi,一件安装

测试安装:

```shell
go version #go version go1.15 windows/amd64
```

## 2. 国内镜像

查看一下自己的环境配置

```shell
go env
```

可以看到`GOPROXY`这个选项,现在需要将代理设置成国内代理

可以访问https://goproxy.cn/

用法如下:

```shell
go env -w GO111MODULE=on
go env -w GOPROXY=https://goproxy.cn,direct
```



## 3. 编辑器

* goland(推荐)
* vscode