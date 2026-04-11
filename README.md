<div align="center">

# Celebrity Skills

> *"Great minds don't die — they get distilled into frameworks that outlive them."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-blue)](https://openclaw.ai)
[![中文](https://img.shields.io/badge/Language-中文-blue)](README.zh-CN.md)

<br>

**The Cyber Immortality Project** — Turn legendary thinkers into AI skills.

We distill the wisdom of the world's greatest investors and tech leaders into practical AI skills. Not quotes. Working frameworks.

<br>

[Warren Buffett](#warren-buffett-skill) · [Greg Abel](#greg-abel-skill) · [Contributing](#contributing)

</div>

---

## The Mission

**Celebrity Skills** is a project to create **AI-native representations** of the world's most influential thinkers.

### What We Mean by "Cyber Immortality"

When Buffett, Munger, or any great mind shares their wisdom, it's locked in:
- Books that go unread
- Letters buried in archives
- Interviews watched by thousands, remembered by dozens

**We fix this.**

By distilling their thinking into structured skills, we create AI agents that:
1. **Think like them** — Not parroting quotes, but reasoning through their mental models
2. **Advise in their voice** — Match their communication style
3. **Outlive them** — Their wisdom becomes permanently accessible

### The Value

| Before | After |
|--------|-------|
| "What would Buffett do?" | Ask Buffett directly |
| Scroll through 60 years of letters | Get the answer in seconds |
| Misremember a quote | Verify from source |
| Wonder about edge cases | Apply the framework |

---

## Current Skills

### Warren Buffett .skill {#warren-buffett-skill}

> *"The secret to investing has nothing to do with how smart you are. It's about whether you have the temperament to think independently."*

**The Oracle of Omaha. 60+ years of documented investing wisdom.**

| Specs | Detail |
|-------|--------|
| Mental Models | 5 (Moat, Intrinsic Value, Circle of Competence, Mr. Market, CAP) |
| Decision Heuristics | 8 |
| Investment Cases | 11 (Coca-Cola, Apple, GEICO, Airlines, etc.) |
| Source Material | 60+ years of shareholder letters |

**Links:** [SKILL.md](./warren_buffett/SKILL.md) · [References](./warren_buffett/references/)

---

### Greg Abel .skill {#greg-abel-skill}

> *"It's really the investment philosophy and how Warren and the team have allocated capital for the past 60 years. Really, it will not change."*

**Berkshire Hathaway CEO since 2026. The operator who inherited Buffett's empire.**

| Specs | Detail |
|-------|--------|
| Focus | Operational excellence, culture preservation |
| Key Decision | BYD investment oversight (2008-2025, ~3,890% return) |
| Challenge | No public investing philosophy — he's an operator, not an investor |
| Source Material | <5 direct interviews, ~90% secondhand from Buffett/Munger |

**Links:** [SKILL.md](./greg_abel/SKILL.md) · [References](./greg_abel/references/) · [_meta.json](./greg_abel/_meta.json)

---

## Why These Two?

**Buffett** represents the gold standard of public investing wisdom — 60 years of letters, interviews, and documented decisions.

**Abel** represents a different challenge: What happens when the successor has almost no public record? His skill is inherently limited, but represents the reality of great organizations — the **operator** who keeps the machine running, not the **investor** who makes headlines.

Together, they show the full spectrum:
- The legendary investor with documented wisdom
- The quiet operator who inherited the legacy

---

## How to Use

### For Claude Code / OpenClaw

```bash
# Warren Buffett
> Analyze Apple using Buffett's moat framework
> What's the five-minute test for Tesla?

# Greg Abel
> How would Greg Abel evaluate a new acquisition?
> What's the Abel approach to capital allocation?
```

### For Development

Each skill follows the same structure:

```
skill_name/
├── SKILL.md              ← Core skill file (Anthropic format)
├── _meta.json            ← Metadata for distribution
├── references/
│   ├── 01-writings.md    ← Original writings + summaries
│   ├── 02-conversations.md ← Interviews + transcripts
│   ├── 03-expression-dna.md ← Communication style
│   ├── 04-external-views.md ← Criticisms + perspectives
│   ├── 05-decisions.md   ← Key decisions + cases
│   └── 06-timeline.md    ← Complete timeline
```

---

## Quality Standards

Every skill we produce meets these criteria:

1. **Primary Sources Only** — All content from original English sources
2. **Full Transparency** — Every claim linked to source
3. **Quantified Uncertainty** — We tell you when information is secondhand
4. **Honest Limitations** — Greg Abel's skill explicitly acknowledges what we don't know
5. **Living Documents** — Skills are updated as new information emerges

---

## Contributing {#contributing}

Have a suggestion for a new skill? Open an issue.

We're particularly interested in:
- **Investors:** Charlie Munger, Peter Lynch, Ray Dalio, Carl Icahn
- **Tech Leaders:** Steve Jobs, Jeff Bezos, Elon Musk, Satya Nadella
- **Thinkers:** Naval Ravikant, Shane Parrish, Morgan Housel

---

## Repository Structure

```
celebrity_skills/
├── README.md              ← English version
├── README.zh-CN.md        ← 中文版
├── plan.json              ← Current project plans
├── warren_buffett/
│   ├── SKILL.md
│   └── references/
└── greg_abel/
    ├── SKILL.md
    ├── _meta.json
    └── references/
```

---

## Disclaimer

These skills are distilled from public writings and interviews for learning purposes only. They do not constitute financial, investment, or professional advice.

---

<div align="center">

**The best minds, working for you, forever.**

MIT License © [Leo Li](https://github.com/Talentedleo)

</div>
