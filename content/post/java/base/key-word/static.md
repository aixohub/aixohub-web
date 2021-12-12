---
title: "java 关键字 static"
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: ["static", "java"]
keywords: []
description: "java Integer"
---

### 用法

- 修饰变量：静态变量随着类加载时而被完成初始化，内存中只有一个，且JVM也只会为它分配一次内存，所有类共享静态变量
- 修饰方法：在类加载的时候就存在，不依赖任何势力；static方法必须实现，不能用abstract修饰
- 修饰代码块：在类加载完之后就会执行代码块中的内容
- 加载顺序： 父类静态代码块 -> 子类静态代码块 -> 父类非静态代码块 -> 父类构造方法 -> 子类非静态代码块 -> 子类构造方法



### static方法是否可以覆盖？

static方法不能被覆盖，因为方法覆盖是基于运行时动态绑定的，而static方法是编译时静态绑定的。

static方法跟类的任何实例都不相关，所以概念上不适用。