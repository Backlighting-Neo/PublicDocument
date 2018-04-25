# 个人信息

 - 唐宗超
 - 男 / 1993 / 三年工作经验 / 本科 青岛大学 通信工程
 - Github
 > [https://github.com/Backlighting-Neo](https://github.com/Backlighting-Neo)
 - Blog
 > [http://www.tangzongchao.com](http://www.tangzongchao.com)

# 联系方式

- 15620819010
- tjtzc@126.com

# 工作经历

## 2017.6 - 2018.6 便利蜂

作为前端Leader，带领一个6人小组负责便利蜂便利店门店端所有涉及售卖的业务，其中前端项目16个，后端项目1个。前端项目以ReactNative技术栈为主，负责整体业务的把控，基础技术框架的输出，后端以Node为主，对接公司内其他业务系统。

### 前端项目

前端项目主要为便利蜂便利店卖场内各类以售卖为目的的设备，例如收银机、自助核验设备、广告屏等等共计16个项目的开发维护，技术栈以RN为主，后期在业务日渐复杂的情况下逐步引入了Rx.js以及一些函数式编程的库。

### 后端项目

搭建了一个以前端为主，以设备为唯独的独立监控体系，依托ELK和Grafana对所有运行着RN项目的设备进行24小时监控。
以node为主要开发语言，监控ELK日志系统上的日志是否正常，并接收来自Grafana产生的报警数据，打通公司内其他系统，对日志进行实时的DSL处理，并与其他系统使用Kafka共享数据。

## 2015.6 - 2017.6 小红唇

### 前端项目

小红唇Wap端H5页面和小红唇App内的ReactNative混合页面，参考CodePush自建RN的热更新体系，整体前端服务架构单人完成，包括服务器购买https证书购买上线部署等，整体前端架构从上古时代迁移到以Vue为主框架的方案。

### 后端项目

天天跟我买小程序后端微服务化迁移，负责三分之一的微服务开发，使用SpringCloud，配合Eureka,Feign,Hystrix。

# 技能

## 前端

React Vue均在生产环境中使用，状态管理使用Redux辅助以Mobx，目前的最佳实践是借助Rx.js将业务代码全部epic话，实现代码的高复用高可读。
研究过RN打包器的实现原理，已经跨框架的AST级别的代码同构直出，见开源项目1。

## 后端

以Node为主的Koa框架，实现了简易的node上的微服务框架，包括服务发现，心跳检测，定时任务等。

Java端以SpringCloud为主，辅助以Eureka和Feign实现简易的微服务。实现了业务微服务，但没有参与网关的实现。

## 数据库

业务关系型数据库以MySQL为主，能够进行简单的业务查询优化，看过分布式数据库的拆表拆库的操作。KV数据库以Redis为主，实现过简单的业务队列和超时缓存。借助Redis实现过MyBatis的缓存中间件。

ElasticSearch能够进行简单的分片维护，带聚合等复杂操作的DSL编写。

## 其他

搭建过ELK日志系统，自己配置es logstash和kibana，参与过odps的数据清洗平台的搭建。

研究过TensorFlow（js实现）的一点点内容，实现过demo级别的简单图。

# 开源项目

## Vue2MINA

由于 ```天天跟我买``` 项目业务要求，H5版本和小程序版本同时维护，加之人手不足，故独立开发了一个从Vue到微信小程序的代码转换器，节省了大量的人力时间。

由于我们的H5前端技术选型采用Vue，微信小程序的语法非常接近Vue语法，故采用了这种办法来加快开发速度。

使用了`Recast`框架对js进行AST级别的拆分，修改后再重新生成js达到重构的目的。同样对于css进行rules级别的修改，对于html，按照xml解析后进行语法修改然后prettify后进行输出。

项目在Github上开源并发布在npm上

npm  [https://www.npmjs.com/package/vue2mina](https://www.npmjs.com/package/vue2mina)
Github [https://github.com/Backlighting-Neo/Vue2Mina](https://github.com/Backlighting-Neo/Vue2Mina)

## Uno在线版

Uno是一种卡牌游戏，在一次同学聚会中发现异常好玩且游戏规则简单，加之女朋友非常喜欢，故完成了一个基于`Node` `Websocket`和 `Vue`的在线版Uno，方便远程玩。项目目前部署在Linode上。

注意，这并不是造轮子，考察了市面上的在线Uno，不是Steam系的很贵，就是粗制滥造，所以才萌生了自己搞一个的想法。

2017年春节期间完成，包括Icon的PS绘制，服务端的整体构架和前端UI的实现。
Github [https://github.com/Backlighting-Neo/uno](https://github.com/Backlighting-Neo/uno)

# 技术分享

## ReactNative入门【应届生培训】

在便利蜂对新入职的应届生进行RN体系的培训

[KeyNote查看](https://github.com/Backlighting-Neo/PublicDocument/blob/master/ReactNativeAtBlibee.pdf)

## 基于ELK的业务实时监控系统

请参见工作项目中便利蜂后段项目一节，这个分享是在系统上线后对整个系统涉及的一个分享。

[KeyNote查看](https://github.com/Backlighting-Neo/PublicDocument/blob/master/ELKbasedDeviceMonitorSystem.pdf)


# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。