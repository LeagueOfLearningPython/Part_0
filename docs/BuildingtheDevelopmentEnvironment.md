# 开发环境的搭建

## Python简介
1. Python的发展历史
2. Python的优点

3. Python官网 

https://www.python.org/

## Windows下开发环境的搭建
### Python2.7的安装
### Python3.5的安装
### anaconda的安装(kk推荐)

## Ubuntu Linux下开发环境的搭建

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

后面两行是字符编码

这两个实际上是没有什么区别的,但是第二种看上去比较好看

## 输入输出
1. print
2. raw_input
3. input 

## 标识符、关键字(保留字)
1. 标识符
2. 关键字（保留字）

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
