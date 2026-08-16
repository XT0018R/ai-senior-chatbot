# AI 虚拟学长 · AI Virtual Senior

田欣然的大学专业选择对话助手，基于大创项目「可感可视化大学专业体验馆」的 AI 升级版。

## 项目简介
面向高中生与家长的大学专业体验工具：以对话形式解答专业选择、就业前景、学习路径等疑问。纯前端单文件实现，接入 DeepSeek 大模型。

## 技术栈
- 单文件 HTML（CSS / JS 全内联）
- [marked.js](https://github.com/markedjs/marked) 渲染 Markdown
- Google Fonts（Inter / Space Grotesk）
- DeepSeek Chat API

## 本地运行
本开源版**不内置 API Key**。使用前请在 `ai-senior-chatbot.html` 第 871 行填入你自己的 DeepSeek API key：

```js
const apiKey = ''; // 在此填入你的 DeepSeek API key（https://platform.deepseek.com）
```

保存后刷新页面即可开始对话。

## 说明
- 本仓库仅用于作品集 / 简历展示，不含任何真实密钥或个人隐私信息。
- 原项目对话数据由 Supabase 托管，本仓库仅含前端代码。

## 作者
田欣然（Tian Xinran）· 2026
