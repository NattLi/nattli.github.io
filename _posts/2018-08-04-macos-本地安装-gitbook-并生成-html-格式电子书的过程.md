---
title: "macOS 本地安装 gitbook 并生成 html 格式电子书的过程"
date: "2018-08-04"
categories: 
  - "skills"
tags: 
  - "gitbook"
  - "gitbook教程"
  - "mac"
  - "macos"
---

第一步：安装node.js

https://nodejs.org/en/download/

第二步：第二步：安装gitbook

npm install gitbook-cli -g 或者 sudo npm install gitbook-cli -g

第三步：初始化 记得选择目标文件夹，然后： gitbook init

第四步：粘入内容 将md文件都拷入目标文件夹

第五步：生成 gitbook build

第六步：上传 将 \_book 文件夹传到网站服务器，即可
