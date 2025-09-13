# GenBI Governance Harness

An open framework for testing AI in Business Intelligence (BI) under enterprise governance rules. Built on a synthetic Fortune 500 retail dataset (\~\$6B annual revenue) with a 50-case test harness.

## Features

* Synthetic retail BI dataset: sales, payroll, digital orders, shrink
* 50-case test harness for evaluating Copilot, Fabric Data Agent, or other AI BI tools
* Governance checklist: fiscal calendar, payroll rules, metric definitions
* Scoring rubric: Correct / Partial / Incorrect

## Quick Start

1. Clone the repo:
   git clone [https://github.com/](https://github.com/)<your-handle>/genbi-governance-harness
2. Load the dataset from `/data` into your BI tool (Power BI, Microsoft Fabric, dbt, or SQL engine).
3. Run the prompts listed in `/evaluation/prompts.md`.
4. Score outputs using `/evaluation/scoring.md`.
5. Review governance alignment with `/docs/governance_checklist.md`.

## Governance Rules (Highlights)

* Always use fiscal weeks (Mon–Sun), never calendar weeks
* No daily payroll reporting
* Consistent metric definitions across all prompts
* Narratives must include sales, payroll, and gross margin drivers
* Enforce one version of truth by tying outputs to the semantic model

## Citation

If you use this work, please cite:
Ghosh, R. (2025). *GenBI Governance Harness: An Open Framework for AI in BI Testing.* Zenodo. DOI: \[to be added]

Once the repository is connected to Zenodo, a DOI badge will appear here.

## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Keywords

AI-in-BI, Governance, Microsoft Fabric, Power BI, Semantic Models, Generative AI, Business Intelligence

---

✅ You can paste this straight into your **README.md** — no broken YAML/Markdown formatting issues.

Do you also want me to prepare the **governance\_checklist.md** in the same copy-paste friendly style?
