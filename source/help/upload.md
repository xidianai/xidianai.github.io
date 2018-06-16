---
title: 上传步骤
date: 2018-06-15
subtitle: 周会论文管理
type: about
layout: about
---

# 上传步骤

> 当完成 `source/_drafts/templete.md` 中的内容后，就可以执行下列步骤上传了。


## 1. 本地测试

在项目当前目录下执行命令行命令：

```
hexo s
```

打开浏览器访问: [http://localhost:4000/](http://localhost:4000/)


## 2. 上传

在项目当前目录下执行命令行命令：

```
hexo d
```


## 3. commit and push

当上传成功后，需要将最新的项目内容 `commit` 到 `github` 上。


## 得到静态的网页（非必须）

在项目当前目录下执行命令行命令：

```
hexo g
```

此时会在 `public` 中生成静态的网页，你可以将该文件夹中的内容放到任何的服务器容器中。

