---
title: "String不可变好处"
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: [ "dubbo", "rpc", "java"]
keywords: []
description: "String不可变好处"
---



1. String 不可变？ final

- final
   - 首先因为String不可变，如果String不是final，那么子类可以继承，然后子类覆盖其方法，使得这些方法可以修改字符串，这样就违背了String的不可变性
- 不可变原因
    - 提高效率： 比如一个字符串String s1="abc", "abc"被放到常量池里面去了，再创建String s2 = "abc",不会
