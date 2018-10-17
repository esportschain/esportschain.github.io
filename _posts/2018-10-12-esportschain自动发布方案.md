---
layout:     post
title:      esportschain自动发布方案
subtitle:   自动发布系统的构建
date:       2018-10-12
author:     PlayCode
header-img: img/post-bg-code.png
catalog: true
tags:
    - 发布
---

## 前言

为了满足不断增长的业务需求，支持多机房服务，保持各机房的软件版本统一，能够部署、灰度、升级、回滚，对应的需求是：esportschain_自动发布系统构建


## 1.发布流程

>关键词：自动化发布

##### 主要说明

统一目录结构

测试 => 预发布 => 现网 是一个完整的工作流程

![流程图](https://ws2.sinaimg.cn/large/006tNbRwly1fw5ggymivoj30fq0dddgl.jpg)

### 2. 数据结构 
参考 walle
在项目表中新增（测试环境、预发布、现网环境）

### 3.功能页面
项目配置
用户管理
工单审核
工单发布、新增文件、回退、关闭
ansible 配置
统一目录结构

### 参考

- [walle 瓦力-部署系统](https://walle-web.io)
- [Ansible 进阶技巧](https://www.ibm.com/developerworks/cn/linux/1608_lih_ansible/index.html)
- [ansible官方文档](https://docs.ansible.com/)
 

