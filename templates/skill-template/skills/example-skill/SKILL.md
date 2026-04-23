---
name: example-skill
description: |
  一句话描述这个 Skill 的能力和触发场景。
  AI Agent 会根据这段描述自动判断何时加载本 Skill。
  例如："帮助用户基于 xxx 模板快速搭建 xxx 类型网站并部署到 EdgeOne Pages。"
trigger_keywords:
  - 关键词 1
  - 关键词 2
  - "自然语言触发句 1"
  - "自然语言触发句 2"
references:
  - references/step1.md
  - references/step2.md
---

# Example Skill

## 决策流程

```
用户请求
  │
  ├─ 用户已有 Prompt？
  │    ├─ 是 → 读取 references/step1.md（解析用户 Prompt）
  │    └─ 否 → 走内置问答（询问产品方向 / 配色 / 功能模块）
  │
  ├─ 拉取模板：npx degit xxx/xxx <project>
  │
  ├─ 按用户意图定制 → 读取 references/step2.md
  │
  ├─ 环境变量配置 → 读取 references/env-setup.md
  │
  └─ 部署到 EdgeOne Pages
       → 提示调用 edgeone-pages-deploy Skill
```

## 核心原则

- **保持 SKILL.md 轻量**：只写主流程 + 决策逻辑
- **细节放 references/**：按需加载，避免 AI 上下文爆炸
- **每一步必须幂等**：用户中途失败可重新触发

## 下一步

根据用户当前所处阶段，按需读取以下参考文档：

- `references/step1.md` — xxx 详细流程
- `references/step2.md` — yyy 详细流程
