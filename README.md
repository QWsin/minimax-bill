# MiniMax Bill Analyzer

> English version · [中文版](./README_zh.md)

<!-- shields -->
<div align="center">

![license](https://img.shields.io/github/license/QWsin/minimax-bill?style=flat-square&color=6366f1)
![stars](https://img.shields.io/github/stars/QWsin/minimax-bill?style=flat-square&color=6366f1)
![last-commit](https://img.shields.io/github/last-commit/QWsin/minimax-bill?style=flat-square&color=6366f1)
![version](https://img.shields.io/badge/version-1.0.0-6366f1?style=flat-square)

</div>

<br>

<div align="center">

**📊 Pure frontend MiniMax bill visualization — no upload, no server, just open and go.**

_Zero dependencies · Three themes · Bilingual · Works offline_

</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/-JavaScript-ES2022-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</div>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📂 **Multi-mode loading** | Click to select, drag & drop, or paste a file path |
| 📈 **Overview stats** | Total records, input/output tokens with percentage breakdown |
| 📊 **API breakdown** | Per-API consumption with animated progress bars |
| 📅 **Date heatmap** | Daily grid with peak days auto-highlighted |
| 🧠 **Model table** | Per-model consumption with % share |
| 🎨 **3 themes** | White / Black / Pink — switchable instantly |
| 🌐 **Bilingual** | 简体中文 / English — top-bar toggle |
| 🔒 **Privacy first** | All data stays in your browser, nothing is uploaded |

---

## 🚀 Quick Start

### No install required

```bash
# Just open the file directly
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Or use a local server

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# Then visit http://localhost:8080
```

---

## 🎯 Usage

1. **Export** your bill from MiniMax console as CSV
2. **Open** `index.html` in your browser
3. **Load** the file via click, drag, or path input
4. **Filter** by date range if needed
5. **Switch** theme / language via the top-right buttons

---

## 🗂️ Data Fields

MiniMax bill export columns are auto-detected:

| Field | Aliases |
|-------|---------|
| Timestamp | 消费时间 / 时间 |
| API name | 消费接口 / 接口名称 |
| Model name | 消费模型 / 模型 |
| Input tokens | 输入消费数 / 输入消费 |
| Output tokens | 输出消费数 / 输出消费 |
| Total tokens | 总消费数 / 总消费 |

---

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **Tailwind CSS** (CDN) — utility-first styling, shadcn/ui-inspired design
- **Inter** (Google Fonts) — clean typography
- **Vanilla JS** — no framework, no build step, ~600 lines total

---

## 📌 License

[MIT](./LICENSE)

---
