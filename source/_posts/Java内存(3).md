tags:
  - Testing                   
  - Another Tag               
---
java内存划分5个部分
### 栈（stack）
作用：存放的都是方法中的局部变量  
作用域：一旦超出作用域，立即从栈内存中消失
### 堆（heap）
作用：凡是new出来的东西都存储在堆内存中  
堆内存的东西都用一个地址值：16进制  
堆内存里面的数据都有默认值，规则：  

数据类型 | 默认值
---|---
整数 | 0
浮点数| 0.0
字符|\u0000
布尔|false
引用类型|null  

###  方法区（Method Area）
作用：存储.class相关的信息，包含方法的信息  
### 本地方法栈（Native Method Stack）
与操作系统相关  
### 寄存器（pc Register）
与cpu相关  
