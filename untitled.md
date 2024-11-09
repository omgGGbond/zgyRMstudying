# 视觉组第二次学习

## 1.makedown的使用学习

> [何方小站](https://www.bilibili.com/video/BV1hG4y1H7iZ?t=38.0&p=10)(iamhefang.cn)

## 2.ros的介绍认识

> [ROS简介-从零开始讲解ROS（适合超零基础阅读）-CSDN博客](https://blog.csdn.net/qq_25267657/article/details/84316111)
>
> [ROS架构详细分析](https://blog.csdn.net/weixin_46999174/article/details/138012626)

## 3.github的学习和使用

> [‌‌​﻿​​​⁠​⁠​‬​​‍​‍​​‬‌​​​​​​‬​​⁠‌​​‍​​﻿​​‬​​​⁠​‬‍‌‌创建自己的第一个仓库 - 飞书云文档 (feishu.cn)](https://west2-online.feishu.cn/wiki/GaRpw5gevi5uBMkTZO4ceQylnQd)
> 
> [Git命令初上手 - 飞书云文档 (feishu.cn)](https://west2-online.feishu.cn/wiki/SKQ4wTtZji7Hv4kPquRcJOqEnKg)

##  4.ros2中publisher和listener的使用，并发布信息welcome to RM

![使用豆包](/home/ggbond/Documents/16456DFB01B408F213D185ABE584D34C.jpg)

下为终端中输出Welcome to RM！

![输出Welcome to RM！](/home/ggbond/Downloads/listener.png)

## 5.阐述ros架构以及话题节点服务等之间的通信关系

### 5.1ros架构

分为三个主要层次：OS层、中间层和应用层。

### 5.2话题节点服务之间的通信关系

先是一个节点需要某种话题类型的信息，那么该节点（listener）就去接受该信息，通过节点管理器帮助寻找发布这个信息的节点（talker），之后两个节点建立联系，通讯

这是一种服务通讯，单向流动，从talker（服务器）流至listener（客户端），只允许有一个服务器，但是可以有多个客户端，采取请求和应答的模式进行通信
