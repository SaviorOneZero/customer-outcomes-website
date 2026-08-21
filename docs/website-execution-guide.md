# PromiseArc Website Execution Guide

## Purpose

This guide defines the standing execution rules for agents working on the PromiseArc marketing website.

GitHub Issues are the source of truth for **what** to change. This guide defines **how** website work should be selected, implemented, validated, and handed off so agent time is spent on useful, verified progress rather than rediscovering strategy or introducing unnecessary complexity.

The operating goal is simple:

> **Make the public website clearer, more credible, more persuasive, and easier to maintain without drifting from the PromiseArc methodology, market strategy, or actual product.**

Do not duplicate full issue requirements here. Read the relevant issue and its latest comments before making changes.

---

## 1. Source-of-truth hierarchy

For website work, use this order of authority:

1. **The active GitHub issue and its latest comments** for the requested change.
2. **Current repository content** for what is already implemented.
3. **Current PromiseArc business/product sources** from `SaviorOneZero/customer-outcomes-platform` when the issue depends on positioning, terminology, ICP, product meaning, or implementation approach:
   - `docs/promise-arc-methodology.md`
   - `docs/market-strategy-and-validation.md`
   - `docs/outcome-assessment-playbook.md`
   - `docs/demo-and-discovery-guide.md`
4. **Existing PromiseArc website design language** for visual implementation consistency.

Do not invent new product strategy while implementing a bounded website issue.

If issue copy, current site copy, and current strategy conflict, resolve the conflict from the latest authoritative source or document the discrepancy before proceeding.

### Public/private boundary

The confidential founder/company strategic-optionality and acquisition material in the product repository is **not a public messaging source**.

Never expose or allude to:

- founder retirement or personal financial goals;
- acquisition or exit strategy;
- named or implied potential acquirers;
- build-versus-buy strategy;
- acquisition-readiness scorecards;
- confidential strategic-optionality language;
- any other internal-only company planning that is not explicitly approved for public use.

The public PromiseArc story remains customer-first and outcome-first.

---

## 2. Current website execution order

Unless a newer issue or explicit instruction changes this sequence, the current order is:

1. **#7. GTM positioning and narrative**
2. **#1. Homepage density / layout refinement using the revised narrative**
3. **#8. Real PromiseArc product screenshots from the canonical demo portfolio**
4. **#6. Small hero visual defect**
5. **#3. LinkedIn link and other small polish**

Do not spend time perfecting a section that a higher-priority issue is about to substantially reposition, remove, or restructure.

Prefer **one active substantive issue per agent at a time**. Combine issues only when they are genuinely coupled and shared implementation reduces duplicated effort without making validation ambiguous.

When the assigned issue is complete, verified, committed, and handed off, **stop unless explicitly asked to continue**. Do not open a new substantive workstream merely because some execution capacity remains.

---

## 3. Preserve the current architecture

The website is intentionally simple:

- static HTML;
- CSS;
- small vanilla JavaScript enhancements;
- no build step;
- no application framework;
- no dependency runtime;
- straightforward static hosting.

Preserve that simplicity unless a concrete issue explicitly requires a change.

Do not introduce React, Vue, Next.js, a CSS framework, a bundler, a component framework, analytics, a CMS, or another dependency merely because it is familiar or convenient.

For this site, a small clear HTML/CSS/JS change is usually preferable to a new abstraction.

### Scope discipline

When an issue is primarily messaging/copy work, preserve the existing visual composition unless the issue explicitly requests layout changes.

When an issue is primarily layout/density work, preserve the approved messaging unless the issue explicitly requests copy changes.

When an issue is visual polish, do not silently turn it into a broader redesign.

This separation prevents agents from consuming time solving adjacent backlog items out of sequence.

---

## 4. Public messaging rules

The website is a public commercial asset. Copy must be accurate, supportable, and consistent with current PromiseArc strategy.

### Preserve strong core language where it still fits

Examples currently considered strong include:

- **Connect promise to outcome.**
- **Companies know what they sold. Can they prove the customer achieved what they bought?**
- **Activity is not evidence of value.**
- **Evidence over scores.**
- **Renewal should not be the first moment you discover whether a customer received value.**

Do not rewrite good language merely to make a commit look more substantial.

### Current positioning direction

PromiseArc should be presented as an evidence-backed customer-outcome operating / decision layer that works alongside the systems a B2B organization already uses.

The public story should make clear that:

- CRM records commercial context;
- delivery / services systems record implementation work;
- product systems show usage and adoption;
- support systems show friction and incidents;
- Customer Success platforms may manage engagement, workflow, health, and Outcomes;
- those facts and activities do not automatically prove that the customer achieved the business Outcome they purchased;
- PromiseArc keeps the customer Promise, Outcome, Value Path, Evidence, Risks, Actions, cadence, and realized-value conclusion connected.

Do not position PromiseArc as a generic broad Customer Success Platform replacement.

### Important methodology distinction

Preserve this idea wherever relevant:

> **Delivered is not the same as adopted. Adopted is not the same as value realized.**

Do not collapse Delivery, Adoption, and Value into one generic progress or health concept for marketing convenience.

### CTA principle

The primary CTA should normally invite a conversation about the **customer-outcome operating problem**, not present PromiseArc as a generic software demo with no methodology context.

Keep CTA choices simple. Do not create multiple competing conversion paths unless an issue explicitly requires them.

---

## 5. Claims discipline

Never invent or imply proof that does not exist.

Do not fabricate:

- customers, logos, testimonials, quotes, or case studies;
- adoption, retention, NRR, churn, ROI, or other outcome claims;
- analyst recognition, market share, funding, or partnerships;
- available integrations or AI capabilities;
- certifications, compliance, or security claims;
- benchmark data or customer results.

If a capability is planned rather than available, say so clearly or leave it out.

Do not convert a roadmap idea into present-tense product copy.

Do not publish internal-only company strategy, private planning assumptions, or non-public decision material.

---

## 6. Competitive messaging guardrails

Use category contrast, not unsupported competitor attacks.

### Safe direction

- PromiseArc works alongside CRM, Customer Success, Support, Services, delivery, and product systems.
- Activity and adoption do not by themselves prove business value.
- Risk and customer attention should be explainable and evidence-backed.
- PromiseArc preserves the original customer Promise and keeps Evidence and accountable Actions connected to the Outcome.

### Do not say

- Nobody else connects promise to outcome.
- Customer Success platforms cannot manage Outcomes.
- Gainsight only tracks health.
- PromiseArc is the only value-realization platform.
- A named competitor lacks a capability unless the statement is explicitly sourced, current, and appropriate for public use.

When in doubt, make PromiseArc's own operating model clearer rather than diminishing another vendor.

---

## 7. ICP and audience discipline

Do not market PromiseArc as universally relevant to every B2B company.

The strongest current fit is companies with several of these characteristics:

- complex B2B customer relationships;
- meaningful recurring contracts and renewals;
- multiple customer and vendor stakeholders;
- implementation and adoption dependencies;
- formal or informal business cases / success criteria;
- measurable or observable customer Outcomes;
- fragmented post-sale information across multiple systems;
- manual or activity-heavy QBR / EBR / renewal preparation;
- enough economic exposure that proving customer value matters.

Relevant role groups may include:

- Customer / Customer Success leadership;
- Revenue leadership;
- Revenue Operations;
- Services / delivery leadership;
- executive leadership.

Do not imply one title universally owns the problem unless that has been validated.

---

## 8. Outcome Assessment public story

Where the website explains how organizations start, keep the Outcome Assessment concise and commercial rather than turning the site into a consulting manual.

A useful public sequence is:

1. Understand how promise, handoff, value, and renewal work today.
2. Identify where Outcomes, Evidence, ownership, or accountability are lost.
3. Define the Outcome Framework.
4. Test the model with representative accounts.
5. Configure PromiseArc around the approved model.
6. Establish the operating cadence.

Core principle:

> **The technology follows the operating model.**

Do not publish internal implementation detail, pricing hypotheses, workshop mechanics, or confidential planning material unless a specific public-facing decision approves it.

---

## 9. Design and UI rules

The website and application should look like two parts of the same PromiseArc product family.

Preserve the current visual DNA:

- restrained navy / blue / cyan palette;
- clean typography hierarchy;
- precise spacing;
- understated surfaces and borders;
- deliberate use of brand accents;
- modern executive tone;
- consistent icon style;
- strong contrast and accessible interaction.

Do not introduce a website-only visual language simply because a new component could look interesting.

Before adding a new treatment, ask:

> **Does this look like it belongs beside the PromiseArc application?**

Avoid decorative effects, generic startup illustrations, stock photography, mismatched icon libraries, excessive animation, or novelty interaction that does not materially improve comprehension.

---

## 10. Responsive and accessibility standard

Every website change must be considered on desktop, tablet, and phone.

At minimum verify:

- no horizontal overflow;
- headings and body copy wrap cleanly;
- navigation remains usable;
- buttons and links remain easy to tap;
- focus states remain visible;
- keyboard navigation still works;
- mobile menu behavior is intact;
- interactive content does not depend only on hover;
- color is not the only communication mechanism;
- contrast remains adequate;
- reduced-motion behavior remains respected where motion exists;
- long and sparse content states both look intentional.

Do not solve mobile density problems merely by shrinking type or touch targets.

---

## 11. Product screenshots and visual proof

When real product screenshots are introduced, treat them as evidence rather than decoration.

Use only approved fictional canonical demo data. Prefer the canonical demo portfolio from the product repository once it is ready.

Never expose real customers, real contacts, real email addresses, confidential values, internal notes, credentials, admin secrets, or unfinished internal controls.

Prefer screenshots that prove the GTM story, especially:

- Portfolio / management view;
- Customer workspace;
- Outcome workspace;
- Delivery / Adoption / Value distinction;
- Evidence and realized-value validation;
- Risk and accountable Action;
- Executive / renewal proof;
- adoption without value Evidence where the canonical demo supports it.

Do not fake functionality into a screenshot that the product does not actually provide.

Do not capture final marketing screenshots from unstable hand-edited data when a canonical demo-data issue is about to replace it.

---

## 12. Metadata and domain checks

When GTM copy, production domain, or page identity changes materially, review the related metadata rather than changing visible copy only.

Check as applicable:

- `<title>`;
- meta description;
- Open Graph title / description / image;
- social metadata;
- canonical URL;
- `robots.txt`;
- `sitemap.xml`;
- favicon / social preview asset references.

Do not update these mechanically for every tiny copy change. Update them when public positioning or destination has materially changed.

---

## 13. Legal-page guardrails

Privacy and Terms content is not a place to improvise legal policy.

Agents may fix broken links, remove internal publishing notes from public pages, improve clearly non-legal presentation when instructed, and preserve accurate interim disclosures already approved for public use.

Agents must not invent legal commitments, claim compliance not established elsewhere, create contractual promises, or add tracking/privacy assertions that have not been verified.

When legal substance is required, leave it for explicit legal review.

---

## 14. Implementation workflow

### Before editing

1. Read the complete issue and latest comments.
2. Read this execution guide.
3. Inspect the current source and nearby styles/scripts.
4. Inspect the current rendered page before deciding what needs to change.
5. Identify whether the requested change affects messaging, layout, responsive behavior, metadata, navigation, legal pages, or assets.
6. Confirm no higher-priority issue is about to invalidate the work.

### During implementation

1. Make the smallest coherent change that satisfies the issue.
2. Reuse existing classes and patterns where sensible.
3. Avoid unrelated cleanup.
4. Keep HTML semantic and readable.
5. Keep CSS changes localized where possible.
6. Keep JavaScript progressive and minimal.
7. Do not add a dependency for something the current stack can handle simply.
8. Do not implement adjacent backlog issues unless the active issue explicitly requires them.

### Before delivery

1. Run the site locally.
2. Review the changed section in context of the full homepage.
3. Read the full homepage top to bottom after messaging changes.
4. Verify desktop, tablet, and phone layouts.
5. Check navigation and interactive behavior.
6. Check console/runtime for obvious errors where practical.
7. Review the final diff for unrelated changes.
8. Confirm public claims remain defensible.
9. Confirm no internal-only information has leaked into visible copy, source comments, metadata, or assets.

---

## 15. Local verification

Run locally with:

```sh
python3 -m http.server 8000
```

Inspect the site through a browser at:

```text
http://localhost:8000
```

For meaningful UI changes, inspect representative widths such as:

- ~1440px desktop;
- ~1024px tablet / small desktop;
- ~768px tablet;
- ~390px phone.

Do not validate only one desktop viewport.

---

## 16. Branch, PR, deployment, and evidence standard

Respect repository branch protection. Do not bypass protected `main` rules for convenience.

For normal implementation work:

1. use a short-lived issue-scoped branch when required;
2. commit a focused change with a concise message;
3. open a PR against `main` when required by repository policy;
4. verify available checks before merge;
5. merge through the permitted repository workflow;
6. verify the production/static-hosting deployment when the change affects the public site;
7. smoke-check the live site after deployment where practical;
8. update the relevant issue with concise delivery evidence.

A delivery update should include, where applicable:

- commit SHA or PR;
- concise summary of what changed;
- files changed;
- responsive validation performed;
- accessibility / interaction checks performed;
- deployment result;
- production verification;
- anything requiring manual product-owner acceptance.

Do not write long status reports for trivial work. Provide enough evidence that the next person can tell what was delivered and what remains.

---

## 17. Efficiency rules for agents

To conserve development capacity:

- read before editing;
- use the issue and this guide rather than rediscovering decisions;
- do not redesign working areas outside scope;
- do not create speculative variants unless an issue asks for them;
- do not repeatedly rewrite copy that already passed review;
- do not run broad refactors during a small public-site change;
- do not rebuild the architecture for a static-site requirement;
- do not begin another substantive issue when remaining capacity is unlikely to finish and verify it;
- stop once the acceptance criteria are satisfied and the result is verified.

The goal is not maximum code change.

The goal is maximum **credible public improvement per unit of effort**.

---

## 18. Final public-quality check

Before final delivery, read the homepage top to bottom as though encountering PromiseArc for the first time.

Ask:

- Do I understand what problem PromiseArc solves?
- Do I understand why existing systems alone may not answer that problem?
- Do I understand what is distinct about the PromiseArc operating model?
- Do I understand whether my company is a strong fit?
- Do I understand how we would start?
- Does the product feel real and credible rather than conceptual?
- Is every claim supportable?
- Does the copy sound like an experienced B2B operator rather than generic SaaS marketing?
- Is there anything on the page that should not be public?

If the answer to the last question is yes, remove it before delivery.
