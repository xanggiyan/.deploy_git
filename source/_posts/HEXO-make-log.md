---
title: HEXO make log
date: 2021-08-13 11:13:43
tags:
---
hexo make log

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
            repo: https://github.com/xanggiyan/xanggiyan.github.io.git
            branch: main
      2. git config --global http.sslVerify "false"