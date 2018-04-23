# 大疆软件方向面试 - 15分钟

## 1. 简单介绍一下自己

- 学的什么
- 聊到同研

## 2. 同研平台简单说一下，几个人，做了哪些事情，架构是什么样子的

- 分工：
    - 一个前端一个后端
    - 做了全部的设计，和后端的工作

- 架构：
    - 前后端分离 vue + spring cloud
    - 静态代理 nginx
    - 网关 zuul
    - 服务注册 eureka
    - 消费者和服务者 feign
    - 会话集中管理 spring session
    - 安全验证 jwt + spring security
    - wechatkit
    - aliyun 邮件推送
    - redis 计数 + 缓存
    - 数据库独立

## 3. 这个平台里面的安全是怎么保证的

- user - role - authority 的角色-权限的权限管理设计
- 每个平台权限独立，用户平台做总开关
- spring security 在网关入口做认证
- spring security 在服务入口做鉴权

## 4. 里面技术难点是什么

## 5. 是基于Docker部署的？

## 6. 协作的时候有没有遇到什么障碍

## 7. 对北京和深圳有没有什么看法

## 8. 有没有什么补充的
