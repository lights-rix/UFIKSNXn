# 医院门诊预约系统

## 前言

此项目是基于Java语言和Spring Boot框架开发实现的医院门诊预约系统。该系统致力于为患者提供便捷的在线预约服务，同时为医院管理门诊预约提供了高效的解决方案。以下是项目的详细介绍。

## 内容介绍

本项目主要包括用户注册、登录、预约挂号、查看预约记录等功能。患者可以通过系统实时查看医生出诊时间，选择合适的门诊并进行在线预约。医院管理员可以对预约信息进行管理，包括预约确认、预约取消等操作。系统界面友好，操作简便，极大提高了医院门诊工作的效率。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.js 12\14\16

## 核心代码

以下是项目中关于预约挂号的一个简单示例代码：

```java
//预约挂号
@RequestMapping(value = "/appoint", method = RequestMethod.POST)
public String appoint(@RequestBody Appointment appointment) {
    //检查用户是否已登录
    if (SecurityUtils.getSubject().getPrincipal() == null) {
        return "用户未登录";
    }

    //检查预约是否成功
    if (appointmentService.appoint(appointment)) {
        return "预约成功";
    } else {
        return "预约失败";
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/328184/25/4862/100452/689f0e43Fc78174f5/f8da74b36da5cb7a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324619/25/4961/40989/689f0e1eF13c3ff8a/3608a0a16cc6db25.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324939/30/4867/40946/689f0e1eF3755fe2a/d0f69d42c3484c0d.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/312617/5/26663/86759/689f0e20F3c33c659/40b20b2505c46f7c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325447/1/4961/37342/689f0e20F3c9c41e3/a49d6d4e34552a41.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/317035/15/25055/53736/689f0e22F7b5f2a8c/212a003d9846f717.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/312355/22/26996/53507/689f0e22F28697e20/373f8503cff8af0a.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/309022/40/26653/68764/689f0e23F69cd8a9e/ef18725d25361a82.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/294148/9/18821/67621/689f0e23Fe1eeed0f/e3f26fa0a3ecaa92.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323984/38/4980/46674/689f0e24Ffd9d5521/d305221a32ff9944.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
