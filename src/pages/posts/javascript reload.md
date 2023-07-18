---
layout: '../../layouts/MarkdownPost.astro'
title: 'JAVASCRIPT 快速执行'
pubDate: 2035-07-18
description: '代码'
author: 'Apple Newsroom'
cover:
    url: 'https://www.apple.com.cn/newsroom/images/values/environment/Apple-Earth-Day-India-mangrove-Alibaug-canoe_Full-Bleed-Image.jpg.large_2x.jpg'
    square: 'https://www.apple.com.cn/newsroom/images/values/environment/Apple-Earth-Day-India-mangrove-Alibaug-canoe_Full-Bleed-Image.jpg.large_2x.jpg'
    alt: 'cover'
tags: ["python","JAVASCRIPT","记录"]
theme: 'dark'
featured: True
---　

# JAVASCRIPT 快速在控制台定时刷新和执行网页任务 简单快捷的命令
这段代码可以在浏览器控制台定时循环的执行一段代码和动作
```javascript
let intervalId = setInterval(function(){ 
    location.reload(); 
}, 10000);

// 当你想要停止刷新时，运行以下代码：
clearInterval(intervalId);
```
