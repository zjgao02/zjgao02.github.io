---
title: '并行计算心得和总结'
date: 2022-12-22
permalink: /posts/2012/08/blog-post-4/
tags:
  - cool posts
  - category1
  - category2
---

基于openmp编程模型，先从粗粒度的层面对算法进行优化，此时就需要考验对算法本身的理解程度和基本的编程算法能力，此时要多次迭代，正确分析算法复杂度；后续进入细粒度层面优化，主要是在计算和访存之间做trade-off，向量化是一个很强大的工具，向量寄存器yyds!另外有些开放的问题，比如循环展开最合适的次数等等...
