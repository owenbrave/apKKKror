## 前言

微信小程序已经成为我们日常生活中不可或缺的一部分，为广大开发者提供了便捷的开发途径。在此，我们向大家分享一款基于SSM框架的微信小程序考试系统，旨在帮助用户实现在线考试、成绩管理等功能。

## 内容介绍

本微信小程序考试系统主要包括以下功能模块：考生管理、试题管理、考试管理、成绩查询等。通过使用本系统，可以方便地进行试题的创建、编辑，安排考试，并对考生成绩进行统计和分析。此外，系统还具备良好的用户体验，易于操作。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于试题管理的核心代码：

```java
// 查询试题列表
@RequestMapping("/getQuestionList")
public ResponseEntity<List<Question>> getQuestionList(@RequestBody Map<String, Integer> param) {
    Integer examId = param.get("examId");
    List<Question> questionList = questionService.getQuestionList(examId);
    return ResponseEntity.ok(questionList);
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
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/334248/37/12816/85303/68c4dc2aFb1f5b06a/e9059649a73f9ed7.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328955/22/19456/15399/68c4dc02F86a9e835/3d761f1f2d6ec2fc.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327966/5/19627/16200/68c4dc02Fcc47b27d/2edf830fe772fc3e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/337522/34/10190/22243/68c4dc03F91405f43/023da92cd47089ac.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/346147/27/2821/45507/68c4dc03Fab65bb9e/c8e282a8daea3580.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344721/36/2870/17568/68c4dc03F8fdfddd6/4411df829ec37e68.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/332225/34/12440/60857/68c4dc03Fee6266b7/8c585811e4ad7cff.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/327661/21/19472/20825/68c4dc04F2b05b1f1/382a2bf11c4df342.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326386/20/19224/17038/68c4dc04F597abe97/c7de630853a05576.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/340851/35/8542/14298/68c4dc04Ff4347764/ec22e5f082866d38.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
