# product-research

A [Kimi Code](https://www.kimi.com/code/docs/en/) **User Skill** for decision-oriented market & product research.

It turns a rough topic into a decision-ready output by **matching the research scope to the decision**: connecting evidence, assumptions, validation tasks, and recommendations — instead of always running a full search.

## Task modes

| Mode | Input example | Minimal output |
| --- | --- | --- |
| 快速初筛 (quick screen) | a new direction, public links | one-page brief: judgment, core facts, key unknowns, next step |
| 竞品/技术专项 (competitor/tech) | product list, specs, papers or patents | like-for-like matrix, evidence, maturity gaps |
| 立项与路线决策 (initiation) | opportunity, resources, target market | full decision report, route comparison, staged investment |
| 更新与复盘 (update & review) | previous report + new material | change list (new / revised / withdrawn / still-unknown) |

Quick tasks are never forced through full strategy + finance + team modules; modules are picked per decision and labeled 必选 / 可选 / 不适用(理由).

## What's inside

- `SKILL.md` — entry point: mode selection, shortest main flow, non-negotiable quality rules, module library, load-on-demand index
- `references/` — method files loaded only when needed: evidence rules, research methods, decision framework (stage gates, PIC, portfolio, finance, regulatory, patent/FTO screening), PDMA seven-domain self-check map, prompt library, privacy rules
- `templates/` — full report outline (16 sections for initiation mode), one-page brief, and four registers (evidence, requirements traceability, assumption & decision log, validation gate plan)
- `examples/` — clearly labeled fictional walkthroughs (no real companies or cases)

## Key rules baked in

- Claims are classified (fact / vendor claim / inference / internal assumption / to-verify); key claims trace to evidence IDs with source, channel, and three dates (published / data-as-of / accessed).
- Republished copies of the same source are **not** independent verification; "not found in search" ≠ "does not exist".
- Requirement hypotheses are separated from validated needs; without first-hand research, only a validation plan is produced.
- Route comparison (build / integrate / outsource / partner / resell / status quo) uses one delivery scope — no preset winners.
- Patent stats define count vs. family; PCT is a filing route, never added to countries or types; FTO screening is a starting clue, not a legal opinion.
- Financial inputs are marked known / estimated / assumed; profit ≠ cash flow; scenarios and sensitivity required; no fabricated precision.
- Privacy: public sources only for the repo itself; internal data stays task-local and is never sent to external searches or written into the repo.

Method framework inspired by the PDMA Body of Knowledge (7 domains), used as an omission checklist only — not an official PDMA artifact.

## Install

Clone directly into your Kimi Code skills directory:

```bash
mkdir -p ~/.kimi-code/skills
git clone https://github.com/weniix168-tech/product-research.git ~/.kimi-code/skills/product-research
```

## Usage

Manual invocation:

```
/skill:product-research 你的调研主题
```

The skill also triggers automatically when the conversation involves market research, competitor analysis, or product/initiation decisions. Quick tasks may answer with just the one-page brief; complex ones use the full report and registers.
