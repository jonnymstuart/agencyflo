# AgencyFlo — Google Stitch Design Prompts

Ready-to-paste prompts for Google Stitch (also works in Figma AI, v0, Lovable).

**How to use:** for any page, paste §0 (the shared design system) first, then the
matching page-type prompt below it. Tool pages: paste §0, then the §T0 base tool
prompt, then the specific §T1–T10 tool spec.

Page → prompt mapping is in `docs/sitemap.md`.

---

## §0 — Shared design system (paste at the start of EVERY prompt)

```
# AgencyFlo Design System

## Brand identity
- Company: AgencyFlo — the AI-native operating system for agencies
- Tone: confident operator, not corporate SaaS. Premium. High polish.
- Audience: agency founders (5–50 person teams). Sophisticated, design-literate, skeptical.

## Visual direction
- Base palette: charcoal black (#0A0A0B) primary, off-white (#F5F4EE) secondary
- Accent: iridescent / oil-on-water optical effect — subtle holographic gradients on
  key elements (CTAs, hero accents, the "F" logomark)
- Iridescent gradient spec: violet (#A78BFA) → teal (#5EEAD4) → soft amber (#FCD34D)
  → rose (#FB7185), at 15–25% opacity, used sparingly as accent only
- Logo: wavy abstract "F" letterform — fluid, organic, slightly off-axis
- NEVER use: generic SaaS purple gradient mesh, 3D objects, stock photography,
  emoji decoration, rounded-pill buttons with shadows

## Typography
- Headings: serif or geometric sans-serif with editorial weight — GT Sectra,
  Editorial New, or PP Editorial
- Body: clean modern sans-serif — Inter, Söhne, or similar
- Type sizes: large display headlines (60–96px desktop), generous body (17–19px),
  tight line-height on headlines (1.05–1.1), looser on body (1.5–1.6)
- Editorial spacing — feels more like a magazine than a SaaS dashboard

## Layout principles
- Density beats whitespace on the homepage. We respect the reader.
- Asymmetric grid where it serves clarity
- Generous vertical rhythm between sections (96–144px)
- Max content width: 1280px, with breakouts to full-bleed for hero and section accents
- Mobile-first responsive — every layout must work at 375px

## Component vocabulary
- Buttons: sharp corners (0–2px radius), bold weight, never gradient-filled
  (iridescent only on hover/active)
- CTA primary: black background, white text, micro-iridescent shimmer on hover
- CTA secondary: thin black border, transparent fill, black text
- Cards: thin 1px borders (#0A0A0B at 10% opacity), no drop shadows, subtle hover lift
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

## Accessibility & performance
- All layouts must work at 375px width
- Color contrast meets WCAG AA
- No heavy animations, no large hero videos — Lighthouse Performance 95+ target
- Include schema-markup placeholders as HTML comments in the code
```

---

## §1 — Homepage

```
[Paste §0 shared design system above]

## Design the AgencyFlo homepage

Highest-stakes page. 10 seconds to convince an agency operator we understand their
problem. 60 seconds to earn enough trust to convert.

## Sections (in order)

1. HERO — Headline: "Stop managing tools. Start managing growth." Subhead: "AgencyFlo
   is the AI-native operating system for agencies. One platform replaces project
   management, time tracking, CRM, proposals, and invoicing — built by operators who
   got sick of stitching together seven tools." Primary CTA "Get early access" (black,
   sharp corners, iridescent on hover). Secondary CTA "See how it works" (text link
   with arrow). Visual: subtle iridescent flowing form behind the headline — abstract.
   No hero illustration, no 3D objects. Editorial.

2. THE PROBLEM — Headline: "Your stack is built like a Rube Goldberg machine."
   3 paragraphs, operator voice, on fragmentation. Numbers: "5–10 disconnected tools,"
   "30–40% of your week on admin." Visual: stylized diagram of fragmented tools
   connected by tangled lines, then a smaller frame of AgencyFlo replacing them all.

3. THE INSIGHT — Headline: "Why every agency tool feels almost-right but never quite
   works." 2 paragraphs. Pull-quote: "We tried 7 tools before we stopped looking and
   started building." Text-led, no visual.

4. THE CLOSED LOOP — Headline: "The proposal-to-paid loop. In one platform." Visual
   centerpiece: horizontal flow diagram Proposal → Contract → Project → Tasks → Time
   → Invoice → Paid → P&L Updates, each node connecting to the next, subtle iridescent
   stroke. 2 paragraphs: no Zapier, no syncing, real-time P&L.

5. PRODUCT PREVIEW — Headline: "Everything an agency runs on. In one place." 2x2 grid
   of cards (icon + 1-line), each linking to a /product/* deep-dive: Dashboard,
   Projects & Tasks, Documents, Flow AI.

6. WHY US — Headline: "Built inside a real studio. Under real pressure. With real
   margins on the line." 2-column: documentary photo of Jonny + Denis left, founder
   bio right. Pull stat: "4+ months of internal use. 15-person studio."

7. PRICING SNAPSHOT — Headline: "Flat pricing. Because growth shouldn't punish you."
   Two cards: Lifetime $500 one-time / Monthly €50/mo flat. Line: "No per-seat
   charges. No 'contact sales.' No enterprise tier." CTA "See pricing details".

8. FREE TOOLS PREVIEW — Headline: "Useful tools, on us." 3 cards: Profitability
   Calculator, Tool Stack Audit, Margin Leak Finder. "Try it free →" each. Frame:
   "Even if you never sign up for AgencyFlo, these will help."

9. STUDIO PROOF — Headline: "What our studio looked like before AgencyFlo. And after."
   3 stat cards: "11 hours / saved per developer per week", "2 projects / where we
   caught margin loss in real-time", "7 → 1 / tools we replaced".

10. FAQ — Accordion, sharp corners, thin dividers, 8 questions: What is AgencyFlo /
    Who is it for / Pricing / vs Productive / vs Notion / White-label / Flow AI /
    Early access.

11. FINAL CTA — Headline: "Built for agencies. By agencies. Out of necessity."
    Subhead: "We're onboarding 1,000 agencies through 2026 with hands-on support."
    Single CTA "Apply for early access".

FOOTER — Three columns Product / Resources / Company. Subscribe box: "Get the weekly
operator memo from Jonny." Logo, copyright, social links (LinkedIn, X, YouTube).

Mobile parity required at 375px. Lighthouse Performance 95+. Schema placeholders as
HTML comments (Organization, SoftwareApplication, FAQPage).
```

---

## §2 — Pillar page (/agency-operating-system, /agency-profitability, /closed-loop-system)

```
[Paste §0 shared design system above]

## Design an AgencyFlo pillar page

Long comprehensive guide (3,000–5,000 words) that owns a category. Authoritative,
scannable, editorial-magazine treatment.

STRUCTURE
- Top: large display H1 (60–80px). "Published [date] · Last updated [date]" small
  caps. Author byline with photo (Jonny or Denis). 40–60 word answer block in larger
  body type (20–22px), italicized or a distinct typeface. Subtle iridescent rule below.
- Table of contents: sticky right sidebar on desktop, collapsible at top on mobile.
  "In this guide" header. Active section highlights on scroll.
- Body: line height 1.6. H2s in editorial typeface (36–42px). H3s semibold sans
  (24px). Pull-quotes large with thin vertical iridescent rule on the left.
  Statistic callouts in outlined boxes with a large number. Editorial tables, no
  zebra striping.
- Sidebar: "Try the free [related tool]" sticky CTA card. Newsletter signup card
  mid-page. Related reading list at the end.
- FAQ: accordion, sharp corners, 10–12 questions.
- End CTA: full-width section, iridescent gradient background accent. "Get early
  access to AgencyFlo" + 1-line value prop + email-only waitlist form inline.

VARIANT — /agency-profitability: embed the Profitability Calculator inline after
section 3, fully functional, not gated. After tool use, soft email ask "Save your
results?". Internal links to /tools/profitability-calculator,
/vs/productive-alternatives, /for/scaling-agencies.

Mobile parity at 375px. Schema placeholders as HTML comments (Article, FAQPage,
BreadcrumbList).
```

---

## §3 — Product overview (/product)

```
[Paste §0 shared design system above]

## Design the /product overview page

- HERO — Headline: "Everything an agency runs on. In one platform." Subhead: 2 lines
  on the closed-loop system. Hero visual: real product screenshot (dashboard view),
  clean, subtle iridescent glow behind it. Not a mockup.
- FEATURE GRID — 10 features, 2-column desktop / single mobile. Each block: real
  product screenshot (cropped), feature name (H3), 1-sentence outcome, 2–3 sentence
  description, "See [feature] →" link to deep-dive. Order: Dashboard, Projects &
  Tasks, Time tracking, Clients (CRM), Documents (proposals + contracts), Invoices,
  Team & Access, White-label, Flow AI.
- CLOSED LOOP VISUALIZATION — full-width, detailed version of the homepage flow
  diagram. Each node clickable, scrolls to that feature.
- WHY US — studio credibility section (same as homepage).
- PRICING SNAPSHOT + CTA.
- FAQ — 6 product-specific questions.

Mobile parity at 375px. Schema placeholders as HTML comments (SoftwareApplication,
FAQPage, BreadcrumbList).
```

---

## §4 — Product deep-dive (/product/[feature])

```
[Paste §0 shared design system above]

## Design a /product/[feature] deep-dive page

- HERO — Headline: feature-specific outcome (e.g. "See real-time profitability across
  every project"). Subhead: who it's for and what it replaces. Hero visual:
  full-bleed real product screenshot of the feature.
- "WHAT IT DOES" — 3-column layout of capability cards, each with a small product
  screenshot + 1-line description.
- "WHY IT MATTERS" — operator-authentic story about the problem this solves.
  Pull-quote from Jonny or Denis.
- "HOW IT WORKS" — step-by-step walkthrough with annotated screenshots.
- COMPARISON SNIPPET — small table "How this compares to [competitor's equivalent]".
- RELATED FEATURES — 3 cards linking to related /product/* pages.
- CTA — "Get early access" + waitlist form.

Feature pages to produce: dashboard, projects-and-tasks, time-tracking, clients-crm,
documents-proposals-contracts, invoices, team-access, white-label, flow-ai.

Mobile parity at 375px. Schema placeholders as HTML comments (SoftwareApplication,
BreadcrumbList).
```

---

## §5 — Comparison page (/vs/[competitor])

```
[Paste §0 shared design system above]

## Design a /vs/ comparison page

Highest-leverage SEO/GEO page (~33% of AI citations come from comparison content).
Must feel honest, structured, parseable.

- HERO — Headline: "AgencyFlo vs [Competitor]: Honest Comparison from an Operator".
  Subhead: "Last updated [date]. Built by people who actually ran an agency."
  40–60 word verdict answer block.
- "WHAT [COMPETITOR] DOES WELL" — 3–4 paragraphs honestly acknowledging strengths.
  A genuine trust signal, not fake-honesty.
- "WHERE THE GAP IS" — 3–4 paragraphs on structural differences. Pull-quote with a
  specific scenario.
- COMPARISON TABLE (centerpiece) — 10 rows, 3 columns (Dimension / [Competitor] /
  AgencyFlo). Dimensions: Architecture, Closed-loop, Profitability visibility,
  Pricing model, Agency-specific features, AI capabilities, White-label, Onboarding
  effort, Best fit, Starting price. Editorial table, no zebra. AgencyFlo column has a
  subtle iridescent left border. Cells use checkmarks, X marks, or descriptive text —
  never bare "Yes/No".
- "WHEN TO CHOOSE [COMPETITOR]" — 2–3 genuine scenarios where they win.
- "WHEN TO CHOOSE AGENCYFLO" — 3–4 scenarios where AgencyFlo wins.
- MIGRATION PATH — step-by-step "How to migrate from [Competitor] to AgencyFlo".
- FAQ — 8 questions.
- CTA — "Apply for early access" (higher-friction full apply form) + link to /pricing.

Variants: alternatives listicles (/vs/[competitor]-alternatives) — 10–15 ranked
tools, AgencyFlo at #1, free-tool + waitlist CTA. Three-way matrices — side-by-side
of three tools, direct apply CTA.

Mobile parity at 375px. Schema placeholders as HTML comments (Article, FAQPage,
BreadcrumbList).
```

---

## §6 — Segment / user-type page (/for/[segment])

```
[Paste §0 shared design system above]

## Design a /for/[segment] user-type landing page

Dedicated funnel for one audience. Tune copy and imagery to the audience without
diluting the visual system.

Segments: design-agencies, dev-agencies, marketing-agencies, ai-agencies,
branding-agencies, ecommerce-agencies, strategic-consultants, small-agencies,
scaling-agencies, freelancers, multi-project-entrepreneurs.

Segment-specific notes for the two newest pages:
- ecommerce-agencies — Shopify/DTC build and growth shops. Lead with retainer +
  performance-fee billing, multi-store client work, and project profitability
  across recurring CRO/dev sprints. Typical tools to compare against: ClickUp,
  Asana, Notion + a separate time tracker.
- strategic-consultants — strategy and advisory consultancies (not delivery-heavy
  production). Lead with high-value time being billed accurately, proposal-to-SOW
  rigor, utilization of senior people, and retainer/value-based pricing. Typical
  tools to compare against: Notion, spreadsheets, Harvest, generic PM tools.

- HERO — segment-specific headline (e.g. "Operations software for design studios
  that bill for craft"). Subhead: 2 lines on what this segment needs that generic
  tools miss. Primary CTA "Get early access" (segment-tagged form). Visual: real
  product screenshot from the most relevant perspective.
- "WHAT [SEGMENT] AGENCIES ACTUALLY NEED" — 3–4 paragraphs of segment-specific
  operational needs.
- "WHERE MOST TOOLS FAIL YOU" — 2–3 paragraphs + one named segment-specific scenario.
- "AGENCYFLO FOR [SEGMENT]" — 4–6 cards showing features through this audience's
  lens, each with feature + segment-specific application + mini screenshot.
- REAL-WORLD EXAMPLE — 200-word scenario of a [segment] agency using AgencyFlo, with
  specific numbers and outcomes.
- COMPARISON SNIPPET — small table: AgencyFlo vs the 2–3 tools this segment uses.
- SEGMENT FAQ — 6 questions only this audience would ask.
- CTA — "Get early access" higher-friction apply form, segment-tagged.

Mobile parity at 375px. Schema placeholders as HTML comments (FAQPage, BreadcrumbList).
```

---

## §7 — Pricing page (/pricing)

```
[Paste §0 shared design system above]

## Design the pricing page

- HERO — Headline: "Flat pricing. Because growth shouldn't punish you." Subhead:
  "Not per seat. Not tiered. Not 'contact sales.'"
- TWO PLANS (side-by-side cards) — Lifetime: big number $500, "One-time payment.
  Yours forever.", "Early adopter pricing. Increases at 100 customers.", full feature
  list, CTA "Get lifetime access". Monthly: big number €50/mo, "Flat. Forever.",
  same early-adopter note, full feature list, CTA "Start monthly".
- ALIGNMENT STORY — 2 paragraphs on why no per-seat pricing. "Per-seat pricing
  punishes growth. Our incentives are aligned with yours."
- WHAT'S INCLUDED — editorial table, every feature, included in both plans. No
  Pro/Enterprise columns — one tier only.
- "WHAT YOU DON'T GET" — honestly list what doesn't exist yet. Trust through
  limitation acknowledgement.
- FAQ — 8 pricing-specific questions.
- CTA — "Apply for early access" full form.

Mobile parity at 375px. Schema placeholders as HTML comments (SoftwareApplication
with Offer fields, FAQPage).
```

---

## §8 — Blog index + article

```
[Paste §0 shared design system above]

## /blog index page
- Editorial magazine layout, not a SaaS blog grid.
- Featured article at top, full-width with large image.
- Below: 2-column article grid. Each card: image, category tag, headline, 1-line
  summary, author + date.
- Filter by category (Tool Stack, Profitability, AI, Operations, Founder).
- Newsletter signup in sidebar/footer.

## Individual blog article page
- Editorial typography (lighter than pillar pages). Article width 680px max for body.
- Pull-quotes break the column width.
- Author byline with photo at top AND end. Reading-time estimate.
- Inline newsletter signup mid-article.
- Related articles at end (3 cards).
- Comments disabled. Share buttons: LinkedIn, X, copy link only.

Mobile parity at 375px. Schema placeholders as HTML comments (Article, BreadcrumbList).
```

---

## §9 — Forms and conversion components

```
[Paste §0 shared design system above]

## Form design system — used across the whole site

WAITLIST SIGNUP (lowest friction) — inline horizontal on desktop, stacked on mobile.
Single email field + button "Get early access". Placeholder "you@youragency.com".
Success: replace form with "You're on the list. We'll be in touch."

DIRECT APPLY FORM (higher friction) — multi-step on mobile, single-page on desktop.
Fields: email, first name, agency name, agency size (dropdown: 1–4, 5–14, 15–49,
50+), agency type (dropdown: design, dev, marketing, AI, branding, other), current
tools (optional multi-select), why now (optional textarea). Progress indicator if
multi-step. Submit "Apply for access". Success: full-screen confirmation + next steps.

NEWSLETTER SIGNUP — inline mid-article and in footer. Single email field + "Subscribe".
Frame: "Operator memo from Jonny. Once a week. Unsubscribe anytime."

FREE TOOL EMAIL CAPTURE — appears after tool output, small inline card, not blocking.
Single email field + "Send me my results". Skippable: "No thanks, just let me use
the tool."

STICKY CTA BAR (optional) — bottom of long pages after 60% scroll. "Get early access"
+ email field + button. Dismissable.

EXIT-INTENT MODAL (sparing — only /pricing and /vs/*) — "Before you go — see how much
your current stack is costing you" + link to /tools/tool-stack-audit. Easy dismiss.

TRUST STRIP (on /pricing, /early-access, /vs/*) — 3–4 logos (G2, Capterra, Product
Hunt, Crunchbase), "Verified by" framing.
```

---

## §10 — Hub pages (/vs, /for, /tools) — recommended additions

```
[Paste §0 shared design system above]

## Design a hub/index page (use for /vs, /for, and /tools)

A clean directory page that concentrates internal link equity.

- HERO — short headline + 1-line subhead.
  /vs: "Honest comparisons. From operators who ran an agency."
  /for: "Built for how your kind of agency actually works."
  /tools: "Free tools for agency owners. No signup. No catch."
- CARD GRID — one card per child page: title, 1-line description, "→" link. 3-column
  desktop, single mobile. /tools cards may show a tiny preview of the tool's output.
- For /vs and /for: a short editorial intro paragraph above the grid.
- For /tools: frame line "Even if you never sign up for AgencyFlo, these will help."
- CTA — newsletter signup (/vs, /for) or "Get early access" (/tools).

Mobile parity at 375px. Schema placeholders as HTML comments (BreadcrumbList,
ItemList).
```

---

# Free Tool Prompts

## §T0 — Base free-tool prompt (paste §0, then §T0, then a §T1–T10 spec)

```
[Paste §0 shared design system above]

## Design a free tool page

The free tools are AgencyFlo's primary lead magnet. They must be genuinely useful.
Never gate the tool itself — optional email capture only AFTER the tool delivers value.

SHARED STRUCTURE (every tool page)
- HERO — tool-specific headline + 1-sentence subhead on what it does. No CTA in hero;
  the tool is the action.
- THE TOOL — full-width interactive area. Clean form-style inputs. Real-time output
  as the user fills it in. Iridescent accent on the primary output number/result.
- "WHAT THIS MEANS" — interpretation of the user's results + specific advice based
  on their input.
- SOFT EMAIL CAPTURE — inline card after output: "Save your results?" + email-only
  field + "Send me my results + how to fix this". Skippable, never blocking.
- "HOW WE CALCULATED THIS" — transparent methodology. Show the math.
- RELATED CONTENT — 3 cards linking to the relevant pillar / cluster / product page.
- END CTA — "AgencyFlo automates this for you" soft link to the relevant /product/*
  page, plus "Get early access" secondary CTA.

Mobile parity at 375px. Lighthouse Performance 95+. Schema placeholders as HTML
comments (WebApplication or SoftwareApplication, BreadcrumbList, FAQPage if FAQ).

Now apply the specific tool spec below.
```

---

### §T1 — /tools/profitability-calculator

```
[Paste §0, then §T0, then this spec]

TOOL: Project Profitability Calculator
Headline: "Calculate your real project profitability."
Subhead: "Most agencies see margin at month-end. See it now."

INPUTS
- Project budget / fee (currency)
- Hours logged on the project (number)
- Blended team hourly cost (currency)
- Direct expenses / pass-through costs (currency)
- Monthly tool-stack cost attributable to the project (currency, prefilled est.)
- Admin overhead % (slider, default 30%)
- Context-switching loss % (slider, default 15%)

OUTPUT (real-time, iridescent accent on the headline number)
- Real project margin (% and currency) AFTER tool cost, admin overhead, and
  context-switching deductions
- Side-by-side: "Margin you think you have" vs "Margin you actually have"
- A simple bar showing where the money went

"WHAT THIS MEANS" — if real margin < 20%, flag it and explain the most likely cause.
RELATED: /agency-profitability, /tools/agency-pricing-calculator, /product/dashboard
END CTA links to /product/dashboard.
```

### §T2 — /tools/tool-stack-audit

```
[Paste §0, then §T0, then this spec]

TOOL: Agency Tool Stack Audit
Headline: "Score your agency's tool stack."
Subhead: "Find the overlap, the gaps, and what it's quietly costing you."

INPUTS
- Multi-select / add list of current tools (project mgmt, time tracking, CRM,
  proposals, invoicing, docs, chat, automation — prefilled common options:
  Notion, ClickUp, Asana, Monday, Toggl, Harvest, Productive, Teamwork, Scoro,
  Pipedrive, HubSpot, PandaDoc, QuickBooks, Xero, Zapier, Slack)
- Team size (number)
- Approx. monthly spend per tool (optional, currency)

OUTPUT
- Estimated total monthly + annual tool spend
- Overlap analysis — which tools duplicate each other's jobs
- Gap analysis — closed-loop steps not covered
- Estimated hours-per-week lost to context-switching across the stack
- A "stack health" score out of 100 (iridescent accent)

"WHAT THIS MEANS" — top 3 consolidation opportunities, ranked.
RELATED: /agency-operating-system, /vs/productive-alternatives, /product
END CTA links to /product.
```

### §T3 — /tools/agency-rate-calculator

```
[Paste §0, then §T0, then this spec]

TOOL: Agency Hourly Rate Calculator
Headline: "Calculate the hourly rate you actually need to charge."
Subhead: "For freelancers and small agencies. Overhead and time off included."

INPUTS
- Desired annual salary / take-home (currency)
- Target profit margin % (slider, default 20%)
- Billable hours per week (number, default 25)
- Weeks worked per year (number, default 46)
- Annual overhead — software, workspace, insurance (currency)
- Effective tax rate % (slider)

OUTPUT (iridescent accent on the rate)
- Required billable hourly rate
- Breakdown: salary portion, overhead portion, tax portion, profit portion
- "Utilization reality check" — what the rate becomes if billable hours drop 20%

"WHAT THIS MEANS" — compare their rate to typical agency ranges; flag under-charging.
RELATED: /for/freelancers, /tools/agency-pricing-calculator, /agency-profitability
END CTA links to /product/time-tracking.
```

### §T4 — /tools/proposal-template-generator

```
[Paste §0, then §T0, then this spec]

TOOL: Proposal Template Generator
Headline: "Generate a project proposal from a brief."
Subhead: "AI-assisted. Fillable. Yours to send."

INPUTS
- Project type (dropdown: branding, website, app, marketing campaign, retainer,
  other)
- Client name
- Scope summary (textarea)
- Timeline (weeks)
- Budget or day rate (optional)
- Tone (dropdown: formal, friendly, premium)

OUTPUT
- A filled, structured proposal: overview, scope, deliverables, timeline, pricing
  table, terms, next steps
- Editable inline preview, formatted like a real document
- "Copy" and "Download as PDF" actions

SOFT EMAIL CAPTURE framed as: "Want this branded with your logo and colors?"
RELATED: /product/documents-proposals-contracts, /tools/contract-clause-library,
/closed-loop-system
END CTA links to /product/documents-proposals-contracts.
```

### §T5 — /tools/agency-margin-leak-finder

```
[Paste §0, then §T0, then this spec]

TOOL: Agency Margin Leak Finder
Headline: "Find out where your margin is leaking."
Subhead: "10 questions. A scored report. Three fixes."

INPUTS — 10-question assessment, one screen at a time with a progress bar. Questions
cover: scope creep handling, time-tracking discipline, proposal-to-project handoff,
month-end vs real-time profit visibility, rate reviews, utilization tracking,
change-order process, tool fragmentation, billing delays, post-project reviews.
Each answer is a 1–5 scale or multiple choice.

OUTPUT
- Margin leak score out of 100 (iridescent accent)
- Top 3 identified leaks, each with a 1-line explanation and severity
- A simple visual: where margin leaks across the project lifecycle

"WHAT THIS MEANS" — personalized: the single highest-impact fix for this agency.
RELATED: /agency-profitability, /tools/profitability-calculator, /product/dashboard
END CTA links to /agency-profitability.
```

### §T6 — /tools/team-capacity-planner

```
[Paste §0, then §T0, then this spec]

TOOL: Team Capacity Planner
Headline: "Plan your team's capacity across the pipeline."
Subhead: "Drag, drop, see who's overbooked before it happens."

INPUTS
- Add team members (name + weekly capacity in hours)
- Add projects (name + estimated hours + start/end weeks)
- A drag-and-drop allocation grid: team members (rows) × weeks (columns)

OUTPUT (real-time)
- Per-person utilization % per week, color-coded (under / healthy / overbooked —
  iridescent accent on healthy)
- Pipeline-level view: total demand vs total capacity per week
- Flags weeks where the team is over capacity

"WHAT THIS MEANS" — which weeks need hiring, deferral, or rescoping.
RELATED: /for/scaling-agencies, /product/projects-and-tasks, /agency-profitability
END CTA links to /product/projects-and-tasks.
```

### §T7 — /tools/contract-clause-library

```
[Paste §0, then §T0, then this spec]

TOOL: Agency Contract Clause Library
Headline: "30+ agency contract clauses, explained."
Subhead: "Search, understand, copy. Built for client work."

LAYOUT (no calculator — a searchable library)
- Search bar + category filter (scope & change orders, payment & late fees,
  IP & ownership, kill fees & cancellation, confidentiality, liability, revisions,
  termination)
- Clause cards: clause title, the clause text, a plain-English "why this matters"
  explanation, a "Copy" action
- 30+ clauses across the categories

SOFT EMAIL CAPTURE framed as: "Want editable, agency-branded versions of every
clause?"
RELATED: /product/documents-proposals-contracts, /tools/proposal-template-generator,
/closed-loop-system
END CTA links to /product/documents-proposals-contracts.
```

### §T8 — /tools/agency-pricing-calculator

```
[Paste §0, then §T0, then this spec]

TOOL: Agency Project Pricing Calculator
Headline: "Price your next project with confidence."
Subhead: "Hours, rates, and the margin you actually want."

INPUTS
- Estimated hours by role (add rows: role + hours + hourly cost)
- Direct expenses / pass-through costs (currency)
- Target profit margin % (slider, default 25%)
- Risk / contingency buffer % (slider, default 10%)
- Discount, if any (%)

OUTPUT (iridescent accent on the recommended price)
- Recommended project price
- Breakdown: cost of delivery, contingency, profit, discount impact
- Effective blended day rate this price implies
- "Floor price" — the lowest price before margin goes negative

"WHAT THIS MEANS" — flag if the discount erodes margin below target.
RELATED: /agency-profitability, /tools/profitability-calculator,
/tools/agency-rate-calculator
END CTA links to /product/documents-proposals-contracts.
```

### §T9 — /tools/client-onboarding-checklist

```
[Paste §0, then §T0, then this spec]

TOOL: Client Onboarding Checklist
Headline: "A client kickoff checklist that nothing falls through."
Subhead: "Editable. Interactive. Built from real agency kickoffs."

LAYOUT (interactive checklist, not a calculator)
- Pre-built checklist grouped into phases: Pre-kickoff, Kickoff meeting, Access &
  tools, Scope & expectations, Communication cadence, First deliverable.
- Each item is a checkable row with a short note. User can check, edit text, add,
  or remove items.
- Live progress bar (iridescent accent) showing completion %.

SOFT EMAIL CAPTURE framed as: "Save this checklist and reuse it for every client?"
RELATED: /for/scaling-agencies, /product/clients-crm, /product/projects-and-tasks
END CTA links to /product/clients-crm.
```

### §T10 — /tools/agency-health-score

```
[Paste §0, then §T0, then this spec]

TOOL: Agency Health Score
Headline: "Score your agency's operational health."
Subhead: "25 questions. An honest scorecard. A growth roadmap."

INPUTS — 25-question assessment, grouped into 5 dimensions (5 questions each):
Profitability, Operations & process, Team & capacity, Client & pipeline, Tooling &
data. One screen per dimension with a progress bar. Answers on a 1–5 scale.

OUTPUT
- Overall agency health score out of 100 (iridescent accent)
- A radar/spider chart across the 5 dimensions
- The strongest dimension and the weakest dimension, named
- 3 prioritized recommendations to raise the score

"WHAT THIS MEANS" — interpret the score band (at risk / stable / scaling-ready) and
the single highest-leverage area to fix first.
RELATED: /for/scaling-agencies, /agency-profitability, /agency-operating-system
END CTA links to /product.
```

---

## Notes for the build

- Every tool is genuinely functional — Stitch generates the UI; the calculation logic
  is wired up in code afterward. Keep all math client-side so the tool works instantly
  (Playbook §18.2 SSG requirement, §19 Lighthouse).
- Never gate a tool behind the email form. Email capture is always post-value and
  skippable (Playbook §28.4).
- Tag every lead at capture with source page slug, funnel stage, segment, and UTM
  (Playbook §28.5). Fire the GA4 events from §28.6.
