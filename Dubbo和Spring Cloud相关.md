# Dubbo和Spring Cloud相关

## Dubbo

* 你说你了解dubbo，能讲一下dubbo的基本原理吗？ 
* dubbo支持的通信协议和序列化协议？ dubbo负载均衡和集群容错策略有哪些？dubbo的spi思想dubbo进行的服务治理、服务降级、失败以及重试。服务端怎么知道客户端要调用的算法的？
* 阐述下dubbo的架构
* dubbo支持的注册中心有哪些，分别的优缺点
* dubbo执行流程？
* dubbo和springclond的架构区别和优劣？
* 说一下dubbo的实现过程?注册中心挂了可以继续通信吗? 
* dubbo复制均衡策略和高可用策略都有哪些啊?动态代理策略呢?
* Dubbo服务调用的概述 consumer每次都要去拉注册中心provider的信息吗 consumer会缓存所有的provider元信息吗
* 为什么要进行系统拆分啊?拆分不用dubbo可以吗?dubbo和thrift什么区别啊?
* Dubbo的服务请求失败怎么处理 •重连机制会不会造成错误 
* Dubbo相比webservice等方式的优势 
* Dubbo的RpcContext是怎么传递的？
*  dubbo默认使用什么传输协议
* dubbo和ZK使用时给ZK提交些什么信息？用户是直接调用dubbo还是ZK？
* Dubbo超时重试；Dubbo超时时间设置；
* dubbo调用端怎么在jvm中生成对应服务？dubbo服务端和调用端超时时间设置和区别、dubbo长连接
* dubbo服务治理是怎样的；
* dubbo如何一条链接并发多个调用。Dubbo的原理，序列化相关问题
* dubbo怎么知道服务器状态有什么内部机制？ 
* 使用dubbo进行远程调用时消费端需要几个线程。
* dubbo支持的注册中心有哪些，分别的优缺点-
* dubbo调用其他服务如何做到不检查；

## Spring Cloud

* spring cloud基本概念 
* SpringCloudy 容器化
* 讲讲springcloud个组件原理，zuul、Hystrix
* 讲一讲springcloud的eureka组件？
* gateway和zuul做网关的区别？
* Spring cloud相关： （1）Eureka服务注册发现，对比其他组件。 （2）Hystrix熔断与降级
* 网关选型 Zuul 和 Spring Cloud Gateway Eureka 服务发现的原理 服务发现选型应该要考虑的因素有哪些？
* 什么是Eureka的自我保护模式
* 服务发现是怎么实现的 熔断是怎么实现的

## Zookeeper

* 分布式锁zookeeper的使用场景，实现分布式锁的方式，redis分布式锁和zookeeper分布式锁结合项目来说 以上两种方式的实现和异同
* 描述下ZooKeeper的选举机制
* ZooKeeper的监听原理是什么？
*  ZooKeeper的部署方式有哪几种？集群中的角色有哪些？集群中最少需要几台？
* ZooKeeper常用命令
* zookeeper的核心是什么?
*  zk原理知道吗?zk都可以干什么?Paxos算法知道吗?说一下原理和实现? 
* 在你的项目中spring是如何管理zookeeper的？
* 看了zookeeper源码，你的收获是什么？
* zookeeper宕机与dubbo直连的情况？
* zookeeper是保存数据的流程

## Nginx

* nginx限流模块；
* nginx有哪些模块？你比较熟悉哪个？
* nginx负载均衡策略有哪几种？
* 谈下你对nginx和uwsgi的理解、为什么要用wsgi？
* nginx负载均衡有哪些，如果其中一台服务器挂掉,报警机制如何实现

## 其他相关内容

* 微服务设计问题，rpc实现方式简单介绍；

* dubbo、RPC介绍原理 限流算法 zk挂了怎么办 分布式锁的实现方式，zk实现和Redis实现的比较 秒杀场景设计，应付突然的爆发流量 分布式数据一致性 一致性哈希

* 分布式服务接口的幂等性如何设计

* 你们项目中分布式的session如何实现?实际就是分布式系统中的session共享 关于分布式事务、以及分布式事务问题

* 聊一聊SOA和微服务。soa和微服务的区别

* 项目中怎样使用微服务？ 两个服务之间调用的流程 rpc与http的区别 设计rpc协议需要注意什么

* 作为调用方和被调用放如何对避免服务雪崩？ rpc接口的超时时间时如何设置得？服务容灾是如何做的,你们工作中采用的微服务是如何部署的？

* 实现RPC框架需要注意什么？

* 什么是节流与防抖，如何实现

* 服务容灾是如何做的？

* 作为调用方和被调用放如何对避免服务雪崩? rpc接口的超时时间时如何设置得？

* 负载均衡有哪些算法？

* 分布式一致性协议raft，paxos 了解吗？Zookeeper中的ZAB协议，选主算法；

* 实现负载均衡和顺序轮询机制；（考虑并发）

* RPC服务的概念，RPC服务一般都怎么做序列化？怎么处理传输层的字节流？

* 分布式锁的实现原理和有多少种实现方式？

* 远程服务框架:dubbo的通信过程，服务发现过程，序列化反序列过程原理理解；分布式协调算法：zk的paxos协议原理,zab原理，metaq的raft协议原理；

* 服务器雪崩是怎么造成的？之前有这样的经历吗？怎么防备？

* 如何实现何高并发下的削峰，限流？ 

* client调用A服务，A服务依赖于B服务，在不知道B是否高可用的情况下，怎么保证A的高可用？

* 分布式任务调度怎么做？

  

  

## dubbo扩展

  以下有关dubbo的面试题来自知识星期【芋道源码】

  * 说说 Dubbo 的整体架构？有哪些角色，怎么交互的？ps：先不用回答到内部的调用链路。

  * 请说说 Dubbo 一次完整调用的过程？越详细越好，最好画个图

* Dubbo 需要考虑优雅上线么？是和否的原因是什么？

* Dubbo 有哪些负载均衡策略？默认是哪一种。

* 43.Duboo 集群容错策略有哪些？如何选择？

* Dubbo 的 SPI 机制是什么？为什么需要 SPI 机制？

* 可以使用 Spring 作为 Dubbo 的 SPI 机制么？可以使用 Java SPI 作为 Dubbo 的 SPI 机制么？ps：这个是换一个思路，看看候选人在 Dubbo SPI 的理解。

* Dubbo Filter 机制是否了解？

* 你有实现过 Dubbo 自定义 Filter 么？

* 日常开发 Dubbo 服务时，怎么开发调试？

* 阅读 Dubbo 的标签路由功能，思考有没更好的 Dubbo 调试便利性。

* Dubbo 有哪些序列化组件？你们目前使用哪个？原因是？

* 如何实现一个 Dubbo 本地调试的封装？

* 在 Dubbo 中，可以使用那些中间件实现链路追踪？知道实现原理么？

* 什么是 Dubbo 隐式传参？有什么用途？

* 如果使用 Redis 作为 Dubbo 的注册中心，需要考虑哪些东西？

  





