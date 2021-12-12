---
title: "Java 8种基本类型"
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: [ "dubbo", "rpc", "java"]
keywords: []
description: "Java 8种基本类型"
---

## Java 8种基本类型有哪些？

基本类型，或者叫做内置类型，是Java中不同于类(Class)的特殊类型。它们是我们编程中使用最频繁的类型。

Java是一种强类型语言，第一次申明变量必须说明数据类型，第一次变量赋值称为变量的初始化。

Java基本类型共有八种，基本类型可以分为三类：

> 字符类型`char`
> 
> 布尔类型`boolean`
> 
> 数值类型`byte`、`short`、`int`、`long`、`float`、`double`。

数值类型又可以分为整数类型`byte`、`short`、`int`、`long`和浮点数类型`float`、`double`。

Java中的数值类型不存在无符号的，它们的取值范围是固定的，不会随着机器硬件环境或者操作系统的改变而改变。

实际上，Java中还存在另外一种基本类型`void`，它也有对应的包装类 `java.lang.Void`，不过我们无法直接对它们进行操作。
