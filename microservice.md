
# 微服务特性

![picture 2](images/352b767e02c2f51d5d501c4c8c97ac2b01e0fbde4a50a0d550b8eb1dd07a2208.png)  

![picture 3](images/7bd607241aa104054856fe30b778f59eebaba00e893dea10107937874278beb0.png)  


微服务全景架构图

![picture 4](images/c21c46d57d049ed473896e2f73960d12adf76c404d4a9c76641328de04a5f178.png)  


微服务的优缺点：

缺点：
![picture 5](images/8d8fa25956e8f79c417f78dcd7849bf5423becb8f95de7d1abf78199e7ee2ec0.png)  
其中所谓的重复性劳动指在不同微服务中有可能用到相同的功能，由于微服务有可能使用不同的框架语言开发，所以单纯的封装相同的类是不行的。

优点：
![picture 6](images/d33deff44e5108a9a861e4a4870f6d3924ab948a8d51203d4122522a69d8821a.png)



# 微服务拆分

方法论：
```
目前主要有两种： DDD(Domain Driven Design)和OOP（Object oriented programming)

1. 职责划分（订单微服务只关注订单相关的业务）
2. 通用型划分（把通用功能做成微服务-用户中心，消息中心）

```

微服务粒度:

如何去拆分得到一个合理的粒度？

1. 良好的满足业务
2. 团队中无人认为微服务太大，或者难以CICD
3. 增量迭代--微服务之间相互独立，一次迭代中只需要迭代部分微服务就行
4. 持续净化--如果相对微服务进行重构，重新的技术选型，这不应该是难以完成的
5. 对于很大的微服务，可以进行拆分
6. 对于粒度过细的微服务，可以进行整合


# 项目的架构图

![picture 7](images/0ab870eec629a41ac9cbb693d8f0fc8a9b452795e0a996f92f5afcec79ffdbed.png)  