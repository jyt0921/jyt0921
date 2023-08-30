### 我是江银涛

- :dog: 大家好啊！我是石家庄铁道大学 软件工程系的在校学生，个人性格开朗，欢迎访问我的GitHub主页！
- :man_technologist: 我是一名热爱编程和探索科技世界的大四学生，也是一个开源代码的狂热爱好者。在我的代码仓库中，你会发现我对各种项目有着浓厚的兴趣，WEB应用开发、Python技术、深度学习等，都曾留下我的足迹。
- :pencil: 博客：[O_O似曾相识 Blog.com](https://www.cnblogs.com/jyt604743080/) - 做了许多的总结啊
- :seedling: 笔记：[覆盖了许多自己的学习笔记 还有许多遇到的问题以及解决方案](https://github.com/jyt0921/jyt0921/blob/main/Photo/img_1.jpg)

### 个人技术栈
 -  熟练掌握Java基础，熟悉JUC、反射、常用集合源码，如HashMap、ArrayList等，具备良好的编程习惯
 -  熟悉计算机网络基础知识，对OSI七层网络模型、HTTP协议、TCP协议、三次挥手四次握手等有一定了解 
 -	熟练掌握Java设计模式，如模板、简单工厂、策略、状态、组合等设计模式，并善用设计原则构建可复用代码
 -	熟悉常用数据结构链表、栈、队列、二叉树、堆等，通过阅读《倚天村·图解数据结构》了解其底层实现逻辑
 -	熟练使用MySQL数据库，熟悉MySQL索引，比如索引结构、索引下推、索引失效等，熟悉并发事务机制，比如MVCC，事务隔离级别等，参与开发数据库路由组件并在项目中 
    使用
 -	熟悉Redis数据类型使用场景，熟悉持久化、过期淘汰策略和内存淘汰策略，熟悉缓存高并发场景解决方案，比如缓存穿透、缓存击穿、缓存雪崩
 -	熟练使用SpringBoot、Spring、SpringMVC、Mybatis框架搭建开发项目，熟悉Spring IOC和AOP机制，具备基于Spring开发SpringBoot Starter的技能，为项目提供 
    通用技术组件
 -	了解常用消息中间件如RabbitMQ、Kafka，具备实现消息的异步处理和解耦的能力，提升系统性能和可扩展性
 -	了解SpringCloud框架、Nacos注册中心、Gateway网关、Feign等组件
 - :feet: 当然除了Java的技术栈之外，在大学期间还学习了很多的其他语言做了许多的项目，具体的直接看下面的项目吧
### 项目概览 ✨

<img align="" height="137px" src="https://github-readme-stats.vercel.app/api?username=0921&hide_title=true&hide_border=true&show_icons=true&include_all_commits=true&line_height=21&bg_color=0,EC6C6C,FFD479,FFFC79,73FA79&theme=graywhite&locale=cn" /><img align="" height="137px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fuzhengwei&hide_title=true&hide_border=true&layout=compact&bg_color=0,73FA79,73FDFF,D783FF&theme=graywhite&locale=cn" />

### 开发的项目

- 课程项目
  - [Policy - 河北科技政策查询开发 - 多表查询](https://github.com/jyt0921/class-04-policy)  [技术栈：Html+JS+Layui+Mysql+Servlet+Lombok] 
  - [OldMan - 老年人能力评估](https://github.com/jyt0921/OldMan0)  [技术栈：Html+JS+Ajax+Layui+Mysql+Servlet+Lombok  Mapper代理]

- 个人项目
  - [reggie_take_out - 基于SpringBoot的餐饮服务开发项目](https://github.com/jyt0921/reggie_take_out)
  - [SocialConnect - 社交分享平台 一个分享平台，用户可以记录和分享生活方式]()
  - [Chat-Api - 学习使用ChatGPT，该项目提供接口可以部署到个人博客或者项目中](https://github.com/jyt0921/chat-api-jyt)
  - [基于PP-Vehicle的交通监控分析系统+二次开发](https://aistudio.baidu.com/projectdetail/6511451) - [二次开发](https://aistudio.baidu.com/projectdetail/6673712)
  - [Python爬取豆瓣视频+Python爬虫基本教程](https://github.com/jyt0921/douban)...
 
  除了上述的项目外，还有一些C#、PHP的项目使用经历，详细的可以进入到我的仓库一一查询

- 项目经历
  
	Lottery抽奖项目                                                                                               
	项目描述：活动抽奖是营销服务中常见的一种活跃用户，激励用户参与，提高平台的活跃度。该抽奖服务基于DDD领域驱动设计开发，主要包括活动领域，抽奖领域，组合规则引擎领域，发奖领域。
	核心技术：SpringBoot、Mybatis、Dubbo、Mysql、Redis、Kafka、XXL-JOB、DB-Router
	主要工作：
	•以 DDD 分层结构的处理方式，搭建整个抽奖系统架构，并负责活动领域，策略领域，发奖领域的开发
	•使用简单工厂模式搭建发奖领域，并利用模板模式设计抽奖流程，通过抽象类定义模板方法流程
	•开发对抽奖和Id生成的算法，采用策略模式，便于后期的拓展，支持多样化Id生成策略和抽奖策略
	•使用Kafka解耦抽奖发货流程，包括消息的发送、库表中活动状态的更新、消息的接收消费、发奖状态的处理，通过XXL-JOB定时任务扫描异常消息并进行补偿
	•使用Redis设计细粒度滑动库存分布式锁替代MySQL数据库行锁，提升了系统的并发性能，同时实现了DB-Router的分库分表组件，满足业务的快速增长系统的承受能力
	
	SocialConnect-社交分享平台                                                                           
	项目描述：SocialConnect是一个分享平台，用户可以记录和分享生活方式。提供安全高效的用户注册和验 证码缓存功能。支持手机号码注册，并使用Redis缓存验证码，提升注册流程的安全性和效率。还有查看附近用户、发 
        布笔记、点赞和关注功能，促进社交互动和交流。
	核心技术：SpringBoot、Mybatis、MySQL、Redis、RabbitMQ
	主要工作：
	•设计并实现了SpringBoot Starter 中间件，配置了白名单功能，以控制哪些用户信息可以被公开或哪些用户可以访问特定功能，增强了用户隐私和内容管理
	•使用Redis来存储验证码和token，结合拦截器实现用户认证和token刷新，提升系统的安全性和性能
	•通过RabbitMQ实现消息队列，将用户的点赞、评论和关注等操作放入消息队列，实现系统解耦和异步处理

#### 🌱 学习与成长

我一直在不断学习和探索，力求提升自己的技术水平。除了课堂学习，我还喜欢阅读技术书籍、参与在线课程和参加技术会议。我的目标是不断精进，成为一名杰出的软件架构师。

#### 🤝 联系我

如果你对我的项目或者任何技术话题感兴趣，欢迎与我联系！你可以在以下社交媒体平台找到我：

- GitHub: [https://github.com/jyt0921](https://github.com/jyt0921)
- 微信: [0921 - 非常欢迎加我微信，交流学习，一起进步！](https://github.com/jyt0921/jyt0921/blob/main/Photo/WeChat.jpg)
- 邮箱: [604743080@qq.com]

### 交个朋友 👬🏻

<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60"> <em><b>I love to make friends.</b> so if you want to say <b>hi, I'll be happy to meet you more!</b> 😊</em>
