# cshub-ui
## Project Introduction
The cshub-ui is the frontend project of the CsHub.
## 项目介绍
cshub-ui 是 CsHub 的前端项目。
## 项目结构
项目采用按功能分模块的开发方式，结构如下：

- cshub-common 为系统的公共模块，各种工具类，公共配置存在该模块。

- cshub-system 为系统的项目入口模块，是系统的核心模块，也是最终需要打包部署的模块。

- cshub-logging 为系统的日志模块，其他模块如果需要记录日志需要引入该模块。

- cshub-tools 为系统的第三方工具模块，包含：图床、邮件、云存储、本地存储、支付宝。

- cshub-generator 为系统的代码生成模块，代码生成的模板在 system 模块中。

- cshub-ui 为系统的前端模块，独立于其他后端模块。
## 技术清单
| | 前端 |
| :----- | :----: |
| 语言 | TypeScript |
| 框架 | React, MUI |
| 工具 | Yarn |
| 应用服务器 | Nginx |
