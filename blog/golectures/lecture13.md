<!--
author: 无闻
head: https://avatars1.githubusercontent.com/u/2946214?v=3&s=400
date: 2016-02-13
title: 第 13 课：反射 reflection
tags: go语言,programing
category: go编程基础
status: publish
summary: 《Go编程基础》是一套针对 Google 出品的 Go 语言的视频语音教程，主要面向新手级别的学习者。
-->

### 基本信息

- **课程时长**：31:33
- **在线观看**：[土豆网](http://www.tudou.com/programs/view/luV8Do0Szqw/) [优才网](http://www.ucai.cn/course/chapter/69/3259/4707) [网易云课堂](http://study.163.com/course/courseLearn.htm?courseId=306002#/learn/video?lessonId=421024&courseId=306002)

### 课程大纲

	[00:00] 知识回顾
	[04:28] 反射基本操作
	[12:10] 反射匿名或嵌入字段
	[16:10] 修改目标对象
	[24:10] 动态调用方法
	[28:15] 课堂作业布置
	
### 作业答案

- 下堂课讲解

### 补充说明

- 视频第 22 分 33 秒，代码第 23 行应该为 `if v.Kind() != reflect.Ptr || !v.Elem().CanSet() {`。

### 相关链接

- 暂无链接

### 课程链接

- [第 12 课：接口 interface](lecture12.html)
- [第 14 课：并发 concurrency](lecture14.html)
