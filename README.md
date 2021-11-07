# CsHub
## Project Introduction
The CsHub is a web application of tools for computer science.
## 项目介绍
CsHub是一个计算机科学工具的网页应用程序。
## 项目结构
项目采用按功能分模块的开发方式，结构如下：

- cshub-common 为系统的公共模块，各种工具类，公共配置存在该模块。

- cshub-system 为系统的项目入口模块，是系统的核心模块，也是最终需要打包部署的模块。

- cshub-logging 为系统的日志模块，其他模块如果需要记录日志需要引入该模块。

- cshub-tools 为系统的第三方工具模块，包含：图床、邮件、云存储、本地存储、支付宝。

- cshub-generator 为系统的代码生成模块，代码生成的模板在 system 模块中。

- cshub-ui 为系统的前端模块，独立于其他后端模块。
