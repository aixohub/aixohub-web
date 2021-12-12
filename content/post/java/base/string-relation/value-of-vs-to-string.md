---
title: "int类型的变量变成String类型"
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: [  "String", "java"]
keywords: []
description: "int类型的变量变成String类型"
---

我们有三种方式将一个int类型的变量变成String类型，那么他们有什么区别？

    1.int i = 5;
    2.String i1 = "" + i;
    3.String i2 = String.valueOf(i);
    4.String i3 = Integer.toString(i);

第三行和第四行没有任何区别，因为String.valueOf(i)也是调用Integer.toString(i)来实现的。

第二行代码其实是String i1 = (new StringBuilder()).append(i).toString();，首先创建一个StringBuilder对象，然后再调用append方法，再调用toString方法。