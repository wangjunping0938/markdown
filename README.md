MarkDown轻量级标记语言
===


## 目录

- [斜体&粗体](#斜体&粗体)
- [链接](#链接)
- [锚点](#锚点)
- [列表](#列表)


## 斜体&粗体

**语法**
```
*斜体* or _斜体_ or **粗体** or **_加粗斜体_** or ~~删除线~~
```

**预览**

*斜体* or _斜体_ or **粗体** or **_加粗斜体_** or ~~删除线~~


## 链接

**行内式语法**
```
常用搜索引擎
百度[baidu](https://www.baidu.com/)
谷歌[google](http://www.google.com "google")
搜狗[sogou](https://www.sogou.com/ "搜狗")
```

**行内式预览**

常用搜索引擎

百度[baidu](https://www.baidu.com/)

谷歌[google](http://www.google.com "google")

搜狗[sogou](https://www.sogou.com/ "搜狗")


**参考式语法**
```
常用网站
[github][1], [知乎][2], [python][3]
[python官网][3]是一个很不错的[网站][]

[1]:https://github.com "github"
[2]:https://www.zhihu.com "知乎"
[3]:https://www.python.org/ "python"
[网站]:https://www.python.org/
```

**参考式预览**

常用网站

[github][1], [知乎][2], [python][3]

[python官网][3]是一个很不错的[网站][]

[1]:https://github.com "github"
[2]:https://www.zhihu.com "知乎"
[3]:https://www.python.org/ "python"
[网站]:https://www.python.org/


**自动链接语法**
```
https://www.python.org/>
```

**自动链接预览**

<https://www.python.org/>


## 锚点

**语法**
```
跳转至[索引](#索引)
```

**预览**

跳转至[索引](#索引)


## 列表

**无序列表语法(-, +, = 效果相同)**
```
- 无序列表
- 无序列表
```

**无序列表预览**

- 无序列表
- 无序列表

**有序列表语法**
```
1. 有序列表
2. 有序列表
3. 有序列表
```

**有序列表预览**

1. 有序列表
2. 有序列表
3. 有序列表

**自定义列表语法**
```
Python

:   python是一门编程语言

示例代码

:   简单一个python代码

        print('hello world')
```

**自定义列表预览**

Python

:   python是一门编程语言

示例代码

:   简单一个python代码

        print('hello world')
