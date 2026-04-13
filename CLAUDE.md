# CLAUDE.md

本文件为 Claude Code (claude.ai/code) 在本仓库中工作时提供指引。

## 项目概述

这是 **awesome-chatgpt-prompts-zh** 项目——一个中文 ChatGPT 提示词（Prompt）合集与使用指南。本项目为纯内容/文档项目，不是软件应用，无构建、测试或 lint 命令。

## 仓库结构

- `awesome-chatgpt-prompts-zh/` — Git 仓库（来源：PlexPt/awesome-chatgpt-prompts-zh）
  - `README.md` — 主文档，按类别/角色组织的全部提示词
  - `prompts-zh.json` — 结构化 JSON 数据，包含所有提示词（字段：`act`、`prompt`）；**数据主源**
  - `prompts-zh-TW.json` — 繁体中文版
  - `question/` — 编号命名的 Markdown 文件（0.md、1.md ...），各含单独问答提示词
  - `cat.md` — 猫娘/角色扮演类提示词变体
  - `USEAGE.md` — 使用示例及截图
  - `old/` — 历史/废弃内容
  - `pic/` — 文档中引用的图片
  - `LICENSE` — MIT 许可证

## 内容规范

- `prompts-zh.json` 中每条提示词格式为 `{ "act": "<角色名>", "prompt": "<完整提示词>" }`
- `README.md` 以二级标题（`##`）+ 引用块（`>`）组织提示词
- 新增提示词时需**同时**更新 `README.md` 和 `prompts-zh.json`，保持两者同步
- 正文使用简体中文；繁体中文内容仅放在 `prompts-zh-TW.json` 中
