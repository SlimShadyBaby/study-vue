# JavaScript

## 基础语法

### 数据类型

1. 分为5种：string, number, boolean, object, function
2. 3种对象类型: Object, Date, Array
3. 不包含任何值的数据类型: null, undefined

### typeof

查看变量的数据类型

### instanceof

用于判断变量是否是某个类型的实例

### 变量的定义

不区分数据类型，都使用var进行声明

``` js
    var name = "jack ma";
    var age = 18;
    var is_leader = true;
    var temp;
    var animal = new Array("dog", "cat", "pig");
    var animal = {type="dog", name="ww", color="yellow"}
```

### 字符串

1. 常用的属性与方法: length, trim, indexOf, split, replace, replaceAll, substr, substring, toLowerCase, toUpperCase
2. 特殊字符的转义:

### 运算符

1. 算术运算符: +, -, *, /, %, ++, --
2. 赋值运算符: =, +=, -=, *=, /=, %=
3. 比较运算符: ==, ===(类型也必须相等), !=, !==, >, <, <=, >=, ?:
4. 逻辑运算符: &&（and）, ||(or), !(not)
5. 类型运算符: typeof, instanceof
6. 位运算符: &(与), |(或), ~(非), ^(异或，相同为0，不同为1), <<(左移), >>(右移), >>>(无符号右移)
7. ??:为空返回右侧值
8. ?.:可选链操作

## 常用的对象和函数

### Array

用于定义数组对象，包含以下常用方法：slice, toString, push, pop, reverse, sort, filter, forEach

### Date

处理时间，常用方法：setFullYear, getFullYear, setHours, getHours

### Math

数学运算，常用方法：random, round, ceil, floor, abs, pow, sqrt

### 常用函数

1. setInterval: 定时器
2. setTimeout: 定时执行一次
3. eval: 定义变量 -> eval("var a = 1");
         执行方法 -> eval("mytest()");
         定义对象 -> eval("{id: 5}");

## 常用事件

1. onchange: html元素改变事件,常用于文本输入框和下拉选择框
2. onclick: 点击html元素
3. onmouseover: 在html元素上移动鼠标
4. onmouseout: 在html元素上移开鼠标
5. onkeydown: 按下键盘
6. onload: 浏览器已完成页面的加载
7. onresize:
8. onscroll:
9. onfocus:
10. onblur:

