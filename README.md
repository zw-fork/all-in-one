# all-in-one
各种Java知识

包说明
### my-demo
##### com.aaron.algorithm
>一些常见算法的Java实现
##### com.aaron.beginner
> 刚学习Java的时候写的代码
##### com.aaron.concurrent
>并发操作学习
>
>CompletionService:用于线程池计算任务，返回时直接调用take().get()，该方法
会优先返回计算完成的线程，而不是按顺序返回


##### com.aaron.designpattern
> 设计模式初探
##### com.aaron.framework
> 框架基础知识：包括spring，quartz等
##### com.aaron.jvm
>java虚拟机方面的模拟，各种异常的模拟
##### com.aaron.netty
>netty框架学习
##### com.aaron.util
>自己写的常用的工具类

### spring-cloud-parent spring cloud全家桶
1. 服务注册中心eureka
2. rpc调用Feign
3. 网关 spring-cloud-gateway
3. 服务降级与熔断机制  hystrix