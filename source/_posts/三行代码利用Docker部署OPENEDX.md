---
title: 三行代码利用Docker部署OPENEDX
tags:
  - 技术
  - 网络
  - docker
  - LMS
  - openedx
excerpt: >-
  新部署一台 Ubuntu 14.04 的主机，SSH之后： 第一行代码，安装docker curl -sSL &#8230; <a
  class="more-link" href="https://www.natt.cc/6046.html">继续阅读<span
  class="screen-reader-text">三行代码利用Docker部署OPENEDX</span></a>
date: 2018-02-03 18:35:59
---

新部署一台 Ubuntu 14.04 的主机，SSH之后： 第一行代码，安装docker curl -sSL … [继续阅读三行代码利用Docker部署OPENEDX](https://www.natt.cc/6046.html)
<!-- more -->
新部署一台 Ubuntu 14.04 的主机，SSH之后：

第一行代码，安装docker  
`curl -sSL https://get.daocloud.io/docker | sh`

第二行代码，拉取镜像

`sudo docker pull wwj718/edx_cypress_docker:1.05`

第三行代码，运行  
`sudo docker run -itd -p 80:80 -p 2022:22 -p 18010:18010 wwj718/edx_cypress_docker:1.05`

参考：

`https://hub.docker.com/r/wwj718/edx_cypress_docker/`

`http://blog.just4fun.site/edx-cypress-cn-install-and-use.html`

`https://www.youtube.com/watch?v=24OiYPnTNv8`