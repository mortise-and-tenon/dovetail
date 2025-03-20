## 燕尾 DoveTail

### 简介

燕尾，指燕尾榫。燕尾榫（Dovetail Joint）是一种传统的木工连接技术，因其形状类似燕子的尾巴而得名。

它通过榫头与榫尾的梯形咬合结构，实现木材的牢固连接，广泛应用于家具、建筑和工艺品制作中。

以其命名项目，既体现了它是 Mortnon 项目群中的一个子项目，也用它来代表项目的目的是用于紧密连接。也体现了项目主旨：

旨在用一个项目提供全面的 SSO 服务端能力，以用于客户端开发 SSO 时进行验证测试。

本项目基于 [mortnon-micronaut](https://github.com/mortise-and-tenon/mortnon-micronaut) 开发。

### 计划路线图

- 基础用户管理能力
  - 用户认证、退出
  - 用户新建、删除（仅内存）
  - 用户基础数据管理（仅内存）
  - 管理界面（前端项目）
  - 支持数据库数据存储
  - 支持Redis 数据存储
- SSO 管理
  - SSO 客户端管理（仅内存）
  - 用户 SSO 开关管理（仅内存）
  - 用户授权数据管理（仅内存）
  - 管理界面（前端项目）
  - 单点登录认证界面（前端项目）
  - 支持数据库数据存储
  - 支持Redis 数据存储
- 提供标准 CAS Server
- 提供标准 OIDC
- 提供一种 OAuth2.0 实现
- 提供标准 SAML
- Docker 镜像
  - 后端镜像
  - 前端镜像
- Docker 镜像前后端一体化部署

### 框架

1. 基于 Micronaut 3.10.1

- [Micronaut 用户指南](https://docs.micronaut.io/3.10.1/guide/index.html)
- [Micronaut API](https://docs.micronaut.io/3.10.1/api/index.html)



