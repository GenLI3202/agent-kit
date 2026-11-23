# agent-kit

[English](README.md)

我给编程智能体做的东西的目录：**Claude 桌面版的 mod 和皮肤**，以及给 Claude Code、Codex 等读 `SKILL.md` 的智能体用的**技能**。每一项都在自己的仓库里；这个仓库是索引，同时也是一个插件市场，所以几个 mod 可以从同一个来源安装。

## 安装 mod 和皮肤

桌面版里：点输入框旁的 **+**，选 **Plugins**，**Add marketplace** 填 `GenLI3202/agent-kit`，再 **Add plugin**。或者在终端里：

```text
/plugin marketplace add GenLI3202/agent-kit
/plugin install star-voyage@agent-kit
/plugin install crab-pal@agent-kit
/plugin install cache-tax-confirm@agent-kit
```

## Mod 和皮肤 · Claude 桌面版

### [star-voyage](https://github.com/GenLI3202/star-voyage) · 星空远征

一款皮肤：一艘飞往你定下那一天（毕业、发布、比赛）的飞船。巡航时是星图，打字时镜头拉近，发送后星际穿梭，缓存凉了就入港；竖排毛笔字的古诗；其他对话显示为远征小队。有星空（夜）和日间两种主题。

| 穿梭（星空） | 抵达和一句诗（日间） |
|---|---|
| <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/warp-night.gif" width="420"> | <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/arrive-day.gif" width="420"> |

### [crab-pal](https://github.com/GenLI3202/crab-pal) · 螃蟹搭子

每个会话一只像素小螃蟹，输入框上方一条沙滩，**所有其他会话和它们的子 agent** 一眼看全，按状态着色。**点一下螃蟹就跳到那个对话**，不用再去侧边栏里找。

<img src="https://raw.githubusercontent.com/GenLI3202/crab-pal/main/docs/images/overview-dark.png" width="640">

### [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm)

[cache-tax](https://github.com/karanb192/cache-tax) 的修改版：提示缓存冷了，发送被拦在一张 **付费发送 / 放弃** 卡片后面，卡片上写着价格，并建议付费还是把工作交给新会话。状态显示在 crab-pal 的沙滩上。不要和上游的 cache-tax 同时安装。

<img src="https://raw.githubusercontent.com/GenLI3202/cache-tax-confirm/main/docs/images/cachetax-dark.png" width="640">

## 技能 · Claude Code、Codex 等

| 技能 | 做什么 |
|---|---|
| [html-presentation-deck](https://github.com/GenLI3202/html-presentation-deck) | 把研究材料做成可交互的 HTML 演讲稿：离线、演讲者窗口、PDF 讲义 |
| [paper-study](https://github.com/GenLI3202/paper-study) | 先讲明白再往下读的论文精读，并维护长期学习笔记 |
| [persona-review-panel](https://github.com/GenLI3202/persona-review-panel) | 乔布斯、马斯克、费曼等人物 agent 并行审阅同一份材料，再汇总分歧 |
| [github-issue-curation](https://github.com/GenLI3202/github-issue-curation) | 按统一标准提交和整理 GitHub issue：短标题、中英双语正文 |
| [session-handoff](https://github.com/GenLI3202/session-handoff) | 在另一个智能体里接续 Codex 或 Claude 的对话（读本地记录） |

每个技能的 README 里有各自的安装步骤。

## 许可

各项目自带许可，见各自仓库。这个索引是 MIT。
