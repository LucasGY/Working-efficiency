>微信公众号：**[码蚁LucasGY](#jump_10)**
**关注可了解更多的机器学习基础及工作效率提高技巧。问题或建议，请公众号留言**;
**[如果你觉得对你有帮助，欢迎赞赏](#jump_20)[^1]**

谢谢给位小伙伴厚爱，有人提出是否在写的过程中show一下代码，因此从本文章开始，用到的代码都会show出来，代码和笔记同时放在我的Github上，欢迎大家继续关注我的公众号。这里的关注指的是点击关注公众号哈！
### 公众号二维码
![勾越公众号](http://pzd8a646b.bkt.clouddn.com/勾越公众号.jpg)
<a id="jump_20"></a>

Working-efficiency Github地址：
* [LucasGY efficiency](https://github.com/LucasGY/Working-efficiency)



### 内容目录

[TOC]

### Tips for Jupyter Notebooks

之前我在自己的电脑上运行Jupyter的时候，由于本人不想在C盘放任何资料，导致每次在运行terminal的时候都要先`cd d:`，然后激活自己非默认的python环境，如`conda activate Tensorflow`，最后运行Jupyter。把大象装冰箱里有几个步骤，它就有几个步骤，个人感觉非常繁琐，因此今天分享一个个人感觉还算得上的小技巧，可以一劳永逸地解决在非C盘直接运行Jupyter Notebook。

#### 创建一个`.bat`文件

键入：
```dos
d:
call activate Tensorflow
jupyter-notebook
```
这三行命令。第一行表示你要切换的盘符；第二行表示激活“Tensorflow”名字的python环境，由于我对于DOS命令不是很了解，call命令大概是用来从一个批处理脚本中调用另一个批处理脚本的；最后运行`jupyter-notebook`命令，在D盘上加载Jupyter。
最后，将这个批处理文件存到固定的位置，之后的快捷方式要调用到这个位置。

至于如何创建bat批处理文件，就太简单了，可以自行百度。

#### 把批处理文件固定在开始菜单

1. 在桌面或者文件资源管理器中点击鼠标右键，新建→快捷方式
![2019-10-19-16-24-57](http://pzd8a646b.bkt.clouddn.com/2019-10-19-16-24-57.png)

2. 键入：
`cmd /k 你文件的绝对路径+文件名`
如图：
![2019-10-19-16-30-02](http://pzd8a646b.bkt.clouddn.com/2019-10-19-16-30-02.png)
3. 命名
![2019-10-19-16-33-43](http://pzd8a646b.bkt.clouddn.com/2019-10-19-16-33-43.png)
**至此，完成快捷方式的创建。**
4. 将快捷方式固定到开始屏幕
右击快捷方式：
![2019-10-19-16-34-48](http://pzd8a646b.bkt.clouddn.com/2019-10-19-16-34-48.png)

5. 完成
![2019-10-19-16-37-34](http://pzd8a646b.bkt.clouddn.com/2019-10-19-16-37-34.png)

这样就可以把桌面的这个快捷方式清掉了，以后可以直接点击开始菜单运行。
![2019-10-19-16-41-02](http://pzd8a646b.bkt.clouddn.com/2019-10-19-16-41-02.png)
<a id="jump_10"></a>

### 公众号二维码
![勾越公众号](http://pzd8a646b.bkt.clouddn.com/勾越公众号.jpg)
<a id="jump_20"></a>

### 赞赏码蚁LucasGY
