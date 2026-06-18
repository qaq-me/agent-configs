# 项目说明

## 项目介绍

- `global/CLAUDE.md` 是个人设备的 Claude Code 全局配置文件。
- `global/AGENTS.md` 是个人设备的 Codex 全局配置文件。
- `global_server/CLAUDE.md` 是服务器环境的 Claude Code 全局配置文件。
- 各设备上的 agent 配置路径会通过符号链接指向这些文件；例如用户目录下的 Claude Code / Codex 全局入口可以链接到本仓库里的对应文件。
- 这三个全局配置文件的规则大体一致，但允许因 agent 和运行环境不同而存在差异。

## 根目录导航

| 路径             | 用途                                                         |
| ---------------- | ------------------------------------------------------------ |
| `CLAUDE.md`      | 本文件。                                                     |
| `AGENTS.md`      | Codex 进入本仓库时读取的项目级说明，应与本文件保持同一套项目事实。 |
| `global/`        | 个人设备使用的 agent 全局配置目录，包含 Claude Code 和 Codex 的全局配置文件。 |
| `global_server/` | 服务器环境使用的 agent 全局配置目录，仅包含 Claude Code 全局配置文件。 |
