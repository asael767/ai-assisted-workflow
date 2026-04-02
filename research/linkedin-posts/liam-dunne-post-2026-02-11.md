# AEO Impact on SEO Performance: What We Learned Across 14M Queries (Liam Dunne, LinkedIn — Feb 11, 2026)

Answer Engine Optimization (AEO) isn’t theory anymore—it’s changing traffic, conversion, and even how we brief stakeholders. Here’s the full breakdown of what we saw across 14M queries and 41 client sites in Q4’25–Q1’26, plus the playbook we now run.

## Benchmarks (14M queries, 8 verticals)
- **AI Overview presence:** 62% of monitored queries now trigger an AI Overview; 71% in health/finance.  
- **Citation share variance:** Top 3 cited domains capture **74%** of all citations in a query set; long tail is mostly UGC.  
- **CTR from AI Overviews:** Mean **3.1%**; but **assisted conversions** from cited pages rose **+18% QoQ** (brand/nav follow-up).  
- **Time to index vs. time to citation:** With IndexNow + priority sitemaps, median time-to-citation dropped from 19 days to **6 days**.  
- **Content type lift:** Pages with **inline stat blocks + methodology** were cited **2.7×** more often than generic blog posts in the same cluster.

## What moved the needle
1) **Evidence pages beat opinions.** Adding a dated stat block (3–5 stats), methodology, and outbound sources increased citation likelihood by **+41%**.  
2) **Inline citations win.** Sentences with on-page, in-line source cues were lifted into AI answers **3.3×** more than footnoted claims.  
3) **Anchor hygiene matters.** We shifted to ~60% brand/URL, 30% partial, <10% exact across unique donors. Citation share rose **+12%** without rank losses.  
4) **Internal link sprints.** 10–15 contextual links from aged, traffic pages to each new evidence asset produced a **+9% crawl rate** increase and faster citations.  
5) **Bot segmentation.** Separating Googlebot, Bingbot, GPTBot traffic in logs surfaced JS hydration issues on PDPs; fixing SSR lifted product-page citations **+28%**.

## Playbook (repeatable)
- **Week 1:** Map 200 priority queries → identify AI Overview presence → classify retrieved/cited/absent. Draft two evidence pages with stat blocks + methodology.  
- **Week 2:** Publish evidence pages; add FAQ/HowTo schema; push via IndexNow and refreshed sitemaps. Start internal link sprint.  
- **Week 3:** Acquire 5 contextual links from research-style donors; avoid donors with >15% sponsored/ugc in last 10 posts.  
- **Week 4:** Re-measure citation share; patch “retrieved-not-cited” pages with inline references, author/reviewer, and clearer summaries. Add intent-specific CTAs for branded follow-up searches.

## Client results (anonymized)
- **B2B SaaS:** Citation share +15%; brand search +11%; assisted demos +9% after 45 days.  
- **DTC Health:** Time-to-citation cut to 5 days; AI-driven sessions flat, but brand/nav clicks +18% → net revenue +7%.  
- **Marketplace:** Removing JS-only rendering on PDPs enabled GPTBot/Bingbot to read data; product citations appeared in Copilot within a week; add-to-cart rate on brand traffic +6%.

## Quick wins you can ship this week
- Add a **stat block** and methodology to your top 10 money pages.  
- Publish a **source-of-truth JSON** (policies, pricing, claims) linked in robots.txt to reduce hallucinations.  
- Run a **log file check** for GPTBot/Bingbot rendering errors; fix SSR/ISR before buying links.  
- Measure **citation share + assisted conversions**, not just sessions.

Bottom line: AEO is now a measurable lever. Engineer pages as the best raw material for AI answers, then capture the branded demand that follows.
