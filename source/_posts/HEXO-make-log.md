---
title: HEXO make log
date: 2021-08-13 11:13:43
tags:
---

其实几年就在github上做过自己的博客,当时在godaddy上注册的域名,绑定github page,用的jekll,做着做着荒废了...
如今捡起来了,也是想解决一些问题,遂再次"故技重施".这次用hexo架构建站.

以下记录制作本站的一些关键节点

## 本地安装HEXO及环境
1.  install Git
2.  install NODE
3.  install hexo
4.  hexo make
   1. hexo init
   2. hexo g
   3. hexo d
      1. config.yml   edit   
          deploy:
            type: git
            repo: `https://github.com/xanggiyan/xanggiyan.github.io.git`
            branch: main
      2. git config --global http.sslVerify "false"

## 图床是个问题,依旧github羊毛
add   picgo
xanggiyan/img

问题来了,国内速度慢,手机基本打不开
那就加速吧
CDN github picgo 
`https://cdn.jsdelivr.net/gh/xanggiyan/img@main`