---
title: 部署环境
date: 2018-06-15
subtitle: 周会论文管理
type: about
layout: about
---


## Install

1. 安装Git：下载[Git](https://git-scm.com/download/win)并安装

2. 安装Node：下载[Node](https://nodejs.org/zh-cn/download/), [8.11.3](https://nodejs.org/dist/v8.11.3/node-v8.11.3-x64.msi)，并安装

3. 安装cnpm

```
npm install -g cnpm -registry=https://registry.npm.taobao.org
```

4. 安装hexo

```
npm install hexo-cli -g
```


## 邀请协同开发

> 请联系项目所有者邀请协同开发

```
https://github.com/xidianai/xidianai.github.io/settings/collaboration
```


## Init

> 只需要进行`from GitHub Init`即可。


## from GitHub Init

1. Clone

```
git clone https://github.com/ALISURE/alisure.github.io.git
```

2. 选择 `source` 分支

3. 安装依赖

```
cnpm install
```

4. 编写代码/主题/插件等

5. 本地调试

```
hexo server
```

6. 生成并部署

```
hexo g --deploy
```

7. 远程访问网站：[https://xidianai.github.io/](https://xidianai.github.io/)


## from Empty Init

1. 初始化

```
hexo init <folder>
cd <folder>
cnpm install
```

2. 新建source分支

3. 编写配置文件`_config.yml`

4. 编写代码/主题/插件等

5. 本地调试

```
hexo server
```

6. 生成并部署

```
hexo g --deploy
```

7. 远程访问网站： [https://xidianai.github.io/](https://xidianai.github.io/)


## 遇到的问题

### 1. Failed with error: Fatal: HttpRequestException encountered.

邀请协同开发：
```
https://github.com/xidianai/xidianai.github.io/settings/collaboration
```

### 2. ERROR Deployer not found: git

项目目录下：
```
npm install --save hexo-deployer-git
```

### 3. 配置`hexo-theme-skapp`主题的问题

[https://github.com/Mrminfive/hexo-theme-skapp/blob/master/README-cn.md](https://github.com/Mrminfive/hexo-theme-skapp/blob/master/README-cn.md)

```
1. 确保node 版本：8.11.3

2. 首先安装下列内容
npm install -g windows-build-tools
npm install -g node-gyp

3. 安装模块（若出错，一个一个装，直到成功）
npm install --save hexo-autoprefixer hexo-filter-cleanup hexo-generator-feed hexo-generator-sitemap hexo-renderer-sass hexo-renderer-swig mamboer/lunr.js moment node-sass object-assign
```

### 4. ERROR Asset render failed: scss/views/page/search.css

```
去掉该文件中的一个“,”号
```

### 5. TypeError: post.tags.each is not a function

```
不要在非"_post"页面添加"tags"
```

