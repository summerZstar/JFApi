# JFApi · 中文轻量 API 调试工具

本仓库为 **JFApi 发行仓**，仅存放 Release 链接与使用说明。源码请见
[summerZstar/JFApi-src](https://github.com/summerZstar/JFApi-src)。

## 下载

> 发行物为各平台**便携 zip**（解压即运行，无安装包）。Windows 用 7-Zip 等第三方解压可避免 SmartScreen 弹窗；macOS 首次运行需解除 Gatekeeper 隔离（`xattr -cr jfapi`）；Linux 需系统 WebKit2 依赖。

### Windows x64（推荐）

- **GitHub**：<https://github.com/summerZstar/JFApi/releases/latest/download/JFApi-windows.zip>
- **Gitee**：<https://gitee.com/8snow/JFApi/releases/download/v1.2.0/JFApi-windows.zip>

### macOS x64

- **GitHub**：<https://github.com/summerZstar/JFApi/releases/latest/download/JFApi-macos.zip>
- **Gitee**：<https://gitee.com/8snow/JFApi/releases/download/v1.2.0/JFApi-macos.zip>

### Linux x64

- **GitHub**：<https://github.com/summerZstar/JFApi/releases/latest/download/JFApi-linux.zip>
- **Gitee**：<https://gitee.com/8snow/JFApi/releases/download/v1.2.0/JFApi-linux.zip>

### 使用文档

<https://jptool.cn/modules/jfapi/index.html>

## 关于

JFApi 是一款本地优先、Git 原生的 API 调试工具（HTTP / WebSocket / SSE），
Tauri 2 + Vue 3 + Rust 实现，单文件绿色版，解压即用。

- 项目就是普通文件夹，直接用 Git 管理请求与集合
- 支持 OAuth2 / JWT / API Key 认证、前置/后置脚本、HMAC 签名
- WebSocket 实时调试与 SSE 流捕获
- 导入 Postman Collection / OpenAPI 3 / cURL