---
name: sourcing-deals
description: Generates Canadian business acquisition deal flow through on-market and off-market channels, and scans live Canadian listing sites for businesses that match a buy box. Use when the user asks how to find deals, source businesses, build a pipeline, find off-market opportunities, or see what is currently listed for sale in a Canadian city or province.
---

# Sourcing Deals

Helps build a consistent pipeline of Canadian acquisition targets. See [reference.md](reference.md) for listing sites by province and niche, channel lists, outreach scripts, and province-specific notes.

## Before you start: ask, then tailor

Good answers depend on who the buyer is and what the deal looks like. Don't research or draft until you have the facts below.

1. Use what the user has already said in this conversation, including answers given to another skill. Never ask for it again.
2. Ask for what's missing in one message: no more than 6 questions, numbered, most important first. Give example answers so each is quick to reply to. Use an ask-question tool if one is available.
3. Only ask what would change the answer. Skip anything with a sensible default.
4. If the user has already given everything, skip the questions and start.
5. If the user says to go ahead without answering, proceed and list your assumptions at the top of the output.
6. Start the output with a one-line recap of the facts you're working from, so the user can correct them.

Ask about:

- Scan what's listed now, or build a repeatable pipeline?
- Buy box: province and city, industry, price or SDE range
- Exclusions, such as licensed trades, franchises, or restaurants
- Hours per week you can spend on sourcing
- Existing network: CPAs, bankers, lawyers, or industry contacts

## Two modes

- **Scan live listings**: the user wants to see what is for sale now ("find what's listed", "what's for sale in Calgary"). Needs web search or fetch.
- **Build a pipeline**: the user wants a repeatable way to find deals. Produce the 30-day plan.

## Workflow: scan live listings

- [ ] Confirm buy box (province, city, industry, max asking price, any exclusions such as licensed trades)
- [ ] Pick sources from reference.md → On-Market: national sites, then the province's local brokers, then any niche sites that match the industry
- [ ] Search each source, filtering by province, city, and category where the site allows it
- [ ] For each listing, record: title, link, asking price, revenue, SDE or EBITDA, and whether each figure is published
- [ ] Drop listings marked Sold, Sold STC, Sold Conditionally, or Pending, and flag listings with no cash flow figure as "can't screen"
- [ ] Remove duplicates: the same business often appears on a broker site, BusinessesForSale, and BizBuySell
- [ ] Say which sources were scanned, how many pages, and which could not be read (login walls, JS-only pages)
- [ ] Hand the list to `deal-screen` for scoring

## Workflow: build a pipeline

- [ ] Confirm buy box (industry, province, EBITDA range)
- [ ] Identify on-market sources to monitor (see reference.md → On-Market)
- [ ] Build off-market referral network: CPAs, lawyers, wealth managers, bankers
- [ ] Draft outreach messages for each referral type
- [ ] Set weekly cadence: review listings + 10–15 new off-market contacts

## Key principles

**Off-market > on-market.** Pocket listings from brokers and professional referrals have less competition and more motivated sellers.

**Listing figures are seller claims.** Report them as listed. Never fill a missing revenue or SDE figure with an estimate.

**Referral sources** (all have financial incentive to help deals close): CPAs, M&A attorneys, wealth managers, commercial bankers at RBC/TD/Scotiabank, BDC advisors, exit planning advisors (CEPA-certified).

**Target seller profile**: Owner aged 55–75, business 10+ years old, no succession plan, $500K–$10M revenue.

## Output

- **Scan mode:** sources scanned, a table of matching listings with links and published figures, excluded listings with the reason, and the hand-off to `deal-screen`.
- **Pipeline mode:** 30-day sourcing plan, recommended on-market channels, off-market referral targets, outreach examples, and weekly pipeline cadence.
