<p align="center">
  <h1 align="center">Debezium real-time data collection</h1>
  <p align="center">
    <a href="README_ZH.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)  
- [Prerequisites](#prerequisites)  
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction  
[Debezium](https://github.com/debezium/debezium) is a low latency streaming platform for capturing change data capture (CDC). Users can install and configure Debezium to monitor the database, and then consume every row level change to the database.  

**Core Features:**
1. Ensure that all data changes are captured.
2. Generate change events with extremely low latency while avoiding an increase in CPU usage due to frequent polling. For example, for MySQL or PostgreSQL, the latency is in the millisecond range.
3. No need to change your data model, such as the 'Last Updated' column.
4. Can capture deletion operations.
5. It can capture the status of old records and other metadata, such as transaction IDs, depending on the functionality and configuration of the database.

**Architecture Design:**

![](./images/img001.png)

This project offers pre-configured [**Debezium Database**](https://marketplace.huaweicloud.com) images with Debezium and its runtime environment pre-installed, along with deployment templates. Follow the guide to enjoy an "out-of-the-box" experience.

> **System Requirements:**
> - CPU: 2GHz or higher  
> - RAM: 4GB or more  
> - Disk: At least 60GB  

## Prerequisites  
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications  

| Image Version                                                  | Description                                             | Notes |  
|----------------------------------------------------------------|---------------------------------------------------------|-------|  
| [Debezium2.4.1-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/Debezium-image/tree/Debezium2.4.1-kunpeng-v1.0) | Deployed on Kunpeng servers with Huawei Cloud EulerOS 2.0 64bit |  | 

## Getting Help
- Submit an [issue](https://github.com/HuaweiCloudDeveloper/Debezium-image/issues)
- Contact Huawei Cloud Marketplace product support

## How to Contribute
- Fork this repository and submit a merge request.
- Update README.md synchronously based on your open-source mirror information.
