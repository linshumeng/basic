# how to use python

## The Most Popular Programming Languages

![The Most Popular Programming Languages](./The%20Most%20Popular%20Programming%20Languages.jpeg)

## What can we do using python?

1. Automation
2. Web Scraping
3. Data Analysis & Data Science
4. Web Development
5. Machine Learning & Artificial Intelligence

## Environment

### What is python environment?

环境由解释器、库（通常是 Python 标准库）以及一组已安装的包组成。

### pip and conda

pip 是 Python 包管理工具，conda 是一个开源的软件包管理系统和环境管理系统。

pip 对 Python 包进行管理，而 conda 不仅能进行包管理，还能够创建隔离的环境，该环境可以包含不同版本的 Python 和或其中安装的软件包。

### CMD Commands

py3 表示创建环境的名字，后面 python=3.5 表示创建环境 python 的版本
`conda create -n py3 python=3.5`

激活 py3
`activate py3`

列出所有环境
`conda env list`

删除环境
`conda env remove -n py3`

查看 python 版本
`python`

在当前环境里安装 ipykernel
`conda install ipykernel`

## library and framework

你调用库(library)来写程序，整体的流程，结构，标准都是你说了算。而框架(framework)，则反过来，是框架(framework)在"调用"你。

数据可以封装在容器(列表 元组 字符串 字典)里面;

代码可以封装在 function 里面;

function 和数据可以封装在 class 里面(或者说方法和属性可以封装在类里面);

上述三类内容可以打包在 module(模块)里面;

多个 module 可以打包在 package(包)里面;

多个 package 可以打包在 library(库)里面。

## if

### if not

在 python 中 None, False, 空字符串"", 0, 空列表[], 空字典{}, 空元组()都相当于 False。

if 条件语句后面需要跟随 bool 类型的数据，即 True 或者 False。然而，如果不是 bool 类型的数据，可以将其转换成 bool 类型的数据，转换的过程是隐式的。

在 Python 中，None、空列表[]、空字典{}、空元组()、0 等一系列代表空和无的对象会被转换成 False。除此之外的其它对象都会被转化成 True。

使用 if not x 这种写法的前提是：必须清楚 x 等于 None, False, 空字符串"", 0, 空列表[], 空字典{}, 空元组()时对你的判断没有影响才行。

## other

### remove

for loop + remove:

- 因为 for 循环实际是循环的列表下标（索引），同时由于列表的可变性，每一次删除一个元素，列表的长度就会发生变化，元素的索引也会发生变化。
- 可以使用 deepcopy 来复制一份，之后一个列表用于循环，一个用于移除值。

## class

### "\_"

\_single_leading_underscore: weak "internal use" indicator. E.g. from M import \* does not import objects whose name starts with an underscore.

single_trailing_underscore\_: used by convention to avoid conflicts with Python keyword, e.g. Tkinter.Toplevel(master, class\_='ClassName')

\_\_double_leading_underscore: when naming a class attribute, invokes name mangling (inside class FooBar, \*\*boo becomes \_FooBar\_\_boo; see below).

\_\_double_leading_and_trailing_underscore\_\_: "magic" objects or attributes that live in user-controlled namespaces. E.g. \_\_init\_\_, \_\_import\_\_ or \_\_file\_\_. Never invent such names; only use them as documented.
`[10, 20].__len__()` => `len([10, 20])`
`a.__getitem__(x)` => `a[x]`

Ref:

[The Most Popular Programming Languages](https://www.statista.com/chart/16567/popular-programming-languages/)

[Here’s Everything You Can Do With Python (And What You Shouldn’t)](https://medium.com/geekculture/heres-everything-you-can-do-with-python-and-what-you-shouldn-t-8e20ad82261b#4ba7)

[pip 和 conda 的联系区别、安装包方法、换源方法](https://blog.csdn.net/weixin_42077074/article/details/113745214)

[初学 Python 者自学 Anaconda 的正确姿势是什么？](https://www.zhihu.com/question/58033789/answer/254673663)

[Anaconda 环境的创建/激活/删除/管理](https://blog.csdn.net/qq1483661204/article/details/78182430)

[anaconda 环境切换](https://zhuanlan.zhihu.com/p/141122337)

[python 中的模块、库、包有什么区别？](https://www.zhihu.com/question/30082392)

[Python 中模块，包，库，框架都是啥？](https://zhuanlan.zhihu.com/p/459244772)

[python 中的 if not](https://blog.csdn.net/qq_36850813/article/details/93464498)

[Why do some functions have underscores "\_\_" before and after the function name?](https://stackoverflow.com/questions/8689964/why-do-some-functions-have-underscores-before-and-after-the-function-name)

[python 中 remove 的一些坑](https://www.cnblogs.com/lipx9527/p/9450819.html)
