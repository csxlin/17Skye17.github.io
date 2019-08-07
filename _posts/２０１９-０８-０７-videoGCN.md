---
title: 'Video+GCN'
date: 2019-08-07
permalink: /posts/2012/08/blog-post-21/
tags:
  - Action Recognition
  - GCN
---

**Videos as Space-Time Region Graphs** (Xiaolong Wang)

用GCN来建模视频动作识别：　

1.建模相关物体长范围的相似性关联；

2.建模相邻物体的时空关联。

大致方法：将输入的视频帧当做一个space-time region graph，其中每个node表示视频中的ROI，node之间有两种edge:１.外观相似度; 2.时空近似。
