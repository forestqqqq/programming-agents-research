# AGENTS.md — 协作约定

## 代码示例语言

向我展示示例代码时**优先使用 Python**。

- 我能读懂的语言：Python、Java、JavaScript/TypeScript。
- 其他语言（Rust、Go、C/C++ 等）对我来说较难阅读。若必须用（如被研究项目的源码就是该语言），请同时给出等价的 Python 实现或逐行解释。
- 在本仓库中编写的分析脚本、示例程序也优先用 Python。

## 运行环境

- 安装依赖、执行 Python 脚本统一使用 **uv**（如 `uv run script.py`、`uv add <pkg>`），不要直接用 `pip install` / 系统 Python。
- 需要一次性脚本时用 `uv run --with <pkg> script.py`，避免污染全局环境。
