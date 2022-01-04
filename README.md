<h1 style="text-align: center">AdminHub</h1>
<div style="text-align: center">

[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://github.com/Xiangyang-Lei/adminhub/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Xiangyang-Lei/adminhub.svg?style=social&label=Stars)](https://github.com/Xiangyang-Lei/adminhub)
[![GitHub forks](https://img.shields.io/github/forks/Xiangyang-Lei/adminhub.svg?style=social&label=Fork)](https://github.com/Xiangyang-Lei/adminhub)

</div>

## Project Introduction

AdminHub is a front-end and back-end meta background management framework based on Spring Boot, Spring Data JPA, Spring Security, PostgreSQL, React and MUI.

## 项目介绍

AdminHub 是一个基于 Spring Boot 、 Spring Data JPA 、 Spring Security 、 PostgreSQL 、 React 和 MUI 的前后端分离的元后台管理框架。

## 项目源码

| | 后端源码 | 前端源码 |
| :-----| :----: | :----: |
| GitHub | https://github.com/Xiangyang-Lei/adminhub | https://github.com/Xiangyang-Lei/adminhub-web |

## 技术清单

| | 后端 | 前端 |
| :-----| :----: | :----: |
| 语言 | Java | JavaScript |
| 框架 | Spring Boot, Spring Data JPA, Spring Security | React, MUI |
| 工具 | Gradle | Yarn |
| 数据库 | PostgreSQL | |

## 项目结构

项目采用按功能分模块的开发方式，结构如下：

- adminhub-common 为系统的公共模块，各种工具类，公共配置存在该模块。

- adminhub-system 为系统的项目入口模块，是系统的核心模块，也是最终需要打包部署的模块。

- adminhub-logging 为系统的日志模块，其他模块如果需要记录日志需要引入该模块。

- adminhub-tools 为系统的第三方工具模块，包含：图床、邮件、云存储、本地存储、支付宝。

- adminhub-generator 为系统的代码生成模块，代码生成的模板在 system 模块中。

## 特别鸣谢

- 感谢 [JetBrains](https://www.jetbrains.com/) 提供的非商业开源软件开发授权

- 感谢 [ELADMIN-WEB](https://github.com/elunez/eladmin-web) 大佬提供的前端模板

