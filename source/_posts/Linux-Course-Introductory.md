---
title: Linux课程大纲
date: 2025-02-26 22:46:09
author: April
img: https://www.notion.so/images/page-cover/nasa_earth_grid.jpg
top: true
cover: false
hide: false
toc: true
summary: 清华大学电机系“先导计划”Linux课程大纲
categories: Linux Course
tags: 
    - DEESAST
---

## 课程引言

欢迎大家选择 Linux 基础课程。本课程并不是系统的 Linux 学习课程，而是由网络上已有的众多资料和项目整合而来。实际上，Linux 相关的基础应用涉及到程序设计、计算机系统、网络原理等多个领域的基础知识。在 MIT 中，有一门由学生发起的“缺失的一课”，旨在覆盖一些正式课堂不会去讲，但是实际应用时又十分必要的零散的知识。本课程的定位大抵亦是如此。

学习任何一门计算机技术最好的办法就是**实践**。通过项目，你可以更直观更快速地理解一项技术涉及到的基本指令。除开课程的大作业，本课程在教学过程中会尽可能提供一些简易的项目实践供大家练习。但其实，正常使用的过程中，往往会不可避免地频繁查阅相关的手册与博客，学会在这个过程自我学习和校验即可。（颇有点用进废退的味道）

需要提醒的是，现在的大模型已经具有很强的编程能力，但比起简单地复用代码，**系统**的学习更需要你去理解每一行代码在干什么，否则，往往会引发不必要的错误和安全风险。多读官方的手册，多读报错，只有这样你才能更好地理解自己在做什么，要做什么。

---

## 课程大纲

| 1    | **Linux 系统概述**：Linux 简介；命令行与 Linux 基本命令；Linux 发行版本安装 |
| ---- | ------------------------------------------------------------ |
| 2    | **Linux 系统初探**：Linux 文件系统；Vim 编辑器；Linux 权限管理；Linux 进程管理 |
| 3    | **Linux 系统开发**：shell 脚本编程；Linux 环境下编程与调试；Linux 网络编程 |
| 4    | **Linux 项目案例**：Git 的使用；个人博客的搭建；Linux 开发案例分析 |
| 5    | **Linux 进阶与答疑**：面向对象、信号、线程与进程；嵌入式基础；软件开发基础 |

该表格为初版课程大纲，实际课程安排可能随课时数、课程进度及学员需求稍加调整。其中第5讲作为补充知识，视学员兴趣择选2～3个主题讲授。

---

## Linux 简介

Linux 是一个开源的操作系统内核，由芬兰程序员 Linus Torvalds 于1991年首次发布。它最初是作为 Minix（一个类 Unix 系统）的免费替代品而开发的。Linux 的诞生标志着自由软件运动的重要里程碑，它让任何人都能自由地使用、研究、修改和分享软件。

Linux 具有以下主要特性：

- **开源性**：源代码完全公开，任何人都可以查看和修改
- **多用户多任务**：支持多个用户同时使用系统，并能同时运行多个程序
- **安全性**：具有完善的用户权限管理机制，系统稳定性高
- **可移植性**：可以运行在各种硬件平台上，从智能手机到超级计算机
- **网络功能**：具有强大的网络支持，是互联网服务器的首选平台

Linux 的主要应用领域包括：

- **服务器市场**：支撑着互联网的大部分基础设施，包括网站服务器、云计算平台等
- **嵌入式系统**：应用于智能手机（Android 系统的核心）、智能家电、汽车系统等
- **超级计算机**：全球 TOP500 超级计算机中的绝大多数都运行 Linux 系统
- **个人桌面**：提供如 Ubuntu、Fedora 等用户友好的发行版，作为个人计算机的操作系统
- **开发环境**：为开发者提供强大的编程和开发工具支持

随着开源社区的不断发展，Linux 已经从一个简单的操作系统内核发展成为了一个庞大的生态系统，推动着现代信息技术的发展。无论是在商业应用还是个人使用方面，Linux 都展现出了强大的生命力和发展潜力。

---

## 课程目标与项目参考

课程希望通过简单的编程实验与具有一定规模的项目开发大作业，帮助同学们认识并较为熟练地使用 Linux 系统，同时建立系统编程和开发的基本概念，掌握自主学习并运用框架的能力，了解并实践团队协作的基本原则（如有组队开发项目的话）

### 以下为部分可参考的案例

- 以下内容摘自 xhr 学长的讲义：

  [**基于*Linux*的QT多平台兼容的打地鼠*游戏***](https://link.zhihu.com/?target=https%3A//github.com/zhangxq1/heatMouse)

  [**基于树莓派的智能垃圾分类系统**](https://blog.csdn.net/DanielSYC/article/details/117627527)

  [**使用树莓派建立一个具有移动连接功能的路由器**](https://opensource.com/article/21/3/router-raspberry-pi)

  除了以上项目之外，Linux嵌入式也可以很好地应用到电气工程领域，例如可以尝试利用嵌入式Linux平台（如树莓派）搭建一个智能电表监控系统，可以远程实时监测电表的用电情况。通过连接电表的通信接口，将实时数据上传至云端服务器，用户可以通过手机App或Web页面查看电能消耗情况，设置用电提醒、用电计划等功能，实现对电能的智能管理。

  （总之只要你认真思考，什么技术都能用到电气工程领域的对吧）

- 以下内容生成自大模型：

  [项目构思参考](https://www.notion.so/1a6b8e0aab55803d8e56d935e5ac5df5?pvs=21)

- 以下内容源自网络：

  [**【项目案例】嵌入式Linux比较好的10+练手项目推荐，附项目文档/源码/视频**](https://blog.csdn.net/u014170843/article/details/142181078)

  [**linux系统编程项目实践**](https://blog.csdn.net/itcastcpp/category_2516205.html)
