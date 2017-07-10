---
layout: post
title: "sed 命令 来一行 "
en_title: "sed command lessson"
date: 2017-07-10 15:40:02 +0800
comments: true
categories: [linux,regexp,pattern]
---

>   Sed 简介   

#### 1. 详细百科   
  &emsp;sed 是一种在线编辑器，它一次处理 ** 一行 ** 内容。处理时，把当前处理的行存储在临时缓冲区中，称为“模式空间” (pattern space),接着用sed命令处理缓冲区中的内容，处理完成后，把缓冲区的内容送往屏幕。接着处理下一行，这样不断重复，直到文件末尾。文件内容并没有 改变，除非你使用重定向存储输出。Sed主要用来自动编辑一个或多个文件；简化对文件的反复操作;编写转换程序等。  

#### 2. 个人内容总结 :  
&ensp;i.  sed 是 linux 中的 ** 行 文本 处理 命令 **  

&ensp;ii. sed 本身 ** 不改变 ** 文件 内容  

&ensp;iii. sed 支持 **正则 处理 **  


> sed 使用格式


> sed 常用 参数 列表  
