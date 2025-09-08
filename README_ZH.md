<p align="center">
  <h1 align="center">debezium实时数据采集</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[Debezium](https://github.com/debezium/debezium) 是一个捕获数据更改(change data capture,CDC)低延迟的流式处理平台。用户安装并且配置Debezium去监控数据库，然后就可以消费对数据库的每一个行级别(row-level)的更改。

**核心特性：**
1. 确保捕获所有的数据变更。
2. 以极低的延迟生成变更事件，同时避免因为频繁轮询导致 CPU 使用率增加。例如，对于 MySQL 或 PostgreSQL，延迟在毫秒范围内。
3. 不需要更改您的数据模型，例如 ‘Last Updated’ 列。
4. 可以捕获删除操作。
5. 可以捕获旧记录状态以及其他元数据，例如，事务 ID，具体取决于数据库的功能和配置。



**架构设计：**

![](./images/img001.png)


本项目提供的开源镜像商品 [**debezium实时数据采集**](https://marketplace.huaweicloud.com/hidden/contents/6b366e2e-b51d-4a81-9c47-876452e5e666#productid=OFFI1169449120448692224)，已预先安装 Debezium 软件及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 4GHz 或更高
> - RAM: 8GB 或更大
> - Disk: 至少 60GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                                | 特性说明                                         | 备注 |
|---------------------------------------------------------------------------------------------------------------------|----------------------------------------------| --- |
| [Debezium2.4.1-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/Debezium-image/tree/Debezium2.4.1-kunpeng-v1.0) | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/Debezium-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
