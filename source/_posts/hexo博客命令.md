---
title: hexo博客命令
date: 2017-09-12 16:32:44
tags:
- hexo
- 命令
- blog
categories: 命令
---
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

<!-- more -->

# 参考文献
[next主题Document](http://theme-next.iissnan.com)

# 版本信息
hexo 3.3.9
nodejs 8.4.0

---
