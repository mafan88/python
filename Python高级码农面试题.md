笔者已经不使用`Python`多年，应年轻人邀请假设作为面试官的话，会问哪些问题呢。下面整理笔者可能提出的`Python`高级码农面试题如下。 

鉴于笔者长期不使用`Python`，如有谬误，欢迎斧正。 


1. 循环内创建正则表达式然后直接使用，可以吗？说明理由
2. 代码中多处重复定义的常量字符串，会保留几份呢？比如*China Power Boy* 出现1000次。
3. 动态属性有哪几种实现方式，说说你使用动态属性的场景
4. `Python`处理128和1024两个整数有什么不同呢？
5. 说说你阅读`Python`编译器源代码后，对编程什么帮助？如果没有阅读过源代码也努力说一说。
6. 第三方知名框架和你的项目代码有什么不同呢？说说看，框架使用了哪些高级语言特性
7. 使用监控工具监控`Python`程序，有什么注意事项？你监控过吗？
8. 正常运行的`Python`程序经常死掉，你准备怎么优化呢
9. 复杂参数列表作为函数参数，和字典作为函数参数，有效率区别吗？请说明原因。形如如下两种函数参数方式

```
def func(a, b, c, d, e, f, g)
....

def func(dictX) 
```
