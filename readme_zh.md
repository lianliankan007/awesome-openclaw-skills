# Awesome OpenClaw Skills 中文说明

> 这是 `README.md` 的中文版导读，保留原仓库结构、链接和分类入口，方便中文读者快速理解和使用本仓库。

## 项目简介

`Awesome OpenClaw Skills` 收集了大量由社区构建的 OpenClaw Skills，并按类别整理，方便查找、安装和参考。

OpenClaw 是一个运行在本地设备上的 AI 助手。Skill 用来扩展它的能力，例如：

- 连接外部服务
- 自动化工作流
- 执行特定领域任务
- 提供面向开发、研究、办公和日常使用的能力

本仓库中的技能列表主要来源于 ClawHub，也就是 OpenClaw 的公开技能注册表。

## 安装方式

### 方式一：使用 ClawHub CLI

```bash
clawhub install <skill-slug>
```

### 方式二：手动安装

将某个 Skill 文件夹复制到以下目录之一：

| 位置 | 路径 |
|---|---|
| 全局目录 | `~/.openclaw/skills/` |
| 工作区目录 | `<project>/skills/` |

优先级：

`Workspace > Local > Bundled`

### 方式三：直接把仓库链接发给助手

也可以把某个 Skill 的 GitHub 仓库链接直接贴到助手对话里，让助手自动处理安装和配置。

## 这个列表为什么存在

OpenClaw 官方公开注册表收录的技能很多，但并不是所有项目都适合直接进入 Awesome 列表。

这个仓库的作用是：

- 帮你更快发现高价值 Skill
- 按主题分类整理，降低检索成本
- 过滤一部分垃圾、重复、低质量或高风险条目
- 为 OpenClaw 的实际使用场景提供参考

如果你想了解完整背景、筛选口径和统计数字，请查看原始英文版 [README.md](/C:/Users/pan.pan2/IdeaProjects/githubProjects/awesome-openclaw-skills/README.md)。

## 安全说明

这里列出的 Skill 是经过整理筛选的，但不是安全审计结果。

使用前请注意：

- Skill 在被收录后，原作者仍然可能继续更新内容
- 安装前应自行检查源码和来源
- 不要默认信任任何第三方 Skill
- 在生产环境使用前，先做安全评估

原仓库也建议配合以下工具进行额外检查：

- `Snyk Skill Security Scanner`
- `Agent Trust Hub`

## 分类导航

下面是仓库中主要分类文件的中文索引。点击后可进入对应英文分类页查看完整技能清单。

- [Git 与 GitHub](categories/git-and-github-zh.md)
- [编码代理与 IDE](categories/coding-agents-and-ides-zh.md)
- [浏览器与自动化](categories/browser-and-automation-zh.md)
- [Web 与前端开发](categories/web-and-frontend-development-zh.md)
- [DevOps 与云](categories/devops-and-cloud-zh.md)
- [图像与视频生成](categories/image-and-video-generation-zh.md)
- [Apple 应用与服务](categories/apple-apps-and-services-zh.md)
- [搜索与研究](categories/search-and-research-zh.md)
- [Clawdbot 工具](categories/clawdbot-tools-zh.md)
- [CLI 工具](categories/cli-utilities-zh.md)
- [健康与健身](categories/health-and-fitness-zh.md)
- [市场营销与销售](categories/marketing-and-sales-zh.md)
- [生产力与任务](categories/productivity-and-tasks-zh.md)
- [AI 与 LLM](categories/ai-and-llms-zh.md)
- [数据与分析](categories/data-and-analytics-zh.md)
- 金融：仓库目前未提供单独的分类页
- [媒体与流媒体](categories/media-and-streaming-zh.md)
- [笔记与 PKM](categories/notes-and-pkm-zh.md)
- [iOS 与 macOS 开发](categories/ios-and-macos-development-zh.md)
- [交通出行](categories/transportation-zh.md)
- [个人成长](categories/personal-development-zh.md)
- [沟通协作](categories/communication-zh.md)
- [语音与转录](categories/speech-and-transcription-zh.md)
- [智能家居与 IoT](categories/smart-home-and-iot-zh.md)
- [购物与电商](categories/shopping-and-e-commerce-zh.md)
- [日历与日程安排](categories/calendar-and-scheduling-zh.md)
- [PDF 与文档](categories/pdf-and-documents-zh.md)
- [自托管与自动化](categories/self-hosted-and-automation-zh.md)
- [安全与密码](categories/security-and-passwords-zh.md)
- [Moltbook](categories/moltbook-zh.md)
- [游戏](categories/gaming-zh.md)
- Agent 间协议：仓库目前未提供单独的分类页

## 如何添加 Skill

如果你想把自己的 Skill 加入这个 Awesome 列表，需要先满足一个前提：

- 你的 Skill 必须已经发布到 `github.com/openclaw/skills`

这个列表不接受：

- 个人仓库直链
- gist
- 其他外部来源链接

提交 PR 时，建议同时附上：

- ClawHub 链接
- GitHub 技能目录链接

详细规则见 [CONTRIBUTING.md](/C:/Users/pan.pan2/IdeaProjects/githubProjects/awesome-openclaw-skills/CONTRIBUTING.md)。

## 贡献

欢迎贡献。你可以：

- 提交新的 Skill
- 修正已有分类或描述
- 改进文档可读性

仓库目前更关注已经被社区采用、并且在真实场景中被验证过的 Skill。

## 许可证

本项目使用 MIT License，详见 [LICENSE](/C:/Users/pan.pan2/IdeaProjects/githubProjects/awesome-openclaw-skills/LICENSE)。

## 说明

这份中文版是面向中文读者的概览文档，不逐条翻译原始 README 中的全部技能描述。

原因很直接：

- 原始 README 很长，且技能条目数量极多
- 单条技能描述变动频繁
- 保留原始条目更利于同步上游更新

如果你后续要我继续做，我可以再把它扩展成：

1. 更完整的逐段中文版本
2. 带中文目录说明的增强版
3. 只翻译前半部分说明区，后半部分完整保留原文列表的混合版
