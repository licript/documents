---
title: 网络是怎样连接的
sidebarDepth: 2
---

::: tip

一直以来，从输入链接到页面显示内容经历了什么是一个非常常规的面试题，而 《网络是怎样连接的》目录已经很好的回答了这个问题。

:::

<img :src="$withBase('/computer/how-networks-work-1.jpg')" alt="how-networks-work-1">

## 第一章 浏览器生成消息 -- 探索浏览器内部

### 1. 生成 HTTP 请求消息

### 2. 向 DNS 服务器查询 Web 服务器的 IP 地址

### 3. 全世界 DNS 服务器的大接力

### 4. 委托协议栈发送消息



## 第二章 用电信号传递 TCP/IP -- 探索协议栈和网卡

### 1. 创建套接字

### 2. 连接服务器

### 3. 收发数据

### 4. 从服务器断开并删除套接字

### 5. IP 与以太网的包收发操作

### 6. UDP 协议的收发操作



## 第三章 从网络到网络设备 -- 搜索集线器、交换机和路由器

### 1. 信号在网线和集线器中传输

### 2. 交换机的包转发操作

### 3. 路由器的包转发操作

### 4. 路由器的附加功能



## 第四章 通过接入网进入互联网内部 -- 探索接入网和网络运营商

### 1. ADSL 接入网的结构和工作方式

### 2. 光纤接入网（FTTH）

### 3. 接入网中使用的 PPP 和隧道

### 4. 网络运营商的内部

### 5. 跨越运营商的网络包



## 第五章 服务器端的局域网有什么玄机

### 1. Web 服务器的部署地点

### 2. 防火墙的结构和原理

### 3. 通过请求平分给多台服务器来平衡负载

### 4. 使用缓存服务器来分担负载

### 5. 内容分发服务



## 第六章 请求到达 Web 服务器，响应返回浏览器 -- 短短几秒的 “漫长旅行” 迎来终点

### 1. 服务器概览

### 2. 服务器的接收操作

### 3. Web 服务器程序解释请求消息并作出响应

### 4. 浏览器响应消息并显示内容
