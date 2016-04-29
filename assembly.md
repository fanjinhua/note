# 数的机器表示

## 机器字(machine word)长　　　（32/64位）
- 一般指计算机进行一次整数运算所能处理的二进制数据的位数
 - 通常也包括地址数据长度
 - 32位字长
 - 64位字长
 
## machine word在内存中的组织
- 地址按字节来定位
 - 机器字中第一个字节的地址
 - 相邻机器字的地址相差4(32-bit)或者8(64-bit)
 
## Byte Ordering (字节序)
- 一个机器字内的各个字节如何排序
 - Big Endian: Sun, PowerPC, Internet
   - 低位字节(Least significant byte, LSB)占据高地址
 - Little Endian: x86
   - 与LSB相反
   - 低地址对低位，高地址对高位
 - 
 
 ![2016-04-29 16:04:45屏幕截图.png](https://ooo.0
 o0.ooo/2016/04/29/572317882a610.png)
 
## 整数的二进制编码方式
- 无符号数
- 带符号数（补码，Two's Complement）
 - 取反加一，即得带符号数
 
### C语言中的无符号数和带符号数
- 常数(Constants)
 - 默认是带符号数
  - 如果有'U'作为后缀则是无符号数
- 混合使用，带符号数默认转换为无符号数
 - 包括比较操作符
 
### 何时采用无符号数
- 模运算
- 按位运算
- 尽量不用无符号数

### 


<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

$ 表示行内公式： 
质能守恒方程可以用一个很简洁的方程式 $E=mc^2$ 来表达。
$$ 表示整行公式：
$$\sum_{i=1}^n a_i=0$$
$$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$
$$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$


$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
\\(x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\\)