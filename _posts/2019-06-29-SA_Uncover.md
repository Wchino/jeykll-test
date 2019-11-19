---
title: "态势认知——还原"
date: 2019-06-29
layout: post
categories: SA
tags: 态势认知 还原
---
大量从不同来源观测获取的关于各类对象（如用户、设备、系统、体系等）的情报，包括通联行为、网络数据报文等结构化数据，以及文本、图像等非结构化数据。

















# 态势认知——还原


## 问题概述

**背景**：大量从不同来源观测获取的关于各类对象（如用户、设备、系统、体系等）的情报，包括通联行为、网络数据报文等结构化数据，以及文本、图像等非结构化数据。

例如，在信号获取领域，美军的EP-3电子侦察机可以从740千米外的地方截获雷达和其他通讯信号并进行追踪、分析。2001年4月1日，美国海军一架EP-3侦察机飞抵中国海域上空实施间谍活动，与前来驱离的PLA海军一架歼8II战机发生碰撞，并迫降海南陵水机场，引发震惊一时的[“中美南海撞机事件”](https://baike.baidu.com/item/4%C2%B71%E4%B8%AD%E7%BE%8E%E5%8D%97%E6%B5%B7%E6%92%9E%E6%9C%BA%E4%BA%8B%E4%BB%B6/9658219?fr=aladdin)。

![EP-3](http://img.hkwb.net/att/site2/20101227/76c54a85068d56bbaea1fcee8068c2e4.jpg)

可搭载各类大型设备的电子侦察船能接收并记录无线电通信、雷达和武器控制系统等电子设备所发射的电磁波信号，查明这些电子设备的技术参数和战术性能，获取对方的无线电通信和雷达配系等军事情报。PLA最新服役的815型电子侦察船，就频繁出现在美海军军演附近区域，“以其人之道还治其人”。

![815](http://5b0988e595225.cdn.sohucs.com/images/20180716/fc6994c375144cdfb6e2683e0a7da646.jpeg)

在网络领域中，有各类主动扫描探测的手段或系统，如[CAIDA](http://www.caida.org/home/)，以及被动接收网络数据包进行流量分析的工具，如[WireShark](https://www.wireshark.org)等。通过主被动的扫描、监听，再结合其他来源的情报，就有可能还原出网络中各层的实体、关系，生成网络空间地图。
![uncover](../../assets/graphs/uncover.gif)

**问题**：如何综合各维度的观测数据，有效还原所观测的对象的整体情况？具体包括：
- 有哪些实体存在？是什么类型？具备什么属性、特征？
- 实体之间存在什么关系？如何推断不可见的关系、识别深层、潜在的关系？
- 各实体在组织中承担什么角色，发挥什么作用？
- 如何形成关于观测对象的整体描述（表征、抽象）？


## 研究选题
 - [小样本/弱监督条件下知识抽取方法](./SA_Uncover_Knowledge.md)
 - [面向网络空间关键地形识别的知识获取与利用技术](./SA_Uncover_Kdata.md)
 - 数据与知识结合的（文本？）对象检测与识别
 - 基于机器学习的结构特征自动提取与结构还原
 - [基于小样本机器学习的非结构化文本关系抽取研究](./SA_Uncover_RE.md)
 - [面向还原与生成的网络空间知识化表示方法](./SA_Uncover_Reduction.md)