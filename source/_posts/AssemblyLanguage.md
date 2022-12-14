---
title: 汇编语言
date: 2022-04-14 09:10:46
tags: 计算机基础
---

> 参考书籍：汇编语言(第四版，王爽)

# 第一章 基础知识

1. 机器语言

   计算机只能读懂0和1，但是对人类来说，晦涩难懂，不易查错，所以就发明了汇编语言

2. 汇编语言的产生

   ```
   机器指令：1000100111011000
   汇编语言：mov ax,bx
   人类语言：把寄存器BX的内容送到AX中
   ```

   程序员输入汇编指令——>编译器将汇编指令变成机器码(1和0)-->计算机识别

3. 汇编语言的组成

   1. **汇编指令**：机器码的助记符
   2. 伪指令
   3. 其他符号：+、-、*

4. 指令和数据

   在内存或者磁盘上，两者没区别，都是一串0和1，主要看CPU工作的时候怎么划分。

   ```
   1000100111011000这串数字
   看做数据：89D8H
   看做指令：mov ax,bx
   ```

5. 存储单元

6. 地址总线(A)

   决定了CPU的寻址能力，地址总线上能够传送多少个不同的信息，CPU就能对多少个存储单元寻址。

   

   









































# 第二章 寄存器
