---
layout: post
title:  Swift循环
date:   2015-03-08 22:21:49
categories: Swift
tags: Swift
---


<h2>Swift 循环</h2>

有的时候，我们可能需要多次执行同一块代码。一般情况下，语句是按顺序执行的：函数中的第一个语句先执行，接着是第二个语句，依此类推。
编程语言提供了更为复杂执行路径的多种控制结构。
循环语句允许我们多次执行一个语句或语句组，下面是大多数编程语言中循环语句的流程图：

<h3> 流程图</h3>

```flow

st=>start: Start
e=>end
op=>operation: 条件
cond=>condition: 条件为false、true?

st->op->cond
cond(yes)->e
cond(no)->op

```

<h4>循环类型</h4>

| 循环类型  | 描述
| :-------- | :--------
for-in | 遍历一个集合里面的所有元素，例如由数字表示的区间、数组中的元素、字符串中的字符。
for 循环 | 用来重复执行一系列语句直到达成特定条件达成，一般通过在每次循环完成后增加计数器的值来实现。
while 循环 | 运行一系列语句，如果条件为true，会重复运行，直到条件变为false。
repeat..while 循环| 类似 while 语句区别在于判断循环条件之前，先执行一次循环的代码块。 


<h4>循环控制语句</h4>

循环控制语句改变你代码的执行顺序，通过它你可以实现代码的跳转。
Swift 以下几种循环控制语句：

| 控制语句	|  描述
| :-------- | :--------
| continue语句 | 告诉一个循环体立刻停止本次循环迭代，重新开始下次循环迭代。
| break   语句 | 中断当前循环。
| fallthrough 语句 | 如果在一个case执行完后，继续执行下面的case，需要使用fallthrough(贯穿)关键字。

