# Programming Agents Research

边研究市面上开源的热门智能体，边编写一本关于**智能体体系**（agent 架构）的书。本仓库用于存放研究成果与研究进度。

## 研究对象

| 智能体 | 源码位置（项目同级目录） | 研究笔记 |
|---|---|---|
| pi | `pi/`（上游已更名 earendil-works/pi） | [agents/pi](agents/) |
| OpenAI Codex（CLI） | 待 clone（`openai/codex`） | [agents/](agents/) |
| Claude Code | 官方公开仓库 + 分发产物分析 | [agents/](agents/) |
| OpenClaw | `openclaw/`（下载中） | [agents/](agents/) |
| Deep Agents（LangChain） | `deepagents/` | [agents/](agents/) |
| LangGraph（运行时） | `langgraph/` | [agents/](agents/) |
| LangChain（基础库） | `langchain/` | [agents/](agents/) |
| Microsoft Agent Framework | `agent-framework/`（下载中） | [agents/](agents/) |
| OpenCode | `opencode/` | [agents/](agents/) |
| OpenHands | `openhands/` | [agents/](agents/) |
| Aider | `aider/`（下载中） | [agents/](agents/) |
| Cline | `cline/`（下载中） | [agents/](agents/) |
| Gemini CLI | `gemini-cli/`（下载中） | [agents/](agents/) |
| browser-use | `browser-use/`（下载中） | [agents/](agents/) |
| smolagents | `smolagents/` | [agents/](agents/) |
| AutoGen | `autogen/` | [agents/](agents/) |
| Hermes Agent | `hermes-agent/` | [agents/](agents/) |

> 候选池（暂未纳入）：Goose、Crush、Qwen Code、SWE-agent、CrewAI、MetaGPT、Agno、AgentScope、Letta、UI-TARS、pydantic-ai、Mastra 等，见研究过程记录。

> 被研究的源码**不放入本仓库**，统一放在与项目同级的目录下（相对本仓库为 `../<仓库名>/`）。

## 目录结构

```
programming-agents-research/
├── README.md      # 本文件：项目说明
├── PROGRESS.md    # 研究进度追踪
├── book/          # 书稿：大纲与章节
├── agents/        # 每个被研究智能体的分析笔记
├── topics/        # 跨项目的主题研究（上下文、工具调用、记忆……）
└── private/       # 本地私密内容（已被 .gitignore 排除，不会入库）
```

## 约定

- 一切私密内容（配置、凭据、个人笔记、未打算公开的书稿）放 `private/` 或确保匹配 `.gitignore` 规则。
- 单个智能体的笔记约定见 [agents/README.md](agents/README.md)。
- 跨项目主题清单见 [topics/README.md](topics/README.md)。
