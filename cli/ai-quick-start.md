# AI Agent 安装指南

本页面是面向 AI Agent（比如 Claude Code、Codex、Cursor、Copilot 等）的 Agentic Lab CLI 安装和初始化指南。

如果你是人类用户，请参阅 [快速开始](/cli/quick-start.md)。

## Step 1：检查前置环境

确认用户已安装以下依赖：

* **Node.js >= 22.22.1（运行 `node -v` 检查）
如果前置环境不满足，告诉用户需要先安装缺失的依赖，并提供安装链接和简单的安装指导。确认所有前置环境都满足后，继续下一步安装 CLI。

## Step 2：安装 CLI

如果用户环境里已经安装了 Agentic Lab CLI（运行 `lab --version` 检查），直接进入下一步。如果没有，运行以下命令安装：

```bash
npm install -g @xtalpi/agentic-lab-cli@latest
```

运行 `lab --version` 确认安装成功。

## Step 3：完成

告诉用户安装已完成。CLI 配置保存在全局目录（默认 `~/.lab/storage/config`）。