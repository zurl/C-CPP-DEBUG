# 第二章 编译错误

编译错误是最常见的一类错误，也是最容易排除的一类错误，它们会导致你的程序无法编译通过，并且会产生红色的错误信息。  

## 第一节 词法错误

词法错误是最好排除的错误。  
### C/C++的变量名
1.必须以下划线或字母开头  
2.只能包含下划线和字母或数字  
3.不能包含其他符号和中文  
### 无效的字符
一般会出现如 “未声明的标识符”（MSVC）  
stray 'XXXX' in program (GCC)  
这时要检查源程序中是否存在中文括号 中文分号 还有其他中文字符。  
英文字符多是C语言支持的字符，除了少部分（比如 @ )  
## 第二节 语法错误

## 第三节 语义错误

