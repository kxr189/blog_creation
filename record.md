blog创建过程记录

# 一、搭建步骤

    1、搭建框架：Hexo
    2、搭建步骤：
      (1)下载node.js  https://nodejs.org/en
      (2)node -v	#查看node版本
      (3)npm -v	#查看npm版本
      (4)npm install -g cnpm --registry=http://registry.npm.taobao.org	#安装淘宝的cnpm 管理器
      (5)cnpm -v	#查看cnpm版本
      (6)cnpm install -g hexo-cli    #安装hexo框架
      (7)hexo -v	#查看hexo版本
      (8)mkdir blog	#创建blog目录
      (9)cd blog	 #进入blog目录
      (10)hexo init 	#生成博客 初始化博客(直接在git bash 里操作)
      (11)hexo s	#启动本地博客服务 http://localhost:4000/	#本地访问地址
      (12)hexo n "我的第一篇文章" #创建新的文章 
      (13)hexo clean #清理
      (14)hexo g #生成
      (15)#Github或者gitee创建一个新的仓库 YourGithubName.github.io
      (16)cnpm install --save hexo-deployer-git #在blog目录下安装git部署插件

# 二、常用指令
  ```
  hexo clean
  hexo g
  hexo s
  ```


