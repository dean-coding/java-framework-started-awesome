## 环境

| 工具  | 版本或描述 |
| ----- | ---|
| JDK   | 1.8  |
| IDE   |  `IntelliJ` IDEA |
| Maven | 3.x                  |
| spring-cloud-dependencies | Greenwich.SR2 |
| spring-boot-starter | 2.1.6.RELEASE |
| spring-cloud-starter-netflix-eureka-client | 2.1.2.RELEASE |
| spring-cloud-starter-netflix-eureka-server | 2.1.2.RELEASE |
| spring-cloud-starter-gateway | 2.1.2.RELEASE |


## 实践规划
服务 | 端口 |功能|状态|描述|
:---|:---:|:---|:---:|---
`gateway-service` | `9999` | API网关| ✅ |
`eureka-registry` | `9000`| 注册中心| ✅ | 
`producer-service` | `8881`| 服务提供者| ✅ |
`consumer-service` | `8882`| 服务消费者| ✅ | 
`CI/CD` |`8888` |  | ✅ |  [Jenkins](http://47.98.168.56:8888/)<br>账户密码: user-sample/user_123
APP应用监控 | | | ✅ |[app-monitor](http://47.98.168.56:3000/d/XT923gPGz/app-monitor?orgId=1)<br>账户密码: user-sample/user_123|
OS系统监控 | | | ✅ |[sys-monitor](http://47.98.168.56:3000/d/9CWBz0bik/dean-test-dashboard?orgId=1)<br>账户密码: user-sample/user_123|
Container容器监控 | | |❌|[container-monitor](http://47.98.168.56:3000)<br>账户密码: user-sample/user_123|
 

## 架构设计✒️