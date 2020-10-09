##  一、安装

1. window系统
> 下载和安装git环境  开始 -> git文件夹

> a.git.bash   支持linux 命令的控制台

> b.git cmd    支持windows命令的控制台

> c.git gui    git可视化界面


## 二、git使用

### 1. git  初始化

```bash  
$ cd 目录
$ git init  初始化
```

>  出现了一个  .git (隐藏文件) ， 存放当前仓库的一些基本信息

>  初始化 ， 以后  会在本机生成一个仓库 暂存区的虚拟仓库

## 2. 创建文件

```bash
$touch  文件名
$ mkdir  目录名
```
windows  不能使用


## 3. 从工作区 -> 暂存区

```bash
$ git log 查看当前的提交版本
```

>  版本的回馈

```bash
$ git reset --hard HEAD^
$ git reset --hard HEAD^^
$ git reset --hard 版本号
```

## 5、 配置团城仓库的用户信息

```bash
$ git config --global user.name "你的git名称"
$ git config --global user.email "你的git验证邮箱"
```

## 6、 配置ssh密匙

```bash
$ ssh-keygen -t rsa -C "youremail@????.com"
```

## 7、上传到远程仓库

```bash

$ git remote add origin  "网址"
$ git push -u origin master
```

## 8、从第二次开始

```bash
git add
git commit
git push //简写
```
## 9、 克隆数据

```bash
$ git clone 仓库地址
```

## 10、 从远程仓库更新数据

```bash
$ git pull
```

## 11、 命令

```bash
$ git add  提交文件
$ git commit -m '对文件的描述' 

$ git diff  '查看工作区和暂存区的状态'
```
