```
# Project Starters

<p align="center">
<a href="README.md">English</a> | 简体中文
</p>

一个用于现代后端和前端项目的 **可直接运行的项目脚手架集合**。

Clone → 重命名 → 开始开发。

---

## 项目目标

开始一个新项目时，不应该每次都从零开始搭建基础设施。

本仓库提供 **最小但可用于生产环境的项目脚手架**，帮助你快速开始开发。

每个 Starter 都包含：

- 基础项目结构
- 构建配置
- 部署脚本
- 基础基础设施配置

---

## 提供的 Starter

### Java API Starter

基于 **Spring Boot** 的后端 API 项目脚手架。

包含：

- Spring Boot 应用结构
- Maven 构建配置
- 部署脚本
- systemd 服务模板
- 生产环境配置示例

---

### Java Multi-Module Starter

Spring Boot 多模块项目结构。

包含：

- parent pom
- 模块化服务结构
- 公共库模块

---

### Vue Admin Starter

基于 **Vue 3 + Vite** 的后台管理系统脚手架。

包含：

- Vite 构建配置
- API 请求封装
- 权限控制示例
- Nginx 部署配置

---

### UniApp Starter

UniApp 项目脚手架模板。

包含：

- 项目结构
- 构建配置
- 部署说明

---

## 仓库结构
```

starters/
 java-api-starter/
 java-multi-module-starter/
 vue-admin-starter/
 uniapp-starter/

docs/

```
---

## 快速开始

示例：创建一个新的 Java 后端项目。

```bash
git clone https://github.com/yourname/project-starters

cd starters/java-api-starter

# 重命名项目目录
mv java-api-starter my-api

# 启动开发
mvn spring-boot:run
```

------

## 部署

每个 Starter 都包含基础部署支持：

- deploy 脚本
- rollback 回滚脚本
- systemd 服务
- 生产环境配置模板

具体部署说明请查看各 Starter 的文档。

------

## 相关仓库

可复用的工程模板和基础设施模板在这里：

👉 https://github.com/yourname/awesome-engineering-templates

------

## 设计理念

这些 Starter 遵循三个原则：

1. **结构简单**
2. **可用于生产**
3. **快速启动项目**

目标是减少环境搭建时间，让你专注于真正的业务开发。

------

## License

MIT