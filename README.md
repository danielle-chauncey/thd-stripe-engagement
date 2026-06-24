# The Home Depot × Stripe — 2026 Executive Engagement Plan

A content strategy for positioning Stripe as The Home Depot's long-term payments and innovation partner, delivered as an interactive web experience.

**▶ View the live plan:** _(GitHub Pages link goes here once Pages is enabled)_

---

## What this is

A 2026 executive engagement plan that treats payments as transformational, not transactional — built around The Home Depot's own strategy of becoming one connected company across the do-it-yourself shopper, the professional contractor, the store, and the screen.

The deliverable is an interactive page (`index.html`), not a slide deck. It walks through the thesis, a reusable content system, the customization approach, a day-and-a-half Executive Briefing agenda, the standout moments, and the before/after journey.

## How this repo is meant to be used

Think of this as a **document repository for an executive engagement** — the kind a team keeps and reuses. The live page is the front end; the supporting strategy and research live alongside it.

```
thd-stripe-engagement/
├── index.html                      → the interactive plan (served live by GitHub Pages)
├── strategy/
│   ├── brief.md                    → the case prompt this answers
│   └── engagement-plan.md          → the full written strategy behind the page
└── research/
    └── thd-and-stripe-facts.md     → the verified, cited public facts the plan is built on
```

**To reuse it for another customer or another meeting:**
1. Update `research/` with the new company's public facts.
2. Adjust the strategy in `strategy/engagement-plan.md`.
3. Edit the content in `index.html` (it's a single self-contained file — no build step, no dependencies; the fonts are embedded so it renders anywhere).
4. Push, and GitHub Pages updates the live link automatically.

That is the point: **build the pieces once, keep them in a repo, and re-cut them fast for the next room.**

## Notes

- Single self-contained HTML file. Open `index.html` in any browser, or view the hosted link above.
- Fonts are embedded, so the page renders identically with or without an internet connection.
- This is a **fictional case exercise.** All facts about The Home Depot and Stripe are drawn from public sources (company investor-relations and newsroom pages, stripe.com) and were fact-checked. Figures are company-stated and point-in-time. Not affiliated with, endorsed by, or representing The Home Depot or Stripe. No confidential information is used.
