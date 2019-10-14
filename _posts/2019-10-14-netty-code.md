---
layout: post
title: Netty源码剖析与实战(视频课))
date: 2019-10-13
categories: test
tags: 算法 数据结构
---

## 一、作者介绍

傅健，Netty 源码贡献者。

思科中国研发中心平台软件工程师，毕业后一直在思科工作，已有 9 年。做过很多项目，从移动端应用到文档存储系统、从消息系统到电话接入系统，接触过很多不同类型的开源软件且很喜欢深究原理，所以现在也是 Netty、Jedis、Spring Data Redis、influxdb–java、Jenkins 等很多开源项目的 Contributor 。

博客：[strolling.cn](http://www.strolling.cn)
github：[jiafu1115](https://github.com/jiafu1115)

## 二、专栏介绍

历经 15 年，Netty 目前已经是 Java 网络编程最热门的框架，是我们开发高性能 Java 服务器的必学框架。它不仅包含了丰富的网络知识，也蕴含了很多 Java 编程的高阶技巧，所以它也是我们学习 Java 、学习网络编程不可多得的经典案例。

用 Netty 写一个简单的网络应用程序很简单，但是学习 Netty 的内部原理、了解它到底怎么工作起来的，却是一个比较漫长的过程，因为它不仅要求对 Java 编程的高阶知识有掌握，还要懂网络知识。同时，Netty 包含了各种算法、优化策略在其中，这也是 Netty 学习的难点之一。

因此，本课程在内容设计上会遵循一个由浅入深的原则。先介绍 Netty 的来龙去脉以及它的发展趋势。随后带你从“点”（领域知识）和“线”（请求处理）这两个维度深入到 Netty 的源码中去理解它的核心功能和原理。之后进入实战部分，首先带着你写一个简单的“玩具”项目，快速上手 Netty，然后逐步去丰富、优化这个项目，将它打磨成一个能够应用到企业生产环境中的成熟产品。最后，我们还会看看其他优秀的开源项目是如何使用 Netty 的，有哪些可以借鉴的地方。

[专栏官方介绍](https://time.geekbang.org/course/intro/237)

## 三、专栏数据

2019年10月推出新专栏，目前尚未完结。专栏每周三更新视频，全部课程预计将于 2019年12月12日更新完成。

专栏订阅数量：2.9k+

## 四、欢迎加入

专栏价格：¥ 129 元

极客不定期会推出拼团优惠活动，最终价格以官方为准。

直接点击站长的[购买链接](https://time.geekbang.org/course/intro/237?code=MVFQA9dEQnRNJDTS6VYmjaKRxJ1pXVsr4UH8eroKnO4%3D&utm_term=SPoster)订阅专栏。

也可以直接使用微信扫码订阅。

[![image.png](https://i.postimg.cc/K8ctNR7R/image.png)](https://time.geekbang.org/course/intro/237?code=MVFQA9dEQnRNJDTS6VYmjaKRxJ1pXVsr4UH8eroKnO4%3D&utm_term=SPoster)

添加站长助理微信（xu952685333），备注返现，发送课程订阅截图以及极客时间昵称， 购买 3 天之后可获得 50% 返佣。