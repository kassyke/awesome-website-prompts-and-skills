# Awesome Website Prompts & Skills

> **EdgeOne Pages 上建站的 Prompt 与 Skill 灵感库**
> 官方维护的示例合集 · 也是「EdgeOne Pages AI Prompt × Skill 挑战赛」作品沉淀地

[🌐 EdgeOne Pages 官网](https://pages.edgeone.ai/) · [🏆 挑战赛活动主页](https://pages.edgeone.ai/) · [💬 开发者社区 Discord](https://discord.gg/pqhvJqC29y)

---

## 这个仓库是什么

一句话：**「给一个 Prompt 或一个 Skill，就能在 EdgeOne Pages 上跑起来一个完整网站」** 的资源合集。

它包含两类资产：

| 类型 | 是什么 | 怎么用 |
|---|---|---|
| 🧠 **Prompts** | 可以直接喂给 AI 编程工具（WorkBuddy / Claude Code / Cursor 等）的**建站提示词** | 复制 Prompt → 粘贴到 AI 对话 → AI 帮你生成并部署一个完整网站 |
| 🧩 **Skills** | 遵循 [Anthropic Skills 规范](https://www.anthropic.com/news/claude-skills) 的**可复用能力包**，封装了特定类型网站的搭建 SOP | 安装 Skill → 一句话触发 → AI 按 SOP 搭站并部署到 EdgeOne Pages |

两类资产都可以在 [EdgeOne Pages](https://pages.edgeone.ai/) 上一键部署为生产级站点。

> 📌 本仓库是「**EdgeOne Pages AI Prompt × Skill 挑战赛**」的**官方作品池**——随着活动推进，所有参赛作品都会沉淀在此，形成开发者可长期复用的 Prompt / Skill 索引。

---

## 仓库内容速览

### 🧠 Prompts｜[浏览全部 →](./prompts)

| 名称 | 类型 | 技术栈 |
|---|---|---|
| [Luxury Jewelry Ecommerce Website](./prompts/luxury-jewelry-ecommerce-website.md) | 奢侈品珠宝电商单页站 | React + Vite + TS + Tailwind + shadcn/ui + Edge Functions |

### 🧩 Skills｜[浏览全部 →](./skills)

| 名称 | 功能 | 场景 |
|---|---|---|
| [ai-saas-skill](./skills/ai-saas-skill) | 基于 `TencentEdgeOne/saas-starter` 模板，交互式搭建 SaaS 网站并部署到 EdgeOne Pages | AI SaaS、卖课、AI 工具站 |

---

## 快速开始

### 我是开发者，我想用一个现成的 Prompt / Skill 建站

**方式 1：使用 Prompt**

1. 打开 [prompts/](./prompts) 目录，挑一个你喜欢的
2. 复制 Prompt 全文
3. 粘贴到 [WorkBuddy](https://www.codebuddy.cn/) / Claude Code / Cursor 等 AI 编程工具
4. 让 AI 自动生成项目 → 部署到 [EdgeOne Pages](https://pages.edgeone.ai/)

**方式 2：使用 Skill**

1. 打开 [skills/](./skills) 目录，进入某个 Skill 的 README
2. 按照 Skill 文档里的「安装方式」把它放到你 AI 工具的 skills 目录
3. 用自然语言触发，例如：`"帮我用 ai-saas-skill 搭一个 AI SaaS 部署到 EdgeOne Pages"`

> 💡 推荐使用 **[WorkBuddy](https://www.codebuddy.cn/)**：国内开发者可直接使用，原生支持 Skills，和 EdgeOne Pages 无缝协作。

### 我是参赛者，我想把作品放进来

欢迎！参加挑战赛并按投稿规范提交作品，你的 Prompt / Skill 会被收录进本仓库。
→ 详见 [CONTRIBUTING.md](./CONTRIBUTING.md)

---

## EdgeOne Pages AI Prompt × Skill 挑战赛

本仓库是挑战赛的**官方作品池**，所有参赛作品最终都会沉淀在这里。

- 🎯 **两条赛道**：Prompt 赛道 / Skill 赛道
- 🏆 **奖励**：EdgeOne 全线产品 Credit + 全网曝光 + 官方证书
- 📅 **时间**：2026.04.23 – 2026.05.15
- 🔗 **活动主页**：[前往报名 →](https://pages.edgeone.ai/)

> GitHub Star 破 1000 后，所有获奖者 Credit 全线 **+10%**。

---

## 关于 EdgeOne Pages

[**EdgeOne Pages**](https://pages.edgeone.ai/) 是腾讯面向全球开发者的 **Serverless 全栈部署平台**，服务于 AI 应用、Web 应用、静态站点的一键部署：

- ⚡ **一键部署**：Next.js / Vite / React / Vue / Astro 等主流框架开箱即用
- 🧠 **Edge Functions**：离用户最近的边缘节点跑后端逻辑，低延迟响应
- 🗃️ **KV Storage**：边缘侧轻量存储，适合会话、缓存、用户状态
- 🤖 **AI 友好**：原生适配 AI SaaS / AI Agent / AI Chatbot 场景
- 🌍 **全球加速 & 安全**：基于腾讯全球 CDN + WAF

📎 相关文档：
- [产品介绍](https://pages.edgeone.ai/document/product-introduction)
- [Pages Functions](https://pages.edgeone.ai/document/pages-functions-overview)
- [KV Storage](https://pages.edgeone.ai/document/kv-storage)

---

## 贡献

欢迎贡献 Prompt 或 Skill！

- 📝 **投稿指南**：[CONTRIBUTING.md](./CONTRIBUTING.md)
- 📋 **Prompt 模板**：[templates/prompt-template.md](./templates/prompt-template.md)
- 📋 **Skill 模板**：[templates/skill-template/](./templates/skill-template)

提交方式：**Fork → 新增文件 → Pull Request**。我们会在 1 周内 Review。

---

## 联系我们

- 💬 [Discord 开发者社区](https://discord.gg/pqhvJqC29y)
- 📨 `edgeonedeveloper@tencent.com`
- 🌐 [EdgeOne Pages 官网](https://pages.edgeone.ai/)

---

## 许可证

[MIT](./LICENSE)

Prompts 与 Skills 的具体使用条款以各自目录下的说明为准。

---

<p align="center">
  Made with ❤️ by <a href="https://pages.edgeone.ai/">Tencent EdgeOne Pages</a>
</p>
