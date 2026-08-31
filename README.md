# JFApi · 中文轻量 API 调试工具

本仓库为 **JFApi 发行仓**，仅存放 Release 链接与使用说明。源码请见
[summerZstar/JFApi-src](https://github.com/summerZstar/JFApi-src)。

## 下载

### 免安装绿色版（推荐）

- **GitHub 下载**（海外节点）：<https://github.com/summerZstar/JFApi/releases/latest/download/jfapi.exe>
- **Gitee 镜像**（国内加速）：<https://gitee.com/8snow/JFApi/releases/download/v0.1.0/jfapi.exe>

### NSIS 安装包（含快捷方式 + 卸载入口）

- **GitHub 下载**（海外节点）：<https://github.com/summerZstar/JFApi/releases/latest/download/JFApi_0.1.0_x64-setup.exe>
- **Gitee 镜像**（国内加速）：<https://gitee.com/8snow/JFApi/releases/download/v0.1.0/JFApi_0.1.0_x64-setup.exe>

### 使用文档

<https://jptool.cn/modules/jfapi/index.html>

## 关于

JFApi 是一款本地优先、Git 原生的 API 调试工具（HTTP / WebSocket / SSE），
Tauri 2 + Vue 3 + Rust 实现，单文件绿色版，解压即用。

- 项目就是普通文件夹，直接用 Git 管理请求与集合
- 支持 OAuth2 / JWT / API Key 认证、前置/后置脚本、HMAC 签名
- WebSocket 实时调试与 SSE 流捕获
- 导入 Postman Collection / OpenAPI 3 / cURL