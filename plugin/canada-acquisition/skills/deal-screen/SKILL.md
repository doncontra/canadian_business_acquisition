---
name: deal-screen
description: Run a Canada-specific first-pass screen on a business acquisition target and decide whether it is a red, yellow, or green deal. Use when the user shares a listing, CIM, broker teaser, or one-sheet and asks whether the deal is worth pursuing.
---

# Canada Deal Screen

Review a Canadian acquisition opportunity before the user spends serious time or money on it.

## Before you start: ask, then tailor

Good answers depend on who the buyer is and what the deal looks like. Don't research or draft until you have the facts below.

1. Use what the user has already said in this conversation, including answers given to another skill. Never ask for it again.
2. Ask for what's missing in one message: no more than 6 questions, numbered, most important first. Give example answers so each is quick to reply to. Use an ask-question tool if one is available.
3. Only ask what would change the answer. Skip anything with a sensible default.
4. If the user has already given everything, skip the questions and start.
5. If the user says to go ahead without answering, proceed and list your assumptions at the top of the output.
6. Start the output with a one-line recap of the facts you're working from, so the user can correct them.

This workflow loads several skills. Ask one combined set of questions for the whole workflow; the loaded skills should not ask again.

Ask about:

- The listing, CIM, teaser, or key figures (paste or link)
- Your buy box: province, industry, maximum price
- Cash available for a down payment, and how you plan to finance
- Owner-operator or owner-investor, and your experience in this industry
- Your deal-breakers
- Where you are with it: just found it, talked to the broker, or under NDA

## Load these skills first

- `vetting-deals`
- `transfer-of-value-analysis`
- `red-light-green-light-analysis`

## Workflow

1. Ask for the listing, broker summary, one-sheet, or basic financial details.
2. Run a first-pass vet.
3. Evaluate transfer of value.
4. Produce a red, yellow, or green decision with the reasons.
5. If the deal is yellow, specify exactly what must be clarified before moving forward.

## Output

Provide:

- Deal summary
- Key strengths
- Key risks
- Transfer-of-value view
- RAG decision and score
- Next step this week
