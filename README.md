# Awesome Agent Skills

> 精选优秀的 Agent Skills 开源库集合，方便 AI 开发者查询使用。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## 什么是 Agent Skills
Agent Skills 是 Anthropic 于 2025 年 10 月推出的开放标准，用于为 AI Agent（如 Claude）提供模块化的能力扩展。

### 核心概念
Skills 本质上是一个目录结构，包含 SKILL.md 文件（指令和元数据）、可选脚本（如 Python）、参考文档和资源。Agent 只在任务匹配时动态加载完整内容，实现**渐进式披露**，避免上下文浪费。

### 主要优势
 - Token 效率：按需加载，节省 80%+ tokens。
 - 知识复用：创建一次，可跨对话、平台（如 Claude、Cursor、VS Code）使用。
 - 团队协作：封装组织流程，如代码审查或数据分析。

### Skills 文档
 - [Agent Skills 的规范和文档](https://agentskills.io/)

## Skills 网站
- [Skills Marketplace](https://skillsmp.com/) \
Skills Marketplace 是一个 agent skills 的发现平台：聚合 63000+ 来自 GitHub 的 skills，提供智能搜索和分类，提供一键安装命令。

- [SkillStore](https://skillstore.io/) \
开放的 AI 技能市场。发现、安装并分享为 Claude、Codex 与 Claude Code 预构建的能力。

- [Skills.sh](https://skills.sh/) \
The open agent skills ecosystem.

- [Claude Marketplace](https://claudemarketplaces.com/) 

- [AITmpl Skills](https://www.aitmpl.com/skills) 



## Skills 开源仓库
### 官方 Skills

- [Anthropic 官方 Skills](https://github.com/anthropics/claude-skills) \
Anthropic 官方的公开仓库，展示 Claude AI 的 Agent Skills 示例，用于扩展模型在专业任务上的能力。
Skills 按类别组织技能，包括创意应用（艺术、设计）、技术任务（网页测试、MCP 服务器生成）和企业流程（品牌、沟通）

- [ClaudeKit - Agent Skills](https://github.com/mrgoonie/claudekit-skills) \
ClaudeKit-skills 是 ClaudeKit.cc 平台的强大技能集合，专为增强 Claude AI 代理能力而设计。
Skills 位于 .claude/skills/ 目录下，按类别组织技能文件，包括前端开发（Next.js、Tailwind、shadcn/ui）、后端基础设施（Docker、DevOps、数据库）、浏览器自动化（Chrome DevTools、Puppeteer）、AI 多模态处理（Gemini 视觉、文档处理）以及流程方法论（规划、调试、代码审查）。

- [Awesome GitHub Copilot](https://github.com/github/awesome-copilot/tree/main/skills) \
GitHub Copilot 的社区精选自定义资源仓库，汇集提示、指令和聊天模式，提升 Copilot 在代码生成、文档编写和问题解决中的效率。Skills 位于项目 skills 目录下。

- [Hugging Face Skills](https://github.com/huggingface/skills) \
Hugging Face 官方技能库，提供 Agent Context Protocol (ACP) 定义的 AI/ML 任务技能文件夹，支持 Claude Code、OpenAI Codex、Gemini CLI 和 Cursor 等代理工具。

- [OpenAI Skills](https://github.com/openai/skills) \
OpenAI 为 Codex 代理提供的技能目录，汇集指令、脚本和资源的文件夹，帮助 AI 代理重复执行特定任务，实现“一次编写，到处使用”。


---

**持续更新中...** 欢迎关注和贡献！
