## Git教程

史上最浅显易懂的Git教程！ 



## Git简介

Git是目前世界上最先进的分布式版本控制系统（没有之一）。 

#### Git的诞生

Linus花了两周时间自己用C写了一个分布式版本控制系统，这就是Git！ 

#### 集中式vs分布式

CVS及SVN都是集中式的版本控制系统，而Git是分布式版本控制系统。

集中式的特点：

 - 版本库是集中存放在中央服务器的 
 - 必须联网才能工作 

分布式的特点：

- 每个人的电脑上都是一个完整的版本库
- 分布式版本控制系统的安全性要高很多
- Git极其强大的分支管理
- 不需要联网



## 安装Git

#### 在Linux上安装Git

首先，你可以试着输入`git`，看看系统有没有安装Git：

```shell
$ git
The program 'git' is currently not installed. You can install it by typing:
sudo apt-get install git
```

像上面的命令，有很多Linux会友好地告诉你Git没有安装，还会告诉你如何安装Git。

如果你碰巧用Debian或Ubuntu Linux，通过一条`sudo apt-get install git`就可以直接完成Git的安装，非常简单。

#### Mac OS X上安装Git

一是安装homebrew，然后通过homebrew安装Git 

第二种方法更简单，也是推荐的方法，就是直接从AppStore安装Xcode，Xcode集成了Git 

#### 在Windows上安装Git

在Windows上使用Git，可以从Git官网直接下载安装程序

安装完成后，还需要最后一步设置，在命令行输入：

```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

因为Git是分布式版本控制系统，所以，每个机器都必须自报家门：你的名字和Email地址。 

注意`git config`命令的`--global`参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。 



## 创建版本库

什么是版本库呢？版本库又名仓库，英文名**repository**，你可以简单理解成一个目录，这个目录里面的所有文件都可以被Git管理起来，每个文件的修改、删除，Git都能跟踪，以便任何时刻都可以追踪历史，或者在将来某个时刻可以“还原”。

所以，创建一个版本库非常简单，首先，选择一个合适的地方，创建一个空目录：

```
$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit
```













## 时光机穿梭

## 远程仓库

## 分支管理

## 标签管理

## 使用GitHub

## 使用码云

## 自定义Git

## 期末总结