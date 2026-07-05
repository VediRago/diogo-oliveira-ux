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
- Case studies (5, all complete): Blueprint Systems, Layering as a Method, Stretching, Whole Portfolio Structure, CEM
- Evidence supporting all five case studies, each in its own vault folder

**Planned**

- Vault duplication cleanup: Ecosystem Map's image currently cross-links into Layering's vault folder instead of having its own copy in `vault/whole-portfolio-structure/` — needs `Map.png` duplicated per the "no cross-linking" rule
- Confirm the four Scene Blueprint vault files (`scene-blueprint-template.md`, `act-01-lucreta.md`, `bedroom-preparation.md`, `lucreta.md`) have correct top-of-file return links
- Duplicate the three Blueprint Depth vault files into `vault/stretching/` if any are still only present in Layering's vault folder
- Remove or relocate CEM's internal "pending" note out of public-facing content
- Apply 4 confirmed `PRINCIPLES.md` wording edits: title, opening sentence, and Layered Reading
- People Before System — confirmed as a Narrative Design concept, needs writing there
- Form as Signal — confirmed cut entirely from UX

**Status:** Case studies complete (5 of 5). Remaining work is vault file cleanup and small text edits, not content or architecture.

**Notes**

- UX Portfolio is now the reference implementation informing the Layer 2 Blueprint extraction; Narrative Design Portfolio remains intentionally provisional until that Blueprint exists.
- Treasure → Key → Treasure is not a standalone UX case study — it's a Noeme-specific concept, referenced within the Stretching case study.
- CEM appears both as its own Layer 4 repo (direct link from Layer 1) and as UX case study #5 — reachable both ways by design.

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
- Fix README heading — currently still shows old repo name (`diogo-oliveira-noeme-production-systems`)

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

**UX Portfolio Cleanup**

- [ ] Duplicate Ecosystem Map image into `vault/whole-portfolio-structure/` and update the image link
- [ ] Remove or relocate CEM's internal "pending" note out of public-facing content
- [ ] Apply confirmed `PRINCIPLES.md` wording edits
- [ ] Confirm Vault return links after final cleanup

**Publishing**

- [ ] Founding Era — content written but sitting in Narrative Design repo; migrate to its own repo, then link from Layer 1
