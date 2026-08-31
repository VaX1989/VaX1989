# VaX1989 Flagship README Standard

## Repository Front-Door, Product Truth & Evidence Presentation Standard

**Standard ID:** `VAX-FRONTDOOR-README-1.0`  
**Version:** `1.0.0`  
**Date:** `2026-08-31`  
**Status:** `CANONICAL`  
**Scope:** flagship repositories presented under the VaX1989 portfolio  
**Primary families:** Weavidence · NOIA Universe · Editorial Works

---

## 0. Purpose

A flagship repository README is not a file index, an engineering diary, a release note, a backlog, a test report, or a compressed documentation site.

It is the **canonical public front door of a project**.

Its job is to make a serious visitor understand, in progressively deeper layers:

1. **what this project is;**
2. **why it matters;**
3. **what is real today;**
4. **what makes it different;**
5. **what it looks or feels like in use;**
6. **how it works;**
7. **what has actually been verified;**
8. **what has not yet been proven;**
9. **where to go next.**

The README must make the project feel **clearer, stronger and more trustworthy** than the raw repository beneath it, without ever becoming more impressive than the evidence permits.

This standard defines one editorial system for all VaX1989 flagship repositories while allowing each project family to retain its own visual and narrative identity.

---

# 1. Design objective

The target is not a conventional developer README.

The target is a hybrid of:

- a premium product front page;
- an editorial cover;
- a technical abstract;
- an evidence-aware project dossier;
- a precise navigation layer into the repository.

The standard optimizes simultaneously for five audiences:

- a curious visitor deciding whether to continue;
- a technical reviewer deciding whether the project is serious;
- a founder, collaborator or institutional stakeholder evaluating the thesis;
- a domain expert evaluating claims and boundaries;
- the future maintainer trying to recover project truth months or years later.

No one audience is allowed to destroy the experience for the others.

---

# 2. Normative language

The words **MUST**, **MUST NOT**, **SHOULD**, **SHOULD NOT** and **MAY** are normative.

- **MUST / MUST NOT** — required for flagship compliance.
- **SHOULD / SHOULD NOT** — default rule; deviation requires a concrete project-specific reason.
- **MAY** — optional technique when it improves the project rather than decorating it.

A README that satisfies every structural rule but misrepresents project reality is **non-compliant**.

Truth has precedence over aesthetics.

---

# 3. Core doctrine

## 3.1 Front door, not warehouse

The README MUST expose the minimum amount of information necessary to make the next layer understandable.

Long specifications, historical evidence, exhaustive test matrices, migration history, agent handoffs, forensic audit logs and implementation diaries belong in dedicated documents.

The README points to them; it does not become them.

## 3.2 Product before repository

The first screen MUST explain the project as something that exists in the world, not as a folder tree.

Bad opening:

> React/FastAPI monorepo with DDD, CQRS and PostgreSQL.

Better opening:

> A governed research-design system that turns an incomplete study idea into an auditable protocol while keeping methodological authority with the researcher.

Technology follows meaning.

## 3.3 Show before enumerating

For projects with a visual or experiential surface, the README MUST show real product evidence before presenting a long capability list.

A current screenshot, product composition, real rendered spread, gameplay capture, architecture-as-experience diagram or other faithful visual is preferred over decorative artwork.

## 3.4 Thesis before feature count

A flagship project MUST have a recognizable thesis.

The README SHOULD answer:

> What belief about this problem caused this project to be built this way?

Journey's strongest pattern is exemplary: the product is not introduced as a list of protocol features, but through a thesis about governed decisions, visible uncertainty and human authority.

## 3.5 Evidence without evidence theatre

The README MUST distinguish product truth from verification truth.

A long test count is not automatically persuasive. A short, well-scoped statement tied to exact current evidence often is.

The README SHOULD summarize evidence and link to the evidence system. It SHOULD NOT reproduce the evidence system in full.

## 3.6 Public state must be truthful

A visitor MUST never be sent toward:

- a private repository presented as publicly accessible;
- a dead demo;
- a historical release described as current;
- an unavailable product described as operational;
- a design mockup described as a live surface;
- test source described as executed proof;
- internal validation described as external validation.

## 3.7 One canonical narrative

README, GitHub About text, homepage, release metadata, status document, screenshots and social preview MUST describe the same current project identity.

Semantic drift between these surfaces is a release defect.

## 3.8 Distinctive restraint

The portfolio MUST NOT imitate the generic GitHub-profile aesthetic.

Flagship READMEs SHOULD avoid:

- badge walls;
- trophy widgets;
- star-history charts as prestige signals;
- contribution snakes;
- typing-banner gimmicks;
- animated counters;
- stacks of framework logos;
- dozens of tiny external widgets;
- decorative AI-generated UI presented as product proof.

A few functional badges MAY be used when they communicate information that materially changes the reader's decision: release, license, build state, package version or security status.

---

# 4. The 10 / 30 / 120 / 600 test

Every flagship README MUST pass four reading horizons.

## 4.1 Ten seconds — identity

Without scrolling deeply, the visitor must know:

- project name;
- project category;
- core value proposition;
- intended user or world;
- whether there is something real to see or use.

The top region SHOULD contain:

1. title or project mark;
2. one-line proposition;
3. one primary CTA if one exists;
4. one strong real visual;
5. at most a very small number of high-value status indicators.

If the visitor still needs to read architecture, milestone names or internal vocabulary to know what the project is, the README fails the ten-second test.

## 4.2 Thirty seconds — reason to care

The visitor must understand:

- the problem or ambition;
- the project's thesis;
- the main experience or workflow;
- one or two important differentiators.

A strong anti-positioning sentence MAY be used when it clarifies the thesis.

Example pattern:

> **Not a chatbot that writes a protocol.** It governs the decisions that make the protocol coherent.

This technique MUST clarify the category; it MUST NOT be used merely to sound provocative.

## 4.3 One hundred twenty seconds — reality

A serious reader must be able to determine:

- what exists now;
- what the user can actually do;
- the major system model;
- how the project differs from obvious alternatives;
- current operational or publication status;
- important limitations;
- how to try, inspect or understand it further.

## 4.4 Ten minutes — confidence

A technical or domain reviewer must be able to reach, through clear links:

- architecture;
- current status;
- evidence index;
- limitations;
- security/privacy or scientific boundaries where applicable;
- local-development or reproduction instructions;
- repository map;
- license / publication / contribution terms.

The README itself does not need to contain all of this detail. It needs to make the route obvious.

---

# 5. Canonical information architecture

All flagship READMEs share the same **narrative chassis**.

Sections MAY use project-specific titles, but the information order SHOULD remain stable.

## Layer A — Hero / identity

**Required.**

Contains:

- project name;
- one-line proposition;
- optional subline;
- primary CTA if applicable;
- optional secondary CTA to documentation or evidence;
- hero product visual or editorial visual where appropriate.

### Rules

The one-line proposition SHOULD be approximately one sentence and SHOULD be short enough to reuse, with minor adaptation, in the GitHub About field.

The hero MUST NOT begin with:

- version history;
- development methodology;
- internal milestone status;
- framework list;
- long legal text;
- agent instructions.

A critical safety or status warning MAY precede the hero only when a visitor could otherwise materially misuse the project.

---

## Layer B — Proof of reality

**Required for visual products, games and editorial works. Strongly recommended for all others.**

Use one of:

- real application screenshot;
- concise screenshot composition;
- short GIF from real runtime;
- rendered book cover or spread;
- real gameplay capture;
- concrete CLI example;
- benchmark chart when performance is the product claim;
- conformance/interoperability example for a standard.

The first visual SHOULD prove the project's central promise rather than merely display a logo.

### Screenshot truth

Every screenshot or capture MUST be one of:

- current real product state;
- current synthetic/demo state;
- explicitly labelled concept/prototype;
- explicitly labelled editorial candidate.

If synthetic data are used, say so once in a concise caption.

AI-generated marketing images MUST NOT serve as evidence that a feature or product surface exists.

---

## Layer C — Problem and thesis

**Required.**

Usually 2–5 short paragraphs.

Explain:

1. the problem or ambition;
2. why conventional handling is insufficient;
3. the project's governing idea.

For a research/scientific product, this is where methodological authority and uncertainty can be framed.

For a game, this is where the player fantasy and systemic thesis belong.

For an editorial work, this is where the intellectual question and editorial form belong.

Do not start with implementation history.

---

## Layer D — What the project does today

**Required.**

Describe current user-facing or reader-facing capabilities.

Prefer 5–9 meaningful capabilities over an exhaustive inventory.

Each item SHOULD describe an outcome, not a component.

Good:

> Compare candidate study designs while preserving concerns, alternatives and a reasoned human override.

Weak:

> CandidateDesignService, ScoreEngine, OptionBank, ReviewService.

Large capability inventories belong in product documentation.

---

## Layer E — Experience / workflow / mental model

**Required when the project has a meaningful sequence or system loop.**

One concise visual or list should explain the primary journey.

Preferred forms:

- 5–8 stage workflow;
- gameplay loop;
- evidence lifecycle;
- learning cycle;
- editorial production sequence;
- standard interoperability flow.

A Mermaid diagram MAY be used when it clarifies structure better than prose.

The diagram MUST describe the project model, not merely the deployment topology.

---

## Layer F — Why this is different

**Required for flagship projects in a recognizable competitive category.**

Use either:

- a short comparative table;
- 3–5 explicit differentiators;
- one strong contrast statement followed by evidence.

Journey's comparison between conventional protocol generation and governed decision-state is the reference pattern.

A differentiation table MUST compare architectural or product principles, not attack named competitors.

---

## Layer G — Try it / experience it / inspect it

**Required whenever a public or reproducible path exists.**

The CTA hierarchy is:

1. **experience the real thing** — live application, readable edition, playable build;
2. **run or download** — release artifact, self-contained app, package;
3. **reproduce locally** — minimal quick start;
4. **inspect** — documentation or evidence when no runnable public surface exists.

Do not lead a product visitor into local development if a real hosted experience exists.

If the project is private or pre-publication, say so and provide the best truthful alternative.

---

## Layer H — Architecture

**Required for software flagships; optional for purely editorial repositories.**

Architecture SHOULD fit into:

- one system diagram;
- 3–7 architecture principles;
- one compact technology line.

The first architecture diagram SHOULD show **authority and flow**, not every package.

Deep component maps belong in `docs/ARCHITECTURE.md` or equivalent.

The README SHOULD answer:

- what owns canonical state;
- where decisions are made;
- what is derived or rebuildable;
- where external services sit;
- where human authority remains;
- what crosses trust boundaries.

---

## Layer I — Current status, evidence and boundaries

**Required.**

This is the trust layer.

Use one compact status matrix or a short structured block.

It MUST distinguish at least:

- what is currently available;
- what is implemented;
- what has actually been verified;
- what remains incomplete or unvalidated;
- any material non-use or safety boundary.

The README MUST link to the canonical current-status document and, for evidence-heavy projects, an evidence index.

A workflow definition or test command is not evidence that the workflow or test executed.

---

## Layer J — Repository / developer layer

**Required for software repositories; optional for publication-only repositories.**

Keep this concise.

Recommended contents:

- repository map;
- minimal local setup;
- canonical verification commands;
- link to complete developer onboarding.

Large prerequisite guides, environment-variable catalogs and troubleshooting trees SHOULD live outside the README.

Long repository trees MAY be placed inside `<details>` if they are useful but visually heavy.

---

## Layer K — Documentation, governance and legal boundary

**Required where applicable.**

End with a clean map to:

- architecture;
- current status;
- evidence;
- limitations;
- security/privacy;
- scientific status;
- publication status;
- contribution policy;
- license;
- citation information.

Historical mission packets and agent handoffs MUST NOT be primary navigation unless the repository exists primarily to preserve them.

---

## Layer L — Project identity

**Recommended.**

A concise close MAY identify:

- creator / project direction;
- parent ecosystem;
- human-led development model;
- relevant acknowledgements.

This is not the place for a long personal biography.

---

# 6. Project-family overlays

The chassis is universal. The **emphasis** changes by project family.

## 6.1 Weavidence family

Applies to Journey, Academy and Lab.

### Hero priority

1. user / scientific outcome;
2. real product surface;
3. relationship to Weavidence ecosystem;
4. current public availability.

### Must communicate

- governed state rather than fluent output as authority;
- human authority;
- visible evidence and uncertainty;
- product-specific job to be done;
- relationship to the other Weavidence products without making the README an ecosystem brochure.

### Product-specific emphasis

**Journey** — research decision journey, candidate design, revision integrity, review, protocol outputs.  
**Academy** — learner experience, knowledge-to-evidence cycle, canonical experience state, real curriculum/content state.  
**Lab** — governed analytical workflow, data quality, lineage, evidence artifacts, bounded cognitive/AI surfaces.

### Do not lead with

- F0/F1/F2/F3 vocabulary;
- RC history;
- phase-gate internals;
- large capability matrices;
- legacy product naming;
- CI status before product value.

Those remain available below the fold or in canonical engineering documents.

---

## 6.2 NOIA Universe

Applies to NOIA and FIELD.

### Hero priority

1. player fantasy;
2. persistent consequence;
3. what the player actually does;
4. a real visual or experiential proof;
5. only then the OPTIC / WINDOW / FIELD architecture.

### NOIA README must answer rapidly

- Who am I in this world?
- What do I investigate or do?
- What makes one operation matter later?
- How do evidence, interpretation and physical action interact?
- What can I see or play today?

### FIELD README must answer rapidly

- What embodied experience does FIELD create?
- Why is it authoritative rather than merely graphical?
- How does it connect back to the same NOIA world state?

### Architecture rule

`OPTIC → WINDOW/EventWeave → FIELD` is a powerful system model, but it is **Layer E/H**, not the first sentence of the product.

Milestone matrices, M1/M2/M3 gates, `operations.v1`, authority rules and execution evidence remain crucial — but belong after the player/product model has landed.

---

## 6.3 Editorial Works

Applies to *Tempo. Libero.* and *Elements of Population Health*.

### Hero priority

1. title as a work;
2. subtitle / intellectual proposition;
3. cover or real publication spread;
4. author identity;
5. publication status.

The README should initially feel like an **editorial object**, not a build pipeline.

### Tempo. Libero.

Lead with:

- the intellectual question;
- the book's conceptual form;
- a cover/spread;
- current editorial candidate state.

The repository architecture and production system follow later.

### Elements of Population Health

Lead with:

- the canonical title `Elements of Population Health`;
- bilingual scientific-series identity;
- true current volume/publication state;
- representative cover/spreads or reader-edition evidence;
- sourcing, scientific-review and publication boundaries.

Repository names such as `enciclopedia` are technical identifiers, not the public product identity.

### Scientific/editorial boundary

A rendered and internally checked publication is not automatically peer reviewed, externally validated or formally published.

Publication classes MUST be explained in human language, not only internal enum strings.

---

# 7. Visual presentation standard

## 7.1 Visual hierarchy

A flagship README SHOULD have one dominant visual grammar.

Use:

- strong whitespace;
- large, legible imagery;
- restrained accent color;
- short captions;
- consistent aspect ratios;
- project-specific art direction.

Avoid visual noise.

## 7.2 Hero assets

Preferred repository path:

```text
assets/readme/
  hero-light.*
  hero-dark.*
  product-01.*
  product-02.*
  architecture.*
  social-preview.*
```

Images committed in the repository SHOULD be referenced with relative paths.

Where a hero needs different contrast in GitHub light and dark mode, use `<picture>` with `prefers-color-scheme`.

Example:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/readme/hero-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/readme/hero-light.png">
  <img alt="Concise description of the product surface" src="assets/readme/hero-light.png">
</picture>
```

## 7.3 Accessibility

Every meaningful image MUST have useful alt text.

Do not encode critical product truth only inside text baked into an image.

Color MUST NOT be the sole means of distinguishing status.

## 7.4 Screenshot discipline

The first visual set SHOULD normally contain:

- one hero screenshot or composition;
- at most 2–4 supporting surfaces.

A wall of ten screenshots weakens hierarchy.

Use additional galleries only when visual breadth is itself central to the product.

## 7.5 Diagrams

Use Mermaid for living system diagrams when appropriate.

Prefer a diagram that answers a question:

- How does evidence become a protocol?
- How does NOIA move from perception to embodied consequence?
- How does canonical knowledge become learner evidence?

Avoid diagrams whose only purpose is to show that many services exist.

## 7.6 Social preview

Every public flagship SHOULD have a custom GitHub social-preview image.

Target **1280 × 640 px** where possible, with the project name and one recognizable visual idea. It must remain legible when reduced.

The social preview is part of the repository front door and MUST use the same project identity as the README.

## 7.7 External dynamic assets

Remote badges and analytics images introduce availability, privacy and visual-consistency costs.

They SHOULD be kept to an absolute minimum.

Locally committed static assets are preferred for core brand/presentation elements.

---

# 8. Editorial copy standard

## 8.1 Language

For globally oriented software flagships, canonical `README.md` SHOULD be English.

Italian MAY be provided as `README.it.md` when useful.

For intrinsically bilingual editorial/scientific works, language treatment MAY be project-specific, but one canonical navigation model must remain clear.

## 8.2 Opening proposition

The opening line should describe **category + distinctive value**, not ambition alone.

Avoid:

- revolutionary;
- next-generation;
- enterprise-grade;
- state-of-the-art;
- intelligent platform;
- AI-powered;

unless the following sentence makes the term concrete and the evidence supports it.

## 8.3 Paragraph length

Front-door paragraphs SHOULD generally remain short enough to scan.

Prefer one idea per paragraph.

Dense governance prose belongs later.

## 8.4 Link discipline

Every link must have a job.

At the top of the README, prefer no more than roughly five high-value destinations:

- live product / experience;
- how it works;
- architecture;
- current status/evidence;
- limitations/docs.

Do not turn the hero into a sitemap.

## 8.5 Tables

Use tables for genuine comparison or structured status.

Do not use a table where simple prose or bullets would be easier to read.

The strongest permitted uses are:

- conventional approach vs project approach;
- current-status matrix;
- small compatibility matrix;
- compact evidence-state matrix.

---

# 9. Claim and evidence discipline

This section is mandatory policy.

## 9.1 Evidence vocabulary

The following concepts MUST remain distinct when material:

- `DESIGNED` — specified or intended;
- `IMPLEMENTED` — corresponding code/content exists;
- `TEST_SOURCE_EXISTS` — test code exists;
- `TEST_EXECUTED` — a test was actually run;
- `CI_EXECUTED` — hosted CI actually executed relevant repository steps;
- `VERIFIED` / `PASS` — the defined gate passed in the stated environment;
- `PRODUCT_OBSERVED` — a real product/browser/device surface was directly observed;
- `PRODUCTION_VALIDATED` — the relevant production environment was directly validated;
- `EXTERNALLY_VALIDATED` — independent external validation occurred within a defined scope.

A README may use friendlier prose, but MUST preserve these semantic distinctions.

## 9.2 Prohibited evidence laundering

The following transformations are forbidden:

- workflow file exists → CI passed;
- test source exists → feature verified;
- local test passed → production validated;
- internal review passed → external validation;
- rendered manuscript → published work;
- schema exists → interoperability demonstrated;
- AI-generated recommendation → scientific authority;
- code path exists → real user flow observed.

## 9.3 Current-status source

Every flagship repository MUST maintain one canonical current-status source.

Preferred:

```text
PROJECT_STATUS.md
PROJECT_STATUS.json
```

or an equivalent clearly named pair.

The README status summary MUST be derived from or reconciled against that source.

Historical reports MUST NOT silently override current status.

## 9.4 High-consequence domains

Scientific, healthcare, financial and public-health projects MUST state material non-claims near the relevant product claims.

Examples:

- not clinical decision support;
- not tax filing or investment advice;
- internal methodological verification is not external scientific validation;
- prepublication is not peer review;
- synthetic demonstrations are not real patient/user data.

The limitation should clarify the project, not bury it in defensive legal prose.

## 9.5 AI claims

If AI is involved, the README SHOULD identify which of these is true:

- development assistance only;
- optional user-facing assistant;
- bounded runtime component;
- proposal generator;
- non-authoritative summarizer;
- external provider dependency;
- deterministic core with AI outside authority.

"AI-powered" alone is not an acceptable architecture or trust statement.

---

# 10. The README Presentation Manifest

To prevent presentation drift, every flagship redesign SHOULD introduce:

```text
docs/presentation/README_MANIFEST.yaml
```

Recommended contract:

```yaml
standard: vax1989.flagship-readme/v1
project_name: "Example"
project_family: "weavidence | noia | editorial"
project_kind: "product | platform | game | runtime | book | scientific-series"
canonical_readme: "README.md"
canonical_status: "PROJECT_STATUS.md"
canonical_status_machine: "PROJECT_STATUS.json"
primary_cta: "https://example.com"
public_state: "operational | private-development | prepublication | archived"
hero_asset: "assets/readme/hero-light.png"
evidence_index: "docs/EVIDENCE_INDEX.md"
limitations: "docs/LIMITATIONS.md"
last_editorial_review: "YYYY-MM-DD"
```

The manifest does not create truth by itself. It defines which artifacts the README is expected to stay synchronized with.

Repositories MAY add a CI presentation gate that verifies:

- required files exist;
- hero assets resolve;
- top links resolve where network validation is appropriate;
- current version/status identifiers agree;
- forbidden stale product names do not reappear;
- private/public CTAs match declared public state;
- required limitation links exist;
- README language variants point to each other correctly.

---

# 11. GitHub repository metadata standard

A polished README cannot compensate for an empty repository shell.

Every public flagship MUST also configure:

## About

- concise description;
- canonical homepage or live product URL when one exists;
- meaningful repository topics;
- correct visibility and archive state.

The description MUST be semantically consistent with the opening proposition.

## Social preview

Use the custom project social image defined in this standard.

## Releases

When the project ships downloadable artifacts, Releases SHOULD be the canonical download path.

Release assets SHOULD include integrity information where appropriate.

## Citation

Scientific software or publications SHOULD provide `CITATION.cff` when citation is meaningful.

## License truth

The README MUST describe the repository's actual license state.

A private or unlicensed repository MUST NOT be described as open source solely because openness is a future intention.

---

# 12. Progressive disclosure techniques

GitHub Markdown can support a richer presentation without turning the README into a web page clone.

## Recommended

- `<picture>` for light/dark visuals;
- Mermaid for one or two meaningful system diagrams;
- GitHub alerts for truly important `NOTE`, `IMPORTANT` or `WARNING` content;
- `<details>` for long developer/repository material;
- restrained HTML tables for side-by-side product screenshots;
- anchored navigation for long READMEs.

## Not recommended

- excessive HTML layout hacks;
- unreadable nested tables;
- animation for decoration;
- auto-updating external cards that dominate the document;
- critical information hidden inside collapsed blocks;
- decorative diagrams with no explanatory purpose.

Innovation is measured by how effectively the README guides attention, not by how many Markdown tricks it uses.

---

# 13. Length and density

The standard does not impose a rigid word count because a game, scientific platform and book require different detail.

However:

- the project identity and real proof MUST land before deep scrolling;
- internal engineering history SHOULD NOT appear before product meaning;
- a README above roughly 3,000 words SHOULD be reviewed for extraction opportunities;
- a README above roughly 4,000 words requires a deliberate reason;
- large evidence matrices, historical tranches and detailed specifications SHOULD move to dedicated documents.

Journey is the semantic benchmark, not the target length benchmark.

The ideal README is **as deep as necessary, but no deeper than the front door needs to be**.

---

# 14. Canonical documentation neighborhood

A mature flagship SHOULD converge toward a small, predictable set of documents.

Example:

```text
README.md
README.it.md                       # optional
PROJECT_STATUS.md
PROJECT_STATUS.json                # optional but preferred for machine checks
LICENSE                            # if applicable
SECURITY.md                        # if applicable
CITATION.cff                       # scientific/editorial where useful
assets/
  readme/
    hero-light.png
    hero-dark.png
    product-01.png
    architecture.svg
    social-preview.png
docs/
  ARCHITECTURE.md
  EVIDENCE_INDEX.md
  LIMITATIONS.md
  SECURITY_AND_PRIVACY.md
  SCIENTIFIC_STATUS.md             # scientific projects
  PUBLICATION_STATUS.md            # editorial projects
  presentation/
    README_MANIFEST.yaml
```

Not every repository requires every file.

The important property is that **current truth has an obvious home**.

---

# 15. Anti-pattern registry

A flagship README is non-compliant if any of these materially affect its front door.

## P0 — blocking

- stale README describes a materially old product state;
- primary CTA is broken or inaccessible to the stated audience;
- private product is presented as public;
- unsupported production/external-validation claim;
- wrong public project name;
- AI mockup presented as implemented product proof;
- critical scientific/security/publication boundary omitted;
- README claims an open-source status contradicted by repository licensing;
- current-status evidence is known to be stale but presented as current.

## P1 — serious degradation

- no real visual evidence for a visual flagship;
- architecture before the reader understands the product;
- internal milestone vocabulary dominates the first two screens;
- exhaustive feature matrix before thesis/workflow;
- hero contains more navigation than product meaning;
- giant stack/logo wall;
- screenshot gallery without captions or hierarchy;
- history/agent instructions positioned as primary visitor content;
- generic claims such as "enterprise-grade" without concrete meaning.

## P2 — polish debt

- inconsistent capitalization/naming;
- missing alt text;
- excessive badges;
- non-responsive visual assets;
- duplicated links;
- unnecessary tables;
- overly long paragraphs;
- missing social preview;
- stale screenshot labels.

---

# 16. Flagship acceptance score

Each redesigned README receives a 100-point review.

| Dimension | Weight | Standard |
|---|---:|---|
| Instant clarity | 15 | What / who / why understandable in ~10 seconds |
| Product or work proof | 15 | Real, current, meaningful visual or executable proof |
| Thesis and narrative | 12 | Problem and governing idea are memorable and specific |
| Experience / workflow | 10 | Reader understands what actually happens |
| Differentiation | 8 | Distinction is concrete rather than marketing language |
| Truth and evidence discipline | 15 | Claims align with current evidence and status |
| Boundaries / limitations | 8 | Important non-claims are visible and proportionate |
| Architecture legibility | 7 | Authority and flow understandable without implementation dump |
| Navigation / operability | 5 | Try, inspect, run, docs and evidence paths are obvious |
| Editorial / visual craft | 5 | Cohesive, restrained, accessible, project-specific presentation |

### Thresholds

- **95–100** — exceptional flagship front door
- **90–94** — flagship compliant
- **85–89** — strong but not finished
- **75–84** — materially under-presented
- **<75** — redesign required

A P0 blocker prevents flagship compliance regardless of numeric score.

The portfolio target is **95+**, not merely compliance.

---

# 17. README release gate

A flagship README MUST be reviewed whenever any of the following changes materially:

- project name or positioning;
- public/private state;
- primary live URL;
- major user workflow;
- current release or publication state;
- architecture authority;
- core evidence posture;
- scientific/publication limitation;
- license;
- hero product surface.

A major project release is incomplete if the repository front door still tells the previous project's story.

Recommended release checklist:

```text
[ ] 10-second test passes
[ ] 30-second test passes
[ ] 120-second test passes
[ ] hero visual is current and truthful
[ ] public CTA works
[ ] GitHub About description matches
[ ] social preview matches current identity
[ ] README version/status agrees with canonical status
[ ] evidence claims are current and scoped
[ ] limitations are current
[ ] screenshots use safe/demo data where required
[ ] all important links resolve
[ ] light mode checked
[ ] dark mode checked
[ ] mobile GitHub rendering checked
[ ] private/public links checked as an unauthenticated visitor where relevant
[ ] no P0 anti-pattern exists
```

---

# 18. Canonical skeleton

This is a **structure**, not copy to paste unchanged.

```markdown
# PROJECT NAME

One-line proposition.

[Primary CTA] · [How it works] · [Status/Evidence] · [Limitations]

[REAL HERO / PRODUCT / WORK VISUAL]

> Optional high-value positioning statement.

## The problem / idea
Why this exists.

## The thesis
The governing idea that makes the project different.

## What it does today
5–9 outcome-oriented capabilities.

## How it works
Primary user journey / gameplay loop / editorial or evidence lifecycle.

[ONE MEANINGFUL DIAGRAM]

## Why it is different
Comparison or 3–5 concrete differentiators.

## Try / Experience / Read
The fastest truthful path to the work.

## Architecture
One authority-and-flow diagram + principles + compact stack.

## Current status
Small current-state matrix.

> Tests and source existence are not silently promoted into stronger claims.

## Boundaries
Scientific / security / privacy / publication / runtime non-claims.

## Repository and verification
Minimal developer path; deep material linked elsewhere.

## Documentation
Architecture · status · evidence · limitations · security/privacy · publication/scientific status.

## Project identity
Creator / parent ecosystem / relevant development statement.

## License / contribution / citation
Only what actually applies.
```

---

# 19. What this standard deliberately takes from existing work

## Weavidence Journey — primary internal benchmark

Retain:

- immediate product thesis;
- live CTA;
- real screenshot near the top;
- strong anti-positioning sentence;
- explicit problem → thesis structure;
- seven-stage mental model;
- conventional-vs-Weavidence comparison;
- human-authority explanation;
- architecture as authority flow;
- "try it" scenario;
- current-status matrix;
- explicit evidence and limitation boundary.

Improve:

- shorten the permanent front door;
- push Build Week history lower or outward;
- reduce documentation density before the core product story is complete.

## Financial Decision Studio — secondary internal benchmark

Retain:

- immediate category definition;
- real hero screenshot and compact supporting gallery;
- clear local-first proposition;
- quick start and release download path;
- privacy and limitation clarity;
- truthful license language;
- language switch where useful;
- synthetic/example-data caption.

Improve:

- strengthen product thesis and differentiation before feature inventory;
- avoid letting a capability list become the project's identity.

## Weavidence Landing

Retain:

- truthful public-state discipline;
- product-specific art direction;
- claim governance;
- static/no-JS resilience as a technical truth when relevant.

Do not reproduce its publishing-system detail in a product README front door.

## Weavidence Lab / Academy

Retain:

- excellent evidence vocabulary;
- explicit boundaries;
- authority architecture;
- deep repository truth.

Move downward:

- internal tranche vocabulary;
- milestone history;
- large status/capability matrices;
- preflight and agent-facing operational detail.

## NOIA

Retain:

- sharp three-surface architecture;
- exact authority/evidence distinction;
- unusually disciplined anti-scope boundary.

Invert the presentation order:

**player fantasy and experience first; architecture and milestone governance second.**

## Tempo. Libero. / Elements of Population Health

Retain:

- unusually honest publication boundaries;
- editorial-system thinking;
- precise candidate status;
- distinction between reader-facing work and repository-facing production truth.

Add:

- visual editorial proof before production architecture;
- canonical work identity before internal phase language.

---

# 20. External design research incorporated into this standard

This standard is not copied from a public template. It extracts useful principles from several mature approaches.

### GitHub documentation

- README files are the primary repository explanation layer and should make purpose and navigation clear.
- Repository-hosted images should use relative paths.
- GitHub supports `<picture>` with `prefers-color-scheme` for light/dark images.
- Links should be purposeful rather than numerous.
- Repository social previews can use a dedicated image; GitHub recommends a large 2:1 asset, with 1280×640 providing strong display quality.

References:

- https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github
- https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/customizing-your-repositorys-social-media-preview
- https://docs.github.com/en/contributing/style-guide-and-content-model/style-guide

### Standard Readme

Useful retained idea: information should deepen progressively, with title, short description, usage and supporting detail arranged for rapid evaluation.

Reference:

- https://github.com/RichardLitt/standard-readme

This standard intentionally departs from Standard Readme where a flagship product needs stronger visual proof, thesis, evidence state and portfolio presentation than a conventional package/library README.

### Art of README

Useful retained idea: a README should tell the reader what the thing is, show it in action, show how to use it, then provide deeper detail — and it should be as short as it can be without becoming incomplete.

Reference:

- https://github.com/hackergrrl/art-of-readme

### Modern public repositories reviewed

Patterns were inspected in projects including:

- Astral `uv` — exceptionally fast category/value recognition, concrete benchmark proof, immediate installation path;
- Immich — product-first logo/screenshot, demo path, explicit critical warning and clear documentation routes;
- Supabase — short category statement, feature truth, concrete screenshot, architecture path;
- Maybe Finance — large editorial hero and strong application identity;
- Cal.diy — clear boundary/warning state and direct self-hosting orientation.

These are research inputs, not visual templates. VaX1989 flagship repositories should remain recognizably their own.

---

# 21. Final editorial rule

When deciding whether something belongs in a flagship README, ask:

> **Does this help a serious visitor understand the project, trust its claims, experience its value, or reach the next correct layer?**

If the answer is no, move it elsewhere.

The highest standard is not maximum information.

It is **maximum signal, maximum truth, and deliberate depth**.

---

## Canonical maxim

> **Show the work. Explain the thesis. Prove the state. Expose the boundaries. Then let the repository go deep.**
