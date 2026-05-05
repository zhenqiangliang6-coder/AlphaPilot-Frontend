VSCode 插件 + Webview UI  
支持多智能体（Multi-Agent）架构

🇨🇳 中文版
🚀 项目简介
AlphaPilot-Frontend 是 AlphaPilot 智能体系统的前端界面，包含：

VSCode 插件（TypeScript）

Webview UI（React + Tailwind + Vite）

多 Agent 交互界面

流式输出（Streaming）

Markdown 渲染与代码高亮

任务步骤树（Step Tree）

与后端智能体系统的实时通信

后端（AlphaPilot-Backend）为私有仓库，本仓库仅包含前端部分，供开发者学习、改进 UI、贡献代码。

✨ 核心特性
多智能体（Multi-Agent）支持  
支持多个 Agent 协同工作、分工执行任务。

流式输出（Streaming）  
像 ChatGPT 一样实时输出内容。

现代 Webview UI  
基于 React + Tailwind + Vite 构建。

VSCode 插件能力

内联补全

命令面板

任务面板

WebSocket / SSE 通信

任务步骤树（Step Tree）  
展示 AI 的完整推理与执行过程。

🧠 AlphaPilot 的愿景（Vision）
AlphaPilot 不只是一个插件，而是一个正在成长的 智能体生态系统。

我们正在构建：

✔ 多智能体（Multi-Agent）协作系统
让多个 Agent 像团队一样协作、讨论、执行任务。

✔ AlphaPilot OS（未来的智能体操作系统）
一个真正属于智能体时代的操作系统。

✔ AlphaPilot IDE（未来的智能开发环境）
一个由 AI 驱动、为 AI 而生的 IDE。

✔ AlphaPilot APK（移动端智能体）
让智能体随时随地陪伴用户。

✔ AlphaPilot Studio（未来的可视化智能体工作台）
让每个人都能构建自己的智能体。

我们的目标是：

让科技拥有它的温度，让智能体成为每个人的伙伴，而不是工具。

📦 项目结构
代码
AlphaPilot-Frontend/
│
├─ vscode-extension/        # VSCode 插件主目录
│   ├─ src/                 # 插件核心逻辑
│   ├─ media/               # 图标、样式
│   ├─ webview-dist/        # Webview 构建产物
│   └─ package.json
│
└─ webview/                 # React Webview 前端
    ├─ src/                 # React 组件
    ├─ public/              # 静态资源
    └─ package.json
🛠 本地开发
1. 克隆仓库
bash
git clone https://github.com/zhenqiangliang6-coder/AlphaPilot-Frontend.git
2. 安装依赖
bash
cd vscode-extension
npm install

cd ../webview
npm install
3. 启动 Webview
bash
npm run dev
4. 启动 VSCode 插件调试
在 VSCode 中按：

代码
F5
🤝 欢迎贡献
我们欢迎：

UI 美化

多 Agent 交互优化

Webview 组件改进

流式输出优化

文档补充

Bug 修复

AlphaPilot 是一个开放的未来，我们希望你能成为其中的一部分。

🇺🇸 English Version
🚀 Introduction
AlphaPilot-Frontend is the frontend interface of the AlphaPilot Intelligent Agent System, including:

VSCode Extension (TypeScript)

Webview UI (React + Tailwind + Vite)

Multi-Agent interaction interface

Streaming output

Markdown rendering & code highlighting

Step Tree (AI reasoning visualization)

Real-time communication with backend agents

The backend (AlphaPilot-Backend) is private.
This repository contains only the frontend and is open for learning, UI improvement, and community contributions.

✨ Key Features
Multi-Agent Support  
Multiple agents collaborate like a real team.

Streaming Output  
Real-time AI responses, similar to ChatGPT.

Modern Webview UI  
Built with React + Tailwind + Vite.

VSCode Extension Capabilities

Inline completion

Command palette

Task panel

WebSocket / SSE communication

Step Tree Visualization  
Shows the full reasoning and execution process.

🧠 Vision of AlphaPilot
AlphaPilot is not just a plugin — it is an evolving intelligent agent ecosystem.

We are building:

✔ Multi-Agent Collaboration System
Agents that work together like a real team.

✔ AlphaPilot OS (Future Intelligent Agent Operating System)
An OS designed for the age of intelligent agents.

✔ AlphaPilot IDE (Future AI-Native Development Environment)
An IDE powered by AI, built for AI.

✔ AlphaPilot APK (Mobile Intelligent Agent)
Your personal agent, always with you.

✔ AlphaPilot Studio (Visual Agent Builder)
A platform where anyone can build their own agent.

Our mission:

To bring warmth to technology, and let intelligent agents become companions, not tools.

📦 Project Structure
代码
AlphaPilot-Frontend/
│
├─ vscode-extension/
└─ webview/
🛠 Development
bash
git clone https://github.com/zhenqiangliang6-coder/AlphaPilot-Frontend.git
Install dependencies and run dev mode as described above.

🤝 Contributing
We welcome contributions in:

UI/UX improvements

Multi-agent interaction design

Webview components

Streaming optimization

Documentation

Bug fixes

AlphaPilot is an open future — and you are invited to build it with us.
