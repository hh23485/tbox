
技术面初面


## 1 介绍一下自己

## 2 同研平台架构 （一个项目）

## 3 分布式事务是怎么处理的

没有用tcc或者其他的分布式事务，预判结果进行补偿

## 4 路由是动态的吗

## 5 路由如何通过应用名称来确认接收方

zuul组件

## 6 授权和认证是怎么设计的

网关认证，服务独立授权，介绍了设计的原因

## 7 负载均衡在什么地方操作了

## 8 从 MVC 到 Cloud 主要的工作量在什么地方

## 9 微服务体系结构的概念和难点

## 10 旷视是怎么做的，在 API 层有什么特别的操作吗

## 11 要你设计一个 api 层，你会在意哪些事情

提到了幂等，他提出了防篡改

## 12 幂等性是怎么保证的，防篡改是如何做的

- 无状态+版本号
- map定时过滤+redis分布式锁

篡改提到了https，他说你们的身份信息有加盐么。。感觉好像聊的不是一个事情。。

## 13 JUC的包里的东西用过吗，讲讲线程池吧

## 14 线程池的的队列的作用，以及线程池3个参数的作用，coreSize maxSize queue

## 15 在旷视还做了什么，后续工作的计划