# AgencyFlo — AEO/GEO & Site Architecture Playbook

**Version:** 1.2
**Owner:** Jonny (CEO/CPO)
**Last updated:** May 2026
**Review cadence:** Quarterly
**Next review:** Two months from publish

---

## Purpose

This is the tactical operating manual for getting AgencyFlo cited by AI engines (ChatGPT, Claude, Perplexity, Gemini, Google AI Overviews) and ranking in traditional search. It's the companion to the Master Brief — the Master Brief defines *what we say*; this defines *how, where, and on what infrastructure*.

This version is built to be the working document Denis, content writers, and any Claude Code agent can execute against without needing additional briefing. It includes the lead-magnet sitemap with user-type landing pages and free tools, plus Google Stitch design prompts to bootstrap the site build.

---

## What's new in v1.2

- §6 Keyword research with quantitative filters (KD ≤30, volume ≥100)
- §7 "Steal the winning formula" reverse-engineering method
- §12 Personality, humor, and dwell time as ranking signals
- §13 Consolidated on-page checklist (80+ factors)
- §16 Programmatic /for/ × /vs/ pairing strategy
- §18.2 Static Site Generation as a hard requirement
- §19 Lighthouse loop and Core Web Vitals
- §21 Full tooling stack with costs
- §23 Publishing cadence and fast-track indexing
- §25.3 personality.md companion file
- §28 The lead-magnet sitemap — user-type landing pages and free tools designed to capture leads at every funnel stage
- §29 Google Stitch design prompts — ready-to-paste prompts to design every page type

## What's new in v1.1

- §2 Three Pillars framework (Structure, Authority, Presence)
- §3 Princeton GEO tactic ranking
- §9 URL conventions
- §14 Citation share by content type
- §18.5 Machine-readable files for AI agent buyers
- §25 Claude Code agent integration

---

## Contents

1. AEO vs GEO vs SEO — what each is, how to win each
2. The three pillars of AI search: Structure, Authority, Presence
3. The Princeton GEO tactic ranking
4. Entity & brand consistency strategy
5. Query taxonomy — keywords mapped to intent, funnel, format, page
6. Keyword research — the golden nugget method
7. The "steal the winning formula" method
8. Site architecture — pillar / cluster / spoke topology
9. URL conventions and information architecture rules
10. Schema markup specification per page type
11. Content templates — answer blocks, FAQ blocks, comparison pages
12. Personality, humor, and dwell time as ranking signals
13. The consolidated on-page SEO checklist (80+ factors)
14. Citation share by content type
15. Comparison page system
16. Programmatic content — the /for/ × /vs/ pairing strategy
17. Off-site presence — Reddit, G2, Wikipedia, podcasts, founder LinkedIn
18. Technical infrastructure — SSG, crawlability, LLMs.txt, machine-readable files
19. The Lighthouse loop and Core Web Vitals
20. Measurement framework
21. The tooling stack — Semrush, GSC, Lighthouse, monitoring tools
22. Content lifecycle — refresh, audit, decommission
23. Publishing cadence and fast-track indexing
24. The closed-loop positioning campaign
25. Claude Code agent integration (product-marketing.md convention)
26. 90-day execution plan
27. Appendix — checklists, templates, prompts
28. The lead-magnet sitemap — every page mapped to funnel stage and capture mechanism
29. Google Stitch design prompts — ready-to-paste prompts per page type

---

# 1. AEO vs GEO vs SEO

## 1.1 The three disciplines, defined

| Discipline | What it optimizes for | Where the user is | Primary measurement |
|---|---|---|---|
| **SEO** | Ranking position 1–10 on Google/Bing SERP | Search results page | Organic clicks, rank position, impressions |
| **AEO** | Featured snippets, People Also Ask, Google AI Overviews, voice answers | Still on SERP, reading the answer box | Snippet ownership, position 0, PAA inclusion |
| **GEO** | Citation inside ChatGPT, Claude, Perplexity, Gemini answers | Inside the AI chat — may never see SERP | Citation frequency, share of voice, brand mention |

## 1.2 Why this matters now (the market data)

- **AI Overviews appear in ~45% of Google searches** and reduce clicks to websites by up to 58%.
- **35% of US consumers use AI at the product discovery stage** vs 13.6% who use traditional search.
- **Brands are 6.5x more likely to be cited via third-party sources than their own domains.**

## 1.3 The core mental model: passages, not pages

> **AI systems extract passages, not pages.** A well-structured paragraph on page 3 can get cited when a poorly-structured paragraph on page 1 cannot. Every section of every page must work as a standalone unit that makes sense lifted out of context.

## 1.4 What's different about GEO

- **Entity-level, not page-level.**
- **Third-party citations dominate.** Wikipedia alone = 7.8% of all ChatGPT citations. Reddit = 1.8%.
- **Rank position is decoupled from citation.**
- **Consistency across the web matters.**
- **Recency is harshly weighted.**

## 1.5 What stays the same

Strong SEO foundations make GEO easier. Layer GEO on top of solid SEO, not instead of it.

---

# 2. The Three Pillars of AI Search

- **Pillar 1 — Structure (make content extractable):** definition blocks, step-by-step blocks, comparison tables, pros/cons blocks, FAQ blocks, statistic blocks.
- **Pillar 2 — Authority (make content citable):** citations and statistics give the biggest lift; keyword stuffing hurts.
- **Pillar 3 — Presence (be where AI looks):** brands are 6.5x more likely to be cited via third-party sources.

---

# 3. The Princeton GEO Tactic Ranking

| Tactic | Visibility lift | How to apply |
|---|---|---|
| Cite sources | **+40%** | Authoritative references with links |
| Add statistics | **+37%** | Specific numbers with sources and dates |
| Add quotations | **+30%** | Expert quotes with name, title, organization |
| Authoritative tone | **+25%** | Demonstrated expertise, no hedging |
| Improve clarity | **+20%** | Short sentences, one idea per paragraph |
| Technical terms | **+18%** | Domain-specific terminology |
| Unique vocabulary | **+15%** | Word diversity |
| Fluency optimization | **+15–30%** | Readability and flow |
| Keyword stuffing | **−10%** | **ACTIVELY HARMS** AI visibility |

**Best combination: Fluency + Statistics.** Low-authority sites benefit even more — up to 115% visibility increase when citations are added to fluent content.

Per-article checklist: 3+ cited sources, 5+ statistics with sources, 1+ named quote, authoritative tone, clarity pass, domain terminology, varied vocabulary, fluency pass, zero keyword stuffing.

---

# 4. Entity & Brand Consistency Strategy

## 4.2 Canonical definitions (use verbatim)

**One-liner (50 chars):** `The AI-native operating system for agencies.`

**Short (140 chars):** `AgencyFlo is the AI-native operating system for agencies. One platform replaces project management, time tracking, CRM, proposals, and invoicing.`

**Medium (300 chars):** `AgencyFlo is the AI-native operating system for agencies. One closed-loop platform replaces fragmented stacks of project management, time tracking, CRM, proposals, contracts, and invoicing — with Flow AI generating documents, drafting invoices, and spotting margin risks in real time.`

**Long (~500 chars):** `AgencyFlo is the AI-native operating system for agencies. It replaces the fragmented stack of project management, time tracking, CRM, proposals, contracts, and invoicing tools with one closed-loop system of record — where marking an invoice paid updates your P&L in real time. Built by Jonny Burch and Denis Khramov inside their own 15-person studio after 4+ months of internal use. Founded 2025. Headquartered in Malta.`

## 4.3 Naming rules

- Canonical: **AgencyFlo** (one word, capital A, capital F)
- Never: Agency Flow, AgencyFlow, Agency Flo, agencyflo (lowercase)
- Domain: agencyflo.com canonical. Redirect typo variants.

## 4.4 sameAs map

Website, LinkedIn, X, Crunchbase, G2, Capterra, GetApp, Product Hunt, YouTube — all `/agencyflo` handles.

## 4.6 Wikipedia priority

Wikipedia = ~7.8% of all ChatGPT citations. Adjacent edits months 4–6; notability watch months 9–12.

---

# 5. Query Taxonomy

Every query mapped on four dimensions: Intent / Funnel stage / Format / Target page. See playbook source for full keyword tables (problem-aware, solution-aware, product-aware/comparison, segment, conversational query layer).

Key target pages: /agency-operating-system, /agency-profitability, /closed-loop-system, /vs/[competitor], /for/[segment], /tools/[tool].

---

# 6. Keyword Research — The Golden Nugget Method

Filter rules: KD ≤ 30, volume ≥ 100/month, intent informational/commercial/transactional, must map to an existing pillar or planned page.

Sources: Semrush Keyword Magic Tool, Ahrefs, GSC queries ranking 5–20, competitor backlink analysis, AnswerThePublic, Reddit/Quora.

Cadence: quarterly full pass (20–40 new targets), monthly GSC refresh, weekly community scan.

---

# 7. The "Steal the Winning Formula" Method

Before writing, analyze top 3 ranking results on: word count, header structure, image count, internal links, external links, specific elements (tables/FAQ/stats/process/video). Match within ±15%. Differentiate with original data, operator-authentic perspective, closed-loop framing. Reverse-engineer structure, not content.

---

# 8. Site Architecture

## Pillar / cluster / spoke model

**Pillar 1 — Agency Operating System** (/agency-operating-system)
Clusters: /blog/anatomy-of-an-agency-operating-system, /blog/all-in-one-agency-software, /blog/agency-tool-sprawl-cost, /blog/consolidate-agency-tool-stack, /blog/agency-software-stack-2026, /blog/from-7-tools-to-1

**Pillar 2 — Agency Profitability** (/agency-profitability)
Clusters: /blog/why-agency-projects-lose-money, /blog/agency-project-margin-tracking, /blog/real-time-vs-month-end-profitability, /blog/agency-pricing-models-profitability, /blog/utilization-vs-profitability-metrics, /tools/profitability-calculator

**Pillar 3 — The Closed-Loop System** (/closed-loop-system)
Clusters: /blog/proposal-to-paid-closed-loop, /blog/zapier-agency-stack-problems, /blog/integrated-vs-stitched-agency-tools, /blog/data-silos-in-agencies, /blog/closed-loop-vs-integrations

## Internal linking topology

- Every cluster article: link UP to pillar, SIDEWAYS to 2–4 siblings, OUT to one /vs/ or /for/, to one tool if relevant.
- Every pillar page: link DOWN to every cluster, sideways to other pillars, to most relevant /product/ deep-dive.
- Anchor text: descriptive, keyword-bearing, varied. Never "click here." 3–5 internal links per blog article; pillars 15–30.

---

# 9. URL Conventions

- Human-readable, hyphens not underscores, lowercase always, no trailing slash, reflect hierarchy, short but descriptive, no dates in blog URLs, no stop words, no file extensions.
- BreadcrumbList schema on every non-homepage page. Three clicks max from homepage to any page.
- Redirect baseline: www→root, http→https, trailing slash→none, uppercase→lowercase, typo domains→canonical, old URLs→new canonical.

---

# 10. Schema Markup Specification

- Organization schema sitewide (with sameAs map and knowsAbout array)
- SoftwareApplication on product pages (/, /product, /product/*, /pricing)
- Article + Author on every blog post (datePublished + dateModified non-negotiable)
- FAQPage where FAQs appear
- HowTo on tutorial articles
- BreadcrumbList on non-homepage pages
- Review/AggregateRating once 5+ G2 reviews exist
- Validate every page in Google Rich Results Test + Schema.org Validator

---

# 11. Content Templates

## Answer block (most important pattern)

40–60 words, immediately after H1, declarative, direct answer + supporting specific + stake. Standalone.

## FAQ block

6–12 questions (homepage 8, pillars 12, /vs/ 8, product 6). Answers 40–80 words, standalone, wrapped in FAQPage schema.

## Cluster article template (1,500–2,500 words)

Question headline → answer block → credibility hook → stakes → body (3–5 question-form H2s) → key takeaways box → FAQ → related reading.

## Pillar page template (3,000–5,000 words)

Category-defining H1 → definitional answer block → TOC → case for category → anatomy → differentiation → buyer's framework → category landscape → implementation → FAQ (10–12) → related reading.

## Fact density rule

A specific (number, named example, statistic, scenario) every 150–200 words.

## Recency

76% of pages cited by ChatGPT updated within 30 days. Visible "Published" and "Last updated" dates. Refresh: cornerstone 60 days, clusters 90, pillars 90, comparisons 60.

---

# 12. Personality, Humor, and Dwell Time

Personality is a measurable ranking input (dwell time, AI citation rate, conversion). For AgencyFlo: operator-authentic voice, real studio anecdotes, dry humor where it lands, opinions stated plainly, unexpected specifics.

Dwell tactics: open with a stakes hook, bury one unexpected insight mid-article, end sections with a cliffhanger, vary sentence rhythm, specific over generic, one unexpected metaphor per article.

Quarterly benchmarks: engagement time 3+ min clusters / 5+ min pillars, scroll depth 60%+ reach 75%, bounce under 60% for cornerstone.

---

# 13. The Consolidated On-Page SEO Checklist

Every page passes before publish: one H1 with primary keyword; title <60 chars; meta 150–160 chars; answer block 40–60 words; 2+ question-form H2s; FAQ 6–10 Qs; 3–5 internal links with descriptive anchors; 2–3 external citations; Princeton tactics (3+ sources, 5+ stats, 1+ quote, no stuffing); personality/dwell tactics; image alt text + WebP; schema validated; named author with Person schema; voice quality tests; post-publish tracker + GSC URL Inspect + LinkedIn excerpt.

---

# 14. Citation Share by Content Type

| Content type | Share of AI citations |
|---|---|
| Comparison articles | ~33% |
| Definitive guides | ~15% |
| Original research/data | ~12% |
| Best-of / listicles | ~10% |
| Product pages | ~10% |
| Opinion / analysis | ~10% |
| How-to guides | ~8% |
| Generic blog posts | ~2% |

First 60 days of content: 60–70% comparison and alternatives pages.

---

# 15. Comparison Page System

Three types: Type A head-to-head (/vs/[competitor]), Type B alternatives listicles (/vs/[competitor]-alternatives), Type C three-way matrices (/vs/X-vs-Y-vs-agencyflo).

Standard template: H1 → answer block verdict → honest competitor strengths → structural gap → comparison table (7–10 dimensions) → when to choose competitor → when to choose AgencyFlo → migration path → FAQ (8) → CTA.

Comparison dimensions: Architecture, Closed-loop, Profitability visibility, Pricing model, Agency-specific features, AI capabilities (shipped), White-label, Onboarding effort, Best fit, Starting price.

Competitor priority — Tier 1: Productive, Teamwork, Scoro, Notion, ClickUp. Tier 2: Asana, Monday.com, Kantata, Harvest, Toggl. Tier 3: Function Point, Workamajig, Float, Forecast, Resource Guru, PandaDoc, Bonsai, Plutio.

---

# 16. Programmatic Content — /for/ × /vs/ Pairing

Pair /for/[segment] × /vs/[competitor]. Build a cell only when: volume ≥ 50/mo, differentiated content, both parents exist, segment genuinely uses the competitor. **Hard cap: 15 pages year 1.** One per week max, after all top-level /for/ and /vs/ pages live (month 4+).

---

# 17. Off-Site Presence

Directory/review stack (first 90 days): G2 (10+ reviews), Capterra (10+), GetApp (5+), Software Advice, Product Hunt (launch month 1), Trustpilot, Crunchbase (verified), Wikipedia (adjacent edits), AlternativeTo, Slant.co.

Community: Reddit (r/agency primary, r/SaaS, r/freelance, r/Entrepreneur, r/marketing, r/webdev), IndieHackers, Hacker News, agency Slack communities, X, LinkedIn.

Founder content as entity signal. Don't buy links — earn citations via original research, public tools, founder writing.

---

# 18. Technical Infrastructure

- **SSG required** — pre-rendered HTML; AI crawlers strip `<script>` tags; JS-rendered content invisible.
- **AI crawler access** — robots.txt must Allow GPTBot, ChatGPT-User, ClaudeBot, Claude-Web, PerplexityBot, Google-Extended, Bingbot, Applebot-Extended, cohere-ai, anthropic-ai. Check Cloudflare "Block AI Scrapers" is OFF.
- **/llms.txt** — tell LLMs what's on the site.
- **Machine-readable files** at root: /pricing.md, /features.md, /about.md.
- Page speed: LCP <2.5s mobile, CLS <0.1, TTFB <600ms.
- Mobile parity, canonical URLs + redirects, auto-generated sitemap.xml, image optimization (WebP).

---

# 19. The Lighthouse Loop and Core Web Vitals

Targets: Performance 95+, Accessibility 95+, Best Practices 95+, SEO 100, LCP <2.5s, FID/INP <200ms, CLS <0.1, TTFB <600ms.

Fix loop: run Lighthouse → export JSON → feed to Claude Code → apply fixes → re-deploy → repeat until all 95+.

Cadence: every new page before publish; top 20 pages monthly; 50-page sample quarterly.

---

# 20. Measurement Framework

SEO, AEO, GEO, and business metrics tracked weekly/monthly. Monthly manual GEO audit: run brand-recognition and category prompts across ChatGPT, Claude, Perplexity, Gemini, Google AI Overviews; record mention, position, accuracy, sentiment, sources.

KPI scorecard (8 numbers, weekly, owned by Jonny): indexed pages, tracked keyword rankings, featured snippets, GEO citation rate, G2 reviews, backlinks, AI referrer sessions, branded search volume.

---

# 21. The Tooling Stack

Keyword/rank: Semrush ($140/mo), Ahrefs ($129/mo), GSC (free), Bing Webmaster Tools (free).
Technical: Lighthouse, Schema.org Validator, Google Rich Results Test, Screaming Frog, GTmetrix.
AI visibility: manual prompts (free), Otterly AI ($49+), Peec AI ($99+), ZipTie ($79+), Profound (enterprise), LLMrefs ($50+).
Analytics: GA4, Plausible/Fathom, Microsoft Clarity.
Content: Claude Code, Framer, Grammarly/Hemingway, Notion/Linear.

Minimum viable stack: ~€140/month. Full stack month 6+: ~€400–500/month.

---

# 22. Content Lifecycle

Publish cadence: months 1–3 = 3/week, months 4–6 = 2/week, months 7+ = 1/week + refresh focus.
Refresh: pillars 90 days, cornerstone clusters 60, standard clusters 90, comparisons 60, product pages on feature ship.
Decommission: <50 organic clicks in 12 months + no link role → 301 to closest pillar. Never delete — always redirect.

---

# 23. Publishing Cadence and Fast-Track Indexing

**Never bulk-publish.** Graduated launch ramp weeks 1–2: day 1 = 1 page, day 2 = 1, day 3 = 2, day 4 = 1, day 5 = 2–3, weekend rest, week 2 = 8–10 across 5 days, week 3+ scale to 3/week.

Fast-track indexing: GSC URL Inspect → Request Indexing within 24h; Bing Webmaster Tools URL submission; sitemap submission; internal link from established pages; social signals.

---

# 24. The Closed-Loop Positioning Campaign

Own "closed-loop agency software" as a category. Canonical definition on /closed-loop-system; repeat across every content piece; distribute off-site; schema the term in knowsAbout; measure ownership monthly by asking each LLM "What is a closed-loop agency system?"

Closed-loop content roadmap: /closed-loop-system (M1), /blog/proposal-to-paid-closed-loop (M1), /blog/zapier-agency-stack-problems (M2), /blog/integrated-vs-stitched-agency-tools (M2), /blog/data-silos-in-agencies (M3), /blog/closed-loop-vs-integrations (M3).

---

# 25. Claude Code Agent Integration

`.agents/product-marketing.md` at repo root (`.claude/product-marketing.md` fallback) — shared product context every marketing-skill agent reads first.
`.agents/personality.md` — studio anecdotes, recurring observations, forbidden phrases, voice examples.

Recommended skill stack from coreyhaines31/marketingskills: ai-seo, site-architecture, schema, seo-audit, competitors, copywriting, copy-editing, content-strategy, programmatic-seo, customer-research, cold-email, emails, social, pricing, launch.

Install: `npx skills add coreyhaines31/marketingskills`

---

# 26. 90-Day Execution Plan

- **Days 1–14:** foundations + graduated launch. Verify SSG, Cloudflare AI access, ship robots.txt + /llms.txt + machine-readable files, lock canonical definitions, Organization schema, GSC + Bing + GA4 + Clarity, buy Semrush/Ahrefs, content tracker, install .agents files + skills, ship homepage + /pricing + /about + /manifesto + /vs/productive + /vs/productive-alternatives + 2–3 free tools.
- **Days 15–30:** comparison surge — /vs/teamwork, /vs/scoro, /vs/notion, /vs/clickup, listicles, first three-way matrix, /closed-loop-system pillar, begin Reddit + LinkedIn.
- **Days 31–60:** pillars + segments + reviews — /agency-operating-system, /agency-profitability, 6 cornerstone clusters, /for/ pages, /tools/profitability-calculator, more /vs/, first 10 G2 reviews, podcast, Product Hunt launch.
- **Days 61–90:** authority build + measurement baseline — 6 more clusters, product deep-dives, more /for/, /tools/tool-stack-audit, first GEO audit, Wikipedia edits, next 10 G2 reviews, Show HN.

90-day output: ~15 comparison pages, 3 pillars, 12+ clusters, 5 segment pages, 3 product deep-dives, 4+ tools, 20 G2 reviews.

---

# 27. Appendix

Pre-publish checklist = §13. Monthly GEO audit template, Claude article-generation prompt, and 12-month success definition live in the full playbook.

12-month success: AgencyFlo cited in >70% of category prompts; position 1–3 for 30+ keywords; 15+ featured snippets; 50+ G2 reviews; 100+ referring domains; "closed-loop agency system" recognized as a category term; AI referrer traffic 10%+ of inbound; branded search 10x baseline.

---

# 28. The Lead-Magnet Sitemap

The operational sitemap. Every page tagged with funnel stage, lead-capture mechanism, priority. The site is a lead-generation engine — every page either captures a lead or funnels to one.

## Lead-capture philosophy

1. Every page has a path to conversion. No dead ends.
2. Free tools beat gated PDFs.
3. Soft CTAs > hard CTAs.

## Four lead-capture mechanisms

| Mechanism | When | Conversion |
|---|---|---|
| Free tool with optional email | High-intent informational queries | 8–15% email capture |
| Early-access waitlist | Product-aware / decision pages | 3–8% signup |
| Newsletter subscription | Problem-aware blog content | 1–3% subscribe |
| Direct early-access apply | Comparison / segment pages | 2–5% apply |

## Sitemap

**Top-level:** / (homepage, waitlist), /manifesto (newsletter+waitlist), /product (waitlist), /pricing (direct apply), /about (waitlist), /reviews (direct apply), /changelog (newsletter), /early-access (direct apply), /security (direct apply), /careers (future).

**Pillars:** /agency-operating-system (newsletter+tool), /agency-profitability (free tool), /closed-loop-system (waitlist).

**Product deep-dives:** /product/dashboard, /product/projects-and-tasks, /product/time-tracking, /product/clients-crm, /product/documents-proposals-contracts, /product/invoices, /product/team-access, /product/white-label, /product/flow-ai.

**Comparison:** /vs/productive, /vs/teamwork, /vs/scoro, /vs/notion, /vs/clickup, /vs/asana, /vs/monday, /vs/kantata, /vs/productive-alternatives, /vs/teamwork-alternatives, /vs/scoro-alternatives, /vs/clickup-alternatives-agencies, /vs/notion-alternatives-agencies, /vs/productive-vs-teamwork-vs-agencyflo, /vs/productive-vs-scoro-vs-agencyflo, /vs/teamwork-vs-scoro-vs-agencyflo.

**Segment / user-type:** /for/design-agencies, /for/dev-agencies, /for/marketing-agencies, /for/ai-agencies, /for/branding-agencies, /for/small-agencies, /for/scaling-agencies, /for/freelancers, /for/multi-project-entrepreneurs.

**Free tools (lead magnets):** /tools/profitability-calculator, /tools/tool-stack-audit, /tools/agency-rate-calculator, /tools/proposal-template-generator, /tools/agency-margin-leak-finder, /tools/team-capacity-planner, /tools/contract-clause-library, /tools/agency-pricing-calculator, /tools/client-onboarding-checklist, /tools/agency-health-score.

**Resources:** /blog, /blog/[slug], /guides, /glossary, /case-studies, /resources/state-of-agency-operations.

**Legal:** /terms, /privacy, /dpa, /security, /status.

## /for/ page structure

Hero → answer block → segment-specific problem → what segment needs → AgencyFlo for segment → real-world example → comparison snippet → segment FAQ (6) → segment-tagged CTA.

## Lead-capture form spec

- Waitlist: email (req), first name (opt), agency size (opt).
- Direct apply: email, first name, agency name, agency size, agency type (all req); current tools, why now (opt).
- Newsletter: email only.
- Free tool capture: optional post-value email ask, never gate the tool.

## Lead routing & tracking

Tag every lead with source page slug, funnel stage, segment, UTM. GA4 events: waitlist_signup, early_access_apply, newsletter_subscribe, free_tool_used, free_tool_email_captured, comparison_page_apply, segment_page_apply.

---

# 29. Google Stitch Design Prompts

Ready-to-paste prompts for Google Stitch (or Figma AI, v0, Lovable).

## 29.1 Shared design system (paste at the start of every prompt)

```
# AgencyFlo Design System

## Brand identity
- Company: AgencyFlo — the AI-native operating system for agencies
- Tone: confident operator, not corporate SaaS. Premium. High polish.
- Audience: agency founders (5–50 person teams). Sophisticated, design-literate, skeptical.

## Visual direction
- Base palette: charcoal black (#0A0A0B) primary, off-white (#F5F4EE) secondary
- Accent: iridescent / oil-on-water optical effect — subtle holographic gradients on key elements (CTAs, hero accents, the "F" logomark)
- Iridescent gradient spec: violet (#A78BFA) → teal (#5EEAD4) → soft amber (#FCD34D) → rose (#FB7185), at 15–25% opacity, used sparingly as accent only
- Logo: wavy abstract "F" letterform — fluid, organic, slightly off-axis
- NEVER use: generic SaaS purple gradient mesh, 3D objects, stock photography, emoji decoration, rounded-pill buttons with shadows

## Typography
- Headings: serif or geometric sans-serif with editorial weight — GT Sectra, Editorial New, or PP Editorial
- Body: clean modern sans-serif — Inter, Söhne, or similar
- Type sizes: large display headlines (60–96px desktop), generous body (17–19px), tight line-height on headlines (1.05–1.1), looser on body (1.5–1.6)
- Editorial spacing — feels more like a magazine than a SaaS dashboard

## Layout principles
- Density beats whitespace on the homepage. We respect the reader.
- Asymmetric grid where it serves clarity
- Generous vertical rhythm between sections (96–144px)
- Max content width: 1280px, with breakouts to full-bleed for hero and section accents
- Mobile-first responsive — every layout must work at 375px

## Component vocabulary
- Buttons: sharp corners (0–2px radius), bold weight, never gradient-filled (iridescent only on hover/active)
- CTA primary: black background, white text, micro-iridescent shimmer on hover
- CTA secondary: thin black border, transparent fill, black text
- Cards: thin 1px borders (#0A0A0B at 10% opacity), no drop shadows, subtle hover lift only
- Forms: minimal — no labels above fields, placeholders + floating labels on focus
- Tables: editorial — horizontal rules between rows, never zebra striping

## Tone of imagery
- Real product UI screenshots only — never mockups, never stock
- Documentary-style real-people-working images where photography is needed
- Iconography: thin-line, geometric, never filled or 3D

## Voice (for any copy you generate)
- Founder-led. Operator-authentic. Not marketing-team voice.
- 80% problem, 20% product
- Specific scenarios, named numbers, real anecdotes
- Never: "game-changer," "revolutionize," "seamless," "unlock," "empower"
- Always: short sentences. Active voice. Present tense.
```

The full per-page-type prompts (homepage, pillar, product, comparison, segment, free tool, pricing, blog, forms) are in §29.2–29.10 of the playbook source and reproduced in `docs/stitch-prompts.md`.

---

# End of Playbook v1.2

This document is the working operations manual. The 90-day plan (§26) is the build sequence. §28 is the sitemap; §29 is the design prompts.
