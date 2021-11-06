# CsHub
The CsHub is a web application of tools for computer science.
## cshub-ui
The cshub-ui is the frontend project of the CsHub.
## cshub-module
The cshub-module is the backend project of the CsHub.
项目采用按功能分模块的开发方式，结构如下

eladmin-common 为系统的公共模块，各种工具类，公共配置存在该模块

eladmin-system 为系统核心模块也是项目入口模块，也是最终需要打包部署的模块

eladmin-logging 为系统的日志模块，其他模块如果需要记录日志需要引入该模块

eladmin-tools 为第三方工具模块，包含：图床、邮件、云存储、本地存储、支付宝

eladmin-generator 为系统的代码生成模块，代码生成的模板在 system 模块中
