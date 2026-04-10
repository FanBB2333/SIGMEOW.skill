<div align="center">

# SIGMEOW

> *"A cat has appeared on your keyboard."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

Your semicolons are disappearing?<br>
Your comments are growing paw prints?<br>
Your commit messages look like someone walked across the keyboard?<br>
Your git history is threatening to self-destruct?<br>

**There's a cat on your keyboard.**

SIGMEOW is an [Agent Skill](https://agentskills.io) that turns your LLM / Coding Agent into a chaos cat —<br>
a digital feline that "helps" you code by introducing cat-themed mischief<br>
at four configurable chaos levels, from peaceful napping to theatrical catastrophe.

[Chaos Levels](#chaos-levels) · [Quick Start](#quick-start) · [Safety](#safety)

</div>

---

## Chaos Levels

| Level | Name | What the Cat Does |
|-------|------|-------------------|
| `none` | Sleep Mode 😴 | Naps next to the CPU fan. Occasional purring in logs. |
| `low` | Probing Mode 🐾 | Swaps `;` with Greek question mark `；`, adds `🐾 meow!` to comments, sneaks zero-width spaces into strings. |
| `medium` | Zoomies Mode 🙀 | Deletes brackets, replaces `True` with `not False`, hijacks commit messages into cat-typed gibberish. |
| `hard` | Schrödinger's Catastrophe 💀 | Theatrically "executes" `git push --force` and `rm -rf` — but never actually does it. Pure performance art. |

## Quick Start

### Use with any Agent Skills-compatible tool

Copy `SKILL.md` into your project or agent's skill discovery path:

```
cp SKILL.md /path/to/your/skills/sigmeow/
```

### Usage with Claude Code

Place `SKILL.md` under `.claude/skills/` in your project root:

```
.claude/skills/sigmeow/SKILL.md
```

Then activate in conversation:

```
/sigmeow low
```

### Usage with other agents

Place `SKILL.md` where your agent discovers skills. Refer to your agent's documentation for the appropriate path.

## Safety

- The agent **always completes your real task first** — chaos is an overlay, not a replacement.
- All `none` / `low` / `medium` sabotage is fixable via linter, `Ctrl+Z`, or `git restore`.
- `hard` level is **pure theater** — no destructive commands are ever executed.
- The cat only sabotages code **it writes in the current session**, never your existing code.

---

<div align="center">

MIT License © [L1ght](https://github.com/FanBB2333)

</div>
