↩ [Return to Whole Portfolio Structure](https://github.com/VediRago/diogo-oliveira-ux/blob/main/case-studies/whole-portfolio-structure.md)

# Portfolio Layer Inventory

**Purpose:** Tracks the current state of the portfolio ecosystem — what has been implemented and what is planned.

**Governed by:** Layer System Blueprint.

**Updated:** Whenever repositories or architectural decisions change.

This document records the current implementation. It does not define architecture. Architectural rules belong in the Layer System Blueprint and the layer-specific blueprints.


## Layer 1 — Identity Hub

**Repo:** `github.com/VediRago/diogo-oliveira`

**Purpose:** Orients the reader. Answers "who is this, and where do I go from here." Nothing else.

**Implemented**

- Repository created

- Framing statement written ("How to make complexity approachable")

- Constraint context written (factory job, self-taught, evening-hours work)

- README links to UX Portfolio, Narrative Design Portfolio, NOEME, and Founding Era

- GitHub description and topics set

**Planned**

- Link Joe, CEM, and Noeme Systems from the hub — currently only four of the seven downstream repos are linked

- Pin `diogo-oliveira` on the GitHub profile — still absent from the 6 pinned repos as of last check

**Status:** Near Complete — content written, missing links to Joe/CEM/Noeme Production Systems and profile pin


## Layer 2 — Method

Governed by the Layer 2 Blueprint. Each repository follows the Layer 2 architecture while applying it to its own professional domain.

### 2a. UX Portfolio

**Repo:** `github.com/VediRago/diogo-oliveira-ux`

**Implemented**

- README — framing statement, reading path, links to Home and Narrative Design Portfolio

- `PRINCIPLES.md`

- Case studies (4): Layering as a Method, Blueprint Systems, Stretching, Form as Signal

- Evidence supporting active case studies

**Planned**

- Case study lineup finalized at 5: (1) Layering as a Method, (2) Blueprint Systems, (3) Stretching, (4) Whole Portfolio Structure — the Layer System itself: why the layers exist, how they were built, the concept behind them, (5) CEM — closing case study

- Whole Portfolio Structure case study — not yet written

- CEM as closing case study — reverses the earlier "CEM stands alone, not a UX case study" decision. CEM keeps its Layer 4 standing and gets its own direct link from Layer 1, but is *also* referenced as UX case study material, so it's reachable both ways: through UX (for someone who wants to see the structural thinking) and directly (for someone who just wants CEM itself)

- Treasure → Key → Treasure will not be a standalone UX case study — it's a Noeme-specific concept, to be mentioned/referenced within the Stretching case study rather than written up separately

- Form as Signal — confirmed out of the numbered case study lineup; still pending whether it's cut entirely or moved to Narrative Design Portfolio

**Status:** Near Complete — 3 of 5 finalized case studies written; Whole Portfolio Structure and CEM remain

**Notes**

- People Before System is confirmed as a Narrative Design concept, not UX — moving there instead of appearing in this repo.

- Form as Signal placement is UNRESOLVED AGAIN — earlier marked resolved (staying in UX as case study #4), but author has now said to remove it. Still needs a decision: cut entirely, or move to Narrative Design Portfolio (its craft/prose focus may fit there better).

- UX Portfolio is being developed first and will directly inform the Layer 2 Blueprint; Narrative Design Portfolio is intentionally provisional and will be refit to match once that Blueprint exists.

- UX README link to Narrative Design Portfolio — fix confirmed by author, pending verification it's live.

### 2b. Narrative Design Portfolio

**Repo:** `github.com/VediRago/diogo-oliveira-narrative-design`

**Implemented**

- README — framing statement, playable prototype link, "start here" reading path

- Case studies (5): The First Note (origin), Building a World to Test Quest Design, Building a Modular Narrative Method, Testing the Method Through Layered Reactivity, Noeme — Layered Narrative System

- Playable prototype: Layer Test Twine Prototype (hosted via GitHub Pages), testing layered reactivity through city state, faction pressure, local behavior, NPC memory

- `vault/development-diary/` — dated process notes and decisions (this is the repo's actual implementation of what the Inventory previously called `process-log/`)

- Prose Series: The Founding Era, currently living inside this repo at `/The Founding Era`

**Planned**

- `PRINCIPLES.md` — not yet written

- Move The Founding Era prose out of this repo into `diogo-oliveira-the-founding-era`

- People Before System — confirmed as a Narrative Design concept (moved from UX Portfolio consideration)

- Revisit structure to fit the Layer 2 Blueprint once it's written (intentionally provisional until then, per author's own note)

**Status:** Content Substantial, Structure Provisional — case studies and prototype are live; final structural shape awaits the Layer 2 Blueprint

**Notes**

- Layered Narrative System is confirmed as living here (case study), resolving part of the earlier Noeme Systems sort-pass question. Stretching and Reader Reward placement is still open; Treasure → Key → Treasure confirmed as a Noeme concept (referenced inside UX's Stretching case study, not a standalone case study anywhere).

- Author intends to revisit this repo's structure only after UX Portfolio is finished and the Layer 2 Blueprint exists — current shape should be read as functional, not final.

### 2c. Noeme Production Systems

**Repo:** `github.com/VediRago/diogo-oliveira-noeme-systems`

**Purpose:** The systems behind producing Noeme — cosmology, structure, and production reference.

**Implemented**

- Repository created

- Description and topics set (cosmology, screenwriting, methodology, worldbuilding, narrative-design)

**Planned**

- Migrate from NOEME repo: `Unity/`, `05_METHOD.md`, `Blueprints/`, `Prose/` (chapters 01–10) and prose samples

- Cosmology

- Unity Explained

- Luck vs Outcome

- Bridge Index (Misdirection Bridges, Visual Motif Bridges, Structural/Behavioral/Emotional Bridges)

- Act Emotional Map

- Scene Blueprint Template

- Camera-movement blueprint layer

- Fix README heading — currently still shows old repo name (diogo-oliveira-noeme-production-systems)

**Status:** Established (metadata only — no content migrated yet)

**Notes**

- Repo scope confirmed as Layer 2 (method), not Layer 4 — this documents *how Noeme was built*, not a singular standalone artifact.


## Layer 3 — Product

**Purpose:** Presents completed work directly. No explanatory layer sits between the reader and the work.

| Project | Repository | Status |
| - | - | - |
| Founding Era | `github.com/VediRago/diogo-oliveira-the-founding-era` | Repo created — content exists but currently lives in Narrative Design repo, migration pending |
| NOEME | `github.com/VediRago/Noeme` | Active — scope confirmed as pilot-ready only |
| Joe | `github.com/VediRago/diogo-oliveira-joe` | Repo created — no content yet |


**Notes**

- NOEME final scope: pitch, teaser, pilot bible, and screenplay samples only. `Unity/`, `05_METHOD.md`, `Blueprints/`, and `Prose/` (plus prose samples) move to Noeme Production Systems.

- Founding Era prose (following Rutare Ventari's final recollections — House Ventari's rise, the exploitation of Viriatus, the origin of Regulatus) is written and currently lives at `diogo-oliveira-narrative-design/The Founding Era` — migration to its own repo is confirmed but not yet done.

- Joe has repo, description, and topics set, but no README content or journal entries yet.


## Layer 4 — Singular Projects

**Purpose:** Exempt from cross-project consistency rules by design. Each project sets its own internal structure.

| Project | Repository | Status |
| - | - | - |
| Capability Evidence Model (CEM) | `github.com/VediRago/CEM` | Active |


**Notes**

- CEM uses its own internal Blueprint methodology (v1.2), not the Layer 2/3 blueprints.

- CEM is now also planned as a UX Portfolio case study (structural/methodology angle), in addition to its direct Layer 1 link — reachable both through UX and independently, by design.


## Open Decisions Tracker

**Architecture**

- [ ] Migrate `Unity/`, `05_METHOD.md`, `Blueprints/`, and `Prose/` (+ samples) from NOEME repo into Noeme Systems — scope confirmed, migration not yet done

- [ ] Layer 3 Blueprint — still not written (referenced by the Layer System Blueprint's completion checklist)

- [ ] Pin `diogo-oliveira` (Layer 1 hub) on the GitHub profile — currently absent from the 6 pinned repos

- [ ] Link Joe, CEM, and Noeme Systems from the Layer 1 README — currently only 4 of 7 repos are linked

- [ ] Sort remaining Noeme Systems material — decide whether Stretching and Reader Reward stay there or move to Narrative Design Portfolio as transferable methodology (Treasure → Key → Treasure resolved: stays a Noeme concept, referenced in UX's Stretching case study)

- [ ] Fix Noeme Systems README heading — still shows old repo name

- [ ] Fix Founding Era's GitHub description — currently says "screenplay pilot," confirmed to actually be a prose series

**Content**

- [ ] Write content for Joe (currently repo shell only — description/topics set, no journal entries)

- [ ] Write `PRINCIPLES.md` for Narrative Design Portfolio — not yet done

- [ ] Write People Before System case study for Narrative Design Portfolio

- [ ] Write content for Noeme Systems beyond the migrated files (Cosmology, Unity Explained, Luck vs Outcome, Bridge Index, Act Emotional Map, Scene Blueprint Template, camera-movement layer)

- [ ] Write Whole Portfolio Structure case study for UX (the Layer System itself)

- [ ] Write CEM case study for UX (structure/methodology angle) — CEM keeps its Layer 4 standing but also becomes reachable through UX

- [ ] Form as Signal — cut from UX entirely, or move to Narrative Design Portfolio? (still open)

**Publishing**

- [ ] Founding Era — content written but sitting in Narrative Design repo; migrate to its own repo, then link from Layer 1
