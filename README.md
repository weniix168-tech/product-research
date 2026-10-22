# product-research

A [Kimi Code](https://www.kimi.com/code/docs/en/) **User Skill** for systematic market & product research and R&D decision support.

It turns a rough topic into a verified, decision-ready research report, covering:

- **Strategy layer** — company-level thinking (trends, opportunities, business/product/technology portfolio, product & technology roadmaps) and product-level thinking (why build it, customer problems & value, strategic fit, commercial worth), aligned to the planning chain: company strategy → roadmap → portfolio management → product planning → project initiation
- **Verified data collection** — 11 categories: trends, market, customer needs, technology, competitor specs, competitor tech stacks, patents, suppliers, team structure, plan & timeline, finance — every data point cross-checked with cited sources and dates
- **Analysis** — value proposition design, build-vs-outsource-vs-resell comparison, and profitability analysis driven by an explicit financial model (assumptions → budget → ROI → payback)

## Install

Clone directly into your Kimi Code skills directory:

```bash
# Kimi-specific skills
git clone https://github.com/<your-name>/product-research.git ~/.kimi-code/skills/product-research

# or the generic cross-tool directory
git clone https://github.com/<your-name>/product-research.git ~/.agents/skills/product-research
```

## Usage

Manual invocation:

```
/skill:product-research 你的调研主题
```

The skill also triggers automatically when the conversation involves market research, competitor analysis, or product/initiation decisions.

## Output

A structured Chinese-language report (see `templates/report-template.md`) with an executive summary, strategy analysis, market & competitor insights, value proposition, plan comparison, team structure, financial model, risks, and a clear go/no-go recommendation — every claim tagged with source, date, and confidence level.
