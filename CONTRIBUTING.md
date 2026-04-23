# 贡献指南 · Contributing Guide

感谢你愿意把你的作品贡献给这个仓库 🎉

本仓库是 **EdgeOne Pages 官方示例库**，也是 **「AI Prompt × Skill 挑战赛」作品沉淀地**，所有贡献都会被认真 Review。

---

## 一、我该贡献 Prompt 还是 Skill？

| 场景 | 建议 |
|---|---|
| 我有一段**结构化的建站提示词**，复制粘贴给 AI 就能跑出一个网站 | → 贡献 [Prompt](#二贡献-prompt) |
| 我有一套**可复用的建站 SOP**（含决策树 / 模板 / 参考文档） | → 贡献 [Skill](#三贡献-skill) |
| 不确定 | 先贡献 Prompt 验证效果，成熟后再升级成 Skill |

---

## 二、贡献 Prompt

### 准入要求

- ✅ Prompt 必须能在 **WorkBuddy / Claude Code / Cursor 等主流 AI 编程工具**中实际生成可运行的项目
- ✅ 项目必须能 **部署到 [EdgeOne Pages](https://pages.edgeone.ai/)** 并正常访问
- ✅ 文件使用 **Markdown** 格式，命名为 `<产品或场景>-<网站类型>.md`，小写 + 短横线连接
  - ✅ 好：`luxury-jewelry-ecommerce-website.md`、`ai-image-editor-landing.md`
  - ❌ 差：`我的Prompt.md`、`test1.md`
- ✅ 建议基于 [`templates/prompt-template.md`](./templates/prompt-template.md) 填写

### 投稿步骤

1. **Fork** 本仓库到你的 GitHub 账号
2. 把你的 Prompt 文件放到 `prompts/` 目录下
3. 在 [README.md](./README.md) 的 Prompts 表格里补上你的条目
4. 提交 Pull Request，标题格式：`[Prompt] 简短描述`
5. 在 PR 描述里附：
   - ✅ 作品在 EdgeOne Pages 上的访问链接（必填）
   - ✅ 1–3 张效果截图（必填）
   - ✅ 使用的 AI 工具 & 大致耗时（可选）
   - ✅ 你的社交账号 / 联系方式（可选，便于推广曝光）

---

## 三、贡献 Skill

### 准入要求

- ✅ 遵循 [Anthropic Skills 规范](https://www.anthropic.com/news/claude-skills)：`SKILL.md` 作为入口 + `references/` 存放按需加载的详细文档
- ✅ Skill 必须能被 AI Agent **自然语言触发**并完成一次端到端的建站 + 部署
- ✅ 目录命名：`<主题>-skill` 或 `edgeone-pages-<场景>`，小写 + 短横线
  - ✅ 好：`ai-saas-skill`、`blog-skill`、`portfolio-skill`
- ✅ 必须包含 **README.md**（Skill 的对外说明）
- ✅ 建议基于 [`templates/skill-template/`](./templates/skill-template) 填写

### 投稿步骤

1. **Fork** 本仓库
2. 把你的 Skill 整个目录放到 `skills/` 下
3. 在 [README.md](./README.md) 的 Skills 表格里补上你的条目
4. 提交 Pull Request，标题格式：`[Skill] 简短描述`
5. 在 PR 描述里附：
   - ✅ Skill 触发示例 + AI 实际执行的录屏 / GIF（必填）
   - ✅ 至少一次完整部署后的 EdgeOne Pages 访问链接（必填）
   - ✅ 前置依赖说明（Node 版本、所需密钥等）

---

## 四、Review 流程

1. 我们会在 **7 天内** 进行首轮 Review
2. 可能会要求你补充信息或小幅调整
3. 合并后作品会被纳入仓库，并附作者署名；挑战赛期间提交的作品还将进入活动评审池

---

## 五、行为准则

- ✅ 原创，或你拥有合法授权的内容
- ✅ 不要涉政、色情、歧视、或任何违反 [内容政策](https://pages.edgeone.ai/) 的内容
- ✅ 不提交包含真实密钥 / 个人隐私信息的代码
- ✅ 保持友善，我们是一个开发者社区 🤝

---

## 六、有问题？

- 💬 [Discord 开发者社区](https://discord.gg/pqhvJqC29y)
- 🐛 [提 Issue](https://github.com/TencentEdgeOne/awesome-website-prompts-and-skills/issues)
- 📨 `edgeonedeveloper@tencent.com`

---

<p align="center">期待你的作品 ✨</p>
