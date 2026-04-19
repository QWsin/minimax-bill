# MiniMax 账单分析

> 中文版 · [English Version](./README.md)

<!-- shields -->
<div align="center">

![license](https://img.shields.io/github/license/QWsin/minimax-bill?style=flat-square&color=6366f1)
![stars](https://img.shields.io/github/stars/QWsin/minimax-bill?style=flat-square&color=6366f1)
![last-commit](https://img.shields.io/github/last-commit/QWsin/minimax-bill?style=flat-square&color=6366f1)
![version](https://img.shields.io/badge/version-1.0.0-6366f1?style=flat-square)
[![pages](https://img.shields.io/badge/%E5%9C%B0%E5%9D%80-GitHub%20Pages-6366f1?style=flat-square)](https://QWsin.github.io/minimax-bill)

</div>

<br>

<div align="center">

**📊 纯前端 MiniMax 账单可视化工具 — 无需上传、无需服务器，直接打开即可使用。**

_零依赖 · 三套主题 · 双语支持 · 离线可用_

</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/JavaScript-ES2022-F7DF1E?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript">
</div>

---

## ✨ 功能特点

| 功能 | 说明 |
|------|------|
| 📂 **多种加载方式** | 点击选择、拖拽上传、或输入文件路径 |
| 📈 **概览统计** | 总记录数、输入/输出 Tokens 及各自占比 |
| 📊 **API 分组** | 按接口类型展示消耗分布，带动画进度条 |
| 📅 **日期热力图** | 按天展示消耗网格，峰值日期自动高亮 |
| 🧠 **模型表格** | 各模型消耗及占比一览 |
| 🎨 **三套主题** | 白色 / 黑色 / 粉色，一键切换 |
| 🌐 **双语支持** | 简体中文 / English — 右上角切换 |
| 🔒 **隐私优先** | 所有数据在浏览器本地处理，不上传任何数据 |

---

## 🚀 快速开始

### 无需安装，直接打开

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### 或使用本地服务器

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# 然后访问 http://localhost:8080
```

---

## 🎯 使用步骤

1. 从 MiniMax 控制台 **导出** 账单为 CSV 文件
2. 在浏览器中 **打开** `index.html`
3. 通过点击、拖拽或路径输入 **加载** 文件
4. 如有需要，按 **日期范围筛选**
5. 点击右上角按钮 **切换** 主题 / 语言

---

## 🗂️ 数据字段

MiniMax 账单导出字段会自动识别：

| 字段 | 别名 |
|------|------|
| 消费时间 / 时间 | Timestamp |
| 消费接口 / 接口名称 | API name |
| 消费模型 / 模型 | Model name |
| 输入消费数 / 输入消费 | Input tokens |
| 输出消费数 / 输出消费 | Output tokens |
| 总消费数 / 总消费 | Total tokens |

---

## 🛠️ 技术栈

- **HTML5** — 语义化结构
- **Tailwind CSS** (CDN) — 工具类样式，参考 shadcn/ui 设计语言
- **Inter** (Google Fonts) — 清晰字体
- **原生 JavaScript** — 无框架，无需构建步骤，约 600 行代码

---

## 📌 开源协议

[MIT](./LICENSE)

---
