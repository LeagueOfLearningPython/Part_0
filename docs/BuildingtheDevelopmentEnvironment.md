# 开发环境的搭建

## Python简介

1. Python的优点
   
   简单、优雅、使用缩进而不是花括号，并且在国外Python作为高校初学者的入门语言

2. Python的应用领域

  机器学习、深度学习、模式识别、web开发、自动化运维开发等

3. Python官网 

https://www.python.org/

## Windows下开发环境的搭建（具体搭建过程可以参考 [小嘉丶学长博客](http://blog.csdn.net/fj_author)）
### Python2.7的安装
### Python3.5的安装
### Python2.7与Python3.5的解决方案
### anaconda的安装(略，kk和小青春强烈推荐)

## 视频教程 [小嘉丶学长]（http://www.bilibili.com/video/av12232633/）

## Ubuntu Linux下使用技巧

## 第一个程序Hello,World!
1. 命令提示符
2. 脚本文件
3. 单行注释

`#`开头的为注释

4. 编码注释

```
#!/usr/bin/env python
#!/usr/bin/python
#conding=utf-8
#-*- coding: UTF-8 -*-
```

前面两行是声明Python解释器

第一行告诉操作系统执行这个脚本的时候，调用/usr/bin下的python解释器,这相当于写死了python路径;

第二行则会去环境设置寻找python目录,推荐这种写法

后面两行是Python脚本的字符编码

这两个实际上是没有什么区别的,但是第二种看上去比较好看

## 输入输出
1. print
2. raw_input
3. input 

## 标识符、关键字(保留字)
1. 标识符

2. 关键字（保留字）

```
python2
>>> import keyword
>>> keyword.kwlist
['and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'els
e', 'except', 'exec', 'finally', 'for', 'from', 'global', 'if', 'import', 'in',
'is', 'lambda', 'not', 'or', 'pass', 'print', 'raise', 'return', 'try', 'while',
 'with', 'yield']
```

31个

```
python3
>>> import keyword
>>> keyword.kwlist
['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', '
def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if',
 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'retu
rn', 'try', 'while', 'with', 'yield']
>>>
```

33个

Python3中有，但python2中没有的关键字
```
False
None
True
nonlocal
```

Python2中有python3中没有的关键字
```
exec   Python2中是语句，而Python3中是函数 
print  Python2中是语句，而Python3中是函数
```

我建议这些都不要当作变量标识符，因为这不是一个好行为

## 物理行与逻辑行
1. 物理行
2. 逻辑行

## 查看帮助
1. help()

```Python
>>> help(input) 
Help on built-in function input in module builtins: 
#描述,在内建模块

input(prompt=None, /)
    Read a string from standard input.  The trailing newline is stripped. 
    #从标准输入设备读取一个字符,不包括结尾换行符

    The prompt string, if given, is printed to standard output 
    without a trailing newline before reading input.
    #prompt为提示字符串,如果传递了,在读取输入以前,在标准输出上打印一个没有换行的字符串

    If the user hits EOF (*nix: Ctrl-D, Windows: Ctrl-Z+Return), raise EOFError.
    #如果遇到EoF(类unix系统:Ctrl+D，windows:Ctrl+z回车)抛出一个EOEError
    
    On *nix systems, readline is used if available.
```
2. 使用IDLE自带的手册

3. python官网的documentation

[点我返回首页](https://leagueoflearningpython.github.io/Part_0/)
