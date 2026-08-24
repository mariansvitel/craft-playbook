# Core Playbook

Use this page as the shortest complete version of the system.

## 1. Frame

Create one issue that records:

- the observable outcome;
- why it matters now;
- non-goals;
- data and trust boundaries;
- acceptance checks;
- the smallest safe rollback.

If those points are unclear, investigation is the work. Do not disguise it as an
implementation task.

## 2. Build

- Start from an up-to-date default branch.
- Use one focused branch for one outcome.
- Keep secrets and personal data outside Git.
- Prefer a reversible change over a broad rewrite.
- Record a decision when the trade-off will matter later.
- Treat copied and AI-generated material as untrusted until reviewed.

## 3. Verify

Collect evidence before writing the success claim:

- run automated checks appropriate to the change;
- exercise at least one expected failure;
- inspect the final diff, not only the running result;
- record what was not tested;
- map the result onto the [Evidence Ladder](docs/EVIDENCE-LADDER.md).

“It worked once” is a useful observation, not a reliability claim.

## 4. Publish

Complete the [Publication Gate](docs/PUBLICATION-GATE.md). Publication is an explicit
human decision with three valid results:

| Decision | Meaning |
| --- | --- |
| Publish | Required checks pass and the artifact is useful without private context |
| Publish a summary | Raw work stays private; a sanitized, evidence-backed explanation is safe |
| Hold | A failed gate becomes a concrete remediation task |

## Definition of done

A work item is done when its intended outcome and acceptance checks are satisfied.
It is public-ready only when the separate publication review passes. These states
must never be treated as synonyms.
