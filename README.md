# 社团管理系统简介 java1152

## 项目概述

社团管理系统是一个为高校社团提供全面管理功能的平台，旨在提高社团管理的效率与质量。系统包含管理员、团长、普通用户三种角色，以实现不同权限下的功能需求。

## 技术栈

### 后端技术栈
- Spring Boot：后端主框架
- MyBatis-Plus：数据持久层框架
- MySQL：关系型数据库
- Maven：项目依赖与构建管理
- 拦截器 + Token 会话管理：登录鉴权机制
- 统一响应与分页工具：`R`、`PageUtils` 等工具类

### 前端技术栈
- 管理端：Vue.js（2.x）+ Element UI
- 接口访问：Axios
- 构建工具：Vue CLI、babel、webpack
- 门户/前台：Layui + jQuery

## 功能模块

### 管理员角色
1. 用户管理
   - 管理管理员账号信息
   - 新增、修改、删除、重置密码
2. 团长管理
   - 维护与审核团长账号与资料
3. 普通用户管理
   - 管理学生注册信息与状态
4. 社团管理
   - 新增、编辑、下架、解散社团
   - 查看成员信息
5. 社团审核
   - 审核社团创建/变更申请
6. 活动管理
   - 查看全站活动，支持查询、导出、归档
7. 活动审核
   - 审核社团活动申请
8. 公告管理
   - 发布和管理系统公告
9. 字典管理
   - 维护系统基础数据字典
10. 系统配置
    - 维护站点基础配置
11. 文件管理
    - 统一上传与资源文件管理

### 团长角色
1. 个人信息
   - 维护团长个人资料与账号安全
2. 社团信息
   - 创建与维护社团资料
3. 社团审核申请
   - 提交与追踪审核进度
4. 活动管理
   - 发起、编辑、取消社团活动
5. 活动审核进度
   - 查看活动审核状态

### 普通用户（学生）角色
1. 个人中心
   - 维护个人信息
2. 社团浏览与加入
   - 浏览社团信息，提交加入申请
3. 活动报名
   - 参与社团活动
4. 公告查看
   - 查看平台公告与社团通知

## 系统角色

- 管理员
- 团长
- 普通用户（学生）

## 运行环境
- JDK 1.8 及以上
- MySQL 5.7 及以上
- Maven 3.x
- IntelliJ IDEA / Eclipse / VS Code（后端任一）
- Node.js 14.x/16.x
- npm 或 yarn

## 数据库设计

主要数据表包括：
- `users`：管理员信息
- `yonghu`：普通用户（学生）信息
- `tuanzhang`：团长信息
- `shetuan`：社团信息
- `shetuanshenhe`：社团审核信息
- `huodong`：活动信息
- `huodongshenhe`：活动审核信息
- `news`：公告/新闻信息
- `dictionary`：数据字典
- `config`：系统配置
- `token`：用户会话

## 目录结构

```
项目目录
├── resources
│   ├── admin  # 管理端前端资源
│   └── front  # 门户/前台前端资源
└── src       # 后端代码
    ├── main
    └── test
```

## 核心亮点

- 分角色的管理功能，确保权限明确，操作安全
- 统一的响应与分页工具，提高后端数据处理的效率
- 基于Token的会话管理，保障用户鉴权的准确性
- 完善的数据库设计，满足各类数据存储与查询需求
- 基于Layui与jQuery的门户/前台，便于用户快速获取信息及参与活动
- 清晰的目录结构，便于开发与维护工作
- 采用Maven进行项目构建与依赖管理，确保项目稳定性和可维护性

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img10.360buyimg.com/ddimg/jfs/t1/240486/16/30380/49829/68d7ec57F0ceb08f9/45b365b970256024.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/332222/40/18028/59165/68d7ec57F1e5a93e8/773de48cbb3b3b0d.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/329448/7/17710/58984/68d7ec59F39ba8ac4/a60152331068783e.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/348413/4/8093/32803/68d7ec59Fe3068b5b/290a5f11a2a9be1b.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/239716/16/31271/51001/68d7ec5aFaa7878a8/d0910470fc2c1cf1.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/332412/6/17952/26582/68d7ec5bF34ffd2f7/fae2763536f5f877.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/328265/21/24702/127050/68d7ec5cF0e22f1e7/db66bb713d7335fc.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/341950/7/8017/119385/68d7ec5cFc0c40eac/e12c0c064836546e.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/346609/32/7837/122160/68d7ec5dF2b9d501d/4d1cde901f2ed0eb.jpg)

