---
title: Hexo博客命令
date: 2017-09-12 16:32:44
tags:
- hexo
- 命令
- blog
categories: hexo
---
hexo是一款基于Node.js的静态博客框架，选择它的原因是因为快速方便而且功能强大，对于完全不会nodejs的我来说，上手也十分简单。以下是搭建博客以及部署到github的基本命令。
<!-- more -->

# 摘要
记录博客hexo的命令

# 安装hexo
```{bash}
$ npm install -g hexo
```

# 新建一个hexo项目
```{bash}
hexo init
hexo init <projectName>
```

# npm模块安装
```{bash}
npm install hexo-generator-feed --save      RSS订阅
npm install hexo-generator-sitemap --save   站长地图
npm install hexo-generator-searchdb --save  本地站内搜索
npm install hexo-deployer-git --save        部署到git
```

# 新建
```{bash}
hexo new <contentName>    新建文章(contentName.md)
hexo new page <name>      新建目录以及页面(name/index.md)
```

# 启动以及部署
```{bash}
启动
hexo clean
hexo generate
hexo server

部署
hexo clean
hexo generate
hexo deploy
```

# 参考文献
[next主题Document](http://theme-next.iissnan.com)

# 版本信息
next 5.1.2
hexo 3.3.9
nodejs 8.4.0

---
