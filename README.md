# python_des_3keys 三个key的python DES加密
通过python实现2006年Guopo写的Javascript版本的3keysDes加密，原JS文件也已上传。

简单说就是通过3个key将加密对象按4的长度拆开后的二进制数据进行三次加密。

本可以直接通过python运行JS语句，但也有不方便使用的场景，且网上并没发现有人制作，于是只能自己仿写下。

作为初学者知道了JS和python在列表定义使用以及for循环结束后计数变量的最终值都有差异。

调用请直接使用:

from Des_3keys import *

strEnc(data, key1, key2, key3) #加密

strDec(data, key1, key2, key3) #解密

对比效果如图：

![Image text](https://github.com/xcx441700/python_des/blob/main/src/1.png)

![Image text](https://github.com/xcx441700/python_des/blob/main/src/2.png)
