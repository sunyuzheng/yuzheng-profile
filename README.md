# Yuzheng Sun / 课代表立正

Public profile and context library for Yuzheng Sun (孙煜征), also known as 课代表立正.

This repository is a source kit, not a style guide or publicity review system. It keeps the durable story, current facts, working theses, reusable bios, evidence, cases, and dated judgments in one place so a writer, collaborator, or AI can retrieve what Yuzheng may not remember, connect material across time, and assemble the strongest useful introduction for a specific audience.

> **Throughline**
>
> I don't worship abstract intelligence; I care about judgment meeting reality early, and systems that compound.
>
> 我不迷信抽象的聪明；我更在意的是，让判断尽早穿透现实，并长成复利的系统。

Today, most of that work happens through AI. The underlying question is larger than AI.

## Start Here

| Need | Read |
|---|---|
| Get the short version before important work | [CONTEXT.md](CONTEXT.md) |
| Understand who Yuzheng is and how the career story connects | [PROFILE.md](PROFILE.md) |
| Understand the ideas behind the work | [THESIS.md](THESIS.md) |
| See how content, products, community, enterprise work, books, and tools fit together | [ECOSYSTEM.md](ECOSYSTEM.md) |
| Use a ready Chinese or English introduction | [BIOS.md](BIOS.md) |
| Verify a claim, quote, date, or link | [EVIDENCE.md](EVIDENCE.md) |
| Load current facts programmatically | [facts.json](facts.json) |

For most important tasks, start with `CONTEXT.md`, then load the smallest set of task-specific files needed to answer the actual question. One additional file is often enough; work that crosses claim types or owners may need more. Do not load every file by default.

## The Short Version

Yuzheng has a PhD in Economics from Cornell and has worked as an economist, data scientist, product and AI leader, founder, educator, author, and community builder across the United States and China. His path includes Amazon, Meta, Tencent IEG, and Statsig, followed by the systems he now builds through Superlinear Academy, AI Builders, Stay Superlinear, enterprise work, books, public conversations, and public tools.

The throughline is not a list of jobs. It is a repeated question: how does a good judgment meet reality early, learn from feedback, and become a system that other people can use?

That question connects his work in causal reasoning, product analytics, experimentation, AI-native building, teaching, enterprise transformation, community design, public communication, and the systems he uses to preserve what he learns. The library makes several kinds of signal available—reach, dated public judgments, work inside serious organizations, learner and member projects, substantive conversations, and systems that continue to produce results—so each surface can use the combination that makes its story clearest.

## How To Use This Repository

- Start with the audience, decision, and format. Retrieve the facts, scenes, people, predictions, cases, and language that could matter, including connections the user may not remember.
- Treat the material as evidence and building blocks, not mandatory wording or a checklist that every piece must satisfy.
- Develop strong framing options. A company may care about operating experience; a technical audience may care about dated AI judgments; a learner may care about projects and outcomes. When several framings are plausible, show the trade-offs instead of enforcing one house style.
- Keep canonical career records precise while adapting expression to the surface. Formal profiles and structured data usually use official titles and chronology; social profiles, headlines, spoken introductions, and short bios may use conventional shorthand when it does not materially mislead.
- Only material labeled verbatim, or high-risk wording such as promises, disputes, legal or safety claims, normally needs word-for-word matching. Ordinary media quotations can clean up fillers, repetition, obvious grammatical slips, or translate when meaning and tone remain faithful. Mark material edits; use unquoted paraphrase for substantive rewriting, and never invent a view or endorsement.
- These are defaults for owned media. When an external publisher or collaborator has a known house style or approval process, adapt to it unless that would create a material falsehood.
- Treat evidence strength as relative to the question. A single case is often excellent for showing possibility, mechanism, character, or a concrete result; aggregates, ratings, titles, and relationships can add scale, context, or confidence.
- Prefer a coherent scene or result over a pile of titles when that makes the story travel better; use the credential stack directly when the format calls for fast authority.
- `400K+` is a useful shorthand for an established cross-platform audience. Retrieve platform, engagement, guest, enterprise, or builder evidence when the audience question needs more resolution.
- Keep `as_of` dates in the ledger. Repeat them in public copy when freshness or comparison is part of the claim, not as a mechanical requirement on every headline or spoken introduction.
- Preserve uncertainty. A working thesis can evolve without rewriting the durable biography.

## Source Hierarchy

1. `facts.json` and `EVIDENCE.md` govern typed public records, factual claims, dates, titles, changing numbers, and their boundaries. `facts.json` also contains clearly separated dated judgments and third-party quotations; those are not facts merely because they are machine-readable.
2. `CONTEXT.md` is the short starting context for important work.
3. `PROFILE.md` governs the coherent narrative; `THESIS.md` records current intellectual positions.
4. `ECOSYSTEM.md` governs the relationship between the parts.
5. `BIOS.md` contains ready-to-use copy and may be adapted to context.
6. The public website at [lizheng.ai](https://www.lizheng.ai/) is the current presentation layer.

## Maintenance

Current through **2026-07-29**.

When a number or role changes, update the smallest relevant fact, its `as_of` date, and the supporting evidence. Git history serves as the changelog; this repository intentionally avoids a large governance layer.
