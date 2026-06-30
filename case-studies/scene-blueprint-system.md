# Case Study: The Scene Blueprint System

## The Problem

Writing *Noeme* meant tracking dozens of scenes across multiple characters, timelines, and emotional arcs — with no formal training in screenwriting or production documentation. Two failure modes kept showing up early on:

1. **Drift** — a visual motif or character rule would mean one thing in an early scene and something slightly different by the time it resurfaced, because nothing centrally owned its definition.
2. **Disposable content** — early scenes felt like setup for later payoff rather than complete experiences in their own right.

The Scene Blueprint Template was built to solve both, without anyone teaching the underlying principles. It was discovered, not studied.

## The System

Two tiers, with a strict division of responsibility:

- **Act/Part summaries** hold anything that repeats: world rules, recurring motifs, character dynamics that apply across many scenes, and a scene map for navigation.
- **Scene blueprints** hold only what's specific to that scene: a numbered Action Flow (the clean physical sequence), Dialogue/Cue Attachments (interpretation, performance notes, line placement), Key Images, and a Scene Summary placed *last* — generated from the structure rather than written first and reverse-justified.

A few specific decisions worth noting on their own:

- **File naming uses gaps of 10** (`10_`, `20_`, `30_`) specifically so scenes can be inserted later without renaming the whole sequence — the same logic behind ID spacing in any system expected to grow.
- **Silent beats only get a `Cue:` field, never `Dialogue: None`.** The absence of dialogue is structurally distinct from the absence of information.
- **Global rules are explicitly forbidden from being repeated in scene files** unless a scene uses them in a specific, different way. This is DRY (don't-repeat-yourself) applied to creative documentation.

## Proof: Spec → Output

Below is a global rule from the **Act 01 — Lucreta** summary, the matching instruction from the **Bedroom Preparation** scene blueprint, and the line it produced in finished prose.

**Global motif rule (Act summary):**
> "The sky is the last part of the outside that remains after the street slips from view... it should feel like freedom, distance, and unreachable life."

**Scene blueprint (local execution):**
> "F07 — The street slips from view first. Lucreta's eyes lift above the rooftops. The bright blue sky remains as the last piece of outside she can still see."

**Finished prose:**
> "Lucreta keeps looking as Vera gently pulls her away from the window. The street slips from view. Her eyes lift. Above the rooftops, a bright blue sky."

The motif's *meaning* lives once, at the global level. The scene blueprint stages it. The prose executes it — without redefining what the sky represents, because it never needed to.

The same traceability holds for dialogue. The blueprint specifies:

> Vera: "Do not tell me you have grown fearful of womanhood at the final hour, dear. You linger so long one might think this marriage burdens you terribly."
> Cue: "Vera is trying to break the silence... trying to pull Lucreta back into the room and out of the fixed gaze."

And the finished screenplay carries the line nearly verbatim, with the physical performance (a hand moving through hair, a practiced smile) built around the cue exactly as specified.

## A Second Lesson: Format-Appropriate Compression

Not every blueprint instruction survives into prose, and that's intentional rather than a failure of the system. The **Wedding Collapse** blueprint stages the fall in eight separate beats — a stumble, a hand reaching the door handle, fingers slipping, a knee striking the floor — because a director or animator needs that granularity to execute the scene physically.

The finished screenplay compresses all of it into a few lines, because a reader doesn't need timing notation — they need the fall to *feel* sudden. The blueprint and the screenplay are two different outputs generated from the same underlying scene, each retaining only what its audience needs and discarding the rest.

That's the same principle behind a single content model feeding multiple format-specific views — a CMS serving both a print layout and a responsive web layout from one source, exposing different fields to each. The data doesn't change. What's surfaced does, deliberately, per output target.

## Why This Matters

Most people who can produce *good output* can't show *the system that reliably produces it*. This blueprint format does both: it's a real documentation discipline (schema design, single-source-of-truth, scalability planning) that was independently necessary to solve a writing problem, and it demonstrably produces traceable, consistent output when followed — while knowing when to deliberately diverge for a different deliverable.
