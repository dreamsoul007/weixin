# weixin

#### 介绍


1. Spring Cloud微服务化开发，采用Nacos注册和配置中心，具有统一授权、认证后台管理系统，其中包含具备用户管理、资源权限管理、数据导出、打印、Swagger API 管理等多个模块，支持多业务系统并行开发，可以作为后端服务的开发脚手架。代码简洁，架构清晰，restful接口规范，适合学习、毕设、实际项目等使用
1. 采用最新前后端完全分离框架（Spring Cloud+Spring Boot+Vue+Element ui）
1. 前端封装微信专用vue组件，开发中实现灵活调用，杜绝重复造轮子，让前端开发更容易
1. 微信接口采用WxJava（微信开发 Java SDK），开发中无需一个个对接微信接口，直接方法调用。极大的提高了微信开发效率
1. 第三方平台全网发布、支持多公众号，redis全局缓存access_token
1. 后续会提供小程序、h5商城版本

[了解更多](http://joolun.com/post/7)
[演示环境](http://demo.joolun.com)
#### 软件架构

1. 核心框架：Spring Boot2 + Spring Cloud Alibaba + Spring Cloud Gateway 。
1. 安全框架：Spring Security OAuth2。
1. 前端框架：Vue2 + element-ui2 + avue2 。
1. 持久层框架：MyBatis-plus。
1. 微信开发 Java SDK：WxJava 。
1. 文件管理：阿里OSS、minio。
1. JDK：java8+


![自定义菜单](https://images.gitee.com/uploads/images/2019/0615/235522_4a27ee4a_5079715.gif "wx-menu.gif")
![微信粉丝实时聊天](https://images.gitee.com/uploads/images/2019/0615/235540_d512fa59_5079715.gif "liaotian.gif")
![输入图片说明](https://images.gitee.com/uploads/images/2019/0615/235616_dc33cdea_5079715.png "QQ截图20190612232849.png")
![多账号管理](https://images.gitee.com/uploads/images/2019/0626/094510_96c2c21a_5079715.png "屏幕截图.png")
[演示地址](http://demo.joolun.com)
