# 前言

欢迎来到基于微信小程序的高校就业招聘系统的设计与实现项目的Gitee仓库。本项目旨在为广大高校毕业生和招聘企业提供便捷、高效的招聘与求职平台。以下将详细介绍本项目的相关内容。

## 内容介绍

本项目采用前后端分离的设计模式，后端基于Spring Boot框架，前端使用微信小程序进行开发。系统主要包括企业招聘信息发布、学生简历投递、招聘会安排等模块。通过本系统，企业可以轻松发布招聘信息，学生也能便捷地查看并投递简历，大大提高了招聘与求职的效率。

## 技术介绍

### 语言：Java

### 使用框架：

- Spring
- Springmvc
- Mybatis
- 微信小程序

### 前端技术：

- JS
- Vue
- CSS3
- Uniapp

### 开发工具：

- IDEA/Eclipse
- Uniapp

### 数据库：

- MySQL 5.7/8.0

### 数据库管理工具：

- phpstudy/Navicat

### JDK版本：

- jdk1.8

### Maven：

- apache-maven 3.8.1-bin

### 前端环境：

- Node.Js 12\14\16

## 核心代码

以下为一段后端处理企业发布招聘信息的核心代码：

```java
// EnterpriseController.java

@PostMapping("/publishJob")
public ResponseEntity<String> publishJob(@RequestBody Job job) {
    if (enterpriseService.publishJob(job)) {
        return new ResponseEntity<>("发布成功", HttpStatus.OK);
    } else {
        return new ResponseEntity<>("发布失败", HttpStatus.INTERNAL_SERVER_ERROR);
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

## 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/347700/39/3203/117665/68c63baeFfbe68605/80f1d4d1bfba508e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/340453/35/10694/29536/68c63b86Fd3993824/d8d2cdc44f0cf915.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/351140/30/3247/56035/68c63b86Fef89be51/09eff1fca280d881.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/329375/28/12971/39308/68c63b86F53ea1e1e/a4365df4191800c8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/330654/33/13045/22200/68c63b86Fc7a90bfe/4d969a14ddb6eadf.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/333421/34/13134/29864/68c63b86F77745cf2/afcede1da5880212.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/350380/2/3232/40156/68c63b86Fb9b070d8/94438f1f3d863c94.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/345636/3/3255/58107/68c63b87Fec7b2f97/1aa82e5ef5d7dde7.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/345577/18/2847/56239/68c63b87Fba56bbdb/8a4ec776fc229e6a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/348505/30/3033/55866/68c63b87F211ffdcf/2857576f3ca26683.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
