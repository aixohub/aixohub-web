---
title: "java set和List 区别"
date: 2021-12-12T01:18:05-05:00
draft: false
author: "wangpwm"
tags: ["HashSet", "java"]
keywords: []
description: ""
---

List,Set都是继承自Collection接口。都是用来存储一组相同类型的元素的。

List特点：元素有放入顺序，元素可重复 。

有顺序，即先放入的元素排在前面。

Set特点：元素无放入顺序，元素不可重复。

无顺序，即先放入的元素不一定排在前面。
不可重复，即相同元素在set中只会保留一份。所以，有些场景下，set可以用来去重。
不过需要注意的是，set在元素插入时是要有一定的方法来判断元素是否重复的。这个方法很重要，决定了set中可以保存哪些元素。