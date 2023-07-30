---
layout: '../../layouts/MarkdownPost.astro'
title: 'UML 统一建模语言'
pubDate: 2035-07-29
description: '软件设计师'
author: '软件设计师考证笔记'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/values/environment/Apple-Earth-Day-India-mangrove-Alibaug-canoe_Full-Bleed-Image.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/values/environment/Apple-Earth-Day-India-mangrove-Alibaug-canoe_Full-Bleed-Image.jpg.large_2x.jpg'
    alt: 'cover'
tags: ["UML","统一建模语言","软件设计师笔记"]
theme: 'dark'
featured: True
---　

# 可视化建模语言（UML）
非程序设计语言。包括 构造快（重要）、规则（未考过）、公共机制（未考过）
构造快：组成 事务+关系+图
# 关系模式
依赖关系：人依赖空气的变化而变化
关联：现实生活关系中存在最广泛的关系  分为组合（共同生命周期）和聚合（非共同生命周期）关系 部分和整体的关系
泛化：一般/特殊之间的关系，子类和父类的关系
实现：一个类元制定了另一个类元保证执行的契约
# 关系图(UML2.0图)
 UML图 分为静态图（结构图） 动态图（行为图） 

 类图（静态设计视图）  对象、接口、协作和他们之间的关系
 对象图 是类图的快照 某一时刻一组对象及他们之间的关系
 用例图（翻译：功能 重要）用例、参与者以及他们之间的关系
    参与者 即实体
    关系有 扩展（执行某一个操作的时候，可做可不做另一个命令、
    包含（执行某一个操作的时候，必须先执行一个命令）、
    泛化（父子关系）
序列图（顺序图） 以时间顺序组织的对象之间的交互活动
    特征：对象生命线 对象是长方形 有时间线
    同步消息（阻塞调用 实心三角箭头） 异步消息（发出后继续执行 空心肩头） 返回消息（从右往左 虚线表示）
通信图 协作图 消息链 有序号 消息传递
状态图 （动态图）状态机 
    特征：圆角矩形 状态框 事件触发器 触发事件 满足监护条件 进行检查