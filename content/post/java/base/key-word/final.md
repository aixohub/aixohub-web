---
title: "java 关键字 final "
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: ["fianl", "java"]
keywords: []
description: "java Integer"
---

### 用法

- 修饰变量：
  - 编译期常亮：类加载的过程完成初始化，编译后带入到任何计算式中。只能是基本类型
  - 运行时常量：基本数据类型或引用数据类型。引用不可变，但引用的类型可变
  
- 修饰方法：不能被继承，不能被子类修改
- 修饰类：  不能被继承
- 修饰形参：final形参不可变

### final的好处：

1. final关键字提高了性能。JVM和Java应用都会缓存final变量。

2. final变量可以安全的在多线程环境下进行共享，而不需要额外的同步开销。

3. 使用final关键字，JVM会对方法、变量及类进行优化。
