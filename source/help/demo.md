---
title: 模板说明
date: 2018-06-15
subtitle:  周会资料的整理和再利用
cover: /resources/system/help_cover.png
type: about
layout: about
---

# 模板说明

> `模板文件` 请参见 `source/_drafts/templete.md`


## 目录结构

1. 所有的资源都在`source/resources`中，包括图片、论文、PPT等。

2. 每个人需要在改目录下新建一个文件夹，该文件夹用于存储自己的文件。

3. 在自己的文件夹下可以按照日期来管理。


## 页面配置

* 标题/子标题/日期

```
title: 文章的标题
subtitle: 文章的子标题
date: 2018-06-15
```

* 封面图片

用于展示在首页和文章页面，推荐使用论文中最能代表论文思想的图片，比如：网络架构图、实验结果图等。

```
cover: /resources/you name/path/you cover.png（请修改为自己的封面图片）
```

* 分类和标签

```
categories: 分类（请修改合适的类别）
tags:
    - 标签 1（请修改合适的标签，可以多个）
    - 标签 2（请修改合适的标签，可以多个）
    - 标签 3（请修改合适的标签，可以多个）
```

* 作者信息

```
author: 
  nick: you nick（请修改为名称）
  link: /search/?search=you nick（推荐这个，也可以将此行删除）
```

