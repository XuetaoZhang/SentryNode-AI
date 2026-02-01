# SentryNode AI

**The Intelligent Sentinel for Web3 Communities.**
**您的 Web3 社群智能中枢**

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Next.js](https://img.shields.io/badge/Next.js-15.1-black)](https://nextjs.org/)
[![Web3](https://img.shields.io/badge/Web3-SpoonAI-green)](https://spoonai.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## 🎯 一句话介绍 | Introduction

**SentryNode AI** 是一个专为 Web3 社群设计的智能群聊助手，通过集成 **SpoonAI** 获取链上数据，解决信息过载、安全风险和重复劳动问题，打造清洁、高效的社群环境。

**SentryNode AI** is an intelligent group chat assistant designed for Web3 communities. By integrating **SpoonAI** for on-chain data, it addresses information overload, security risks, and repetitive tasks, creating a clean and efficient community environment.

---

## 演示地址 | Demo

*  [SentryNode-chat](https://slogan-chat.vercel.app/)

## ✨ 为什么需要这个工具? | Why SentryNode AI?

在 Web3 市场中，社群面临着诸多痛点：
In the Web3 market, communities face several pain points:

*   **⚠️ 安全黑洞 (Security Black Holes):** 钓鱼链接、诈骗广告泛滥，用户资产面临威胁。
*   **🤯 信息过载 (Information Overload):** 海量消息中难以筛选有价值的信息。
*   **🔄 重复劳动 (Repetitive Work):** 管理员需要不断回答相同的基础问题。

**SentryNode AI 帮你：**
*   🛡️ **智能风控 (Risk Warning):** 自动识别并预警高风险链接和诈骗行为。
*   🤖 **智能问答 (Smart Q&A):** 自动回答 Web3 基础问题，引导新手入门。
*   📊 **链上洞察 (On-Chain Insights):** 结合 SpoonAI 实时获取项目白皮书和链上数据，提供可信的分析。
*   🧹 **高效管理 (Efficient Management):** 简单的举报机制 (`/report` 或 `@admin`)，快速清理违规内容。

---

## 🏆 核心特性 | Core Features

### 🔍 智能承诺提取 & 验证 (Smart Commitment Verification)
*   基于 **SpoonAI** 分析项目方白皮书与实时链上数据。
*   对比承诺与实际行为，量化项目可信度。

### 🛡️ 社群安全卫士 (Community Security)
*   **钓鱼识别:** 自动扫描群内链接，识别潜在的钓鱼和诈骗风险。
*   **广告拦截:** 智能过滤垃圾广告，保持群聊清净。

### 💡 Web3 知识图谱 (Web3 Knowledge Graph)
*   **新手引导:** "如何开始了解与参与？" —— 自动推送学习资料和安全提示。
*   **风险教育:** 普及 Web3 岗位风险、合约漏洞等安全知识。

---

## 📂 项目结构 | Project Structure

*   **`/SentryNode-chat`**: 前后端一体化应用 (Frontend & Backend)
    *   基于 **Next.js** + **Socket.io** + **Mongoose**。
    *   提供群聊界面、后台管理及 SpoonAI 数据接口集成。
*   **`/SentryNode-AI`**: AI 核心引擎 (AI Engine) *(开发中 / Under Development)*
    *   基于 **Python**。
    *   负责复杂的数据分析、NLP 处理及链上数据深度挖掘。

---

## 🚀 快速开始 | Getting Started

### 1. 启动 Web 客户端 (SentryNode-chat)

前端界面与 Socket 服务端。

```bash
cd SentryNode-chat

# 安装依赖 | Install dependencies
npm install

# 启动 Socket 服务端 (需要单独终端运行) | Start Socket Server (Run in separate terminal)
npm run server

# 启动 Next.js 前端开发服务器 | Start Frontend Dev Server
npm run dev
```

访问 `http://localhost:3000` 查看效果。

### 2. 启动 AI 引擎 (SentryNode-AI)

AI 核心逻辑与数据处理服务。

```bash
cd SentryNode-AI

# 创建虚拟环境 (推荐) | Create virtual environment (Recommended)
python -m venv venv
# 激活环境 | Activate environment
# Mac/Linux:
source venv/bin/activate
# Windows:
# venv\Scripts\activate

# 安装依赖 | Install dependencies
pip install -r requirements.txt

# 启动 AI 服务 | Start AI service
python main.py
```

---

## 🤝 贡献 | Contributing

欢迎提交 Issue 或 Pull Request 来改进 SentryNode AI！

---

## 📄 许可证 | License

MIT License
