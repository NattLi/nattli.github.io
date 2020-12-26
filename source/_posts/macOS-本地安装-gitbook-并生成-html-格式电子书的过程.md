---
title: macOS 本地安装 gitbook 并生成 html 格式电子书的过程
tags:
  - 技术
  - gitbook
  - gitbook教程
  - MAC
  - MACOS
excerpt: >-
  第一步：安装node.js https://nodejs.org/en/download/ 第二步：第二步：安&#8230; <a
  class="more-link" href="https://www.natt.cc/6166.html">继续阅读<span
  class="screen-reader-text">macOS 本地安装 gitbook 并生成 html 格式电子书的过程</span></a>
date: 2018-08-04 16:55:28
---

第一步：安装node.js https://nodejs.org/en/download/ 第二步：第二步：安… [继续阅读macOS 本地安装 gitbook 并生成 html 格式电子书的过程](https://www.natt.cc/6166.html)
<!-- more -->
第一步：安装node.js

https://nodejs.org/en/download/

第二步：第二步：安装gitbook

npm install gitbook-cli -g  
或者  
sudo npm install gitbook-cli -g

第三步：初始化  
记得选择目标文件夹，然后：  
gitbook init

第四步：粘入内容  
将md文件都拷入目标文件夹

第五步：生成  
gitbook build

第六步：上传  
将 \_book 文件夹传到网站服务器，即可