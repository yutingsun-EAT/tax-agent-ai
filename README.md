# Tax Agent AI — PM Design Exercise

An end-to-end **Product Management design exercise**: how an AI agent keeps a third-party tax platform and an internal billing system in sync, and resolves sales-tax classification gaps.

## Live prototype
▶️ **Open the interactive prototype:** [tax-agent-ai demo](https://yutingsun-eat.github.io/tax-agent-ai/)

## What's here
- **`index.html`** — self-contained interactive prototype (three use cases: new-SKU classification, discrepancy debug, and regulation-change alert)
- **`ONEPAGER.md`** — the design one-pager (problem, assumptions, users, use cases, solutions, prototype rationale)

## The three use cases in the prototype
1. **New SKU → tax category classification** — when a new SKU is created in the catalog, the agent proactively assigns the correct tax category instead of leaving it blank/defaulting to exempt. *(prevention path)*
2. **Discrepancy debug** — why does billing vs. tax platform show a $29,860 gap for Q3?
3. **Rule-change alert** — a sales-tax rate change (8.9% → 9.6%) with an old-vs-new tax comparison.

Each use case has a corresponding left-sidebar menu (Discrepancies, Rule Updates, SKU Taxonomy) in the prototype.

> Built as a think-aloud, clickable artifact for a PM design take-home.
