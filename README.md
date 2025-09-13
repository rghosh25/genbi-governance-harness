# GenBI Governance Harness

[![DOI](https://zenodo.org/badge/1056216982.svg)](https://doi.org/10.5281/zenodo.17114449)

An open framework for testing AI in Business Intelligence (BI) under enterprise governance rules. Built on a synthetic Fortune 500 retail dataset (~$6B annual revenue) with a 50-case test harness.

## Features
- Synthetic retail BI dataset: sales, payroll, digital orders, shrink
- 50-case test harness for evaluating Copilot, Fabric Data Agent, or other AI BI tools
- Governance checklist: fiscal calendar, payroll rules, metric definitions
- Scoring rubric: Correct / Partial / Incorrect
- Lightweight semantic model export for Power BI / Fabric

## Repository Structure
- [Data](./data) → synthetic dataset (CSV files)
- [Evaluation](./evaluation) → prompts (50 test cases) + scoring rubric
- [Governance Docs](./docs) → governance checklist (fiscal rules, metrics, narratives)
- [Power BI Assets](./powerbi) → semantic model JSON + placeholder assets

## Quick Start
1. Clone the repo:
   git clone https://github.com/<your-handle>/genbi-governance-harness
2. Load the dataset from `/data` into your BI tool (Power BI, Microsoft Fabric, dbt, or SQL engine).
3. Run the prompts listed in `/evaluation/prompts.md`.
4. Score outputs using `/evaluation/scoring.md`.
5. Review governance alignment with `/docs/governance_checklist.md`.

## Governance Rules (Highlights)
- Always use fiscal weeks (Mon–Sun), never calendar weeks
- No daily payroll reporting
- Consistent metric definitions across all prompts
- Narratives must include sales, payroll, and gross margin drivers
- Enforce one version of truth by tying outputs to the semantic model
- Fulfillment methods must remain as stored codes (IFC, ISP/CSP, LHD, MPD, POS, TWD)

## Citation
If you use this work, please cite:
Ghosh, R. (2025). GenBI Governance Harness: An Open Framework for AI in BI Testing. Zenodo. https://doi.org/10.5281/zenodo.17114449

## License
This project is licensed under the MIT License – see the LICENSE file for details.

## 🔑 Keywords
AI-in-BI • Governance • Microsoft Fabric • Power BI • Semantic Models • Generative AI • Business Intelligence
