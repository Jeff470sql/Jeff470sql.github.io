---
title: "LLM"
subtitle: "Welcome to the world of models"
layout: post
author: "Jeff"
published: false
header-style: text
tags:
  - CS Idols
---

### Optimization
当遇到critical point(也就是gradient为0或趋近于0的位置)：
**local minima**：掉入陷阱，无路可走。
**saddle point**：可以escape这个陷阱。
**local maxima**
可以使用Hessian来判断是属于哪一种critical point，本质上是判断二阶导数的驻点。
对于Hessian矩阵，计算出它的eigen value：
如果全部大于0，那么就是local minima
如果全部小于0，那么就是local maxima
如果部分大于0、部分小于0，那么就是saddle point
