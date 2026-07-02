# Yuan Tools

`yuan-tools` 是 Yuan 的小工具总索引仓库。

这里不直接存放每个小工具的完整源码，而是作为所有工具的入口目录，用来维护工具清单、发布信息和本地开发约定。

## 目录用途

- `TOOLS.md`：人类可读的小工具清单。
- `tools.json`：机器可读的小工具注册表。
- `AGENTS.md`：Codex 在这个工作区内需要遵守的开发约定。
- `yuan-*`：本地小工具项目目录，每个工具会单独发布到自己的 GitHub 仓库。

## 发布结构

每个小工具通常会提供两个交付版本：

- Web 静态版：`release/html`
- Windows 桌面版：`release/win`

每个工具也会有自己的独立 GitHub 仓库、版本 tag 和 GitHub Release。

## 当前工具

查看完整列表：

- [TOOLS.md](TOOLS.md)
- [tools.json](tools.json)
