---
title: "三行代码利用Docker部署OPENEDX"
date: "2018-02-03"
categories: 
  - "skills"
  - "tech"
tags: 
  - "docker"
  - "lms"
  - "openedx"
  - "技术"
---

新部署一台 Ubuntu 14.04 的主机，SSH之后：

第一行代码，安装docker `curl -sSL https://get.daocloud.io/docker | sh`

 

第二行代码，拉取镜像

`sudo docker pull wwj718/edx_cypress_docker:1.05`

 

第三行代码，运行 `sudo docker run -itd -p 80:80 -p 2022:22 -p 18010:18010 wwj718/edx_cypress_docker:1.05`

 

参考：

`https://hub.docker.com/r/wwj718/edx_cypress_docker/`

`http://blog.just4fun.site/edx-cypress-cn-install-and-use.html`

`https://www.youtube.com/watch?v=24OiYPnTNv8`
