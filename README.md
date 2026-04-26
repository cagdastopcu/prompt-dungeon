# Prompt Dungeon

Prompt Dungeon is a bilingual collection of long-form AI RPG system prompts focused on passive narration, xianxia cultivation, alchemy progression, economy loops, and persistent save/load memory.

The repository currently contains two core systems:
1. `The Dao of Narrative` (v33.0): compact passive-world framework (TR + EN).
2. `The Dao of Gentle Alchemy` (v38.0): extended cozy xianxia cultivation/alchemy simulator (TR + EN).

## What This Repository Is

Each markdown file is a complete, drop-in system prompt designed for LLM roleplay sessions where:
- the world updates only on explicit player command,
- progression is simulation-heavy rather than railroady,
- mechanics are explicit (commands, loops, state panels, save/load JSON),
- tone and pacing are controlled by prompt-level constraints.

## Repository Contents

| File | Language | Scope |
|---|---|---|
| `the-dao-of-narrative.md` | Turkish | Compact passive narrative core, commands, state-zero start |
| `the-dao-of-narrative-en.md` | English | English adaptation of the narrative core |
| `turkish-gentle-xianxia-cultivation-alchemy-rpg-prompt.md` | Turkish | Full cozy xianxia alchemy system (foraging, production, market, travel, quests) |
| `english-gentle-xianxia-cultivation-alchemy-rpg-prompt.md` | English | English version of the full alchemy system |

## Core Mechanics Across Prompts

- Strict passive narration (no auto events without player input)
- Command-driven gameplay loops
- Persistent status/memory panel
- JSON save/load protocol
- Alchemy crafting and experimentation
- Foraging and material property systems
- Market/economy and quest workflows
- Time skip and automation helpers
- Xianxia naming and world-consistency rules

## Quick Start

1. Open one of the prompt files.
2. Copy all content.
3. Paste it as the system prompt (or first instruction block) in your LLM chat.
4. Start with a command from that prompt's command list.

Recommended starting files:
- English: `english-gentle-xianxia-cultivation-alchemy-rpg-prompt.md`
- Turkish: `turkish-gentle-xianxia-cultivation-alchemy-rpg-prompt.md`

## Use Cases

- AI text RPG design
- Prompt engineering for interactive fiction
- Xianxia cultivation simulation
- Alchemy/economy gameplay prototyping
- Bilingual (English/Turkish) prompt workflows

## SEO Keywords

`xianxia prompt`, `ai rpg prompt`, `cultivation game prompt`, `alchemy roleplay prompt`, `passive narration prompt`, `chatgpt rpg system prompt`, `interactive fiction prompt`, `json save load prompt`, `bilingual prompt engineering`, `cozy xianxia`

## Suggested GitHub Topics (Repo Tags)

Add these in GitHub repository settings:

`prompt-engineering`, `ai-rpg`, `interactive-fiction`, `xianxia`, `cultivation`, `alchemy`, `game-design`, `chatgpt`, `llm-prompts`, `bilingual`

## Optional SEO Meta Tags (for GitHub Pages or custom docs site)

If you publish this content on a website, use:

```html
<title>Prompt Dungeon - Bilingual Xianxia AI RPG Prompts</title>
<meta name="description" content="Bilingual English/Turkish AI RPG prompts for passive xianxia cultivation, alchemy systems, economy loops, and JSON save/load gameplay.">
<meta name="keywords" content="xianxia prompt, ai rpg prompt, cultivation, alchemy, interactive fiction, llm prompt, prompt engineering, chatgpt rpg">
<meta property="og:title" content="Prompt Dungeon">
<meta property="og:description" content="Long-form passive xianxia AI RPG prompts with save/load, commands, and alchemy progression.">
<meta property="og:type" content="website">
```

## License

Released under the terms of the [LICENSE](LICENSE).
