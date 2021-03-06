# MineboatX

[![输开源协议](https://img.shields.io/badge/License-MIT-brightgreen.svg "MIT")](https://opensource.org/licenses/mit-license.php)
![image](https://img.shields.io/badge/build-passing-brightgreen.svg)

MineboatX 项目是 [Mineboat](https://github.com/PatrickRoot/Mineboat) 项目的服务器端实现，可作为单独的项目使用。

Mineboat 是一个前后端分离的框架，目的是实现一个**非分布式**的简单框架。

Mineboat 基于这样一个需求：当需要搭建一个简单的网站的时候，希望能够快速上线，不需要过多的配置和框架的搭建。

Mineboat 的后端基于 SpringBoot 技术栈，前端基于 Vue 技术栈。 

Mineboat 的名称分别是 mine 和 boat 两个单词，mine 来源于 Minecraft 游戏，boat 发音与 boot 类似。

MineboatX 的 X 意味着这是服务器端代码**。

希望 Mineboat 成为一只乘风破浪的小船，简单好用，装满代码，直挂云帆济沧海。

## 如何使用

1. 安装文档[待定]

## 已完成

- [x] 建立 Git 仓库并初始化
- [x] 完成模块的划分
- [x] 集成Redis
- [x] 开启Spring 自带定时器
- [x] 核心模块：用户登录及校验

## TODO

- [ ] 研究 plugin 挂载方式，力求简单方便
- [ ] 添加数据库连接池
- [ ] 配置日志

## 计划

- 完成基于 Spring Boot 的后台基础框架项目：[MineboatX](https://github.com/PatrickRoot/MineboatX)。
- 完成基于 Vue 和 Element-UI 的前端基础框架项目：[Mineboat](https://github.com/PatrickRoot/Mineboat)。

## 技术选型

- 核心框架：Spring Boot
- 安全框架：Spring Security
- 持久层框架：Spring Data JPA
- 数据库：MySQL
- 模板引擎：Spring Thymeleaf
- 缓存框架：Redis
- 定时器：Spring Scheduling Tasks

待定：根据需要以及进度考虑是否添加
- [待定]数据库连接池：Alibaba Druid
- [待定]任务调度：Spring + Quartz
- [待定]文档性架构：MongoDB + FastDFS
- [待定]缓存框架：Redis + Guava
- [待定]会话管理：Spring Session + Redis
- [待定]日志管理：SLF4J、Log4j2
- [待定]前端框架：Spring Thymeleaf + jQuery + Vue + ElementUI

## 特别感谢

1. Jetbrains： Intellij 平台
2. Oracle 和 逝去的 Sun ：Java 语言、JVM
3. Spring、Spring Boot
4. Vue、Element-UI
5. Git
6. Github、码云
7. ...