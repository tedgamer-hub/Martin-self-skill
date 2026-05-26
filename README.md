<div align="center">

# Self Perspective.skill

> *先把东西做出来，但不要用未来的信誉给今天的速度买单。*

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-yellow.svg)](LICENSE)

<br>

**一个产品型独立开发者的个人决策副驾驶。不是人格分析报告，是可运行的产品判断框架。**

<br>

基于个人文章、AI 对话、朋友聊天和创业复盘材料蒸馏，<br>
提炼出 6 个核心心智模型、8 条决策启发式和一套表达 DNA，<br>
用于判断产品点子、MVP 范围、商业化路径、内容选题和长期信誉边界。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：这个 AI 产品点子值不值得做？

```
Self Perspective > 先验证，不要直接做大。

它表面上是一个 AI 产品点子，本质上要先证明三件事：

1. 它解决的是真实需求，不只是圈内人觉得酷。
2. 用户会反复回来，而不是看一次 demo 就结束。
3. 这个方向不会让你的长期身份变成“追热点的人”。

MVP 不要做平台。先做一个高频小入口：
输入一个具体场景，输出一个可直接使用的结果。
找 10 个真实用户试用，看他们是否愿意第二次回来。

下一步：把这个点子压缩成 3 个词。如果压不下来，说明现在还不是产品，是叙事。
```

### 问：这个变现方式会不会伤害我的身份？

```
Self Perspective > 能做，但需要降级包装。

问题不在于收费，而在于用户会不会误解你到底在卖什么。

如果你是产品开发者，商业化就应该围绕工具、效率、结果和服务展开；
如果包装成信息差、社群焦虑或夸张承诺，短期可能赚钱，
但长期会污染你想建立的开发者/创业者身份。

更稳的做法：
- 免费内容建立信任
- 小额产品验证付费意愿
- 高价服务只卖明确交付，不卖模糊焦虑

下一步：写一句用户半年后知道全部真相时，你仍然愿意挂在自己名字下面的收费说明。
```

### 问：帮我把一个大想法拆成一周内能展示的 MVP

```
Self Perspective > 先收束，再构建。

这个想法现在太大，已经接近“平台叙事”了。
一周 MVP 只保留一个代表性场景、一个核心动作、一个可展示结果。

最小功能：
用户输入一个明确问题，系统输出一份能马上使用的结果。

最小用户：
不要找泛人群，先找最容易理解这个痛点的 5-10 个真实用户。

最小验证：
不是问他们“喜不喜欢”，而是看他们会不会继续用、会不会转发、会不会愿意付一小笔钱。
```

这不只是一个“更懂我”的 prompt。每段回答都在运行具体的判断模型：入口权、现实需求、身份信誉、可感知收益、MVP 收束和场景聚焦。它不替你做决定，但会把机会、风险和下一步动作压到桌面上。

---

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行，例如 Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、Gemini CLI、OpenCode 等。

### 方式一：一行命令

```bash
npx skills add tedgamer-hub/Martin-self-skill
```

通用 CLI 安装器会自动识别当前 runtime，并把 skill 放到对应目录。需要指定 runtime 时，可以加 `-a claude-code`、`-a codex`、`-a cursor`、`-a openclaw` 等参数。

### 方式二：手动安装

<details>
<summary>展开查看常见 runtime 的 skills 目录</summary>

| Runtime | 安装路径 |
|---|---|
| Claude Code | `~/.claude/skills/self-perspective/` |
| Codex CLI | `~/.codex/skills/self-perspective/` |
| Cursor | `~/.cursor/skills/self-perspective/` |
| OpenClaw | `~/.openclaw/workspace/skills/self-perspective/` |
| Hermes Agent | 跟随该 runtime 的 skills 安装路径 |

```bash
git clone https://github.com/tedgamer-hub/Martin-self-skill <对应路径>
```

</details>

### 方式三：作为参考资料使用

如果你的 runtime 暂时不支持 Agent Skills 自动加载，也可以直接把 `SKILL.md` 的内容放入对话上下文。它本质上是一份 Markdown + YAML frontmatter。

### 使用

安装后，告诉你的 agent：

```text
> 用我的 self perspective 判断这个 AI 产品点子值不值得做。
> 按我的偏好，把这个需求拆成一个一周内能展示的 MVP。
> 用我的个人决策 skill 帮我复盘这次选择，重点看我是不是被热点带跑了。
> 站在我的长期信誉角度，判断这个变现方式能不能做。
```

---

## 蒸馏了什么

### 6 个心智模型

| 模型 | 一句话 | 适用场景 |
|------|--------|----------|
| **入口权优先于供货权** | 真正有价值的不是拿到某个资源，而是成为别人默认使用这个资源的入口 | AI 工具、开发者平台、Agent 服务、内容社区 |
| **前沿叙事必须被现实需求校准** | 热点能提供势能，但真实用户、支付意愿和长期维护才决定项目能不能活 | Agent、Web3、vibe coding、AI 游戏 |
| **身份信誉是产品资产** | 用户信任和长期身份比短期流量更贵 | 知识付费、社群、API 转售、灰色渠道 |
| **把复杂技术翻译成可感知收益** | 技术点必须变成用户能感知的成本、效率、场景或情绪 | 文章、pitch、demo、产品首页 |
| **先收束，再构建** | 大想法必须压缩成 2-3 个核心杠杆词，才适合进入 MVP | 平台、社区、Agent 系统、AI 游戏 |
| **场景聚焦先于平台叙事** | 复杂 AI 产品对外表达时，先讲清一个强场景，再讲长期平台化 | 官网、短视频、路演、B2B 解决方案 |

### 8 条决策启发式

1. 先问入口，再问功能。
2. 商业化不能污染身份。
3. 热点先降一档。
4. MVP 要能被展示。
5. 任何借鉴都要过原创边界检查。
6. 写热点必须回答本质问题。
7. 先承认不确定，再给最低成本验证。
8. 多场景产品先讲一个强场景。

### 表达 DNA

- **句式**：先结论，再拆 2-4 层原因；常用“表面上/本质上”“不是 X，而是 Y”。
- **词汇**：入口、产品、真实需求、变现、信誉、开发者、Agent、AI 工具、MVP、同温层、落地。
- **节奏**：先指出机会，再立刻补风险，最后给一个可执行动作。
- **比喻**：收费站、插座、创意工坊、背板、入口。
- **边界**：对产品方向可以直接判断；对市场、政策、他人动机保留不确定性。

### 诚实边界

这个 skill 基于当前本地材料生成，更适合辅助产品判断、内容写作和自我复盘，不适合替代法律、财务、心理健康或重大人生决策建议。

它不是完整人生画像，也不应该被当成固定人设。更准确地说，它是一套基于当前材料整理出的工作流型自我副驾驶。

---

## 调研来源

6 个研究文件，共 558 行，保存在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writings.md` | 文章与公开表达分析，包括 AWS Bedrock、AI API 中转站、AI + Web3、Codex 实战分享 | 111 |
| `02-conversations.md` | AI 对话、朋友聊天、产品判断和创业退出后的自我叙述 | 113 |
| `03-expression-dna.md` | 表达风格、常用句式、比喻系统和情绪节奏 | 72 |
| `04-external-views.md` | 朋友、同僚和 AI 对用户工作方式的镜像反馈 | 86 |
| `05-decisions.md` | 关键决策记录，包括创业退出、商业化边界、AI 游戏平台收束等 | 130 |
| `06-timeline.md` | 个人阶段、项目经历和近期方向时间线 | 46 |

### 一手来源

原始材料包括：

- `sources/writings.txt`：文章和公开表达材料。
- `sources/chat with ai.txt`：与 AI 的对话记录。
- `sources/chat with others.txt`：与朋友和同僚的聊天记录。

出于隐私和长期信誉考虑，公开仓库默认只保留 skill 与研究摘要，不直接公开原始聊天和文章全文。

---

## 这个 Skill 是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 基于本地材料生成。

女娲的工作流大致是：输入材料 -> 并行调研文章、对话、表达、外部反馈、决策和时间线 -> 交叉验证 -> 提炼心智模型 -> 构建 `SKILL.md` -> 用示例问题验证输出风格。

想蒸馏其他人物或个人材料，可以安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

---

## 仓库结构

```text
Martin-self-skill/
├── README.md
├── SKILL.md
└── references/
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

---

## 许可证

Apache License 2.0。详见 [`LICENSE`](LICENSE)。

---

## 关于作者

**Martin Li** - 产品型软件开发者、独立开发者、AI 工具使用者和早期创业型 builder。

关注 AI 工具、开发者产品、Agent、内容表达、MVP 验证和长期可信的个人产品身份。

<div align="center">

*先把东西做出来，但不要用未来的信誉给今天的速度买单。*

<br>

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
