# CppPrimer-Chap3

第2章是讲了C++的**内置类型**（是由C++语言直接定义的），这一章是讲**标准库**类型。这一章讲最重要的两个标准库类型：

 - `string`：支持可变长字符串；
 - `vector`：表示可变长集合。
 - 还有一个标准库类型**迭代器**，它是`string`和`vector`的配套类型，常被用于访问`string`中的字符或`vector`中的元素。

## 命名空间using声明
`std::cin`的意思是要使用命名空间`std`中的名字`cin`。但每次都打上`std`未免太麻烦，要想简化，**最安全**的方法是使用**using声明**：
```c++
using namespace::name; //一般格式
using std::cin; //举例
```

**注意：**

    1. 用到的每个名字都必须有自己的声明语句，而且每句话都得以分号结束；
    2. 头文件不应包含using声明，因为头文件的内容会拷贝到所有引用它的文件中去；

## 标准库类型string
使用`string`类型必须首先包含`string`头文件。作为标准库的一部分，`string`定义在命名空间`std`中。
```c++
#include<string>
using std::string;
```

## 标准库类型vector



## 迭代器介绍
## 数组
## 多维数组