# Work Loop

The loop is intentionally small enough to repeat on every meaningful change.

## 1. Frame

Write the problem as an observable difference between the current and desired state.
Add non-goals to protect the task from expansion. Identify data, identity, permission,
and external-system boundaries before choosing tools.

Useful framing sentence:

> After this change, **who** can do **what**, under **which boundary**, demonstrated
> by **what evidence**?

## 2. Build

Choose the smallest change that can test the important assumption. Keep the branch
focused and commits explainable. Prefer local or synthetic data while behavior and
trust boundaries are still uncertain.

Stop and re-frame when implementation reveals a materially different problem.

## 3. Verify

Verification has four layers:

1. **Behavior** — does the intended path work?
2. **Failure** — does an important invalid or adversarial case fail safely?
3. **Change** — does the diff contain only the intended scope?
4. **Claim** — does the evidence support the wording used in documentation?

Record negative results. They narrow uncertainty and often provide stronger learning
evidence than a polished screenshot.

## 4. Publish

Review the artifact as an outsider would receive it. Remove dependence on private
context, scan the complete Git history for secrets, confirm ownership and licensing,
and state current limitations.

Public visibility is a product change: it expands the audience and threat surface.
Use the [Publication Gate](PUBLICATION-GATE.md) even when the code itself did not
change.

## Loop again

Link the published evidence back to the original issue. Convert unresolved risks into
new, bounded work items rather than hiding them in a vague future-work paragraph.
