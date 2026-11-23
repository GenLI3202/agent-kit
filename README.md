# agent-kit

[简体中文](README.zh-CN.md)

Everything I use with coding agents, in one index: **mods and skins for the Claude desktop app** and **skills** for Claude Code, Codex and other agents that read `SKILL.md`. Mine live in their own repositories; third-party ones I use a lot are listed too, **clearly marked 🔗 3rd-party** and linked to their authors. This repository is also a plugin marketplace for my mods.

## How to read the tables

- **Source**: 🟢 mine, or 🔗 3rd-party with its author. Third-party items are not mirrored here; follow the link and respect the author's licence.
- **Use (sessions)**: the number of my own Claude Code sessions (May to November 2026, local transcripts) in which the skill or its command ran. ★★★ = 30 or more, ★★ = 10 to 29, ★ = 3 to 9, — = fewer. It is a count of my own habits, not a quality ranking. n/a = always-on or not measurable.
- Each table is sorted by use.
- Anthropic's built-in skills (docs, artifacts, browser…) and the Claude Code commands I also use daily are not listed.

## My most-used

| | |
|---|---|
| ★★★ | [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm) (112), [star-voyage](https://github.com/GenLI3202/star-voyage) (81), [focus-timer](https://github.com/GenLI3202/focus-timer) (45), [session-handoff](https://github.com/GenLI3202/session-handoff) (42), [html-presentation-deck](https://github.com/GenLI3202/html-presentation-deck) (36) |
| ★★ | 🔗 [zotero-cli](https://github.com/54yyyu/zotero-mcp) (24), [walkthrough-cards](https://github.com/GenLI3202/walkthrough-cards) (21), [persona-review-panel](https://github.com/GenLI3202/persona-review-panel) (19), [paper-study](https://github.com/GenLI3202/paper-study) (11) |

## By category

### Presentations, documents and diagrams

| Name | Source | Use (sessions) | What it does |
|---|---|---|---|
| [html-presentation-deck](https://github.com/GenLI3202/html-presentation-deck) | 🟢 mine | ★★★ · 36 | Turn research material into an interactive HTML talk: offline deck, presenter window, PDF handout. |
| [diagram-design](https://github.com/cathrynlavery/diagram-design) | 🔗 3rd-party · cathrynlavery | ★ · 8 | Editorial-quality diagrams (architecture, flow, sequence, charts…) as standalone HTML/SVG. |
| [huashu-design](https://github.com/alchaincyf/huashu-design) | 🔗 3rd-party · alchaincyf | — · 2 | High-fidelity HTML prototypes, slides and animation from one sentence. |
| [archify](https://github.com/tt-a1i/archify) | 🔗 3rd-party · tt-a1i | — · 1 | Turn an idea, plan or codebase into an interactive diagram. |

### Reading and research

| Name | Source | Use (sessions) | What it does |
|---|---|---|---|
| [zotero-cli](https://github.com/54yyyu/zotero-mcp) | 🔗 3rd-party · 54yyyu | ★★ · 24 | Read and write your Zotero library from the shell: search, PDF full text, notes, annotations, citations. Ships with zotero-mcp (`zotero-mcp install-skill`). |
| [walkthrough-cards](https://github.com/GenLI3202/walkthrough-cards) | 🟢 mine | ★★ · 21 | Turn a model, a codebase or a research storyline into learning cards: one question per card, layers, diagrams, offline HTML, EN/中文. |
| [paper-study](https://github.com/GenLI3202/paper-study) | 🟢 mine | ★★ · 11 | Explanation-first guided reading of academic papers, with durable study notes. |
| [weread-skills](https://github.com/Tencent/WeChatReading) | 🔗 3rd-party · Tencent | — · 2 | WeChat Reading: search books, shelf, highlights, reviews, reading stats. |
| [agent-reach](https://github.com/Panniantong/Agent-Reach) | 🔗 3rd-party · Panniantong | — · 1 | Read and search Twitter, Reddit, YouTube, Xiaohongshu, Bilibili and more, read-only. |

### Thinking partners and review

| Name | Source | Use (sessions) | What it does |
|---|---|---|---|
| [persona-review-panel](https://github.com/GenLI3202/persona-review-panel) | 🟢 mine | ★★ · 19 | Persona agents (Jobs, Musk, Feynman…) review one document in parallel; disagreements are pulled together. |
| [elon-musk-perspective](https://github.com/alchaincyf/elon-musk-skill) | 🔗 3rd-party · alchaincyf | ★ · 6 | Think through a problem the way Musk would: first principles, cost teardown. |
| [feynman-perspective](https://github.com/alchaincyf/feynman-skill) | 🔗 3rd-party · alchaincyf | ★ · 5 | Feynman's lens: cargo-cult check, naming vs understanding, a demo instead of an argument. |
| [steve-jobs-perspective](https://github.com/alchaincyf/steve-jobs-skill) | 🔗 3rd-party · alchaincyf | ★ · 4 | Jobs's lens on products and decisions: 6 mental models, 8 heuristics. |
| [andrej-karpathy-perspective](https://github.com/alchaincyf/karpathy-skill) | 🔗 3rd-party · alchaincyf | — · 2 | Karpathy's lens: AI reliability, learning, vibe coding, hype checks. |
| [zhang-yiming-perspective](https://github.com/alchaincyf/zhang-yiming-skill) | 🔗 3rd-party · alchaincyf | — · 1 | Zhang Yiming's lens on product, organisation, globalisation and talent. |
| [ilya-sutskever-perspective](https://github.com/alchaincyf/ilya-sutskever-skill) | 🔗 3rd-party · alchaincyf | — · 0 | Ilya Sutskever's lens on AI direction, safety strategy and research taste. |
| [huashu-nuwa](https://github.com/alchaincyf/nuwa-skill) | 🔗 3rd-party · alchaincyf | — · 0 | Distil anyone's way of thinking into a runnable skill (the perspective skills above come from it). |
| [grilling · grill-me · grill-with-docs](https://github.com/mattpocock/skills) | 🔗 3rd-party · Matt Pocock | ★ · 6 | Get interviewed relentlessly about a plan until the gaps show; the docs variant also writes ADRs and a glossary as it goes. |

### Agent workflow, sessions and cost

| Name | Source | Use (sessions) | What it does |
|---|---|---|---|
| [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm) | 🟢 mine | ★★★ · 112 | Cold prompt cache? The send waits behind a Pay and send card, with advice to pay or hand off. A patch of cache-tax by Karan Bansal. |
| [session-handoff](https://github.com/GenLI3202/session-handoff) | 🟢 mine | ★★★ · 42 | Continue a Codex or Claude conversation from its local record in another agent. |
| [run-watch](https://github.com/GenLI3202/run-watch) | 🟢 mine | ★ · 3 | Watch long runs from their log files with no model calls: progress, ETA, and a notice when a run finishes, fails or stalls. |
| [github-issue-curation](https://github.com/GenLI3202/github-issue-curation) | 🟢 mine | ★ · 6 | File and curate GitHub issues to one standard: short titles, bilingual bodies. |
| [checkpoint](https://github.com/GenLI3202/checkpoint) | 🟢 mine | — · 1 | `/checkpoint` writes a short handoff file; a card suggests compacting at a calm moment; a welcome back after a break, with no model call. |
| [model-router](https://github.com/GenLI3202/model-router) | 🟢 mine | n/a | Runs light subagent jobs on Sonnet instead of the pricier session model; never starts or suggests a subagent. Automatic, so no usage count. |
| [codebase-design · domain-modeling](https://github.com/mattpocock/skills) | 🔗 3rd-party · Matt Pocock | — · 1 | Design deep modules; build a project's domain language and decision records. |

### Desktop mods: look, feel and housekeeping

| Name | Source | Use (sessions) | What it does |
|---|---|---|---|
| [star-voyage](https://github.com/GenLI3202/star-voyage) | 🟢 mine | ★★★ · 81 | A skin: a ship flying toward a day you choose. Star chart, warp, harbour, poems; night and day. |
| [focus-timer](https://github.com/GenLI3202/focus-timer) | 🟢 mine | ★★★ · 45 | A focus countdown card above the prompt: one outcome per round, four dots a day, breaks that say something, a crab that drops by. |
| [mods-manager](https://github.com/GenLI3202/mods-manager) | 🟢 mine | — · 2 | `/mods`: a pane that lists your installed mods and turns each on or off with a click. |
| [crab-pal](https://github.com/GenLI3202/crab-pal) | 🟢 mine | n/a | A crab per session; see your other sessions and their subagents, click to jump. Always on, so no usage count. |

### Project-specific

| Name | Source | Use (sessions) | What it does |
|---|---|---|---|
| [acc-content-posting-system](https://github.com/GenLI3202/acc-content-posting-system) | 🟢 mine | n/a | Telegram-driven posting skills for Across Cycling Club's website: router plus events, routes, media and knowledge posters. Specific to that club. |

## Install

**Mods and skins**: in the desktop app click **+** next to the prompt box, then **Plugins**, **Add marketplace** with `GenLI3202/agent-kit`, then **Add plugin**. Or in a terminal:

```text
/plugin marketplace add GenLI3202/agent-kit
/plugin install crab-pal@agent-kit     # or any other mod
```

Mods in this marketplace: star-voyage, crab-pal, cache-tax-confirm, focus-timer, checkpoint, run-watch, model-router, mods-manager. Do not install cache-tax-confirm beside upstream cache-tax. **Skills**: each repository's README has its own steps. Third-party skills: follow the author's instructions.

## Gallery

### Mods and skins · Claude desktop

#### [star-voyage](https://github.com/GenLI3202/star-voyage) · 星空远征

| Warp, night | Arrival and a poem, day |
|---|---|
| <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/warp-night.gif" width="420"> | <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/arrive-day.gif" width="420"> |

#### [crab-pal](https://github.com/GenLI3202/crab-pal) · 螃蟹搭子

<img src="https://raw.githubusercontent.com/GenLI3202/crab-pal/main/docs/images/overview-dark.png" width="640">

#### [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm)

<img src="https://raw.githubusercontent.com/GenLI3202/cache-tax-confirm/main/docs/images/cachetax-dark.png" width="640">

#### [focus-timer](https://github.com/GenLI3202/focus-timer) · 专注计时

<img src="https://raw.githubusercontent.com/GenLI3202/focus-timer/main/docs/images/card.png" width="520">

## License

Each project carries its own licence; see its repository. This index is MIT.
