# 1. Markdown简介

## 1.1 Markdown简介

Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。  
Markdown具有一系列衍生版本，用于扩展Markdown的功能（如表格、脚注、内嵌HTML等等），
这些功能原初的Markdown尚不具备，它们能让Markdown转换成更多的格式，例如``LaTeX``，``Docbook``。
Markdown增强版中比较有名的有``Markdown Extra``、``MultiMarkdown``、 ``Maruku``等。
这些衍生版本要么基于工具，如Pandoc；要么基于网站，如GitHub和Wikipedia，在语法上基本兼容，但在一些语法和渲染效果上有改动。

## 1.2 注意事项及前提

1. 本文针对Jupter Notebook上的笔记进行pdf转化时发现，有些Markdown语法在转化成pdf时，会出现格式错误等问题，摸索出的原则是选择越简单的语法编写转化的pdf越准确。
目前可用的语法规则有：`标题`、`字体`、`超链接`、`表格`。  
2. 纯Markdown文本使用md文件编写最合适不过，这里用Jupyter只是为了熟练Jupyter。 
3. Jupyter 上编辑一般都使用Markdown和代码，原生NBConvert一般不用，传到Github上很难看。

## 1.3 目前存在的问题

1. 在转化为PDF时，存在自动的首行缩进。

## 1.4 参考网址

* [Markdown基本语法](https://www.jianshu.com/p/191d1e21f7ed)  
* [markdown语法之列表与缩进](https://blog.csdn.net/qq_33229669/article/details/81610939)

# 2. 标题




