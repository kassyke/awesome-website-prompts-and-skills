<!--
【Prompt 模板说明】（投稿时请删除本段注释）

1. 文件名命名规则：<产品或场景>-<网站类型>.md，小写 + 短横线
   例：luxury-jewelry-ecommerce-website.md / ai-image-editor-landing.md
2. 整份 Prompt 用英文书写，便于 AI 输出更稳定的代码结构（中文描述会被 AI 翻译）
3. 每个章节用大写英文做标题（GOAL / STACK / STRUCTURE 等），结构越清晰 AI 执行越稳
4. 投稿前请实际跑一遍，确保能端到端部署到 EdgeOne Pages
-->

Build a [网站类型] in [语言] using [技术栈].

GOAL
简单描述这个网站是什么、目标用户是谁、要传递什么感觉。
例：Create a premium English-language homepage for a fictional luxury jewelry maison called Maison Perle. The site should feel like a shoppable oil-painting exhibition...

This is not a generic ecommerce template, not a SaaS landing page...
（明确它 **不是什么**，帮 AI 避坑）

---

STACK
- Framework: React + Vite + TypeScript
- Styling: Tailwind CSS + shadcn/ui
- Backend: EdgeOne Pages Edge Functions
- Storage: EdgeOne KV (optional)
- Deployment: EdgeOne Pages

---

ASSETS
列出所有需要用到的 CDN 图片 / 视频链接，AI 会直接引用，不要让它自己生成图。

Media URLs:
- Hero video: https://...
- Hero image: https://...
- Product image 1: https://...

---

STRUCTURE
- Hero section: ...
- About / Story section: ...
- Product showcase: ...
- CTA section: ...
- Footer: ...

（越具体越好，AI 会严格按此结构生成）

---

VISUAL LANGUAGE
- Colors: #xxxxxx / #yyyyyy / ...
- Typography: serif for headlines, sans-serif for body
- Spacing: generous whitespace
- Mood: dark / light / cinematic / minimal / ...

---

INTERACTIONS
- Hover: subtle scale + shadow
- Scroll: fade-in on enter viewport
- Click CTA: open modal / navigate / ...

---

EDGE FUNCTIONS
说明哪些接口走边缘函数，例如：
- `/api/subscribe`: handle newsletter subscription, store email in KV
- `/api/contact`: forward form to email

---

CONSTRAINTS
- 单页站点 / 多页站点
- 响应式断点
- 不要使用的库（例如：不要用 framer-motion）
- 必须使用的库（例如：必须用 shadcn/ui 的 Button）

---

DEPLOY
After generation, deploy to EdgeOne Pages:
1. `npm install && npm run build`
2. Use EdgeOne Pages CLI or web UI to deploy
3. Verify all media loads correctly

---

<!-- 投稿者信息（可选，写在这里会显示在展示页） -->
Author: [你的名字 / GitHub handle]
Contact: [可选：邮箱 / 社交账号]
Demo: [部署后的 EdgeOne Pages URL]
