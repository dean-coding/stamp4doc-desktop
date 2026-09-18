[README.md](https://github.com/user-attachments/files/32374041/README.md)
# Stamp4Doc Desktop

> 隐私优先的 PDF 桌面工具 — 水印、加密、格式转换，全部本地处理，文件不上传。

[![License](https://img.shields.io/badge/license-proprietary-blue.svg)](https://github.com/dean-coding/stamp4doc-desktop)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-lightgrey.svg)](#)
[![Version](https://img.shields.io/badge/version-1.0.7-green.svg)](#)

## 简介

Stamp4Doc Desktop 是一款面向个人与团队的 PDF 处理桌面应用。所有文件处理均在本地完成，不会上传到任何服务器，从根源上保护文档隐私。

核心功能：

- 🖼️ **PDF 加水印** — 支持文字、图片水印，可自定义透明度、旋转角度、平铺密度
- 🔒 **PDF 加密** — 使用密码保护 PDF，支持 AES 加密
- 📝 **Markdown 转 PDF** — 将 Markdown 文档渲染为专业排版的 PDF
- 💻 **代码转 PDF** — 源代码一键导出为带语法高亮的 PDF
- 📦 **批量处理** — 多文件批量加水印、批量加密
- 💾 **模板管理** — 保存水印模板，一键复用

## 下载安装

从 [Releases](https://github.com/dean-coding/stamp4doc-desktop/releases) 页面下载对应平台安装包：

| 平台 | 架构 | 文件名 |
|------|------|--------|
| macOS | Apple Silicon (arm64) | `stamp4doc-arm64.dmg` |
| macOS | Intel (x64) | `stamp4doc-x64.dmg` |
| Windows | x64 | `stamp4doc-x64.exe` |

### macOS

打开 `.dmg` 文件，将 Stamp4Doc 拖入 Applications 文件夹即可。

> 首次打开若提示"无法验证开发者"，请在「系统设置 → 隐私与安全性」中点击「仍要打开」。

### Windows

运行 `.exe` 安装程序，按提示完成安装。

## 本地处理与隐私

Stamp4Doc Desktop 坚持 **本地优先** 原则：

- ✅ 所有 PDF 处理在本地完成，文件不上传服务器
- ✅ 不收集用户文档内容
- ✅ 不使用第三方分析追踪
- ✅ 离线可用（许可证激活除外）

## 许可证

Stamp4Doc Desktop 为商业软件，使用许可证激活。获取许可证请访问 [Stamp4Doc 官网](https://stamp4doc.netlify.app)。

许可证类型：

- **个人版** — 单设备使用
- **团队版** — 多设备，团队协作

## 开发构建

本仓库为发行仓库，仅包含构建产物。如需查看或修改源代码，请联系开发团队。

构建脚本：

```bash
# 构建 macOS 安装包
npm run dist:mac

# 构建 Windows 安装包
npm run dist:win

# 构建全部平台
npm run dist
```

## 技术栈

- **框架**: Electron + React 19
- **渲染**: Vite + electron-vite
- **PDF 处理**: 本地 PDF 引擎
- **打包**: electron-builder

## 系统要求

- **macOS**: 11.0 或更高版本
- **Windows**: 10 或更高版本

## 反馈与支持

- 问题反馈：[GitHub Issues](https://github.com/dean-coding/stamp4doc-desktop/issues)
- 官网：[stamp4doc.netlify.app](https://stamp4doc.netlify.app)

## 版本历史

详见 [CHANGELOG](https://github.com/dean-coding/stamp4doc-desktop/releases)。

---

© 2026 Stamp4Doc. All rights reserved.
