# Yunba iOS SDK Changelog  

##1.7.4
1. 支持通配符

##1.7.3
1. 修复一个内存申请过多导致的问题
2. 修复demo中的显示错误
3. 修复网络状况较差时长时间connnect无返回的问题

##1.7.1
1. 解决1.7.0版本在飞行模式下的assert crash bug

##1.7.0
1. 优化SDK在IPv6-only网络下的链接状况
2. 针对新版本iOS做出链接优化
3. 增加iOS 9.3支持

##1.6.4
1. 修复在网络状况反复失效时造成的token上传错误
2. 修复一个demo显示错位的问题
3. 修复预编译头文件编译告警

##1.6.3
1. 修复一个网络层的bug
2. 修复Xcode7下的无效编译告警
3. 加快SDK链接速度

##1.6.2
1. 增加`API timeout`和`heartbeat`的启动参数选项
2. 增加API超时后的网络检查
3. 修复一个网络层的bug
4. 修复一个demo显示错误

##1.6.0
1. 修改注册请求，适配iOS9 ATS
2. 重构demo
3. 在断链通知中增加链接断开原因
4. 增加apns界面及apns通知处理

##1.5.2
1. 允许setAlias参数为空（unset alias）
2. 增加iOS 8.4支持

##1.5.1
1. 增加GetStateV2/GetAliasListV2/GetTopicListV2 API
2. 增加带有ttl参数的publish2 API
3. 增加iOS8.3支持

##1.5.0
* 初始版本，具体请参考SDK文档
