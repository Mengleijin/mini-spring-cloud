# [前言](#前言)

前置知识。阅读spring、springboot、spring cloud三者的源码必须严格按照 spring => springboot => spring cloud 的顺序进行，阅读spring cloud源码的必备前置知识：

- spring，推荐本人写的简化版的spring框架 [**mini-spring**](https://github.com/DerekYRC/mini-spring/blob/main/README_CN.md) 。熟悉spring源码，阅读springboot源码会非常轻松。
- springboot，重点掌握：1、启动流程 2、**自动装配的原理! 自动装配的原理!! 自动装配的原理!!!** 推荐文章:
  - [Spring Boot精髓：启动流程源码分析](https://www.cnblogs.com/java-chen-hao/p/11829344.html)
  - [细说SpringBoot的自动装配原理](https://blog.csdn.net/qq_38526573/article/details/107084943)
  - [Spring Boot 自动装配原理](https://www.cnblogs.com/javaguide/p/springboot-auto-config.html)

关于spring cloud。spring cloud是构建通用模式的分布式系统的工具集，

写作本项目的目的之一是降低阅读原始spring cloud源码的难度。

建议。


# [服务注册](#服务注册)
> 分支: service-registry