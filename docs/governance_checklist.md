# Governance Checklist

This checklist defines the enterprise governance rules applied in the GenBI Governance Harness.  
All prompts, metrics, and narratives are evaluated against these rules to ensure consistency and trust.

---

## 1. Fiscal Calendar
- Always use **fiscal weeks (Mon–Sun)**.
- No use of calendar weeks or months.
- Year-to-date (YTD), week-to-date (WTD), and last-year (LY) comparisons must align with the fiscal calendar.

---

## 2. Payroll
- Payroll reporting is **weekly only**.
- No daily payroll values should ever appear.
- Payroll-to-sales ratios must use defined numerators (payroll $) and denominators (sales $).

---

## 3. Metrics
- Consistent definitions across all prompts.
- Ratios must follow enterprise rules:
  - Payroll-to-Sales % = Payroll $ ÷ Sales $.
  - Gross Margin % = Gross Margin $ ÷ Sales $.
- Variance and YoY % must be calculated as:
  - Variance = TY – LY.
  - YoY % = (TY – LY) ÷ LY.

---

## 4. Narratives
- Narratives must include **sales, payroll, and gross margin drivers**.
- Explanations must reference correct fiscal periods.
- Narratives should highlight performance vs LY, Budget, and Comp/Non-Comp stores where relevant.

---

## 5. One Version of Truth
- All outputs must tie back to the governed semantic model.
- Naming conventions must be followed consistently.
- No invented fields, dimensions, or ungoverned calculations.

---

## 6. Fulfillment Methods
- Codes must be preserved exactly as stored:
  - IFC, ISP/CSP, LHD, MPD, POS, TWD.
- No expansion into full forms unless explicitly requested.

---

This governance checklist ensures AI outputs align with enterprise reporting standards and can be trusted in executive decision support.
