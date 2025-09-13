# GenBI Governance Harness

An open framework for testing AI in Business Intelligence (BI) under enterprise governance rules.  
Built on a synthetic Fortune 500 retail dataset (~$6B annual revenue) with a 50-case test harness.

## Features
- Synthetic retail BI dataset: sales, payroll, digital orders, shrink
- 50-case test harness for evaluating Copilot, Fabric Data Agent, or other AI BI tools
- Governance checklist: fiscal calendar, payroll rules, metric definitions
- Scoring rubric: Correct / Partial / Incorrect

## Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/rghosh25/genbi-governance-harness
2. Load /data into your BI tool (Power BI, Fabric, dbt, or SQL engine).

3. Run the prompts listed in /evaluation/prompts.md.

4. Score results against /evaluation/scoring.md.
