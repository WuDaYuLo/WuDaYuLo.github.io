---
title: git的学习笔记
date: 2020-01-22 21:49:50
tags:
categories: 
thumbnail: "/images/desert.jpg"
comments: 
toc: true
---


## 1.查看当前的仓库的修改状态
```
git status
```
<!-- more -->
## 2.添加到暂存区
```
git add 文件名
```

## 3.从暂存区添加到本地仓库
```
git commit -m "自己的描述"
```
## 4.从本地仓库添加到远程仓库
```
git push
```

## 最后注意的是；每次添加要git status 查看状态

***

## 使用hexo写博客

## 基于js，需要node和npm

## 0.全局安装hexo-cli

```
cnpm install -g hexo-cli
```
## 00.初始化博客 hexo项目
```
hexo init
```
## 000.在本地启动服务来浏览效果

```
hexo s
```

## 1.先创建一个博客
```
hexo new "My New Post" 
```
or

```
hexo n "My New Post"
```
## 2. 清理一下

```
hexo clean
```

## 3. 生成静态文件

```
hexo g
```

## 4.在本地启动服务来浏览博客的内容是否渲染了

```
hexo s
```


## 5.安装hexo-deployer-git工具

```
cnpm install --save hexo-deployer-git
```

## 6.修改_config.yml的配置文件 

deploy:  
  type: 'git'  
  repo: 'https://github.com/WuDaYuLo/homework.git'  
  branch: master

## 7.修改博客的主题

git clone github的地址 themes/以主题名的文件夹名



## 部署到远端
```
hexo d
```
