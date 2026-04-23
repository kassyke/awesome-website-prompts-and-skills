# Skills（官方示例 Skill）

> Tencent EdgeOne 维护的**建站能力包合集**——安装一个 Skill，用一句话触发，AI 就能生成并部署一个带登录、支付、AI 等完整能力的网站。

## 如何使用

1. 进入某个 Skill 目录，阅读它的 `README.md`
2. 按 README 里的「安装方式」把 Skill 放到你 AI 工具的 skills 目录
   - **WorkBuddy**：`~/.codebuddy/skills/`
   - **Claude Code**：`~/.claude/skills/`
   - **Cursor**：项目 `.cursor/rules/` 或全局 skills 目录
3. 在 AI 对话中用自然语言触发，并把 Skill 的 GitHub 地址一并贴上，让 AI 自动读取完整定义。例如：

   ```
   帮我用这个 Skill 搭一个 AI SaaS 部署到 EdgeOne Pages：
   https://github.com/TencentEdgeOne/awesome-website-prompts-and-skills/tree/main/official-skills/ai-saas-skill
   ```

4. AI 会按 Skill 定义的 SOP 完成整个项目的搭建，并部署到 [EdgeOne Pages](https://pages.edgeone.ai/)

---

## Skill 列表

| 名称 | 功能 | 适用场景 |
|---|---|---|
| [ai-saas-skill](./ai-saas-skill) | 基于 `TencentEdgeOne/saas-starter` 模板交互式搭建 SaaS 网站并部署到 EdgeOne Pages | AI SaaS、卖课、AI 工具站 |

> 随着「WorkBuddy × Tencent EdgeOne AI Prompts × Skills 挑战赛」推进，更多优秀作品将陆续沉淀在此。

---

↩ [返回仓库首页](../README.md)
