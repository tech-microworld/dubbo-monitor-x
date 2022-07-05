# dubbo-monitor-x

 要求 Dubbo 2.7.11+ 以上版本，Dubbo 3.0+ 需要升级jar适配。




#### 功能
- [x] 打包后一键部署
- [ ] 支持本地文件模式
- [ ] Docker容器化部署
- [ ] 支持异步队列统计Dubbo调用情况到数据库
- [ ] 支持一部写入队列，由其他系统(异构)进行消息消费，并分析。
- [ ] 支持告警模块。配置指定告警模式，短信/邮件/推送（自行实现API）



#### 声明
仅适合小规模Dubbo服务集群，服务节点较多请参考Apache Dubbo 官方接入[SkyWalking](https://skywalking.apache.org/)等链路监测工具