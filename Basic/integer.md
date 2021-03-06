# C 语言中的六种整型

> * short 2 -32768-32767

> * int 2

> * long 4

> * unsigned short 2 0-65535

> * unsigned int 2 0-65535

> * unsigned long 4

# 数值在内存中是以补码形式储存的

> * 正数的补码和原码相同；

> * 负数的补码：将该数的绝对值的二进制形式按位 `取反加1`；

> * -32768 比较特殊，最高位占用了符号位，任何一个原码都不可能在转成补码时变成 1000000000000000 所以，人为规定 1000000000000000 这个补码编码为 -32768。

> * 补码最大的好处就是可以将加法和减法统一，于是可以简化运算单元的设计、减小晶圆面积、降低散热；

# 补码的特性

> * 一个负整数（或原码）与其补数（或补码）相加，和为模；

> * 对一个整数的补码再求补码，等于该整数自身；

> * 补码的正零与负零表示方法相同；



