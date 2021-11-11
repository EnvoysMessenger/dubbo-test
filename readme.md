# 个人练手向dubbo仿写项目
## 项目功能实现优先级
1. 面向接口的RPC调用功能
2. 抽象化以及以zookeeper为中心的服务自动注册与发现
    - 后期拓展：暂无 
3. 高度拓展能力
    - 对下层协议的内置与第三方实现的平等交互能力（参考spi）
4. 流量调度能力 && 负载均衡

## 开发流程
~~~
  迭代式开发，上述功能点完成一个测试通过
后封版，进行下一阶段开发
~~~

资料

[Spring Guide文档](https://spring.io/guides)

[收藏夹项目文档](http://www.ityouknow.com/springboot/2016/09/26/spring-boot-opensource-favorites.html)

[Spring Boot 小示例](https://github.com/ityouknow/spring-boot-examples)

[Bootstrap 文档](https://v3.bootcss.com/getting-started/#examples)

[MVN仓库](https://mvnrepository.com/)

工具

[]()

BGM

[光明 汪峰](https://www.bilibili.com/video/av13708087?p=13)

记录

当出现进程未终结，端口被占用需终止进程时，可以使用Netstat –ano|findstr “<端口号>” 找到其PID（最后一列）
然后使用tskill PID 即可终止该进程

网页访问出现问题的时候可以F12看看错误

出现JQ文件缺失时，需要手动引入JQ文件，并且要在JS那一行前面，否则也会报错

为导出表，可以在表的内容页右键，选择DATAEXTRACT: SQL,选中sql insert，然后选dump data > to file 即可导出sql文件

快捷键
ALT + INSERT : get，set方法等代码自动补全

疑问


激活码
微信：雨梦code