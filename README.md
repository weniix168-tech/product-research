# product-research

A [Kimi Code](https://www.kimi.com/code/docs/en/) **User Skill** for systematic market & product research and R&D decision support.

It turns a rough topic into a verified, decision-ready research report, covering:

- **Strategy layer** — company-level thinking (trends, opportunities, business/product/technology portfolio, product & technology roadmaps) and product-level thinking (why build it, customer problems & value, strategic fit, commercial worth), aligned to the planning chain: company strategy → roadmap → portfolio management → product planning → project initiation
- **Verified data collection** — 12 categories: trends, market, customer needs, regulations & compliance (NMPA / FDA / CE-MDR pathways and applicable standards such as GB 9706 / IEC 60601 family, with version verification), technology, competitor specs, competitor tech stacks, patents (broken down by type — invention / utility model / design — by legal status — granted / pending — and by jurisdiction — CN / US / EU / PCT / single-country / patent families), suppliers, team structure with recruiting keywords for each role, plan & timeline, finance — gathered across multi-channel public sources (frontier literature incl. new technologies and animal/clinical studies, patent filings, official registries & websites, industry media & WeChat accounts, IPO filings / annual reports) — every data point cross-checked with cited sources and dates
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
