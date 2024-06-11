---
layout:     post
title:      装GitBook请用低版本Node.js
date:       2024-04-16
---
![node](/images/202404/node.jpg)


在本地部署GitBook, 结果安装时候出现cb.apply报错。

查阅了一些资料，发现是 node 版本太高（我装的是18.x 的LTS），于是删了 node 18, 重新装了  node 10.x 后，gitbook 顺利安装。
