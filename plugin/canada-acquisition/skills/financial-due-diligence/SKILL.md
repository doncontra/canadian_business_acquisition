---
name: financial-due-diligence
description: Performs deep financial analysis of a Canadian acquisition target including EBITDA normalization, revenue quality assessment, CRA document review, and cash flow validation. Use when the user has received financial statements and wants to understand the true earnings and risks of a Canadian business.
---

# Financial Due Diligence

Produces a normalized EBITDA, revenue quality assessment, and financial risk summary for a Canadian acquisition target. See [reference.md](reference.md) for document checklists, add-back categories, and Canadian tax considerations.

## Before you start: ask, then tailor

Good answers depend on who the buyer is and what the deal looks like. Don't research or draft until you have the facts below.

1. Use what the user has already said in this conversation, including answers given to another skill. Never ask for it again.
2. Ask for what's missing in one message: no more than 6 questions, numbered, most important first. Give example answers so each is quick to reply to. Use an ask-question tool if one is available.
3. Only ask what would change the answer. Skip anything with a sensible default.
4. If the user has already given everything, skip the questions and start.
5. If the user says to go ahead without answering, proceed and list your assumptions at the top of the output.
6. Start the output with a one-line recap of the facts you're working from, so the user can correct them.

Ask about:

- Which documents you have: financial statements, T2 returns, bank statements, GST/HST filings, payroll (and for which years)
- The seller's claimed SDE or EBITDA and their list of add-backs
- Industry, province, and asset or share purchase
- Anything that already looks off to you

## Workflow

- [ ] Confirm all primary documents are received (see reference.md → Documents to Request)
- [ ] Normalize EBITDA: start from T2 net income, apply add-backs
- [ ] Assess revenue quality: recurring vs. project-based, concentration risk
- [ ] Plot 3-year trends: revenue, gross margin, EBITDA margin
- [ ] Analyze working capital (current assets minus current liabilities)
- [ ] Estimate maintenance capex and calculate true free cash flow
- [ ] Flag any CRA issues (liens, unpaid remittances, HST/GST gaps)
- [ ] Produce confidence rating (High / Medium / Low) and risk summary

## EBITDA Normalization Formula

```
Net Income (from T2 Corporate Return)
+ Interest Expense
+ Taxes paid
+ Depreciation & Amortization
+ Owner salary above fair replacement market rate
+ Personal expenses run through business (vehicle, travel, family payroll)
+ One-time non-recurring expenses
- One-time non-recurring income
= Normalized EBITDA
```

## Free Cash Flow

```
Free Cash Flow = EBITDA - Maintenance Capex - Taxes - Annual Debt Service
```

This is the number that actually pays the deal. DSCR must be ≥ 1.25x for Canadian lenders.

## Output

Normalized EBITDA (3-year table), revenue quality rating, trend analysis, working capital snapshot, FCF, top 3–5 financial risks, confidence rating, recommended purchase price range.
