# awesome-learning-materials
- [0 前言](#0-前言)
- [1 编程语言](#1-编程语言)
  - [C](#c)
  - [Cpp](#Cpp)
  - [Rust](#rust)
  - [Go](#go)
  - [Python](#python)
  - [Scala](#scala)
- [2 Java](#2-java)
  - [虚拟机和字节码](#虚拟机和字节码)
  - [多线程和异步编程](#多线程和异步编程)
  - [其他](#其他)
- [3 Java服务端开发](#3-java服务端开发)
  - [Spring](#spring)
  - [SpringBoot](#springboot)
  - [MyBatis](#mybatis)
  - [Tomcat \& Jetty](#tomcat--jetty)
  - [Nginx](#nginx)
  - [HTTP](#http)
  - [Netty](#netty)
- [4 分布式系统和大数据框架](#4-分布式系统和大数据框架)
  - [理论和总览](#理论和总览)
  - [RPC](#rpc)
  - [分布式业务系统和微服务](#分布式业务系统和微服务)
  - [Hadoop](#hadoop)
  - [Spark](#spark)
  - [Flink](#flink)
  - [Zookeeper](#zookeeper)
  - [消息队列Kafka和RocketMQ](#消息队列Kafka和RocketMQ)
  - [分布式机器学习](#分布式机器学习)
- [5 数据库](#5-数据库)
  - [理论](#理论)
  - [SQL](#sql)
  - [MySQL](#mysql)
  - [HBase](#hbase)
  - [Redis](#redis)
  - [Etcd](#etcd)
  - [Elasticsearch](#elasticsearch)
- [6 NewSQL](#6-newsql)
  - [分布式数据库](#分布式数据库)
  - [TiDB](#tidb)
- [7 Linux](#7-linux)
  - [Linux使用](#linux使用)
  - [Linux系统编程](#linux系统编程)
- [8 云](#8-云)
  - [云计算](#云计算)
  - [容器和docker](#容器和docker)
  - [K8s和Service Mesh](#k8s和service-mesh)
- [9 计算机基础](#9-计算机基础)
  - [算法和数据结构](#算法和数据结构)
  - [网络](#网络)
  - [操作系统和计算机组成原理](#操作系统和计算机组成原理)
  - [编译原理](#编译原理)
- [10 人工智能](#10-人工智能)
  - [AI中的数学基础](#ai中的数学基础)
  - [数据分析](#数据分析)
  - [机器学习](#机器学习)
  - [深度学习](#深度学习)
  - [推荐算法](#推荐算法)
- [11 架构和系统设计](#11-架构和系统设计)
- [12 待分类](#12-待分类)
- [13 博客](#13-博客)
- [14 未看](#14-未看)
  - [前端](#前端)
  - [Serverless](#serverless)
  - [高并发系统调优和案例](#高并发系统调优和案例)
  - [监控压测](#监控压测)
  - [工具](#工具)
  - [Cpp](Cpp)

# 正文

## 0 前言

本学习大纲主要侧重于Java后端，分布式系统，大数据，数据库和云计算

学习新知识时，我一般会学习如下学习资料：

1 豆瓣高分书籍，其中大于9分的都是特别好的书，8分以上的书也不错，8分以下的书，选择性读

2 极客时间专栏，极客时间是IT领域很好的知识付费平台，活动时买个超级会员，可以观看所有专栏

3 官方文档资料，社区和github文档等

4 B站播放量高的视频

5 公开课

6 论文



## 1 编程语言

### C

- 《Linux C一站式编程》，豆瓣评分9.0
- 极客时间：[深入 C 语言和程序运行原理](https://time.geekbang.org/column/intro/100100701?tab=catalog)

### Cpp

- 《Accelerated C++》，豆瓣评分9.1

### Rust

- 官方书籍：[The Rust Programming Language](https://doc.rust-lang.org/book/)

- 视频：[Rust编程语言入门教程](https://www.bilibili.com/video/BV1hp4y1k7SV)
- 极客时间：[陈天 · Rust 编程第一课](https://time.geekbang.org/column/intro/100085301?tab=catalog)

### Go

- 《Go专家编程》，豆瓣评分9.2
-  《The Go Programming Language》 ，豆瓣9.6，[中文电子版](https://gopl-zh.github.io/)

- 视频：[Go语言编程快速入门](https://www.bilibili.com/video/BV1fD4y1m7TD)
- 极客时间：[Tony Bai · Go 语言第一课](https://time.geekbang.org/column/intro/100085301?tab=catalog)

### Python

- [廖雪峰Python教程](https://www.liaoxuefeng.com/wiki/1016959663602400)

### Scala

- 《快学Scala（第2版）》，豆瓣评分8.3

- 视频：[尚硅谷大数据技术之Scala入门到精通教程](https://www.bilibili.com/video/BV1Xh411S7bP)

  

## 2 Java

### 虚拟机和字节码

- 《深入理解Java虚拟机》，豆瓣评分9.4
- 《深入理解JVM字节码》，豆瓣评分8.2
- 《实战Java虚拟机：JVM故障诊断与性能优化》，豆瓣评分8.3
- 极客时间：[深入拆解 Java 虚拟机](https://time.geekbang.org/column/intro/100010301?tab=catalog)

### 多线程和异步编程

- 《Java并发编程实战》，豆瓣评分9.0
- 《Java并发实现原理：JDK源码剖析》，豆瓣评分8.0
- 《Java异步编程实战》，豆瓣7.8
- 极客时间：[Java 并发编程实战](https://time.geekbang.org/column/intro/100023901?tab=catalog)

### 其他

- 极客时间：[Java 业务开发常见错误 100 例](https://time.geekbang.org/column/intro/100047701?tab=catalog)

- 极客时间：[深入剖析 Java 新特性](https://time.geekbang.org/column/intro/100097301?tab=catalog)

- 《Effective Java》，豆瓣评分9.6

- 《Maven实战》，豆瓣评分8.2

- Gradle：[【尚硅谷】Gradle教程入门到进阶（从gradle安装到项目实战）](https://www.bilibili.com/video/BV1yT41137Y7)

  
  

## 3 Java服务端开发

### Spring

- 《精通Spring 4.x》 豆瓣评分8.4
- 《Spring揭秘》 豆瓣评分9.2
- 视频：[尚硅谷Spring注解驱动教程(雷丰阳源码级讲解)](https://www.bilibili.com/video/BV1gW411W7wy)
- [spring文档](https://docs.spring.io/spring-framework/docs/current/reference/html/)
- 极客时间：[玩转 Spring 全家桶](https://time.geekbang.org/course/intro/100023501?tab=catalog)

### SpringBoot

- 视频：[【尚硅谷】SpringBoot2零基础入门教程](https://www.bilibili.com/video/BV19K4y1L7MT) 尚硅谷雷丰阳

- 视频：[尚硅谷SpringBoot顶尖教程](https://www.bilibili.com/video/BV1gW411W76m) 尚硅谷雷丰阳

- [springboot文档](https://docs.spring.io/spring-boot/docs/current/reference/html/)

### MyBatis

- 《通用源码阅读指导书――MyBatis源码详解》，豆瓣评分8.2


### Tomcat & Jetty

- 极客时间：[深入拆解 Tomcat & Jetty](https://time.geekbang.org/column/intro/100027701?tab=catalog)

### Nginx

- 视频：[尚硅谷Nginx教程](https://www.bilibili.com/video/BV1yS4y1N76R)
- 极客时间：[Nginx 核心知识 150 讲](https://time.geekbang.org/course/intro/100020301?tab=catalog)

### HTTP

- 极客时间：[透视 HTTP 协议](https://time.geekbang.org/column/intro/100029001?tab=catalog)
- 极客时间：[Web 协议详解与抓包实战](https://time.geekbang.org/course/intro/100026801?tab=catalog)

### Netty

- 《Netty实战》，豆瓣评分7.5
- 《Netty源码剖析与应用》



## 4 分布式系统和大数据框架

### 理论和总览

- 《深入理解分布式系统》，豆瓣评分9.3

- 《大数据日知录》，豆瓣评分8.3
- MIT6.824：http://nil.csail.mit.edu/6.824/2020/schedule.html

- 极客时间：[分布式协议与算法实战](https://time.geekbang.org/column/intro/100046101?tab=catalog)

- 极客时间：[分布式技术原理与算法解析](https://time.geekbang.org/column/intro/100036401?tab=catalog)

- 极客时间：[大数据经典论文解读](https://time.geekbang.org/column/intro/100091101?tab=catalog)

- 极客时间：[深入浅出分布式技术原理](https://time.geekbang.org/column/intro/100104701?tab=intro)

  

### RPC

- 《架构探险：从零开始写分布式服务架构》
- 《分布式服务框架原理与实践》

- 极客时间：[RPC 实战与核心原理](https://time.geekbang.org/column/intro/100046201?tab=catalog)
- 极客时间：[Dubbo 源码剖析与实战](https://time.geekbang.org/column/intro/100312101?tab=catalog)
- 极客时间：[深入浅出 gRPC](https://time.geekbang.org/column/intro/100005601?tab=catalog)



### 分布式业务系统和微服务

- 《微服务架构设计模式》，豆瓣9.0

- [springcloud文档](https://docs.spring.io/spring-cloud/docs/current/reference/html/)
- [Spring Cloud Alibaba Reference Documentation](https://spring-cloud-alibaba-group.github.io/github-pages/2021/en-us/index.html)
- 极客时间：spring cloud Alibaba：[Spring Cloud 微服务项目实战](https://time.geekbang.org/column/intro/100101301?tab=catalog)
- 极客时间：[从 0 开始学微服务](https://time.geekbang.org/column/intro/100014401?tab=catalog)
- 极客时间：[Spring Boot 与 Kubernetes 云原生微服务实战](https://time.geekbang.org/course/intro/100031401?tab=catalog)
- 极客时间：[微服务架构实战 160 讲](https://time.geekbang.org/course/intro/100007001?tab=catalog)



### Hadoop

- 《Hadoop》权威指南，豆瓣评分7.7

### Spark

- 《大数据处理框架Apache Spark设计与实现》，豆瓣评分9.3
- 《Spark SQL内核剖析》，豆瓣评分7.9

- 极客时间：[零基础入门 Spark](https://time.geekbang.org/column/intro/100090001?tab=catalog)
- 极客时间：[Spark 性能调优实战](https://time.geekbang.org/column/intro/100073401?tab=catalog)

### Flink

- 《基于Apache Flink的流处理 : 流式应用基础、实现及操作》，豆瓣评分8.4

### Zookeeper

- 《从Paxos到Zookeeper》，豆瓣评分7.8
- 极客时间：[ZooKeeper 实战与源码剖析](https://time.geekbang.org/course/intro/100034201?tab=catalog)

### 消息队列Kafka和RocketMQ

- 《深入理解Kafka：核心设计与实践原理》，豆瓣评分8.8



### 分布式机器学习

- 《分布式机器学习：算法、理论与实践》，豆瓣评分8.8



## 5 数据库

### 理论

- 《数据库系统概念》，豆瓣评分8.5
- 《数据库系统实现》，豆瓣评分8.7

### SQL

- 极客时间：[SQL 必知必会](https://time.geekbang.org/column/intro/100029501?tab=catalog)

### MySQL

- 《MySQL技术内幕》 豆瓣评分8.3
- 《高性能MySQL》 豆瓣评分9.4
- 《MySQL是怎样运行的》，豆瓣评分9.5

- 极客时间：[MySQL 实战 45 讲](https://time.geekbang.org/column/intro/100020801?tab=catalog)

### HBase

- 《HBase原理与实践》，豆瓣评分9.0
- 《HBase权威指南》，豆瓣评分8.1

### Redis

- 极客时间：[Redis 核心技术与实战](https://time.geekbang.org/column/intro/100056701?tab=catalog)

- 极客时间：[Redis 源码剖析与实战](https://time.geekbang.org/column/intro/100084301?tab=catalog)

- 《Redis设计与实现》，豆瓣评分8.6

- 《Redis开发与运维》，豆瓣评分9.0


### Etcd

- 极客时间：[etcd 实战课](https://time.geekbang.org/column/intro/100069901?tab=catalog)

### Elasticsearch

- 《Elasticsearch实战》，豆瓣评分7.3

- 极客时间：[Elasticsearch 核心技术与实战](https://time.geekbang.org/course/intro/100030501?tab=catalog)

  

## 6 NewSQL

### 分布式数据库

- 极客时间：[分布式数据库 30 讲](https://time.geekbang.org/column/intro/100057401?tab=catalog)

### TiDB

- 视频：[PingCAP课程中心](https://learn.pingcap.com/learner/course)

- 博客：https://cn.pingcap.com/blog/

- 社区：https://tidb.net/

  

## 7 Linux

### Linux使用

- 极客时间：[Linux 性能优化实战](https://time.geekbang.org/column/intro/100020901?tab=catalog)
- 极客时间：[网络排查案例课](https://time.geekbang.org/column/intro/100104301?tab=catalog)

- 极客时间：[eBPF 核心技术与实战](https://time.geekbang.org/column/intro/100104501?tab=catalog)

### Linux系统编程

- 《Unix环境高级编程》，豆瓣评分9.7

- 《Unix网络编程》一二卷，豆瓣评分9.5

  

## 8 云

### 云计算

- 极客时间：[深入浅出云计算](https://time.geekbang.org/column/intro/100046901?tab=intro)

### 容器和docker

- 极客时间：[容器实战高手课](https://time.geekbang.org/column/intro/100063801?tab=catalog)

### K8s和Service Mesh

- 《深入剖析Kubernetes》，豆瓣评分9.4，[极客时间电子版](https://time.geekbang.org/column/intro/100015201?tab=catalog)
- 《Kubernetes生产化实践之路》，豆瓣评分8.0

- 极客时间：[Service Mesh 实战](https://time.geekbang.org/course/intro/100049401?tab=catalog)
- 



## 9 计算机基础

### 算法和数据结构

- 极客时间：[数据结构与算法之美](https://time.geekbang.org/column/intro/100017301?tab=catalog)
- 《算法导论》，豆瓣评分9.3



### 网络

- 《计算机网络：自顶向下方法》，豆瓣8.9

- 极客时间：[趣谈网络协议](https://time.geekbang.org/column/intro/100007101?tab=catalog)
- 极客时间：[网络编程实战](https://time.geekbang.org/column/intro/100032701?tab=catalog)



### 操作系统和计算机组成原理

- 《现代操作系统》，豆瓣9.0，公开课网址：https://ipads.se.sjtu.edu.cn/ospi/

- 《深入理解计算机系统》，豆瓣9.7

- 极客时间：[计算机基础实战课](https://time.geekbang.org/column/intro/100117801?tab=catalog)
- 极客时间：[深入浅出计算机组成原理](https://time.geekbang.org/column/intro/100026001?tab=catalog)
- 极客时间：[操作系统实战 45 讲](https://time.geekbang.org/column/intro/100078401?tab=catalog)
- 极客时间：[趣谈 Linux 操作系统](https://time.geekbang.org/column/intro/100024701?tab=catalog)
- 极客时间：[编程高手必学的内存知识](https://time.geekbang.org/column/intro/100094901?tab=catalog)



### 编译原理

- 极客时间：[编译原理之美](https://time.geekbang.org/column/intro/100034101?tab=catalog)
- 极客时间：[编译原理实战课](https://time.geekbang.org/column/intro/100052801?tab=catalog)
- 极客时间：[手把手带你写一门编程语言](https://time.geekbang.org/column/intro/100085201?tab=catalog)





## 10 人工智能

### AI中的数学基础

- 视频：[线性代数的本质](https://www.bilibili.com/video/BV1ib411t7YR) 

### 数据分析

- 《利用Python进行数据分析》，豆瓣评分8.6

- 极客时间：[数据分析实战 45 讲](https://time.geekbang.org/column/intro/100021701?tab=catalog)

### 机器学习

- 《机器学习-周志华》，豆瓣评分8.6

### 深度学习

- B站有吴恩达，李沐等人的深度学习课程

### 推荐算法

- 《推荐系统实战》，豆瓣评分8.1
- 《深度学习推荐系统》，豆瓣评分9.4，极客时间版本：[深度学习推荐系统实战](https://time.geekbang.org/column/intro/100060801?tab=catalog)



## 11 架构和系统设计

- 《数据密集型应用系统设计》，豆瓣评分9.6

- 《凤凰架构》，豆瓣评分9.3，http://icyfenix.cn/
- 《微服务架构设计模式》，豆瓣评分9.0
- 极客时间：[从 0 开始学架构](https://time.geekbang.org/column/intro/100006601?tab=catalog)
- 极客时间：[设计模式之美](https://time.geekbang.org/column/intro/100039001?tab=catalog)



## 12 待分类

- 极客时间：[左耳听风](https://time.geekbang.org/column/intro/100002201?tab=catalog)
- 极客时间：[技术与商业案例解读](https://time.geekbang.org/column/intro/100001901?tab=catalog)
- 极客时间：[说透芯片](https://time.geekbang.org/column/intro/100079201?tab=catalog)



## 13 博客

- 美团技术博客：https://tech.meituan.com/
- 陈皓：https://coolshell.cn/
- 四火的唠叨：https://www.raychase.net/
- 廖雪峰：https://www.liaoxuefeng.com/



## 14 未看

### 前端

- 极客时间：[重学前端](https://time.geekbang.org/column/intro/100023201?tab=catalog)
- 极客时间：[JavaScript 进阶实战课](https://time.geekbang.org/column/intro/100122101?tab=catalog)
- 极客时间：[Vue 开发实战](https://time.geekbang.org/course/intro/100024601)
- 极客时间：[玩转 Vue 3 全家桶](https://time.geekbang.org/column/intro/100094401?tab=catalog)
- 极客时间：[现代 React Web 开发实战](https://time.geekbang.org/column/intro/100119601?tab=catalog)
- 极客时间：[React Native 新架构实战课](https://time.geekbang.org/column/intro/100110101?tab=catalog)
- 极客时间：[微信小程序全栈开发实战](https://time.geekbang.org/course/intro/100052401?tab=catalog)

- 极客时间：[全栈工程师修炼指南](https://time.geekbang.org/column/intro/100035501?tab=catalog)

  

### Serverless

- 极客时间：[Serverless 入门课](https://time.geekbang.org/column/intro/100050201?tab=catalog)

- 极客时间：[Serverless 进阶实战课](https://time.geekbang.org/column/intro/100119701?tab=catalog)

### 高并发系统调优和案例

- 极客时间：[高并发架构实战课](https://time.geekbang.org/column/intro/100105701?tab=catalog)
- 极客时间：[高并发系统实战课](https://time.geekbang.org/column/intro/100309001?tab=catalog)
- 极客时间：[性能工程高手课](https://time.geekbang.org/column/intro/100041101?tab=catalog)
- 极客时间：[系统性能调优必知必会](https://time.geekbang.org/column/intro/100051201?tab=catalog)
- 极客时间：[手把手带你搭建秒杀系统](https://time.geekbang.org/column/intro/100091501?tab=catalog)
- 极客时间：[如何设计一个秒杀系统](https://time.geekbang.org/column/intro/100017501?tab=catalog)
- 极客时间：[即时消息技术剖析与实战](https://time.geekbang.org/column/intro/100034901?tab=catalog)

### 监控压测

- 极客时间：[运维监控系统实战笔记](https://time.geekbang.org/column/intro/100522501?tab=catalog)
- 极客时间：[全链路压测实战 30 讲](https://time.geekbang.org/column/intro/100093001?tab=catalog)
- 极客时间：[容量保障核心技术与实战](https://time.geekbang.org/column/intro/100078501?tab=catalog)

### 工具

- 极客时间：[玩转 Git 三剑客](https://time.geekbang.org/course/intro/100021601?tab=catalog)
- 极客时间：[Vim 实用技巧必知必会](https://time.geekbang.org/column/intro/100055801?tab=catalog)

### Cpp

- 《C++ Primer 中文版（第 5 版）》，豆瓣评分9.5
- 《Effective C++》，豆瓣评分9.4
- 《现代C++语言核心特性解析》，豆瓣评分9.5
