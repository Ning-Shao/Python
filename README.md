# Python 学习笔记仓库

这是我学习 Python 的笔记 + 示例代码 +练习项目仓库。目的是记录我在学习过程中的理解、例子、问题与解决方案，帮助自己回顾，也希望对别人有用。

---

## 目录

- [简介](#简介)  
- [内容结构](#内容结构)  
- [主要笔记主题](#主要笔记主题)  
- [如何使用](#如何使用)  
- [示例代码](#示例代码)  
- [更新日志](#更新日志)  

---

## 简介

- 仓库名：`Python`  
- 作者：Ning-Shao  
- 内容包括：运算符、流程控制、函数、文件 I/O、练习项目等  

---

## 内容结构

Python/
├── README.md ← 本文件
├── basics/
│ ├── operators.md
│ ├── conditionals_loops.md
│ └── functions.md
├── examples/
│ ├── floor_mod_example.py
│ └── project1/
└── projects/
└── some_project_name/


---

## 主要笔记主题

- 运算符（Operators）：floor division (`//`)、modulo (`%`)、加减乘除等
- 控制流程：`if` / `else` / `elif`、while / for 循环  
- 函数：定义、参数、返回值、作用域等  
- 文件 I/O：读写文件，JSON／文本处理等  
- 实践项目：练习用例，用来巩固所学内容  

---

## 如何使用

- Operators
- keywords: 
Values: True, False, None
Conditions: if, elif, else
Logical operators: and, or, not
Loops: for, in, while, break, continue
Functions: def, return


```python
###syntax for printing a string of text.
print("Hello, world!")

###遍历列表
friends = ['Taylor', 'Alex', 'Pat', 'Eli']
for friend in friends:
    print("Hi"+friend)

###重复输出repeat a string of text for i times
for i in range(10):
  print ("hello, world")

###define
name = "Jolyne"
print ("Hello " + name) 

###Python as a calculator
print (((1+2)*3)/4)

###x // y           Floor division operator returns the integer part of the integer division of x by y
###向下取整，正数只需要取小数点，负数-1.77则取-2
###只有当你用 round()、math.ceil()（向上取整）或 math.floor()（向下取整）时，才涉及“舍入”策略
print (7//2)
print (-7//2)

### x%y取余数
### x == (x // y) * y + (x % y)）

