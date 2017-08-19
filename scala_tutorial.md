# Scala入门教程 #

## 目录 ##
* [第0章 - Scala概述](#第0章)
* [第1章 - 熟悉 IntelliJ IDEA](#第1章)
* [第2章 - 基础](#第2章)
* [第3章 - 函数](#第3章)
* [第4章 - 类](#第4章)
* [第5章 - 使用Trait](#第5章)
* [第6章 - 不可变集合](#第6章)
* [第7章 - 可变集合](#第7章)
* [第8章 - 集合函数](#第8章)

### 第0章 ###
> Scala 概述

1. [Scala 介绍](0_1.md)
2. [Scala 编程语言](0_2.md)
3. [Scala 函数编程功能及相关内容](0_3.md)


### 第1章
> 熟悉 IntelliJ IDEA

1. [本章介绍](1_1.md)
1. [Scala环境设置 – 安装 Java Development Kit (JDK)](1_2.md)
1. [Scala环境设置 – 怎样安装 IntelliJ IDE](1_3.md)
1. [Scala环境设置 – 怎样在IntelliJ中安装 Scala 插件](1_4.md)
1. [第一个Scala程序 - Hello World](1_5.md)
1. [从main方法运行Scala应用](1_6.md)
1. [运行你的Scala应用](1_7.md)
1. [调试你的Scala应用](1_8.md)
1. [Scala 项目入门](1_9.md)
1. [Scala 项目Classpath](1_10.md)
1. [build.sbt 入门](1_11.md)
1. [SBT 依赖和Maven](1_12.md)
1. [IntelliJ 设置和首选项](1_13.md)
1. [IntelliJ 导航快捷键](1_14.md)
1. [IntelliJ 搜索快捷键](1_15.md)
1. [IntelliJ 快捷键 – 编译, 调试，运行](1_16.md)


### 第2章
> 学习Scala基础

1. [章节介绍](2_1.md)
1. [变量和数据类型](2_2.md)
1. 字符串插值
1. 如何字符转义和创建多行字符串
1. 类型推导
1. If Else 语句和表达式
1. For 循环
1. Range 表达式
1. While 和 Do While 循环
1. 模式匹配
1. 元组（Tuples）
1. Option
1. 类的层次结构
1. 枚举（Enumerations)

### 第3章
> 在函数上思考

1. 章节介绍
1. 函数
1. 函数 - 参数
1. 函数 - Option类型参数
1. 函数 - 返回Option类型
1. 函数 - 隐式参数
1. 隐式函数
1. 泛型函数
1. 多态函数 - 返回通用类型
1. 函数 - 可变参数
1. 函数作为符号
1. 函数柯里化 - 使用参数组
1. 高阶函数
1. 高阶函数 - 传名调用
1. 高阶函数 - Callback参数
1. 函数定义使用 Val 代替 Def
1. 函数组合 - 使用AndThen
1. 函数组合 - 使用Compose
1. 尾递归函数 - @annotation.tailrec
1. 尾递归函数 - scala.util.control.TailCalls._
1. 蹦床(Trampoline)尾递归函数 - 使用scala.util.control.TailCalls._
1. 偏函数 - 使用PartialFunction Trait
1. 嵌套函数

### 第4章
> 你认为自己了解面向对象编程吗？

1. [本章介绍](4_1.md)
1. [类和对象](4_2.md)
1. [伴生对象 (Companion Objects)](4_3.md)
1. [伴生对象的Apply方法作为工厂方法 (通过类的继承实现)](4_4.md)
1. [伴生对象中的字段和值](4_5.md)
1. [单例对象 (Singleton Object)](4_6.md)
1. [Case Class](4_7.md)
1. [类型别名: 类型别名 VS Case Class](4_8.md)
1. [隐式类 - 扩展方法](4_9.md)
1. [包对象(Package Objects)](4_10.md)
1. [继承抽象类](4_11.md)
1. [Case Class 继承](4_12.md)
1. [Type Class](4_13.md)
1. [协变(Covariance)](4_14.md)
1. [逆变(Contra-Variance)](4_15.md)

### 第5章
> Dependency Injection reinvented using traits

1. 章节介绍
2. 创建 Trait 和继承 Trait
3. 带有泛型参数的 Trait
4. 继承多个 Trait
5. 依赖注入 - 使用 Traits (Part 1)
6. 依赖注入 - 使用 Traits (Part 2 - 避免Cake模式）
7. Traits, 伴生对象(Companion Objects), 工厂模式


### 第6章
> Immutable 集合

1. [本章介绍](6_1.md)
1. [List](6_2.md)
1. [ListSet](6_3.md)
1. [ListMap](6_4.md)
1. [Map](6_5.md)
1. [HashMap](6_6.md)
1. [TreeMap](6_7.md)
1. [Queue](6_8.md)
1. [Sequence](6_9.md)
1. [Set](6_10.md)
1. [HashSet](6_11.md)
1. [TreeSet](6_12.md)
1. [SortedSet](6_13.md)
1. [BitSet](6_14.md)
1. [Stack](6_15.md)
1. [Stream](6_16.md)
1. [Vector](6_17.md)


### 第7章
> Mutable 集合

1. [本章介绍](7_1.md)
1. [Array](7_2.md)
1. [ArrayBuffer](7_3.md)
1. [ArrayStack](7_4.md)
1. [ListBuffer](7_5.md)
1. [Map](7_6.md)
1. [HashMap](7_7.md)
1. [ListMap](7_8.md)
1. [LinkedHashMap](7_9.md)
1. [Queue](7_10.md)
1. [PriorityQueue](7_11.md)
1. [Set](7_12.md)
1. [HashSet](7_13.md)
1. [SortedSet](7_14.md)
1. [TreeSet](7_15.md)
1. [LinkedHashSet](7_16.md)
1. [BitSet](7_17.md)


### 第8章
> 集合函数

* 本章介绍
* 函数: aggregate	
* 函数: collect
* 函数: diff	
* 函数: drop
* 函数: dropWhile	
* 函数: exists
* 函数: filter & filterNot	
* 函数: find
* 函数: flatMap	
* 函数: flatten
* 函数: fold	
* 函数: foldLeft
* 函数: foldRight	
* 函数: foreach
* 函数: groupBy	
* 函数: head
* 函数: isEmpty	
* 函数: intersect
* 函数: last	
* 函数: map
* 函数: max	
* 函数: maxBy


### 第9章
> Futures
