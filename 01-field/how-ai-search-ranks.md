# How AI Search Actually Ranks (Retrieves, Trusts, Cites)

Most AI answers are built by a retrieve-then-compose pipeline, not by raw
model knowledge:

1. **Interpret** the question and break it into sub-queries (Google calls this
   "query fan-out" — confirmed in its May 2026 guide).
2. **Retrieve** candidate sources — live web search, an index, and/or training
   data. This is the step most sites fail silently.
3. **Judge** which sources answer the question clearly and credibly.
4. **Compose** one answer with citations to the sources used.

Different engines run different pipelines. The practical result: **there is no
single "AI SEO" — each engine has its own citation pattern.**

## Per-engine citation patterns [independent / third-party studies]

- **ChatGPT** — most Wikipedia-heavy (Wikipedia is 26–48% of its top-10 citation
  share; [5WPR Index](https://completeaitraining.com/news/5wpr-index-finds-reddit-accounts-for-40-of-ai-citations/)).
  Also the most industry-variable: citations from brand-owned websites range
  from 28.2% (Food & Beverage) to 43.7% (Organizations) ([Yext Research, Q4 2025](https://www.yext.com/blog/chatgpt-make-your-brand-visible-ai-search)).
  Distinctive habit: institutional sources — 11.9% of citations go to government,
  health, and EU domains ([Agenzy 2026](https://www.agenzy.lt/blog/which-sources-ai-engines-cite-2026)).
- **Perplexity** — skews toward research-credible sources: NIH/PubMed, G2,
  LinkedIn, Microsoft. Most footnote-explicit of the engines (median 6.4
  citations per answer vs 3.1 ChatGPT, 2.4 Gemini, 3.6 Claude — [attrifast 1,200-prompt study, Apr–May 2026](https://attrifast.com/blog/ai-search-citations-by-vertical-2026)).
  Takes 13.6% of citations from news/media vs 5.2% on AI Overviews.
- **Gemini** — gets the largest share from brand-owned websites (51.62%) —
  because it integrates Google search results directly. Strong traditional SEO
  converts to Gemini visibility more than to any other engine ([Yext](https://www.yext.com/blog/chatgpt-make-your-brand-visible-ai-search)).
- **Google AI Overviews** — favor Google-owned properties: YouTube (200× video
  citation advantage), Google.com, Fandom. Takes 10.8% of citations from
  user-generated content vs Perplexity's 3.8% ([Agenzy](https://www.agenzy.lt/blog/which-sources-ai-engines-cite-2026)).
- **Claude** — leans toward long-form editorial (NYT, Atlantic, New Yorker,
  Economist), with older sources than other engines ([5WPR](https://completeaitraining.com/news/5wpr-index-finds-reddit-accounts-for-40-of-ai-citations/)).

The constants: **Reddit appears in the top 5 cited domains on every engine**
(universal channel); journalism is 27% of all citations, rising to 49% on
time-sensitive queries; earned media dominates — one study found Claude and
ChatGPT pulling 93%+ of citations from earned-media sources in tested
categories, with owned brand pages in the low single digits (arXiv:2509.08919,
via [authoritytech.io](https://authoritytech.io/curated/which-publications-get-cited-ai-search-engines-2026)).

## The volatility warning

Citation patterns shift in weeks, not years. ChatGPT's Reddit citation share
fell from ~60% to ~10% in six weeks in late 2025 after a single Google
parameter change; PR Newswire, Forbes, and Medium absorbed the displaced share
([5WPR](https://completeaitraining.com/news/5wpr-index-finds-reddit-accounts-for-40-of-ai-citations/)).
Run-to-run, 49–67% of citations on the same prompt overlap — one in three to
one in two citations changes between executions ([attrifast](https://attrifast.com/blog/ai-search-citations-by-vertical-2026)).
Single-shot checks are directional, not precision-grade.

## What gets cited: the signal hierarchy

1. **Third-party authority.** Yext Q4 2025: ChatGPT gets only 39.55% of
   citations from brand-owned websites vs 53.36% from managed listings; the
   5WPR index found just 15 domains control 68% of all AI citation share —
   more concentrated than PageRank ever was.
2. **Extractable, declarative structure.** Answer-first paragraphs, definitions,
   lists, comparison tables, stats with sources — the Princeton findings.
3. **Freshness on time-sensitive queries** (journalism's share jumps to 49%).
4. **Brand mentions over backlinks.** Models resolve entities and cite named
   mentions; Google explicitly calls inauthentic mention-farming a quality
   violation (May 2026 guide), so mentions must be earned, not planted.
5. **Traditional SEO still feeds the pipeline.** Gemini ≈ Google search results;
   AI Overviews ≈ Google's index + RAG. SE Ranking's 2.3M-page study found
   domain traffic the #1 predictor of appearing in AI answers — not backlinks,
   not keyword optimization ([via dev.to](https://dev.to/fay_/what-is-generative-engine-optimization-geo-and-why-your-brand-is-invisible-to-ai-1il9)).

## The scale of the shift

- ChatGPT: ~800M weekly active users, Q1 2026 ([Reuters via attrifast](https://attrifast.com/blog/ai-search-citations-by-vertical-2026)).
- AI Overviews: 200+ countries; Ahrefs (146.1M SERPs, Sept 2025): present in
  20.5% of SERPs, correlating with 34.5% lower CTR for the top-ranking page
  ([via typescape.ai](https://typescape.ai/blog/what-is-geo)).
- AI-referred sessions grew 527% Jan–May 2025; ~14.2% conversion vs 2.8% organic
  **[vendor — Navoto, treat as marketing]** ([navoto.com](https://navoto.com/blog/generative-engine-optimization-geo-complete-guide-to-ai-seo/)).
- LLM traffic: 0.0022% of sessions in 2024 → 0.0359% in 2025 (+1,506%);
  projected ~5% of all organic sessions by early 2026 **[vendor — GR0 client data, small base]** ([gr0.com](https://gr0.com/blog/gr0-geo-results)).
