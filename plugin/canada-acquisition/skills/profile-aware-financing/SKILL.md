---
name: profile-aware-financing
description: Build a Canada-specific financing plan that reflects the buyer profile, deal size, and current targeted programs. Use when the user needs a financing stack tailored to their buyer profile, province, and deal size.
---

# Canada Profile-Aware Financing

Build a realistic Canadian financing stack for an acquisition while separating true purchase-price capital from indirect support programs.

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

- The buyer profile in sourcing-capital → "Step 1: Build the buyer profile" (province and city, age, citizenship, optional self-identified groups, cash, credit, experience)
- Deal facts: price, SDE or EBITDA, asset or share, equipment and real estate included
- Lenders or programs you've already approached, and what they said
- How much personal risk you'll take, such as a personal guarantee or pledging home equity

## Load these skills first

- `sourcing-capital`
- `structuring-deals`
- `building-deal-teams`

## Workflow

1. Build the buyer profile using sourcing-capital → "Step 1: Build the buyer profile". Ask only for fields the user hasn't given, and keep identity questions optional. Never assume a profile.
2. Identify which financing sources are truly available for the purchase price.
3. Filter sourcing-capital → reference.md → Program Matrix to the programs this buyer qualifies for. Note which ones can fund buying a business, and don't over-rely on them.
4. Design 2 to 3 capital stacks ranked by closability.
5. Separate direct acquisition capital from indirect grants, advisory support, and post-close programs.
6. Provide a lender and program outreach order.

## Output

Provide:

- Buyer profile used, and which programs it qualifies for or rules out
- Recommended capital stack
- Direct financing sources
- Indirect support programs
- DSCR view
- Outreach order
- Key eligibility caveats
- Required documents for the first lender calls
