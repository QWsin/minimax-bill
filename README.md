# MiniMax Bill Analyzer | MiniMax 账单分析

[English](#english) | [中文](#中文)

---

## English

A pure frontend MiniMax bill visualization tool, styled with Tailwind CSS + shadcn/ui aesthetics.

### Features

- **File Loading**: click to select, drag & drop, or enter a file path
- **Overview Stats**: total records, input/output tokens with percentage breakdown
- **API Breakdown**: per-API consumption with progress bars
- **Date Distribution**: daily consumption heatmap grid with peak days highlighted
- **Model Breakdown**: table of consumption by model with percentage
- **3 Color Themes**: White / Black / Pink — switchable via the top bar
- **Bilingual**: Chinese / English — switchable via the top bar

### Usage

#### Option 1 — Direct Open

Open `index.html` directly in your browser (Chrome/Edge recommended).

#### Option 2 — Local Server

```bash
cd minimax-bill
python -m http.server 8080
# Visit http://localhost:8080
```

### Data Fields

MiniMax bill export columns:

| Field | Description |
|-------|-------------|
| Account | Main / Sub account |
| Key Name | API key name |
| API | API type |
| Model | Model name |
| Input Tokens | Input token count |
| Output Tokens | Output token count |
| Total Tokens | Input + Output |
| Timestamp | Consumption time |
| Result | SUCCESS / FAIL |

### Tech Stack

- Tailwind CSS (CDN)
- Inter font (Google Fonts)
- Pure vanilla JavaScript, no framework dependency
- All data processing happens in-browser, nothing is uploaded

### Themes & Languages

Click the **Theme** or **Language** buttons in the top-right corner to switch.

- **Theme**: White (light) / Black (dark) / Pink
- **Language**: 中文 / English

## License

MIT

---

## 中文

一个纯前端的 MiniMax 账单可视化分析工具，基于 Tailwind CSS + shadcn/ui 风格设计。

### 功能

- **文件加载**：支持点击选择、拖拽上传或路径输入 CSV 账单文件
- **概览统计**：总记录数、输入/输出 Tokens 及各自占比
- **API 分组**：按接口类型展示消耗分布及进度条
- **日期分布**：按天展示消耗热力网格，峰值日期自动高亮
- **模型分组**：表格展示各模型消耗及占比
- **三种主题**：白色 / 黑色 / 粉色，右上角一键切换
- **双语支持**：中文 / 英语，右上角切换

### 使用方式

#### 方法1 直接打开

在浏览器中直接打开 `index.html` 即可使用（推荐 Chrome/Edge）。

#### 方法2 本地服务器

```bash
cd minimax-bill
python -m http.server 8080
# 访问 http://localhost:8080
```

### 数据说明

MiniMax 账单导出字段：

| 字段 | 说明 |
|------|------|
| 消费账号 | 主账号 / 子账号 |
| 接口密钥名称 | key 名称 |
| 消费接口 | API 类型 |
| 消费模型 | 模型名称 |
| 输入消费数 | 输入 token 数 |
| 输出消费数 | 输出 token 数 |
| 总消费数 | 输入 + 输出 |
| 消费时间 | 消费时段 |
| 消费结果 | SUCCESS / FAIL |

### 技术栈

- Tailwind CSS (CDN)
- Inter 字体 (Google Fonts)
- 纯原生 JavaScript，无框架依赖
- 所有数据处理在浏览器端完成，不上传任何数据

### 主题与语言

点击右上角的 **主题** 或 **语言** 按钮即可切换。

- **主题**：白色（浅色）/ 黑色（深色）/ 粉色
- **语言**：中文 / English

### License

MIT
