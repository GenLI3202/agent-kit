# agent-kit

[English](README.md)

我和编程智能体一起用的所有东西，放在一个索引里：**Claude 桌面版的 mod 和皮肤**，以及给 Claude Code、Codex 等读 `SKILL.md` 的智能体用的**技能**。自己做的各有自己的仓库；我常用的第三方作品也列在里面，**明确标注 🔗 三方**，并链接到原作者。这个仓库同时是我三个 mod 的插件市场。

## 表格怎么读

- **来源**：🟢 自制，或 🔗 三方（带作者）。三方作品不在这里镜像，请点链接，并遵守作者的许可。
- **使用频率（会话数）**：我自己的 Claude Code 会话（2026 年 5 月到 11 月，本地记录）里，这个技能或它的命令出现过的会话数。★★★ = 30 及以上，★★ = 10 到 29，★ = 3 到 9，— = 更少。它只反映我自己的习惯，不是质量排名。n/a = 常驻或无法统计。
- 每张表内按使用频率排序。
- Anthropic 内置的技能（docs、artifacts、浏览器等）和我每天用的 Claude Code 命令不列在这里。

## 我最常用的

| | |
|---|---|
| ★★★ | [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm)（112）、[star-voyage](https://github.com/GenLI3202/star-voyage)（81）、[session-handoff](https://github.com/GenLI3202/session-handoff)（42）、[html-presentation-deck](https://github.com/GenLI3202/html-presentation-deck)（36） |
| ★★ | 🔗 [zotero-cli](https://github.com/54yyyu/zotero-mcp)（24）、[persona-review-panel](https://github.com/GenLI3202/persona-review-panel)（19）、[paper-study](https://github.com/GenLI3202/paper-study)（11） |

## 按功能分类

### 演示、文档与图示

| 名称 | 来源 | 使用频率（会话数） | 做什么 |
|---|---|---|---|
| [html-presentation-deck](https://github.com/GenLI3202/html-presentation-deck) | 🟢 自制 | ★★★ · 36 | 把研究材料做成可交互的 HTML 演讲稿：离线、演讲者窗口、PDF 讲义。 |
| [diagram-design](https://github.com/cathrynlavery/diagram-design) | 🔗 三方 · cathrynlavery | ★ · 8 | 杂志级排版的图示（架构、流程、时序、图表等），输出独立的 HTML/SVG。 |
| [huashu-design](https://github.com/alchaincyf/huashu-design) | 🔗 三方 · alchaincyf | — · 2 | 一句话做出高保真 HTML 原型、幻灯片和动画。 |
| [archify](https://github.com/tt-a1i/archify) | 🔗 三方 · tt-a1i | — · 1 | 把想法、方案或代码库变成可交互的图。 |

### 阅读与研究

| 名称 | 来源 | 使用频率（会话数） | 做什么 |
|---|---|---|---|
| [zotero-cli](https://github.com/54yyyu/zotero-mcp) | 🔗 三方 · 54yyyu | ★★ · 24 | 在命令行里读写 Zotero 文献库：搜索、PDF 全文、笔记、批注、引用。随 zotero-mcp 一起发布（`zotero-mcp install-skill`）。 |
| [paper-study](https://github.com/GenLI3202/paper-study) | 🟢 自制 | ★★ · 11 | 先讲明白再往下读的论文精读，并维护长期学习笔记。 |
| [weread-skills](https://github.com/Tencent/WeChatReading) | 🔗 三方 · Tencent | — · 2 | 微信读书：搜书、书架、划线笔记、书评、阅读统计。 |
| [agent-reach](https://github.com/Panniantong/Agent-Reach) | 🔗 三方 · Panniantong | — · 1 | 只读地搜索、阅读推特、Reddit、YouTube、小红书、B 站等平台的内容。 |

### 思考搭档与评审

| 名称 | 来源 | 使用频率（会话数） | 做什么 |
|---|---|---|---|
| [persona-review-panel](https://github.com/GenLI3202/persona-review-panel) | 🟢 自制 | ★★ · 19 | 乔布斯、马斯克、费曼等人物 agent 并行审阅同一份材料，再汇总分歧。 |
| [elon-musk-perspective](https://github.com/alchaincyf/elon-musk-skill) | 🔗 三方 · alchaincyf | ★ · 6 | 用马斯克的思维框架看问题：第一性原理、成本拆解。 |
| [feynman-perspective](https://github.com/alchaincyf/feynman-skill) | 🔗 三方 · alchaincyf | ★ · 5 | 费曼的视角：货物崇拜检测、命名不等于理解、用演示代替论证。 |
| [steve-jobs-perspective](https://github.com/alchaincyf/steve-jobs-skill) | 🔗 三方 · alchaincyf | ★ · 4 | 用乔布斯的视角分析产品、审视决策：6 个心智模型、8 条启发式。 |
| [andrej-karpathy-perspective](https://github.com/alchaincyf/karpathy-skill) | 🔗 三方 · alchaincyf | — · 2 | 卡帕西的视角：AI 可靠性、学习方法、vibe coding、炒作判断。 |
| [zhang-yiming-perspective](https://github.com/alchaincyf/zhang-yiming-skill) | 🔗 三方 · alchaincyf | — · 1 | 用张一鸣的视角分析产品、组织、全球化和人才。 |
| [ilya-sutskever-perspective](https://github.com/alchaincyf/ilya-sutskever-skill) | 🔗 三方 · alchaincyf | — · 0 | 用 Ilya Sutskever 的视角看 AI 方向、安全策略和研究品味。 |
| [huashu-nuwa](https://github.com/alchaincyf/nuwa-skill) | 🔗 三方 · alchaincyf | — · 0 | 把任何人的思维方式蒸馏成可运行的 skill（上面的人物视角就是它做的）。 |
| [grilling · grill-me · grill-with-docs](https://github.com/mattpocock/skills) | 🔗 三方 · Matt Pocock | ★ · 6 | 被追着拷问一份计划，直到漏洞露出来；docs 版本顺手写决策记录（ADR）和术语表。 |

### Agent 工作流、会话与成本

| 名称 | 来源 | 使用频率（会话数） | 做什么 |
|---|---|---|---|
| [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm) | 🟢 自制 | ★★★ · 112 | 提示缓存冷了，发送被拦在「付费发送」卡片后面，并建议付费还是换新会话。是 Karan Bansal 的 cache-tax 的修改版。 |
| [session-handoff](https://github.com/GenLI3202/session-handoff) | 🟢 自制 | ★★★ · 42 | 在另一个智能体里接续 Codex 或 Claude 的对话（读本地记录）。 |
| [github-issue-curation](https://github.com/GenLI3202/github-issue-curation) | 🟢 自制 | ★ · 6 | 按统一标准提交和整理 GitHub issue：短标题、中英双语正文。 |
| [codebase-design · domain-modeling](https://github.com/mattpocock/skills) | 🔗 三方 · Matt Pocock | — · 1 | 设计「深模块」；建立项目的领域术语和决策记录。 |

### 桌面版的观感

| 名称 | 来源 | 使用频率（会话数） | 做什么 |
|---|---|---|---|
| [star-voyage](https://github.com/GenLI3202/star-voyage) | 🟢 自制 | ★★★ · 81 | 一款皮肤：飞向你定下那一天的飞船。星图、穿梭、入港、古诗；星空与日间两种主题。 |
| [crab-pal](https://github.com/GenLI3202/crab-pal) | 🟢 自制 | n/a | 每个会话一只螃蟹；看其他会话和子 agent，点一下就跳转。常驻显示，所以没有使用次数。 |

### 项目专用

| 名称 | 来源 | 使用频率（会话数） | 做什么 |
|---|---|---|---|
| [acc-content-posting-system](https://github.com/GenLI3202/acc-content-posting-system) | 🟢 自制 | n/a | 给 Across Cycling Club 网站用的 Telegram 发布技能：路由加活动、路线、媒体、知识四个发布器。只适用于那个俱乐部。 |

## 安装

**Mod 和皮肤**：桌面版里点输入框旁的 **+**，选 **Plugins**，**Add marketplace** 填 `GenLI3202/agent-kit`，再 **Add plugin**。或者在终端里：

```text
/plugin marketplace add GenLI3202/agent-kit
/plugin install star-voyage@agent-kit
/plugin install crab-pal@agent-kit
/plugin install cache-tax-confirm@agent-kit
```

cache-tax-confirm 不要和上游的 cache-tax 同时安装。**技能**：每个仓库的 README 里有各自的安装步骤。三方技能请按作者的说明安装。

## 效果图

### Mod 和皮肤 · Claude desktop

#### [star-voyage](https://github.com/GenLI3202/star-voyage) · 星空远征

| 穿梭（星空） | 抵达和一句诗（日间） |
|---|---|
| <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/warp-night.gif" width="420"> | <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/arrive-day.gif" width="420"> |

#### [crab-pal](https://github.com/GenLI3202/crab-pal) · 螃蟹搭子

<img src="https://raw.githubusercontent.com/GenLI3202/crab-pal/main/docs/images/overview-dark.png" width="640">

#### [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm)

<img src="https://raw.githubusercontent.com/GenLI3202/cache-tax-confirm/main/docs/images/cachetax-dark.png" width="640">

## 许可

各项目自带许可，见各自仓库。这个索引是 MIT。
