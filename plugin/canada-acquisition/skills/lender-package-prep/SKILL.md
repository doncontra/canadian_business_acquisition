---
name: lender-package-prep
description: Prepare a Canadian acquisition lender package by organizing the deal story, DSCR logic, document checklist, and lender-facing summary for BDC, banks, credit unions, and profile-relevant Canadian programs. Use when the user is preparing to approach BDC, a bank, or a credit union and needs a lender-ready package, DSCR story, or document checklist.
---

# Canada Lender Package Prep

Help the user prepare a lender-ready package for a Canadian acquisition while separating direct acquisition debt from indirect grants and support programs.

## Before you start: ask, then tailor

Good answers depend on who the buyer is and what the deal looks like. Don't research or draft until you have the facts below.

1. Use what the user has already said in this conversation, including answers given to another skill. Never ask for it again.
2. Ask for what's missing in one message: no more than 6 questions, numbered, most important first. Give example answers so each is quick to reply to. Use an ask-question tool if one is available.
3. Only ask what would change the answer. Skip anything with a sensible default.
4. If the user has already given everything, skip the questions and start.
5. If the user says to go ahead without answering, proceed and list your assumptions at the top of the output.
6. Start the output with a one-line recap of the facts you're working from, so the user can correct them.

This workflow loads several skills. Ask one combined set of questions for the whole workflow; the loaded skills should not ask again.

Identity questions (age, self-identified groups) are optional. Say they are only used to find programs the buyer qualifies for.

Ask about:

- Deal facts: business, province, purchase price, normalized EBITDA, asset or share
- Which lenders you've talked to, and where each stands
- Documents you already have from the seller and for yourself
- Your cash for the down payment, credit score range, and industry or management experience
- Optional profile details for program eligibility (see sourcing-capital → Step 1)
- Deadline: financing condition date or target close

## Load these skills first

- `sourcing-capital`
- `financial-due-diligence`
- `structuring-deals`
- `building-deal-teams`

## Workflow

1. Confirm the target business, province, normalized EBITDA, purchase price, and proposed structure.
2. Identify the most likely lender path: BDC, chartered bank, credit union, a profile-based program the buyer qualifies for, or a blended structure.
3. Separate direct acquisition capital from indirect support programs so the package does not overstate committed funds.
4. Build the lender story: why this business, why this buyer, why this structure works.
5. List the exact missing borrower, business, and deal documents.
6. Summarize DSCR and capital stack logic in lender language.
7. Flag weaknesses the lender will focus on and suggest how to address them before submission.

## Profile-Aware Rule

Using the buyer profile (sourcing-capital → "Step 1: Build the buyer profile"), test and note:

- which profile-based programs the buyer qualifies for (Futurpreneur, BELF, AWE, WELF, Indigenous financial institutions, Community Futures, and others in sourcing-capital → reference.md → Program Matrix), and whether each can fund buying a business
- whether any of them improves the lender story as companion capital
- which ones help only as mentorship or post-close support rather than core acquisition debt

## Output

Provide:

- lender path recommendation
- direct financing sources versus indirect supports
- lender-facing deal summary
- DSCR and capital stack summary
- missing-document checklist
- top lender objections and responses
- next actions before submission
