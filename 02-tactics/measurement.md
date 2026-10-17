# Measuring AI-Search Visibility

Keywords rank; prompts get answered. Measurement in this field is
prompt-based, and it is noisier than SEO — budget for that.

## The core metrics

- **Share of Model (SoM)** / **share of voice**: % of tracked AI answers that
  mention or cite your brand. Practitioners report 10–20% SoM improvement in
  2–3 months, 30–40% by months 4–6 after focused optimization
  **[vendor claim — prominara.com](https://prominara.com/blog/geo-guide-content-format-effects-on-ai-citations)**.
- **Citation rate**: % of prompts where your URLs appear in citations, by
  engine. Track per engine — the patterns differ.
- **Mention sentiment**: positive / neutral / negative framing of your brand
  in answers (some tools report this).
- **AI-referred sessions**: filter GA4 by AI referrers. A commonly shared
  regex covers chatgpt.com, claude.ai, perplexity.ai, gemini.google.com,
  copilot.microsoft.com, grok.com, and others — see the dev.to GEO guide for
  a copy-paste version
  ([dev.to](https://dev.to/techmitten2/the-ultimate-guide-to-generative-engine-optimization-geo-seo-for-the-ai-era-550f)).
  AI referrals convert well (pre-qualified intent) but remain ~1% of web
  traffic **[independent-ish estimate, growing fast]**.
- **Branded search + direct traffic correlation**: agencies report branded
  search volume rising as AI mentions grow (e.g., +156% in one BVM case —
  **[vendor claim]**).

## Tools (prices checked by third parties, Sept 2026 — confirm before buying)

| Tool | Entry price | Engines at entry | Notes |
|---|---|---|---|
| Otterly.AI | $29/mo | ChatGPT, AIO, Perplexity, Copilot | Cheapest real entry; 15/100/400 prompts; free trial; built-in GEO audit |
| Peec AI | $95/mo (~€89) | Any 3 of 6 | Agency favorite; unlimited users; white-label reporting on higher tiers |
| SE Ranking (SE Visible) | $99/mo ($79 annual) | 5 engines | Most prompts under $100 (200 prompts) |
| Profound | $99/mo (ChatGPT only, yearly) / $399 Growth | Up to 9 at enterprise | Highest ceiling; crawler analytics via CDN integrations |
| Semrush AI Toolkit | $99/mo/domain add-on | ChatGPT, Gemini, Perplexity, AIO | 130M+ prompt DB; sentiment focus |
| Ahrefs Brand Radar | ~$199/mo add-on + Ahrefs plan | AI Overviews, AI Mode, ChatGPT+ | Best if already in Ahrefs |
| CueScout | $49/mo | ChatGPT, Perplexity, AIO | 20 prompts daily |
| Scrunch | $250/mo | ChatGPT, Perplexity, AIO, Copilot | AI-crawler analytics |
| AthenaHQ | Free (300 credits) → $295/mo | 7 incl. Claude | Source/URL intelligence; built by ex-Google/DeepMind |
| Rankscale | $20/mo | ChatGPT, Gemini, Perplexity, Claude, Grok, DeepSeek... | Unusual engine coverage; credit-based |

Sources: [growthner.com](https://growthner.com/blog/ai-search-visibility-tools-to-track-your-brand-mentions-in-llms/),
[madx.digital](https://www.madx.digital/learn/ai-visibility-tools),
[cuescout.com](https://cuescout.com/blog/best-ai-search-visibility-tools).
**Solo-founder pick: Otterly.AI ($29/mo) to start, Peec AI ($95/mo) once you
have 2+ clients** — both are agency-workable and don't require procurement.

## Manual prompt-testing methodology (free, and do this anyway)

Tools run synthetic prompts; your buyers ask real ones. Run both.

1. Build a prompt panel: 15–50 questions your buyers actually ask, split into
   **navigational** ("is [brand] good?"), **comparative** ("[brand] vs
   [competitor]"), and **category** ("best [service] in [city]").
2. Run each prompt on ChatGPT, Perplexity, and Gemini (free tiers work), in a
   private/incognito window, **3 runs per prompt** — run-to-run citation
   overlap is only 49–67%, so single runs are noise
   ([attrifast](https://attrifast.com/blog/ai-search-citations-by-vertical-2026)).
3. Log per run: brand mentioned? (Y/N), cited URLs, competitors named,
   sentiment, which third-party sources were cited.
4. Repeat monthly. Report trends, not snapshots.

## Reporting framework for clients

Monthly one-pager: SoM by engine (trend line), top prompts where you appear /
don't, competitor gap (who appears where you don't), cited-source breakdown
(which third-party sites feed your answers — that's your PR hit list), and
AI-referred sessions from GA4. Keep it to one page; the agency case-study
template in `03-agency/outreach-and-sales.md` shows the baseline→actions→results
structure clients actually read.

## Honest limitations

- Synthetic prompts ≠ real user queries; treat vendor "visibility scores"
  with skepticism ([typescape.ai](https://typescape.ai/blog/what-is-geo)).
- Attribution is partial: a cited answer often produces zero clicks (the user
  got the answer). Value shows up in branded search and direct traffic, not
  just referral sessions.
- Expect volatility: re-baseline quarterly, report directionally.
