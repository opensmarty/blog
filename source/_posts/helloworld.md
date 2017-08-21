title: How do you make blog for yourself ?
tags: [Hexo,Next,HelloWorld]
categories: [Python,javascript,Install]
date: 2017-08-18 16:12:00
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Install hexo

``` bash
npm install hexo-cli g #安装
npm update hexo -g #升级
hexo init blog #初始化博客文件夹
```

### Install theme Next

``` bash
git clone https://github.com/iissnan/hexo-theme-next themes/next
```

### Install Plugins

``` bash
# 切换到该路径
cd blog
#安装hexo的扩展插件
npm install
#安装其它插件
npm install hexo-server --save
npm install hexo-admin --save
npm install hexo-generator-archive --save
npm install hexo-generator-feed --save
npm install hexo-generator-search --save
npm install hexo-generator-tag --save
npm install hexo-deployer-git --save
npm install hexo-generator-sitemap --save
npm install hexo-generator-baidu-sitemap --save
```

### Create a new post

``` bash
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo new photo "My Gallery"
hexo new "Hello World" --lang tw
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Abbreviate hexo commands

``` bash
hexo g：hexo generate
hexo c：hexo clean
hexo s：hexo server
hexo d：hexo deploy

hexo clean && hexo g -s #清除、生成、启动
hexo clean && hexo g -d #清除、生成、部署
```

### Generate static files

``` bash
hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html

### Reference links

[Hexo](https://hexo.io/)
[Hexo Next](http://theme-next.iissnan.com/)
[Next Source](https://github.com/iissnan/hexo-theme-next)
[Install Hexo admin](http://yeshaoting.cn/article/hexo/hexo%E4%BD%BF%E7%94%A8%E8%BF%9B%E9%98%B6/)
[Optimize the hexo-theme-next](http://blog.csdn.net/miaoqiucheng/article/details/72794165)