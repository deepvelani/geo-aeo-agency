# Key Studies on AI-Search Visibility

Dated and dated-skeptical. This field's half-life is months; anything pre-2025
is context, not current signal.

## 1. Aggarwal et al. — "GEO: Generative Engine Optimization" (arXiv Nov 2023; ACM KDD '24) [independent, peer-reviewed]

The founding paper. GEO-bench: ~10,000 queries, nine datasets, seven domains.
Simulated engine: Google Search retrieves top-5 sources, GPT-3.5-turbo
synthesizes answers with citations. Nine methods tested: citations, statistics,
expert quotes, technical terminology, fluency optimization, keyword stuffing,
authority claims, unique content, simplicity.

Findings: **statistics** +41% (Position-Adjusted Word Count) / +37% (Subjective
Impression), validated on Perplexity.ai; **citations** gave position-5 pages
+115.1% visibility (an "equalizer effect"); **quotes** +28% subjective
impression; fluency + statistics combined beat every single method by >5.5%;
**keyword stuffing −10% vs baseline** on Perplexity. DOI: 10.1145/3637528.3671900.

What it does NOT prove: results on any live commercial engine. The "up to 40%"
is a benchmark ceiling, measured on sources already retrieved into the answer.
([critique](https://blckalpaca.at/en/knowledge-base/seo-geo/geo-generative-engine-optimization/the-princeton-geo-study-methodology-results-and-critique), [plain-English read](https://kinetixseo.com/articles/geo-paper-princeton-study))

## 2. 5WPR — AI Platform Citation Source Index 2026 (May 1, 2026) [vendor study, large]

Synthesized six citation studies (Aug 2024–Apr 2026); 680M citations across
ChatGPT, AI Overviews, Perplexity, Gemini, Claude. Findings: 15 domains control
68% of citation share; **Reddit cited at ~40% frequency on every engine**;
Wikipedia 26–48% of ChatGPT's top-10 share; YouTube has a 200× video citation
advantage; journalism 27% overall, 49% on time-sensitive queries; ChatGPT's
Reddit share collapsed 60%→10% in six weeks in late 2025 (volatility warning).
([coverage](https://completeaitraining.com/news/5wpr-index-finds-reddit-accounts-for-40-of-ai-citations/))

## 3. SEMrush — 230K-prompt, 13-week tracking study (Nov 2025) [vendor study, large]

Top-5 cited domains per engine: ChatGPT = Wikipedia, Reddit, OpenAI, Walmart,
YouTube; AI Mode = Fandom, Wikipedia, YouTube, Reddit, Google; Gemini = Reddit,
YouTube, Wikipedia, Medium, Forbes; Perplexity = Reddit, LinkedIn, NIH,
Microsoft, G2; AI Overviews = YouTube, Reddit, Forbes, LinkedIn, Wikipedia.
Takeaway: no single "AI SEO" — each engine sources differently. ([via 5WPR](https://www.5wpr.com/research/citation-source-audit-q1-2026/))

## 4. Yang et al. — AI Search Arena analysis (arXiv:2507.05301, 2025) [independent]

366,087 citations across 12 AI models. Reuters took 22.8% of ChatGPT
citations, AP News 12.2%; the top 20 sources captured 67.3% of OpenAI's
citation share. Perplexity favored BBC/Yahoo News; Gemini leaned on Forbes
(the only business publication cited consistently across all 11 sectors).
([summary](https://authoritytech.io/curated/which-publications-get-cited-ai-search-engines-2026))

## 5. AttriFast — AI Citation Rates by Industry 2026 (1,200 prompts, Apr–May 2026) [vendor study]

12 verticals × 100 prompts × 4 engines × 3 runs = 14,400 prompt-engine-runs,
~51,723 citation events, 8,917 unique domains. Median citations/answer:
Perplexity 6.4, Claude 3.6, ChatGPT 3.1, Gemini 2.4. Citation-slot share:
editorial-review 22.3%, vendor sites 14.7%, Reddit 11.4%, Wikipedia 8.9%.
Run-to-run overlap 49–67%. Citation density +28% YoY (May 2025→2026).
([full study](https://attrifast.com/blog/ai-search-citations-by-vertical-2026))

## 6. Agenzy — Which Sources Do AI Engines Cite? (2.28M citations, 2026) [vendor study]

n=138 projects across ChatGPT, AI Overviews, Gemini, Perplexity. Google AI
Overviews takes 10.8% of citations from UGC (Perplexity: 3.8%); Perplexity
takes 13.6% from news/media (AI Overviews: 5.2%); ChatGPT is distinctive on
institutional sources (11.9%). ([full study](https://www.agenzy.lt/blog/which-sources-ai-engines-cite-2026))

## 7. Yext Research — AI Citation Behavior Across Models (Q4 2025) [vendor study]

Brand-owned website vs managed-listing citation share: Gemini 51.62%/39.15%,
Perplexity 46.11%/43.41%, Claude 41.27%/45.93%, ChatGPT 39.55%/53.36%.
ChatGPT is the most industry-variable (28.2% websites in Food & Beverage →
43.7% in Organizations; official hotel sites 38.08% in Hospitality).
Websites earn 4.31 citation occurrences per URL vs 2.46 for listings — deep
first-party content gets re-cited. ([full study](https://www.yext.com/blog/chatgpt-make-your-brand-visible-ai-search))

## 8. Google Search Central — optimizing for generative AI features (May 15, 2026) [primary source]

Not a study — the platform owner's rules of the game. "Optimising for
generative AI search is optimising for the search experience, and thus still
SEO." Rules out llms.txt, content chunking, AI-specific rewriting, and
AI-specific structured data for Google surfaces; confirms RAG grounded in the
Search index + query fan-out; inauthentic mentions = spam. Scope: Google AI
Overviews and AI Mode only. ([guide](https://bring.au/google-aeo-geo-official-position/), [analysis](https://wetheflywheel.com/en/ai-search/generative-engine-optimization/))

## Honest read of the evidence

The convergent signals (multiple independent studies): third-party/earned
sources dominate citations; Reddit and Wikipedia are universal; per-engine
patterns differ; citation behavior is volatile. The single-study signals to
treat carefully: any vendor's % lifts, "14.2% AI conversion rate" claims, and
anything measured on one engine in 2025.
