# Programming Agents Research

边研究市面上开源的热门智能体，边编写一本关于**智能体体系**（agent 架构）的书。本仓库用于存放研究成果与研究进度。

## 研究对象

| 智能体 | 源码位置（`~/gitwork/`） | 研究笔记 |
|---|---|---|
| pi | `pi/` | [agents/pi](agents/) |
| OpenAI Codex（CLI） | 待 clone（`openai/codex`） | [agents/](agents/) |
| Claude Code | 通过其公开分发产物分析 | [agents/](agents/) |
| OpenClaw | `openclaw-docker-cn-im/` | [agents/](agents/) |
| AutoGen | `autogen/` | [agents/](agents/) |
| Hermes Agent | `hermes-agent/` | [agents/](agents/) |

> 被研究的源码**不放入本仓库**，统一 clone 到 `~/gitwork/` 下。

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
