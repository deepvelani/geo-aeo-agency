# Operations SOPs: Delivering GEO Client Work

## Client onboarding checklist

- [ ] Access: GA4 (viewer), Google Business Profile (manager), Search Console,
      website CMS/admin, Bing Places + Yelp + Apple logins (or owner adds you).
- [ ] Baseline prompt panel: 25 prompts × 3 engines × 3 runs. Record mentions,
      cited URLs, competitors, sentiment. Date-stamp everything.
- [ ] Crawl-access audit: robots.txt vs OAI-SearchBot, PerplexityBot,
      Claude-SearchBot, Googlebot, Bingbot; note blocks. Check server response
      < 2s on key pages.
- [ ] GBP + listings audit: category accuracy, NAP consistency across
      site/GBP/Bing/Yelp/Apple, photo count/recency, review count + velocity +
      reply rate.
- [ ] Content audit: top 10 pages — answer-first structure? stats/quotes?
      schema present? one page per service?
- [ ] Competitor gap: who appears in AI answers where the client doesn't, and
      which third-party sources feed those answers (your PR hit list).
- [ ] Kickoff call: walk through baseline, agree on the 3 engines and the
      prompt set (client signs off — prevents "why aren't we tracking X"
      later).

## Monthly delivery workflow

**Week 1 — Measure.** Re-run prompt panel (same prompts, 3 runs each). Pull
GA4 AI-referrer segment. Update the SoM trend sheet.

**Week 2 — Fix.** Work the prioritized list: GBP posts + photo adds, review
asks going out, NAP fixes, schema additions, content restructures.

**Week 3 — Build.** 1–2 new/rewritten answer-first pages (service pages, FAQs,
comparison pages) per the content playbook in `02-tactics/content-and-citations.md`.

**Week 4 — Authority.** (Citation Engine tier) Digital PR outreach: 5–10
pitches to publications/roundups the engines cite; community participation
(Reddit/Quora — genuine, useful answers only); listicle inclusion outreach.

**Month-end — Report.** One-pager (template below). 30-min call. Next month's
priorities agreed in writing.

## Reporting template (one page)

1. **Visibility trend:** SoM by engine, 3-month line. Up/down/flat, no spin.
2. **Wins:** prompts newly won, with dates.
3. **Gaps:** top 5 prompts still lost + who wins them + which sources feed
   those answers.
4. **What we did:** bullets, linked to the fix list.
5. **Next month:** top 3 priorities.
6. **Traffic:** AI-referred sessions (GA4), branded-search trend.

## Tools stack (solo founder)

| Job | Tool | Cost |
|---|---|---|
| AI visibility tracking | Otterly.AI → Peec AI at 2+ clients | $29 → $95/mo |
| Prompt panel + notes | Spreadsheet (prompt, engine, run 1–3, mention?, URLs, sentiment) | $0 |
| GA4 AI-referrer segment | Built-in | $0 |
| Crawl checks | Screaming Frog (free ≤500 URLs) / manual | $0 |
| Schema | Manual JSON-LD + validator.schema.org | $0 |
| Reporting | Docs/Slides template | $0 |
| **Total** | | **~$30–100/mo** |

## What to outsource vs do yourself

- **Do yourself:** prompt panels, audits, GBP work, client calls, reporting —
  this is the judgment clients pay for.
- **Outsource early:** content writing (brief it tightly; you edit for
  answer-first structure), NAP cleanup across directories (VA-friendly),
  review-reply drafting (you approve — review replies are public and
  permanent).
- **Outsource at Citation Engine tier:** digital PR outreach (freelancer with
  media list), keeping your time on strategy and measurement.

## Quality rules (non-negotiable)

- Never guarantee placement — no paid slot exists in ChatGPT local answers.
- Never fake reviews or plant inauthentic mentions — Google's spam policy
  covers AI results too (May 2026 guide).
- Date-stamp every baseline; report trends, not snapshots; disclose
  run-to-run volatility to the client before they discover it.
