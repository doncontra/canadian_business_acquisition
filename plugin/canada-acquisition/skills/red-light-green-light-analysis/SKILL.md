---
name: red-light-green-light-analysis
description: Runs a Canada-specific one-sheet red light green light analysis of an acquisition target by combining financial quality, seller motivation, structure viability, and transfer-of-value checks. Use when the user wants a full go or no-go decision before making an LOI or committing serious diligence time.
---

# Red Light Green Light Analysis

Produces a fast integrated decision on whether a Canadian deal should move forward, be reworked, or be dropped. See [reference.md](reference.md) for the one-sheet scoring model, fatal red flags, and standard output format.

## Before you start: ask, then tailor

Good answers depend on who the buyer is and what the deal looks like. Don't research or draft until you have the facts below.

1. Use what the user has already said in this conversation, including answers given to another skill. Never ask for it again.
2. Ask for what's missing in one message: no more than 6 questions, numbered, most important first. Give example answers so each is quick to reply to. Use an ask-question tool if one is available.
3. Only ask what would change the answer. Skip anything with a sensible default.
4. If the user has already given everything, skip the questions and start.
5. If the user says to go ahead without answering, proceed and list your assumptions at the top of the output.
6. Start the output with a one-line recap of the facts you're working from, so the user can correct them.

Ask about:

- The deal materials or key figures
- Your buy box and how much you can finance
- What you've done so far: vetting, seller calls, documents received
- When you need to decide

## Workflow

- [ ] Confirm deal basics: industry, province, revenue, normalized EBITDA, asking price
- [ ] Test valuation against market range and seller motivation
- [ ] Check debt service coverage under realistic Canadian financing assumptions
- [ ] Review working capital and obvious balance-sheet risks
- [ ] Score transfer of value: customer, employee, structural, social
- [ ] Score seller psychology: motivation, urgency, distress
- [ ] Flag legal and tax issues: CRA arrears, payroll remittances, lease problems, licence transfer issues
- [ ] Return Red, Yellow, or Green with reasons and next move

## Decision bands

| Score    | Outcome                                                  |
| -------- | -------------------------------------------------------- |
| 75-100   | Green: proceed to LOI or diligence                       |
| 55-74    | Yellow: proceed only if weak areas are fixed             |
| Below 55 | Red: pass, or pursue only as a highly creative structure |

## Minimum thresholds

- DSCR of at least 1.25x for most Canadian lender-backed structures
- Preferred DSCR of 1.5x or higher
- No unresolved CRA liens or payroll remittance issues
- No fatal owner-dependence without a transition plan
- No single-customer concentration that makes the deal fragile

## Typical Red flags

- Seller wants full cash at an inflated multiple
- Revenue or margin deterioration with no credible explanation
- Weak books and no reliable add-back support
- Lease, licence, or landlord consent risk that threatens closing
- Seller is the only rainmaker, estimator, or licensed operator

## Output

Return a one-page style summary with score, RAG decision, strengths, risks, financing view, structure recommendation, and the exact next step.
