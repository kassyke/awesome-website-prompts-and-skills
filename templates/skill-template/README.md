# [Your Skill Name]

一句话介绍这个 Skill 做什么。

> 本 Skill 是 EdgeOne Pages [xxx 场景] 的官方/社区贡献实现，用于帮助 AI Agent [具体任务]。

---

## 这个 Skill 做什么

简明描述：当用户说什么样的话，AI Agent 会按什么顺序做什么事。例如：

1. 询问用户的 xxx 需求
2. 拉取模板 / 生成脚手架
3. 按用户意图定制
4. 配置环境变量
5. 本地预览
6. 部署到 EdgeOne Pages

---

## 目录结构

```
[your-skill-name]/
├── README.md                       # 你正在看的文件
└── skills/
    └── [skill-id]/
        ├── SKILL.md                # Skill 入口（frontmatter + 决策树）
        └── references/             # 按需加载的详细文档
            ├── step1.md
            ├── step2.md
            └── ...
```

遵循 Anthropic `skill-creator` 规范：`SKILL.md` 保持轻量（入口 + 决策树），细节文档放 `references/` 按需加载。

---

## 安装方式

### 方式一：自然语言安装（推荐）

在支持 Skills 的 AI 编程工具（WorkBuddy / Claude Code / Cursor 等）中：

> 帮我安装这个 skill：`<this-repo-url>/[your-skill-name]`

### 方式二：手动安装

把 `skills/[skill-id]/` 整个目录复制到工具对应目录：

- **WorkBuddy**：`~/.codebuddy/skills/`
- **Claude Code**：`~/.claude/skills/`
- **Cursor**：项目 `.cursor/rules/` 或全局 skills 目录

---

## 触发方式

在 AI 对话中使用自然语言，示例：

- "帮我..."
- "用 xxx 搭一个..."
- "初始化一个 ... 到 EdgeOne Pages"

---

## 前置依赖

- Node.js ≥ 18
- [其他必要依赖]
- [需要的第三方账号 / 密钥]

---

## 相关链接

- [EdgeOne Pages 官网](https://pages.edgeone.ai/)
- [Anthropic Skills 规范](https://www.anthropic.com/news/claude-skills)
- [模板仓库 / 依赖仓库]

---

## License

MIT
