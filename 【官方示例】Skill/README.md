# Skills（官方示例）

> 遵循 [Anthropic Skills 规范](https://www.anthropic.com/news/claude-skills) 的可复用建站能力包——一句话触发，AI 按 SOP 帮你搭站并部署到 EdgeOne Pages。

## 如何使用

1. 进入某个 Skill 目录，阅读它的 `README.md`
2. 按 README 里的「安装方式」把 Skill 放到你 AI 工具的 skills 目录
   - **WorkBuddy**：`~/.codebuddy/skills/`
   - **Claude Code**：`~/.claude/skills/`
   - **Cursor**：项目 `.cursor/rules/` 或全局 skills 目录
3. 在 AI 对话中用自然语言触发，例如：`"帮我用 ai-saas-skill 搭一个 AI SaaS 部署到 EdgeOne Pages"`

---

## Skill 列表

| 名称 | 功能 | 适用场景 |
|---|---|---|
| [ai-saas-skill](./ai-saas-skill) | 基于 `TencentEdgeOne/saas-starter` 模板交互式搭建 SaaS 网站并部署到 EdgeOne Pages | AI SaaS、卖课、AI 工具站 |

> 随着「EdgeOne Pages AI Prompt × Skill 挑战赛」推进，更多优秀作品将陆续沉淀在此。

---

## Skill vs Prompt，有啥区别？

| | Prompt | Skill |
|---|---|---|
| 形态 | 一段 Markdown 文本 | 一个目录（SKILL.md + references/） |
| 触发 | 复制粘贴 | 自然语言，AI 自动识别 |
| 复用性 | 适合单次建站 | 适合多次、多场景复用 |
| 灵活度 | 高（改 Prompt 即可） | 中（需修改 Skill 内部逻辑） |
| 门槛 | 低 | 中等 |

如果你只是想造一个站，**Prompt** 更快；如果你想让一类站的搭建变得标准化可复用，**Skill** 更值得投入。

---

↩ [返回仓库首页](../README.md)
