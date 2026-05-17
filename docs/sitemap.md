# AgencyFlo — Site Map

Reviewed and consolidated from Playbook §28 (lead-magnet sitemap), §8 (site
architecture), and §26 (90-day build sequence). This is the build-ready site map:
every page tagged with type, funnel stage, lead-capture mechanism, build wave,
and the Google Stitch prompt that designs it.

Stitch prompts referenced below live in `docs/stitch-prompts.md`.

---

## 1. Site map at a glance

```
/                                  Homepage
├── /manifesto                      Long-form story
├── /product                        Product overview
│   ├── /product/dashboard
│   ├── /product/projects-and-tasks
│   ├── /product/time-tracking
│   ├── /product/clients-crm
│   ├── /product/documents-proposals-contracts
│   ├── /product/invoices
│   ├── /product/team-access
│   ├── /product/white-label
│   └── /product/flow-ai
├── /pricing
├── /about
├── /reviews
├── /changelog
├── /early-access
├── /security
│
├── /agency-operating-system        Pillar 1
├── /agency-profitability           Pillar 2
├── /closed-loop-system             Pillar 3
│
├── /vs                             Comparison hub
│   ├── /vs/productive
│   ├── /vs/teamwork
│   ├── /vs/scoro
│   ├── /vs/notion
│   ├── /vs/clickup
│   ├── /vs/asana
│   ├── /vs/monday
│   ├── /vs/kantata
│   ├── /vs/productive-alternatives
│   ├── /vs/teamwork-alternatives
│   ├── /vs/scoro-alternatives
│   ├── /vs/clickup-alternatives-agencies
│   ├── /vs/notion-alternatives-agencies
│   ├── /vs/productive-vs-teamwork-vs-agencyflo
│   ├── /vs/productive-vs-scoro-vs-agencyflo
│   └── /vs/teamwork-vs-scoro-vs-agencyflo
│
├── /for                            Segment hub
│   ├── /for/design-agencies
│   ├── /for/dev-agencies
│   ├── /for/marketing-agencies
│   ├── /for/ai-agencies
│   ├── /for/branding-agencies
│   ├── /for/ecommerce-agencies
│   ├── /for/strategic-consultants
│   ├── /for/small-agencies
│   ├── /for/scaling-agencies
│   ├── /for/freelancers
│   └── /for/multi-project-entrepreneurs
│
├── /tools                          Free tools hub (lead magnets)
│   ├── /tools/profitability-calculator
│   ├── /tools/tool-stack-audit
│   ├── /tools/agency-rate-calculator
│   ├── /tools/proposal-template-generator
│   ├── /tools/agency-margin-leak-finder
│   ├── /tools/team-capacity-planner
│   ├── /tools/contract-clause-library
│   ├── /tools/agency-pricing-calculator
│   ├── /tools/client-onboarding-checklist
│   └── /tools/agency-health-score
│
├── /blog                           Blog index
│   └── /blog/[slug]
├── /guides
├── /glossary
├── /case-studies
├── /resources/state-of-agency-operations
│
└── Legal: /terms · /privacy · /dpa · /security · /status
```

---

## 2. Top-level pages

| URL | Type | Funnel stage | Primary CTA | Lead capture | Stitch prompt |
|---|---|---|---|---|---|
| / | Homepage | All | Get early access | Waitlist | Homepage |
| /manifesto | Long-form story | Problem → Solution-aware | Read / Get early access | Newsletter + waitlist | Blog article (long-form variant) |
| /product | Product overview | Solution → Product-aware | See how it works | Waitlist | Product overview |
| /pricing | Pricing | Decision | Get early access | Direct apply | Pricing |
| /about | Founders + studio | All | Get early access | Waitlist | Blog article (story variant) |
| /reviews | G2/Capterra aggregator | Decision | Get early access | Direct apply | Comparison (light variant) |
| /changelog | Public momentum | Existing audience | Subscribe | Newsletter | Blog index variant |
| /early-access | Single-purpose signup | Decision | Apply now | Direct apply form | Forms |
| /security | Trust page | Decision | Get early access | Direct apply | Product overview (trust variant) |

## 3. Pillar pages

| URL | Funnel stage | Primary CTA | Lead capture | Stitch prompt |
|---|---|---|---|---|
| /agency-operating-system | Solution-aware | Read pillar / Try free tool | Newsletter + tool link | Pillar page |
| /agency-profitability | Solution → Product-aware | Calculate your profitability | Free tool (embedded) | Pillar page (profitability variant) |
| /closed-loop-system | Solution-aware | Get early access | Waitlist | Pillar page |

## 4. Product deep-dives

All use the **Product deep-dive** Stitch prompt. CTA: Get early access (waitlist),
except /product/documents-proposals-contracts which also links the proposal generator.

`/product/dashboard` · `/product/projects-and-tasks` · `/product/time-tracking` ·
`/product/clients-crm` · `/product/documents-proposals-contracts` · `/product/invoices` ·
`/product/team-access` · `/product/white-label` · `/product/flow-ai`

## 5. Comparison pages

Highest GEO leverage (~33% of AI citations). All use the **Comparison** Stitch prompt.

- **Head-to-head** (/vs/[competitor]) — direct apply CTA: productive, teamwork, scoro,
  notion, clickup, asana, monday, kantata
- **Alternatives listicles** (/vs/[competitor]-alternatives) — free tool + waitlist CTA:
  productive-alternatives, teamwork-alternatives, scoro-alternatives,
  clickup-alternatives-agencies, notion-alternatives-agencies
- **Three-way matrices** — direct apply CTA: productive-vs-teamwork-vs-agencyflo,
  productive-vs-scoro-vs-agencyflo, teamwork-vs-scoro-vs-agencyflo

## 6. Segment / user-type pages

All use the **Segment** Stitch prompt. CTA is segment-tagged so lead source is tracked.

| URL | Target user | Primary CTA |
|---|---|---|
| /for/design-agencies | Design studio owner | Get early access |
| /for/dev-agencies | Dev shop owner | Get early access |
| /for/marketing-agencies | Marketing agency owner | Get early access |
| /for/ai-agencies | AI agency owner | Get early access |
| /for/branding-agencies | Branding agency owner | Get early access |
| /for/ecommerce-agencies | Ecommerce / Shopify agency owner | Get early access |
| /for/strategic-consultants | Strategy consultant or consultancy | Get early access |
| /for/small-agencies | 3–8 person agency | Calculate your savings (free tool) |
| /for/scaling-agencies | 15–30 person agency | Apply for early access |
| /for/freelancers | Multi-client freelancer | Try the rate calculator (free tool) |
| /for/multi-project-entrepreneurs | Multi-project founder | Get early access |

## 7. Free tools — the lead-magnet engine

All use the **Free tool** Stitch prompt. Each tool has its own dedicated, paste-ready
prompt in `docs/stitch-prompts.md` §T1–T10. Never gate the tool itself — optional
email capture only after the tool delivers value.

| URL | What it does | Target user | Lead path |
|---|---|---|---|
| /tools/profitability-calculator | Real project margin incl. tool cost, admin overhead, context-switching loss | Any agency owner | → /agency-profitability |
| /tools/tool-stack-audit | Scores current tool stack: overlap, gaps, monthly cost, time waste | Any agency owner | → /agency-operating-system |
| /tools/agency-rate-calculator | True hourly rate incl. overhead, taxes, time off, margin | Solo + small agency | → /for/freelancers |
| /tools/proposal-template-generator | AI-assisted project proposal from a brief | Any agency owner | → /product/documents-proposals-contracts |
| /tools/agency-margin-leak-finder | 10-question assessment finding where margin leaks | Any agency owner | → /agency-profitability |
| /tools/team-capacity-planner | Drag-and-drop capacity planning for a project pipeline | 5+ person agency | → /for/scaling-agencies |
| /tools/contract-clause-library | 30+ agency contract clauses with explanations | Any agency owner | → /product/documents-proposals-contracts |
| /tools/agency-pricing-calculator | Project price from hours, team rate, target margin | Any agency owner | → /agency-profitability |
| /tools/client-onboarding-checklist | Editable interactive client-kickoff checklist | Any agency owner | → /for/scaling-agencies |
| /tools/agency-health-score | 25-question agency health assessment with scored output | Agency owner planning to grow | → /for/scaling-agencies |

## 8. Resources

| URL | Type | Stitch prompt |
|---|---|---|
| /blog | Blog index | Blog index |
| /blog/[slug] | Article | Blog article |
| /guides | Gated long-form | Pillar page (gated variant) |
| /glossary | Entity-rich definitions | Blog index variant |
| /case-studies | Customer stories | Comparison (case-study variant) |
| /resources/state-of-agency-operations | Annual research report | Pillar page |

## 9. Legal / trust

`/terms` · `/privacy` · `/dpa` · `/security` · `/status` — plain templated pages,
no dedicated Stitch prompt needed (use a simple legal-page layout).

---

## 10. Build order (from Playbook §26 — graduated launch, no bulk publishing)

**Wave 1 — Days 1–14 (foundations + first pages)**
Homepage · /pricing · /about · /manifesto · /vs/productive ·
/vs/productive-alternatives · 2–3 free tools (profitability-calculator,
tool-stack-audit, agency-margin-leak-finder)

**Wave 2 — Days 15–30 (comparison surge)**
/vs/teamwork · /vs/scoro · /vs/notion · /vs/clickup · /vs/teamwork-alternatives ·
/vs/notion-alternatives-agencies · /vs/productive-vs-teamwork-vs-agencyflo ·
/closed-loop-system

**Wave 3 — Days 31–60 (pillars + segments)**
/agency-operating-system · /agency-profitability · 6 cornerstone cluster articles ·
/for/design-agencies · /for/dev-agencies · /for/marketing-agencies ·
/tools/profitability-calculator (pillar-embedded) · /vs/asana · /vs/monday ·
/vs/kantata · /vs/clickup-alternatives-agencies · /vs/productive-vs-scoro-vs-agencyflo

**Wave 4 — Days 61–90 (authority build)**
6 more cluster articles · /product/flow-ai · /product/invoices · /product/dashboard ·
/for/ai-agencies · /for/small-agencies · /for/freelancers · /tools/tool-stack-audit ·
/vs/teamwork-vs-scoro-vs-agencyflo

**Beyond day 90** — remaining product deep-dives, /for/ pages, tools, blog clusters,
legal pages, then switch to refresh/compound cadence.

---

## 11. Review notes — gaps and recommendations

Observations from reviewing the Playbook §28 sitemap against §8/§26:

1. **No `/vs` hub landing page.** The playbook lists individual /vs/ pages but no
   index. Add `/vs` as a comparison hub — it captures "agencyflo alternatives"-type
   queries and gives every comparison page a SIDEWAYS link target.
2. **No `/for` hub landing page.** Same gap. Add `/for` as a segment hub for internal
   linking and "agency software for [type]" head queries.
3. **No `/tools` hub landing page.** §29.2 homepage section 8 previews 3 tools, but
   there is no `/tools` index. Add one — it concentrates link equity across 10 tools
   and is itself a citable "free agency tools" listicle.
4. **Pillar cluster articles not in the sitemap tables.** §8.2–8.4 name ~17 cluster
   article slugs under /blog/. They should be tracked in the content calendar; listed
   here only as `/blog/[slug]` for brevity.
5. **/careers** is future — left out of the build waves intentionally.
6. **Three hub pages above (`/vs`, `/for`, `/tools`)** are the only structural
   additions recommended. Everything else in §28 is sound.

Recommendation: add the three hub pages to Wave 1–2. They are low-effort, high-leverage
for internal linking and crawl depth (Playbook §9.3 — three-clicks-to-anything rule).
