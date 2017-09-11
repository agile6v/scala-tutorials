# Scala入门指南 #


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

1. [Scala 介绍](tutorial/0_1.md)
2. [Scala 编程语言](tutorial/0_2.md)
3. [Scala 函数编程功能及相关内容](tutorial/0_3.md)


### 第1章
> 熟悉 IntelliJ IDEA

1. [本章介绍](tutorial/1_1.md)
1. [Scala环境设置 – 安装 Java Development Kit (JDK)](tutorial/1_2.md)
1. [Scala环境设置 – 怎样安装 IntelliJ IDE](tutorial/1_3.md)
1. [Scala环境设置 – 怎样在IntelliJ中安装 Scala 插件](tutorial/1_4.md)
1. [第一个Scala程序 - Hello World](tutorial/1_5.md)
1. [从main方法运行Scala应用](tutorial/1_6.md)
1. [运行你的Scala应用](tutorial/1_7.md)
1. [调试你的Scala应用](tutorial/1_8.md)
1. [Scala 项目入门](tutorial/1_9.md)
1. [Scala 项目Classpath](tutorial/1_10.md)
1. [build.sbt 入门](tutorial/1_11.md)
1. [SBT 依赖和Maven](tutorial/1_12.md)
1. [IntelliJ 设置和首选项](tutorial/1_13.md)
1. [IntelliJ 导航快捷键](tutorial/1_14.md)
1. [IntelliJ 搜索快捷键](tutorial/1_15.md)
1. [IntelliJ 快捷键 – 编译, 调试，运行](tutorial/1_16.md)


### 第2章
> 学习Scala基础

1. [章节介绍](tutorial/2_1.md)
1. [变量和数据类型](tutorial/2_2.md)
1. [字符串插值](tutorial/2_3.md)
1. [如何转义字符和创建多行字符串](utorial/2_4.md)
1. [类型推导](tutorial/2_5.md)
1. [If Else 语句和表达式](tutorial/2_6.md)
1. [For 循环](tutorial/2_7.md)
1. [Range 表达式](tutorial/2_8.md)
1. [While 和 Do While 循环](tutorial/2_9.md)
1. [模式匹配](tutorial/2_10.md)
1. [元组(Tuples)](tutorial/2_11.md)
1. [Option](tutorial/2_12.md)
1. [类的层次结构](tutorial/2_13.md)
1. [枚举（Enumerations)](tutorial/2_14.md)

### 第3章
> 以函数角度思考

1. [章节介绍](tutorial/3_1.md)
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

1. [本章介绍](tutorial/4_1.md)
1. [类和对象](tutorial/4_2.md)
1. [伴生对象 (Companion Objects)](tutorial/4_3.md)
1. [伴生对象的Apply方法作为工厂方法 (通过类的继承实现)](tutorial/4_4.md)
1. [伴生对象中的字段和值](tutorial/4_5.md)
1. [单例对象 (Singleton Object)](tutorial/4_6.md)
1. [Case Class](tutorial/4_7.md)
1. [类型别名: 类型别名 VS Case Class](tutorial/4_8.md)
1. [隐式类 - 扩展方法](tutorial/4_9.md)
1. [包对象(Package Objects)](tutorial/4_10.md)
1. [继承抽象类](tutorial/4_11.md)
1. [Case Class 继承](tutorial/4_12.md)
1. [Type Class](tutorial/4_13.md)
1. [协变(Covariance)](tutorial/4_14.md)
1. [逆变(Contra-Variance)](tutorial/4_15.md)

### 第5章
> 使用traits重新实现依赖注入

1. [章节介绍](tutorial/5_1.md)
2. [创建 Trait 和继承 Trait](tutorial/5_2.md)
3. [带有泛型参数的 Trait](tutorial/5_3.md)
4. [继承多个 Trait](tutorial/5_4.md)
5. [依赖注入 - 使用 Traits (Part 1)](tutorial/5_5.md)
6. [依赖注入 - 使用 Traits (Part 2 - 避免Cake模式）](tutorial/5_6.md)
7. [Traits, 伴生对象(Companion Objects), 工厂模式](tutorial/5_7.md)


### 第6章
> 不可变集合

1. [本章介绍](tutorial/6_1.md)
1. [List](tutorial/6_2.md)
1. [ListSet](tutorial/6_3.md)
1. [ListMap](tutorial/6_4.md)
1. [Map](tutorial/6_5.md)
1. [HashMap](tutorial/6_6.md)
1. [TreeMap](tutorial/6_7.md)
1. [Queue](tutorial/6_8.md)
1. [Sequence](tutorial/6_9.md)
1. [Set](tutorial/6_10.md)
1. [HashSet](tutorial/6_11.md)
1. [TreeSet](tutorial/6_12.md)
1. [SortedSet](tutorial/6_13.md)
1. [BitSet](tutorial/6_14.md)
1. [Stack](tutorial/6_15.md)
1. [Stream](tutorial/6_16.md)
1. [Vector](tutorial/6_17.md)


### 第7章
> 可变集合

1. [本章介绍](tutorial/7_1.md)
1. [Array](tutorial/7_2.md)
1. [ArrayBuffer](tutorial/7_3.md)
1. [ArrayStack](tutorial/7_4.md)
1. [ListBuffer](tutorial/7_5.md)
1. [Map](tutorial/7_6.md)
1. [HashMap](tutorial/7_7.md)
1. [ListMap](tutorial/7_8.md)
1. [LinkedHashMap](tutorial/7_9.md)
1. [Queue](tutorial/7_10.md)
1. [PriorityQueue](tutorial/7_11.md)
1. [Set](totorial/7_12.md)
1. [HashSet](tutorial/7_13.md)
1. [SortedSet](tutorial/7_14.md)
1. [TreeSet](tutorial/7_15.md)
1. [LinkedHashSet](tutorial/7_16.md)
1. [BitSet](tutorial/7_17.md)


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
