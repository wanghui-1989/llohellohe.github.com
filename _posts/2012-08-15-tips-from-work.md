---
layout: post
category: 给自己的提醒
title: 给自己的一点提醒
description: 工作上要注意的事项
tags : [工作, 注意事项]
keywords: 注意事项,小心

---

##关于性能测试

每次有新的数据源变更，尤其是新增数据源的时候，切记以下步骤：

1. 原有的性能如何？并且进行性能评估和测试。
2. 现在的性能如何？满足要求吗？
3. 再次确认峰值访问量下能否承受住压力.

##关于程序健壮性
1.	你提供给别人的服务如果挂了，会导致服务消费者挂了吗？是否需要加上容错（try catch）。
2.	你的服务挂了，有可能是数据源错了、数据解析出错、服务超时等。请再三考虑这些问题。

##线上环境
1.	线上环境和线下环境在源代码一致的情况下出问题，很可能是配置项等的原因。要第一时间想到这点。