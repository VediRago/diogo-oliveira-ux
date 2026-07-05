↩ [Return to Blueprint Systems](../../case-studies/blueprint-systems.md)

# Supporting File Blueprint

## Purpose

Defines the structure and rules governing supporting files across the portfolio ecosystem.

Supporting files exist to deepen understanding without interrupting the flow of a primary document. They provide reference material that is better linked than explained inline.

## Core Principle

Primary documents teach.

Supporting files support.

If a supporting file begins reteaching its parent document, information has been duplicated instead of referenced.

## Compression vs. Overlap

A supporting file may borrow a concept, example, or piece of canon that also appears elsewhere in the wider body of work. That's not automatically overlap.

The test: does the borrowed material serve this file's own question, or does it drift into answering a different file's question?

If a supporting file about Qalm borrows a moment from Kael's story to demonstrate a limitation Qalm itself has, that's healthy compression — the file stays focused on what Qalm is, using the character moment as evidence, never expanding into that moment's emotional function, imagery, or its own separate mechanics. The complete version of that material stays owned by wherever it actually belongs: the case study built around it, or the primary work itself. The supporting file only borrows the sliver needed to answer its own question.

Overlap happens when a supporting file stops borrowing and starts explaining — when it begins covering ground that another document already owns as its main subject, rather than using that ground briefly as evidence for something else.

## Ownership

Every supporting file belongs to exactly one primary document.

The owner may be:

- a Case Study
- a Blueprint
- another primary document

Other documents may reference it.

Ownership remains singular.

## Structure

A supporting file answers one specific question.

Typical supporting files include:

- definitions
- method summaries
- templates
- examples
- reference material
- implementation details

Supporting files should avoid combining unrelated subjects.

## Navigation

Every supporting file begins with a return link to its owning document.

The return link is the first line of the file.

Nothing appears above it.

Supporting files should never become navigation dead ends.

Example:

```md
↩ Return to Layering as a Method
```

## Duplication

Navigation may duplicate.

Information should not.

Duplicate copies may exist when required to preserve navigation or repository structure.

Only one copy is considered authoritative.

## Relationship

Supporting files deepen a Case Study's explanation. They do not own or present raw evidence themselves. Raw evidence remains attached to the owning Case Study.

```text
Layer
    ↓
Case Study
    ├──→ Supporting File   (explanation)
    └──→ Vault             (evidence)
```

Evidence stays tied to the Case Study, so a reader always reaches raw evidence with the case study's framing already in place. A supporting file that links straight to evidence risks sending the reader further down without that context.

Supporting files provide focused depth without interrupting the primary document.

## Completion Checklist

A supporting file is complete when it:

- supports exactly one primary document
- answers one specific question
- begins with a return link
- contains no duplicated explanation from its parent
- links to no raw evidence directly — evidence stays on the owning Case Study
- can be understood independently
- naturally returns the reader to its owner

## Physical Location

The Supporting File Blueprint defines the role of an artifact, not where it is stored.

Supporting files may live inside a Vault when that Vault exists to support the same primary document.

Folder structure is an implementation decision.

Artifact role is an architectural decision.
