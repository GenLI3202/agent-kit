# agent-kit

[简体中文](README.zh-CN.md)

A catalogue of what I have built for coding agents: **mods and skins for the Claude desktop app**, and **skills** for Claude Code, Codex and other agents that read `SKILL.md`. Each item lives in its own repository; this one is the index, and it is also a plugin marketplace, so the mods install from a single source.

## Install the mods and skins

In the desktop app: click **+** next to the prompt box, then **Plugins**, **Add marketplace** with `GenLI3202/agent-kit`, then **Add plugin**. Or in a terminal:

```text
/plugin marketplace add GenLI3202/agent-kit
/plugin install star-voyage@agent-kit
/plugin install crab-pal@agent-kit
/plugin install cache-tax-confirm@agent-kit
```

## Mods and skins · Claude desktop

### [star-voyage](https://github.com/GenLI3202/star-voyage) · 星空远征

A skin: a ship flying toward a day you choose (a graduation, a launch, a race). A star chart at cruise, the camera closing in as you type, a warp when you send, harbour when the cache goes cold, vertical classical poems in brush script, your other conversations as squads. Night and day themes.

| Warp, night | Arrival and a poem, day |
|---|---|
| <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/warp-night.gif" width="420"> | <img src="https://raw.githubusercontent.com/GenLI3202/star-voyage/main/docs/images/arrive-day.gif" width="420"> |

### [crab-pal](https://github.com/GenLI3202/crab-pal) · 螃蟹搭子

A pixel crab for every session, and a strip of sand above the prompt that shows **all your other sessions and their subagents** at a glance, coloured by status. **Click a crab to jump** to that conversation: no more hunting in the side panel.

<img src="https://raw.githubusercontent.com/GenLI3202/crab-pal/main/docs/images/overview-dark.png" width="640">

### [cache-tax-confirm](https://github.com/GenLI3202/cache-tax-confirm)

A patched [cache-tax](https://github.com/karanb192/cache-tax): when the prompt cache is cold, the send waits behind a **Pay and send / Dismiss** card with the price, and advice on whether to pay or hand the work to a fresh session. Shows its status on crab-pal's beach. Do not install beside upstream cache-tax.

<img src="https://raw.githubusercontent.com/GenLI3202/cache-tax-confirm/main/docs/images/cachetax-dark.png" width="640">

## Skills · Claude Code, Codex and others

| Skill | What it does |
|---|---|
| [html-presentation-deck](https://github.com/GenLI3202/html-presentation-deck) | Turn research material into an interactive HTML talk: offline deck, presenter window, PDF handout |
| [paper-study](https://github.com/GenLI3202/paper-study) | Explanation-first guided reading of academic papers with durable study notes |
| [persona-review-panel](https://github.com/GenLI3202/persona-review-panel) | Several persona agents (Jobs, Musk, Feynman…) review one document in parallel, then the disagreements are pulled together |
| [github-issue-curation](https://github.com/GenLI3202/github-issue-curation) | File and curate GitHub issues to one standard: short titles, bilingual bodies |
| [session-handoff](https://github.com/GenLI3202/session-handoff) | Continue a Codex or Claude conversation from its local record in another agent |

Each skill's README has its own install steps.

## License

Each project carries its own license; see its repository. This index is MIT.
