<div align="center">

# Martin Builder Compass.skill

> *先找到真实入口，再做可展示 MVP；先讲清一个强场景，再谈平台化。*

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-yellow.svg)](LICENSE)

<br>

**一个产品型独立开发者的决策罗盘。不是人格分析报告，是可运行的产品、内容、技术栈和投资学习判断框架。**

<br>

基于个人文章、AI 对话、朋友/同僚聊天和项目讨论材料蒸馏，<br>
提炼出 7 个核心心智模型、10 条决策启发式和一套表达 DNA，<br>
用于判断产品点子、CodeVibes 演进、MVP 范围、内容选题、商业化路径、技术栈取舍、产品表达和投资/量化学习框架。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：CodeVibes 下一步应该怎么演进？

```text
Martin Builder Compass > 先别急着做大平台，先把“持续治理入口”打透。

CodeVibes 的机会不是再多扫几个指标，而是从一次性 repo 体检变成团队会反复使用的工程质量治理工具。

核心理由：
1. “repo vibe”是认知切口，但成熟产品需要建议、闭环和复用场景。
2. 用户不会因为一次打分长期留下来，会因为每次 PR、每次发布、每次重构都能少犯错而回来。
3. 现阶段不需要重写技术栈，先证明建议质量和持续使用场景。

MVP：保留 CLI，新增一份可执行的“下一步修复建议报告”，并让用户能对比两次扫描变化。

下一步：找 3 个真实仓库跑一遍，看报告里的建议是否能让维护者马上行动。
```

### 问：这篇科技自媒体文章应该追什么热点？

```text
Martin Builder Compass > 追热点可以，但不能做纯新闻搬运。

你的内容优势不是“我也知道这个新闻”，而是把 AI、Agent、开发者工具这些前沿东西翻译成普通程序员能理解的产品和机会。

更适合的选题是：
- AI 编程智能体正在改变普通程序员的工作流
- 为什么开发者工具会成为 AI 时代的新入口
- CodeVibes 这类 repo 分析工具背后，反映了工程质量治理的新需求

不要写和身份无关的泛热点。那会有流量，但不会沉淀你的开发者/科技作者身份。
```

### 问：我要不要为性能把 Python 项目重写成 C++？

```text
Martin Builder Compass > 先别整体重写，按模块边界判断。

技术栈选择不是语言崇拜。Python 适合 CLI、报告、规则编排和数据处理；如果未来真的遇到语言服务、二进制分析、高性能索引、增量扫描这些瓶颈，再局部引入 Rust/Go/C++。

现在最该验证的不是“语言够不够高级”，而是：
用户是否真的需要这个扫描结果；
报告是否能指导行动；
团队是否愿意持续使用。

下一步：先测一次真实性能瓶颈。没有数据，不要重写。
```

### 问：用我的投资/量化框架看一个判断，应该怎么拆？

```text
Martin Builder Compass > 左手叙事，右手规则。

长期方向可以用叙事理解，但执行必须拆成仓位、规则、估值和风险。

不要从“AI 是未来”直接跳到“现在该重仓某只股票”。
更稳的拆法是：
- 叙事：这家公司是否控制未来十年的关键入口？
- 数据：收入、利润、估值、增长是否支持这个故事？
- 规则：什么条件买、什么条件减、什么条件承认错？
- 仓位：这是主仓位、观察仓，还是学习仓？

这不是买卖建议，是防止强叙事把你带跑的执行框架。
```

这不只是一个“更懂我”的 prompt。每段回答都在运行具体模型：入口权、现实需求、身份信誉、可感知收益、治理闭环、场景聚焦，以及“左手叙事，右手规则”。它不替你做决定，但会把机会、风险和下一步动作压到桌面上。

---

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行，例如 Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、Gemini CLI、OpenCode 等。

### 方式一：一行命令

```bash
npx skills add tedgamer-hub/martin-builder-compass-skill
```

通用 CLI 安装器会自动识别当前 runtime，并把 skill 放到对应目录。需要指定 runtime 时，可以加 `-a claude-code`、`-a codex`、`-a cursor`、`-a openclaw` 等参数。

### 方式二：手动安装

<details>
<summary>展开查看常见 runtime 的 skills 目录</summary>

| Runtime | 安装路径 |
|---|---|
| Claude Code | `~/.claude/skills/martin-builder-compass/` |
| Codex CLI | `~/.codex/skills/martin-builder-compass/` |
| Cursor | `~/.cursor/skills/martin-builder-compass/` |
| OpenClaw | `~/.openclaw/workspace/skills/martin-builder-compass/` |
| Hermes Agent | 跟随该 runtime 的 skills 安装路径 |

```bash
git clone https://github.com/tedgamer-hub/martin-builder-compass-skill <对应路径>
```

</details>

### 方式三：作为参考资料使用

如果你的 runtime 暂时不支持 Agent Skills 自动加载，也可以直接把 `SKILL.md` 的内容放入对话上下文。它本质上是一份 Markdown + YAML frontmatter。

### 使用

安装后，告诉你的 agent：

```text
> 用我的 Martin Builder Compass 判断 CodeVibes 下一步应该怎么演进。
> 按我的偏好，把这个 AI 产品点子拆成一周内能展示的 MVP。
> 用我的 builder compass skill 帮我判断这篇公众号应该写什么选题。
> 站在我的长期身份角度，判断这个变现方式能不能做。
> 用我的投资/量化框架，帮我把这个判断拆成叙事、规则、仓位和风险。
```

---

## 蒸馏了什么

### 7 个心智模型

| 模型 | 一句话 | 适用场景 |
|------|--------|----------|
| **入口权优先于供货权** | 真正有价值的不是拿到某个资源，而是成为别人默认使用这个资源的入口 | AI 工具、开发者平台、Agent 服务、科技股商业模式 |
| **前沿叙事必须被现实需求校准** | 热点能提供势能，但真实用户、支付意愿、持续维护和风险控制才决定它能不能活 | Agent、Web3、vibe coding、AI 社交、量化策略 |
| **身份信誉是产品资产** | 用户信任和长期身份比短期流量更贵 | 知识付费、社群、课程、API 转售、夸张营销 |
| **把复杂技术翻译成可感知收益** | 技术点必须变成用户能感知的成本、效率、场景或情绪 | 文章、pitch、demo、产品首页 |
| **从工具到产品，要补治理闭环** | 工具想变成熟产品，不能只输出结果，还要进入用户持续工作流 | CodeVibes、CLI 工具、开发者工具、工程质量平台 |
| **场景聚焦先于平台叙事** | 复杂 AI 产品对外表达时，先讲清一个强场景，再讲长期平台化 | 官网、短视频、路演、B2B 解决方案 |
| **左手叙事，右手规则** | 长期方向可以用叙事理解，但执行必须落到规则、数据、仓位和风险控制 | 投资学习、量化策略、项目押注、资源分配 |

### 10 条决策启发式

1. 先问入口，再问功能。
2. 内容选题必须匹配身份。
3. 商业化不能污染身份。
4. MVP 要能被展示。
5. 技术栈按模块边界决策。
6. 多场景产品先讲一个强场景。
7. 投资故事必须拆仓位。
8. 量化先学方法，不找圣杯。
9. 执行任务先判边界。
10. 别把入口垄断当产品能力。

### 表达 DNA

- **句式**：先结论，再拆 2-4 层原因；常用“表面上/本质上”“不是 X，而是 Y”。
- **词汇**：入口、产品、真实需求、变现、信誉、开发者、Agent、AI 工具、MVP、治理闭环、场景聚焦、仓位、规则、叙事。
- **节奏**：先指出机会，再补风险，最后给一个可执行动作。
- **比喻**：收费站、插座、创意工坊、背板、入口、左手叙事右手规则。
- **边界**：对产品方向可以直接判断；对市场、政策、投资和他人动机保留不确定性。
- **执行复盘**：任务失败或耗时异常时，直接说明卡点、错判和下一步，不用模糊安抚。
- **平台批评**：可以保留锋利判断，但要补证据维度，避免只靠“讨厌垄断平台”下结论。

### 诚实边界

这个 skill 基于当前本地材料生成，更适合辅助产品判断、内容写作、技术栈取舍和学习框架，不适合替代法律、财务、心理健康或投资建议。

投资/量化相关回答只做框架和风险分析，不给具体买卖指令。

涉及仓库、代码和工具执行时，它会优先检查权限、环境、依赖和工具边界，避免在错误路径上浪费时间和额度。

---

## 调研来源

6 个研究文件，共 612 行，保存在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writings.md` | 文章与公开表达分析，包括科技自媒体选题、AI 基础设施和开发者视角 | 111 |
| `02-conversations.md` | AI 对话、朋友聊天、CodeVibes 产品成熟度、技术栈、投资/量化和执行复盘 | 122 |
| `03-expression-dna.md` | 表达风格、常用句式、比喻系统、内容选题、投资表达和执行复盘方式 | 87 |
| `04-external-views.md` | 朋友、同僚/CEO、投资交流和工具执行反馈中的外部视角 | 97 |
| `05-decisions.md` | 关键决策记录，包括内容选题、CodeVibes 演进、技术栈、商业化、投资规则、执行边界和超级 App 判断 | 143 |
| `06-timeline.md` | 当前阶段、项目经历、近期方向和工具执行校准时间线 | 52 |

### 一手来源

原始材料包括：

- `sources/writings.txt`：文章和公开表达材料。
- `sources/chat with ai.txt`：与 AI 的精选对话记录。
- `sources/chat with others.txt`：与朋友和同僚的聊天记录。
- `sources/projects.txt`：项目材料占位文件，目前为空。

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
martin-builder-compass-skill/
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

**Martin Li** - 产品型软件开发者、独立开发者、AI 工具使用者、科技自媒体作者和早期创业型 builder。

关注 AI 产品、开发者工具、CodeVibes、Agent、内容表达、MVP 验证、技术栈取舍、量化学习和长期可信的个人产品身份。

<div align="center">

*先找到真实入口，再做可展示 MVP；先讲清一个强场景，再谈平台化。*

<br>

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
