# 安浪统一企业级开放平台

## 介绍
Anline General Manage System安浪企业级通用管理系统，终极目标是企业和个人直接获取，然后转变为自己的生产力项目。不仅可以学习使用，也可以在实际生产模式使用。项目的目标是真正的全平台、全端、全栈！跨开发语言、跨数据库、跨端、跨栈。既可以前后端分离，也可以传统模板引擎模式。可以理解为自定义选型来实现相同的功能！即后台面板有Angular版本、React版本、Vue.js版本，甚至还提供HTML版本！后台语言有Java版本、PHP版本、Nodejs版本、Golang版本、Rust版本等，当然不同语言版本的完善度是不会一样的，这取决于我对这个语言的熟练度和语言本身的局限性和特性特长等。客户端的实现为Android、iOS原生、微信小程序等各类小程序的实现、H5网页版的实现等，新增Xamarin、HarmonyOS华为鸿蒙系统实例实现

## 软件架构
1.  数据库 支持所有主流数据库，取决于所选用的数据库驱动和ORM框架
1.  后端 支持主流语言的主流框架，支持Docker等容器环境，取决于框架层是否支持
1.  前端 Angular、React、Vue有分别实现

### 一些说明

本项目只做开发工作，关于服务器部署、分布式与集群、Docker虚拟化、Kubernetes(K8S)、微服务功能，取决于各平台各语言的实现实例是否支持。大多数选型都支持或仅支持独立进程运行，自己使用负载均衡软件开启服务发现即可。请不要把开发和运营混在一起


## 平台模块 【2020-2025】大战略
⚠️⚠️⚠️各个模块项目会建立单独项目目录开发。本项目只作为项目导航汇总

1. [_API](_API)API接口调用调试数据

1. [_DB](_DB) 数据库文件 支持主流数据库
    1. [_DB/ArangoDB](_DB/ArangoDB) NOSQL文档以及图数据库_DB/ArangoDB实现
    1. [_DB/Cassandra](_DB/Cassandra) NOSQL文档Key-Value数据库_DB/Cassandra实现
    1. [_DB/Firebird](_DB/Firebird) SQL文档数据库Firebird实现
    1. [_DB/MongoDB](_DB/MongoDB) NOSQL文档数据库MongoDb实现
    1. [_DB/MySQL](_DB/MySQL) MySQL数据库实现
    1. [_DB/Neo4j](_DB/Neo4j) Neo4j数据库实现
    1. [_DB/PostgreSQL](_DB/PostgreSQL) PostgreSQL实现
    1. [_DB/Redis](_DB/Redis) Redis实现，无持久化数据
    1. [_DB/SQLite](_DB/SQLite) SQLite实现
    1. [_DB/SQLServer](_DB/SQLServer) 微软SQLServer实现（基于Docker跨平台在Mac系统上开发）
    1. [_DB/TiDB](_DB/TiDB) TiDB（MySQL兼容）实现
    

1. [_DesignMaterial](_DesignMaterial) 设计素材

1. [_DOC](_DOC) 应用文档

1. [Client](Client) 前后端分离 客户端实现
    1. [Client/Admin](Client/Admin) 后台管理面板实现
    1. [Client/Android](Client/Android) Android安卓原生APP实现
    1. [Client/Console](Client/Console) 入驻商/平台接入或用户级别管理中台
    1. [Client/Electron](Client/Electron) Electron实现桌面版本
    1. [Client/Flutter](Client/Flutter) Flutter跨平台APP实现
    1. [Client/HarmonyOS](Client/HarmonyOS) HarmonyOS 华为鸿蒙系统客户端实现，该实例包含Java、Node/JS语言实现实例以及各端实例
    1. [Client/iOS](Client/iOS) iOS苹果原生APP实现
    1. [Client/macOS](Client/macOS) macOS苹果电脑系统桌面原生实现（Simple）
    1. [Client/PyQtGUI](Client/PyQtGUI) Qt for Python框架 Desktop桌面客户端实现实例
    1. [Client/QuickApp](Client/QuickApp) 快应用实现
    1. [Client/ReactNative](Client/ReactNative) ReactNative跨平台实现
    1. [Client/Uni-App](Client/Uni-App) Uni-App跨平台框架实现
    1. [Client/Web](Client/Web) PC网页版/或响应式非前后端分离实现
    1. [Client/Wechat-H5](Client/Wechat-H5) 微信H5网页版实现，具有微信服务号接入实现
    1. [Client/Wechat-MiniProgram](Client/Wechat-MiniProgram) 小程序官方原版实现
    1. [Client/Windows](Client/Windows) Windows客户端实现，UWP、WPF、WCF/Forms实现（Simple）
    1. [Client/Xamarin](Client/Xamarin) Xamarin跨平台移动APP方案实现
    
1. [Serve](Serve) 前后端分离 后端实现
    1. [Serve/CSharp](Serve/CSharp) 后台C# .NET core 平台实现语言实现
    1. [Serve/Elixir](Serve/Elixir) 后台Elixir语言实现
    1. [Serve/ErLang](Serve/ErLang) 后台ErLang语言实现
    1. [Serve/Golang](Serve/Golang) 后台Golang语言实现
    1. [Serve/Groovy](Serve/Groovy) 后台Groovy语言实现
    1. [Serve/Java](Serve/Java) 后台Java语言实现
    1. [Serve/Julia](Serve/Julia) 后台Julia语言实现
    1. [Serve/Kotlin](Serve/Kotlin) 后台Kotlin语言实现
    1. [Serve/Node.JS](Serve/Node.JS) 后台Node.JS语言实现
    1. [Serve/PHP](Serve/PHP) 后台PHP语言实现
    1. [Serve/Python](Serve/Python) 后台Python语言实现
    1. [Serve/Ruby](Serve/Ruby) 后台Ruby语言实现
    1. [Serve/Rust](Serve/Rust) 后台Rust语言实现
    1. [Serve/Scala](Serve/Scala) 后台Scala语言实现
    1. [Serve/Swift](Serve/Swift) 后台Swift语言实现
    1. [Serve/VLang](Serve/VLang) 后台VLang语言实现


## 安装教程

1.  根据各分块的安装方式和包管理方式安装
2.  支持容器安装运行
3.  使用特定平台开发者工具打包器打包

## 使用说明

1.  统一使用方式
2.  使用传统模式
3.  开发者自定义

## 参与贡献

1.  Fork 本仓库
2.  新建 项目 分支
3.  提交代码
4.  新建 Pull Request


#### © Copyright @安浪创想 @绿血贵族（jiankian）  版权所有 本项目禁止申请软件著作权
