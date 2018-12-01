电商微服务父工程

一、统一编码声明：使用UTF-8编码

二、技术栈版本说明
1.Java版本：JDK1.8
2.SpringBoot版本：2.1.0.RELEASE
3.SpringCloud版本：Finchley.SR2

三、子工程说明
1.merchant-client：电商接口客户端封装，属程序包，给UI应用使用
2.merchant-domain：电商业务领域设计，属程序包，实体及持久化
3.merchant-object：电商查询对象设计，属程序包
4.merchant-restapi：电商Restful接口，属微服务应用
5.merchant-web：电商PC端Web UI，属微服务应用