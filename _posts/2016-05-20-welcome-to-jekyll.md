---
layout: page
title:  "Zi Liang 第一条"
subtitle: "灯火可亲，有梦可做"
date:   2020-09-12 21:21:21 +0530
categories: ["1"]
---
#搭建个人技术博客

>使用Github pages + jekyll 快速部署个人博客

>- Github pages:
 - 给所有注册用户提供一个个人主页
 - 如何访问:个人域名、用户名、GitHub.io
 - 如何编写主页:建立一个用域名为项目名的远程版本仓库，只需要向远程版本仓库中的master分支提交代码即可（该代码必须有一个文件叫index.html）
- jekyll:
 - 定义:可以将Markdown语法自动编译成HTML语法的一个工具
 - 安装:不需要我们自己安装，在GitHub网站中预安装
 - 使用:当你请求使用个人域名的时候，GitHub服务器会读取仓库（以个人域名命名的远程版本仓库）中的master分支中的代码，如果该代码为Markdown语法会自动使用jekyll将其编译为HTML并返回客户端。

- 建立一个以个人域名为项目名的远程版本仓库
 - 访问一个网址：http://jekyllthemes.org/ 选择一个主题将其代码复制到我们仓库中的master分支
 - 以上操作可以合并为一步，在主题仓库中点击fork，点击setting设置仓库名，即可
 - 将远程版本仓库中的代码克隆到本地
 - 修改配置文件以及页面内容
 - 书写博客