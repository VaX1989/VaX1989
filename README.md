# Software, research systems, and experiments

**Shaped by public health, curiosity and AI-assisted development.**

I came to software from a different path. My background is in public health and epidemiology, but I had always wanted to build tools, systems and ideas of my own. AI-assisted development gave me a practical way to cross that gap — turning things that once remained sketches, notes or unrealized concepts into working software.

This GitHub is where those paths now meet. Some projects grow directly from my professional experience in research, epidemiology and public health. Others are deliberately exploratory: publishing systems, persistent worlds, games, digital persons and experiments I simply wanted to see exist.

What connects them is the same impulse: **learning by building, testing ideas against reality, and exploring how far a good idea can be taken.**

**Pietro Corona** · Public health & epidemiology · Building **[Weavidence](#weavidence)** · `VaX1989` is my technical handle.

[Weavidence](#weavidence) · [Elements of Population Health](#elements-of-population-health) · [Editorial works](#editorial-works--production-systems) · [NOIA / FIELD](#noia--field) · [Experimental systems](#experimental-research-systems)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/readme/profile-hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/readme/profile-hero-light.svg">
    <img src="assets/readme/profile-hero-light.svg" width="100%" alt="Portfolio map with Weavidence at the center: Academy connects sources, learning and evidence; Journey connects research decisions to a protocol; Lab connects methods, results and review. Elements of Population Health, editorial works, NOIA FIELD, Personae and One File Universe form the surrounding portfolio.">
  </picture>
</p>

<p align="center"><sub><strong>Portfolio map.</strong> Editorial orientation, not a product-state or validation diagram.</sub></p>

---

## Weavidence

**Tools for learning research methods, designing studies and inspecting how analytical results were produced.**

I am developing Weavidence around a simple constraint: useful outputs should keep a route back to the sources, decisions, data, methods and review context that produced them.

| Surface | What it preserves | Current public state |
|---|---|---|
| **Landing / ecosystem** | The public map of Academy, Journey, Lab and Weavidence Insights | **Public:** [weavidence.com](https://www.weavidence.com/) |
| **Academy** | Versioned knowledge → learning design → learner action → assessment evidence | **Private, pre-production.** [Public product page](https://www.weavidence.com/academy) |
| **Journey** | Research question → explicit decisions → reviewable protocol | **Operational public application.** [Product page](https://www.weavidence.com/journey) · [Open Journey](https://app.weavidence.com/) |
| **Lab** | Dataset → transformations → methods → results → review context | **Private, active development.** [Public product page](https://www.weavidence.com/lab) |

**Journey keeps methodological authority with the researcher.** It supports research design; it is not a clinical decision system, and external scientific validation of the platform is incomplete. Academy and Lab are not presented as publicly available applications.

### Academy × EPH — from knowledge to evidence

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/readme/weavidence-academy-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/readme/weavidence-academy-light.svg">
    <img src="assets/readme/weavidence-academy-light.svg" width="100%" alt="Weavidence Academy system portrait connecting versioned knowledge, learning design, learner action, assessment judgment and evidence while keeping viewed, practised, passed and demonstrated states distinct.">
  </picture>
</p>

<p align="center"><sub><strong>Academy system portrait — not a product screenshot.</strong> Academy is private and pre-production; the visual describes current system semantics, not public availability or external validation.</sub></p>

**Academy** keeps viewing, practising, passing an assessment and demonstrating a capability as different events. **Journey** keeps decisions, findings and exports tied to protocol revision and explicit human confirmation. **Lab** keeps generated explanations separate from the computations and analytical context they describe.

> **Current boundary:** the Weavidence surfaces have different engineering and access states. Internal testing is not external scientific review, validation, adoption or production readiness.

---

<a id="elements-of-population-health"></a>
## Elements of Population Health

### The knowledge estate connected to Weavidence Academy

**Elements of Population Health (EPH)** is a **21-volume independent population-health series** connecting epidemiological methods, public-health practice and the institutions in which decisions are made. Its editorial architecture keeps sources, claims, manuscripts, editions and publication state distinct.

EPH is also the **principal public-health knowledge estate currently integrated with Weavidence Academy**. That relationship links a real scientific/editorial corpus to a governed learning architecture; it does not turn either project into external scientific validation of the other.

<p align="center">
  <img src="assets/readme/eph-21-spine-continuum.svg" width="100%" alt="Twenty-one Elements of Population Health spine panels crossed by one continuous line, representing the 21-volume collection.">
</p>

<p align="center"><sub><strong>21 volumes, one governed collection.</strong> The continuum is a collection-design study, not a claim that this image is the final cover system.</sub></p>

All **21 volumes are complete and published as Amazon KDP paperbacks**. Thirteen also have complete internally governed digital reader editions; digital reader formats for the remaining volumes are still being progressively materialized. Amazon KDP self-publication is distinct from formal scholarly publication.

I use AI for source discovery, argument structure, first drafts, revision, translation, bibliographic checking, editing and production. I direct the work and remain responsible for reading, verification, correction and final editorial judgment. **The books have not undergone external peer review.**

[Books and author page](https://www.amazon.it/-/en/stores/author/B0GGMQBW3X/about)

---

## Editorial works & production systems

The scientific series is the main editorial bridge from Weavidence. Other work explores essay, visual-book and literary-production forms without being folded into the public-health identity.

### Tempo. Libero.

<p align="center">
  <img src="assets/readme/tempo-libero-cover.svg" width="280" alt="Current typographic cover for Tempo. Libero. by Pietro Corona.">
</p>

**A contemporary essay about technology, acceleration and the difference between time saved and the freedom to change direction.**

Its current editorial identity treats the interval between *Tempo.* and *Libero.* as part of the argument: available time becomes freedom only when it still contains real alternatives.

**Editorial candidate / private source repository.**

### L'Atlante dell'Osservatore

<p align="center">
  <img src="assets/readme/atlas-placard.svg" width="390" alt="Museum-like portfolio placard for L'Atlante dell'Osservatore, explicitly not a book cover.">
</p>

An experimental editorial work under active private development, where page architecture, image, typography and narrative continuity are treated as one artistic system.

**The placard above is presentation only — not the current book cover or evidence of publication readiness.** The current project state remains under artistic refoundation and physical validation is not claimed.

### book_creator

**A provenance-first publishing engine for complete literary works.**

`book_creator` keeps **canon → work structure → edition intent → rendering → evidence → release authority** inspectable rather than collapsing them into one opaque pipeline. It is the production environment currently being developed across several independent literary projects.

<p align="center">
  <img src="assets/readme/book-creator-gallery.svg" width="100%" alt="book_creator executed synthetic reference gallery showing conventional prose, research nonfiction, deterministic fixed layout and hybrid composition.">
</p>

<p align="center"><sub><strong>Executed synthetic reference gallery.</strong> Four reference families completed their planned runner steps in the recorded local environment. This does not establish literary quality, clean-room RC readiness, hosted CI success, external conformance, human visual approval or physical print proof.</sub></p>

**Private development · 0.2.0 · PRE-RC.** `book_creator` is intentionally **not** an “AI writes a book” system. Automation may transform, render and verify; literary, editorial and release authority remain human.

---

## NOIA / FIELD

A persistent stealth-investigation game in which evidence has to survive contact with the world. The player's **Subject** follows signals into questions and **Casefiles**, then into **FIELD**: NOIA's embodied physical-operation layer, not a separate game.

<p align="center">
  <img src="assets/readme/noia-lockup.svg" width="420" alt="NOIA Optic OS lockup from the current NOIA design system.">
</p>

<p align="center">
  <img src="assets/readme/noia-direction.svg" width="100%" alt="NOIA and FIELD concept-direction plate showing OPTIC inquiry, WINDOW interpreted world and FIELD physical consequence. It is concept direction, not current gameplay evidence.">
</p>

<p align="center"><sub><strong>Concept direction · not current gameplay evidence.</strong> This profile plate follows the current NOIA presentation vocabulary and private visual-direction work. It communicates intended experience, not implementation proof.</sub></p>

**Signal → Question → Casefile → FIELD → Evidence → accepted consequence**  
↳ Custody, provenance and changes to the Subject and world remain inspectable.

A shutter can break a sightline and make a sound. What is recovered, who has custody and what the operation establishes can alter later possibilities.

**Private development.**

<details>
<summary>OPTIC, WINDOW / EventWeave and FIELD</summary>

**OPTIC** holds the Subject's inquiry and personal continuity. **WINDOW** makes the world interpretable; **EventWeave** is a rebuildable causal/provenance projection, not the authority for persistent state.

A version-pinned **OperationManifest** defines the operation context. FIELD produces an **OperationResult**; NOIA accepts and reconciles it before persistent custody and consequences change. The player cannot simply declare the outcome.

Sensing, observations and evidence constrain what a seeker can know. Hidden world state is not a shortcut to an omniscient opponent.

</details>

---

## Experimental research systems

Parallel software research explores persistence, identity, causality and model authority outside the main Weavidence line.

### Personae

<p align="center">
  <img src="assets/readme/personae-cover.svg" width="100%" alt="Personae readme cover: whole-person character and continuity.">
</p>

Local-first, model-independent infrastructure for a persistent digital **Person**. A proposed change can be reviewed without changing the Person; only an authorized accepted event extends canonical history.

**Proposal → review → authorized acceptance → accepted history**  
↳ Provenance, event time, recorded time and authority remain distinguishable.

Memory, provenance and model output do not automatically become truth.

**Experimental.** Its current repository state is a **2.0.0-beta.5 public-opening candidate**; repository visibility and a GitHub prerelease are separate final transactions. The Person format remains experimental and the specification remains Draft, not Approved.

### One File Universe

<p align="center">
  <img src="assets/readme/ofu-frame-sequence.svg" width="100%" alt="One File Universe deterministic visual witness comparing a rejected flat baseline with three progressively revealed multiscale views. The source itself labels this presentation-only fixture evidence.">
</p>

A persistent, multiscale reality distributed as **one deterministic HTML file**, built from modular source. Its sparse graph separates stable identities from the views materialized for exploration.

**Stable identity → bounded materialization → view → replay**  
↳ Canonical history, provenance and model authority survive a discarded view.

**Experimental.** [Source, build instructions and limits](https://github.com/VaX1989/One_File_Universe).

<p align="center"><sub>OFU visual: deterministic presentation fixture from the repository. It is explicitly presentation-only evidence, not a browser/WebGL capture or scientific evidence.</sub></p>

---

<details>
<summary><strong>Professional context, AI use and institutional boundary</strong></summary>

My current formal healthcare role is **Assistente Sanitario at ASL Cagliari**. My work has included surveillance, health-information flows and quantitative analysis.

I also teach on contract at the [University of Cagliari](https://web.unica.it/unica/page/it/pietro_corona).

From May 2024 to June 2025, I held a separate appointment as **Esperto epidemiologo** at Sardinia's Regional Epidemiological Observatory. My healthcare roles, contract teaching and independent projects are distinct; they do not imply institutional endorsement.

I use AI extensively in software design, coding and review. Its output is not independent validation. Product decisions, correction and release responsibility remain mine.

</details>

For research methods, technical review or collaboration: **[LinkedIn](https://it.linkedin.com/in/pietro-corona-020959108)**.

<sub>Presentation assets in this profile are provenance-classified so that product evidence, system portraits, editorial artwork and concept direction are not silently conflated. See [`docs/presentation/ASSET_PROVENANCE.md`](docs/presentation/ASSET_PROVENANCE.md).</sub>
