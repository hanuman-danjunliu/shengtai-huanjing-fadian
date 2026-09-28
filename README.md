# shengtai-huanjing-fadian — 生态环境法典 Agent Skill

《中华人民共和国生态环境法典》结构化知识库技能（2026-08-15 施行，5 编 1242 条）。Agent skill generated from the PRC Ecological Environment Code with [book-to-skill](https://github.com/virgiliojr94/book-to-skill).

## 安装

在任何兼容 Agent Skills 的主机（GitHub Copilot CLI、Claude Code、Amp、OpenClaw 等）上执行：

```
npx skills add https://github.com/hanuman-danjunliu/shengtai-huanjing-fadian --skill shengtai-huanjing-fadian
```

## 文件结构

- `SKILL.md` — 核心制度框架 + 章节/主题索引
- `chapters/` — 7 个章节文件（总则/污染防治×3/生态保护/绿色低碳发展/法律责任和附则）
- `glossary.md` — 术语表（含条文索引）
- `patterns.md` — 法律操作模式
- `cheatsheet.md` — 期限数字、处罚检索表、责任判断树、禁止行为速查

## 用法

- 问 `shengtai-huanjing-fadian` → 加载核心框架
- 问 `shengtai-huanjing-fadian 排污许可` / `土壤污染修复` → 定位并读取对应章节
- 问 `shengtai-huanjing-fadian 第 534 条` → 条文要点与适用
- 问 `shengtai-huanjing-fadian ch05` → 深入生态保护编

## 说明

本技能内容为对公开法律文本的结构化摘要与索引，非法律原文，不构成法律意见。具体个案请结合配套行政法规与最新司法解释。
