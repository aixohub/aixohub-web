---
title: "String 的 append"
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: [ "dubbo", "rpc", "java"]
keywords: []
description: "String不可变好处"
---

1. String s = "a" + "b"，编译器会进行常量折叠(因为两个都是编译期常量，编译期可知)，即变成 String s = "ab"

2. 对于能够进行优化的(String s = "a" + 变量 等)用 StringBuilder 的 append() 方法替代，最后调用 toString() 方法 (底层就是一个 new String())
