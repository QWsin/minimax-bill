# MiniMax Bill Analyzer

一个纯前端的 MiniMax 账单可视化分析工具，基于 Tailwind CSS + shadcn/ui 风格设计。

## 功能

- **文件加载**：支持点击选择、拖拽上传或路径输入 CSV 账单文件
- **概览统计**：总记录数、输入/输出 Tokens、总消耗
- **API 分组**：按接口类型展示消耗分布及进度条
- **日期分布**：按天展示消耗热力网格，峰值日期自动高亮
- **模型分组**：表格展示各模型消耗及占比

## 使用方式

### 方法1 直接打开

在浏览器中直接打开 `index.html` 即可使用（推荐 Chrome/Edge）。

### 方法2 本地服务器

```bash
cd minimax-bill
python -m http.server 8080
# 访问 http://localhost:8080
```

## 数据说明

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

## 技术栈

- Tailwind CSS (CDN)
- Inter 字体 (Google Fonts)
- 纯原生 JavaScript，无框架依赖
- 所有数据处理在浏览器端完成，不上传任何数据

## License

MIT
