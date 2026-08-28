# Craft Playbook

**A small operating system for building public work without confusing activity with
evidence.**

Craft Playbook combines GitHub workflow, security review, human-supervised AI, and
proof of work in one repeatable loop:

> **Frame → Build → Verify → Publish**

It is designed for learners and solo builders who want professional habits without
copying an enterprise process they cannot maintain.

## Why this exists

Most starter repositories explain how to create code. Fewer explain when a claim is
supported, when AI output is safe to use, or when unfinished work should remain
private. This playbook treats those decisions as part of the product.

## Start here

1. Read the **[core playbook](PLAYBOOK.md)**.
2. Create a work item with the included **experiment issue form**.
3. Use a focused branch and the **pull request template**.
4. Record evidence using the **[Evidence Ladder](docs/EVIDENCE-LADDER.md)**.
5. Complete the **[Publication Gate](docs/PUBLICATION-GATE.md)** before changing
   visibility or promoting a claim.

## The four parts

| Part | Question | Output |
| --- | --- | --- |
| [Frame](docs/WORK-LOOP.md#1-frame) | What are we solving, and what is outside scope? | Testable outcome and boundaries |
| [Build](docs/WORK-LOOP.md#2-build) | What is the smallest reversible change? | Focused branch and implementation |
| [Verify](docs/WORK-LOOP.md#3-verify) | What evidence survives a skeptical review? | Checks, results, and limitations |
| [Publish](docs/WORK-LOOP.md#4-publish) | Is this useful and safe outside private context? | Approved artifact or explicit hold |

## AI position

AI is a collaborator, not an accountable actor. It may propose, classify, summarize,
or challenge an assumption. A human owns secrets, permissions, merges, external
messages, and publication. See **[AI Boundaries](docs/AI-BOUNDARIES.md)**.

## Repository status

This repository is a **release candidate**. Its content passed an internal review,
but changing visibility remains a separate human decision with transition checks.
See the latest [publication review](reviews/PUBLICATION-REVIEW-2026-08-29.md).

## Reuse

The playbook and templates are available under the [MIT License](LICENSE). Adapt the
process to the risk of your work; do not treat a checklist as a security guarantee.
