---
name: valuing-businesses
description: Calculates the fair market value of a Canadian acquisition target using EBITDA multiples, four-pillar analysis, and seller motivation adjustments. Use when the user wants to know what a business is worth, what multiple to apply, or whether the asking price is fair.
---

# Valuing Businesses

Produces a defensible valuation range and recommended opening offer for a Canadian business. See [reference.md](reference.md) for the multiple table, pillar scoring, and share vs. asset sale impact.

## Before you start: ask, then tailor

Good answers depend on who the buyer is and what the deal looks like. Don't research or draft until you have the facts below.

1. Use what the user has already said in this conversation, including answers given to another skill. Never ask for it again.
2. Ask for what's missing in one message: no more than 6 questions, numbered, most important first. Give example answers so each is quick to reply to. Use an ask-question tool if one is available.
3. Only ask what would change the answer. Skip anything with a sensible default.
4. If the user has already given everything, skip the questions and start.
5. If the user says to go ahead without answering, proceed and list your assumptions at the top of the output.
6. Start the output with a one-line recap of the facts you're working from, so the user can correct them.

Ask about:

- Revenue and SDE or EBITDA for the last 3 years, and the asking price
- Industry and province
- Asset or share purchase, and what's included (real estate, equipment, inventory)
- What you know about the seller's motivation
- Purpose: make an offer, or sanity-check the asking price

## Workflow

- [ ] Confirm normalized EBITDA (from financial-due-diligence skill or provided)
- [ ] Identify base multiple range from EBITDA size (see reference.md → Multiple Table)
- [ ] Apply Pillar 2 quality adjustments (+/- 0.25x per factor)
- [ ] Apply Pillar 3 growth/market position adjustments
- [ ] Apply Pillar 4 seller motivation discount (high motivation = lower multiple)
- [ ] Calculate floor / target / ceiling valuation
- [ ] Recommend opening offer and deal structure
- [ ] Advise on share sale vs. asset sale for Canadian tax optimization

## The Four Pillars

**Pillar 1 — Financial Performance**: Size of EBITDA determines base multiple range.
**Pillar 2 — Business Quality**: Recurring revenue, owner-independence, barriers to entry, customer diversification push multiple up or down.
**Pillar 3 — Growth & Market**: Industry tailwinds, untapped levers, backlog.
**Pillar 4 — Seller Motivation**: High motivation unlocks creative structure and below-market multiples. This is the most underestimated pillar.

## Key insight

**Deal structure changes the effective multiple.** An annuity deal at 5x over 10 years can be cheaper in real terms than a bank deal at 3x all-cash — because the seller nets more after Canadian deferred tax treatment, and you pay from cash flow with no capital out of pocket.

## Output

Normalized EBITDA, base multiple range, pillar adjustments, final multiple range, valuation range (floor/target/ceiling in CAD), recommended offer, share vs. asset sale recommendation.
