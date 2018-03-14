https://wenku.baidu.com/view/3e08150527d3240c8447efdb.html

## USB CAN 互转模块不仅可以转换传输，还可以用于调试CAN总线上的数据。
usbtinviewer

## 一篇关于CAN总线如何和树莓派链接的文章
https://www.raspberrypi.org/forums/viewtopic.php?t=141052
## 相似文章
https://harrisonsand.com/can-on-the-raspberry-pi/

## GITHUB 软件资源
https://github.com/linux-can
https://github.com/autowp/arduino-mcp2515

## CAN 总线通过USB接口调试
https://weibo.com/ttarticle/p/show?id=2309404000062043759550&infeed=1


## CAN 总线介绍
http://blog.csdn.net/app_12062011/article/details/9361805
所有的消息以固定格式发送，ID只是优先级，以位进行逐个仲裁比较，连续输出显性电平最多的单元，仲裁获胜，获得发送权，失利的单元则停止发送而进行接收工作，并且在总线再次空闲之前不会再发送报文。也就是在线与逻辑中，ID的数值越小，优先级越高。这种仲裁，可以让高优先级的数据帧无延时的实时发送，因为在仲裁结束后，数据帧的前面部分起始已经发送过了。（以太网CSMA/CD，CAN总线采用CSMA/CA）。

