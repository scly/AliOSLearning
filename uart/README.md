博文链接：<br>
[SimonLiu的ESP8266与AliOS Things 学习系列之四：uart0和uart1串口打印 - SimonLiu的博客 - CSDN博客](https://blog.csdn.net/toopoo/article/details/87021361)<br>
  
基于AliOS example\uart 例程修改。<br>
默认情况下：<br>
- `LOG()`在`UART0_TXD`输出信息
- `printf()`在`UART1_TXD`输出信息，注意printf()不支持输出float。

如果需要把`LOG()`重定向到`UART1_TXD`则需要根据我的博文进行修改。<br>


