# x-blog

### 博客初始化
```
sudo mkdir blog
sudo chmod -R 777 blog
cd blog
npm install hexo -g
hexo -v
hexo init
npm install
hexo g
npm install hexo-deployer-git --save
hexo d -g
```
 
 ### 安装主题(next)
```
git clone https://github.com/iissnan/hexo-theme-next themes/next
vim themes/next/_config.yml
vim themes/next/languages/zh-Hans.yml
vim _config.yml
hexo d -g
```
 
 ### 发布博客
 ```
 hexo new "博客名" //创建
 hexo g //构建
 hexo d -g //发布
 ```

### 帮助文档
* 使用Hexo+Github一步步搭建属于自己的博客（进阶）http://www.cnblogs.com/fengxiongZz/p/7707568.html


---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)
