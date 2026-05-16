# AgencyFlo — Project Memory

## What AgencyFlo is

AgencyFlo is the AI-native operating system for agencies. One closed-loop platform
replaces project management, time tracking, CRM, proposals, contracts, and invoicing.
Built by Jonny Burch (CEO/CPO) and Denis Khramov (CTO) inside their own 15-person
studio. Founded 2025. Headquartered in Malta.

- Canonical name: **AgencyFlo** (one word, capital A, capital F). Never "Agency Flow",
  "AgencyFlow", "Agency Flo", or lowercase.
- Canonical domain: agencyflo.com.

## The operating manual

The full tactical playbook lives in **`docs/aeo-geo-playbook.md`** (AEO/GEO & Site
Architecture Playbook v1.2). Read it before any content, site-architecture, schema,
or SEO/GEO work. Key sections:

- §3 Princeton GEO tactic ranking — cite sources (+40%), add statistics (+37%),
  add quotations (+30%). Keyword stuffing actively harms (−10%).
- §8 Site architecture — three pillars (Agency Operating System, Agency Profitability,
  Closed-Loop System) with cluster/spoke topology.
- §9 URL conventions — lowercase, hyphens, no trailing slash, no dates in blog URLs.
- §11 Content templates — every article opens with a 40–60 word answer block.
- §13 Consolidated on-page checklist (80+ factors) — the pre-publish gate.
- §14 Comparison content gets ~33% of AI citations — front-load /vs/ pages.
- §26 90-day execution plan — the build sequence.
- §28 Lead-magnet sitemap — every page mapped to funnel stage and lead capture.
- §29 Google Stitch design prompts — per-page-type design prompts.

## Voice rules (from §3, §12)

- Founder-led, operator-authentic. 80% problem and insight, 20% or less product.
- Authoritative tone, no hedging. Specific numbers and named scenarios.
- Forbidden words: "game-changer", "revolutionize", "seamless", "unlock", "empower".
- Ground claims in the 15-person studio's real experience.

## Marketing skills

40 marketing skills from `coreyhaines31/marketingskills` are installed under
`.agents/skills/` (with a `.claude/skills` symlink so Claude Code discovers them).
High-priority for AgencyFlo: ai-seo, site-architecture, schema, competitors,
copywriting, content-strategy, programmatic-seo, seo-audit.

## Agent context files (§25)

Marketing skills look for shared context before drafting:

- `.agents/product-marketing.md` — shared product source-of-truth (not yet created;
  build from the Master Brief when available).
- `.agents/personality.md` — voice, studio anecdotes, forbidden phrases (not yet
  created).

## Git

Develop on branch `claude/general-session-0EECi`. Commit with clear messages.
