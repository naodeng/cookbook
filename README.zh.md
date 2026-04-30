**语言 / Language**

[English](README.md) [中文](README.zh.md)

# Cursor Cookbook

本仓库提供使用 Cursor 构建时的各类小型示例。

## Cursor SDK

Cursor SDK 是用于在你自己的应用、脚本和工作流中运行 Cursor 编程智能体的 TypeScript API。它支持同一套智能体在本地工作区与云端运行时中使用，在运行过程中流式输出智能体事件，并允许你在代码中管理提示词、模型、取消、产物与会话状态。

要运行 SDK 示例，请在 [Cursor 集成面板](https://cursor.com/dashboard/integrations) 创建 Cursor API key，并设置为环境变量 `CURSOR_API_KEY`。

### [快速入门](sdk/quickstart)

一个最小的 Node.js 示例：创建本地智能体、发送一条提示，并流式读取回复。

### [原型工具](sdk/app-builder)

一个 Web 应用，用于在沙盒云端环境中启动智能体，以搭建新项目并迭代想法。

### [看板](sdk/agent-kanban)

用于查看 Cursor Cloud Agents 的看板：按状态或仓库分组、预览产物，以及从仓库与提示创建新的云端智能体。

### [编程智能体 CLI](sdk/coding-agent-cli)

一个最小的命令行界面，让你在终端中启动 Cursor 智能体。

更多说明见 [Cursor SDK TypeScript 文档](https://cursor.com/docs/api/sdk/typescript)。