---
layout: post
title: java中赋值及引用问题
date: 2017-11-02 
tags: java基础    
---


### 什么是赋值

&emsp;&emsp;赋值使用操作符“=”。他的意思是“取右边的值，把它赋值给左边”。右边的值可以是常数，变量或者表达式。左边必须是一个明确的、已命名的变量。也就是说，必须有一个物理空间可以存储等号右边的值。例如`a=4;`但是不能把任何东西赋给一个常数，比如`4=a;`。    
### 常见问题
&emsp;&emsp;我们在为对象赋值的时候，可能会出现不同的效果。对一个对象进行操作时，我们真正操作的是对对象的引用。所以假如要**将一个对象赋值给另一个对象**，实际是将**引用**从一个地方复制到另一个地方。这意味着假如对对象使用**c=d**,那么**c**和**d**都指向原本只有d指向的那个对象。  
**例如这个小例子：**  
![](http://quhailong.top/images/posts/javase/1.png)
**输出结果为**
![](http://quhailong.top/images/posts/javase/2.png)
<br>

转载请注明：[屈海龙的博客](http://quhailong.top) » [java中赋值及引用问题](http://quhailong.top/2017/11/Assignment/)                   

