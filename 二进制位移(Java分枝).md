#二进制<br>
    二进制就是以0,1为基数,满二进一

#二进制的位移<br>
二进制的位移很简单,就是在0101这样的二进制数字里面,把该数字最前面的一个零去掉,补在最后一位
eg:

<font style="color:#ff1148">00000000 00000000 00000000 00000101 </font><br>该数字表示为10进制的数字: 5 ,我们对该数字左位移一位,看看位移后的值为多少<br>
<font style="color:#ff1148">00000000 00000000 00000000 00001010 </font><br>可以看出位移后的二进制数字表示为10,那我们再试一个数字,看看位移有没有什么规律<hr>
<font style="color:#ff1148">00000000 00000000 00000000 00101011 </font><br>该数字为 (32+8+2+1) 43,那我们对它左位移一位看看是多少<br>
<font style="color:#ff1148">00000000 00000000 00000000 01010110 </font><br>该数字为 (64+16+4+2) 86,可以看出对二进制位移,就是把这个数乘以2/除以2