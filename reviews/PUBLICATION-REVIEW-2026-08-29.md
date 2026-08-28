# Publication Review — 2026-08-29

## Decision

**Hold for controlled public-release transition.**

The repository content is suitable for publication. The hold exists only because
changing visibility requires explicit owner approval and two GitHub features can be
verified only during or after the transition to public visibility.

## Evidence reviewed

- purpose, audience, status, workflow, limitations, contribution guidance, and
  security guidance are documented;
- all local Markdown link targets resolve;
- the complete reachable local history, including the pre-squash review commit, was
  scanned with no credential patterns or sensitive filenames found;
- GitHub reports one remote branch (`main`), zero webhooks, zero deploy keys, zero
  Actions secrets, and no GitHub Pages site;
- GitHub recognizes the license as MIT;
- the repository contains documentation and templates only, with no runtime
  dependencies, executable automation, external writes, or AI API calls;
- the Issue Form matches GitHub's documented required structure and field rules;
- the only external repository link is the GitHub private vulnerability-reporting
  route.

## Publication Gate

### Content and value

- [x] Purpose, audience, status, setup, validation, and limitations are clear.
- [x] The artifact is useful without access to private context.
- [x] Claims match the documented Evidence Ladder.
- [x] Local links and examples were checked.

### Secrets, data, and identity

- [x] Current files and complete reachable history were scanned for credentials.
- [x] No personal, customer, employer, or confidential data is included.
- [x] Examples are synthetic and do not resemble active credentials.
- [x] Local environment and common key files are ignored.

### Ownership and maintenance

- [x] The content is original or standard MIT license text.
- [x] GitHub recognizes the repository license as MIT.
- [x] Contribution, conduct, security, and maintenance expectations are documented.
- [x] Release-candidate status is visible in the README.

### Software and AI risk

- [x] The repository has no workflows, runtime dependencies, deploy keys, webhooks, or
  configured Actions secrets.
- [x] AI limitations and mandatory human approval points are explicit.
- [x] Publication grants no infrastructure or external-system access.
- [x] GitHub Pages is disabled.

## Transition-only checks

- [ ] The owner explicitly approves changing visibility to public.
- [ ] After the visibility change, the `Learning experiment` Issue Form renders on
  the new-issue chooser.
- [ ] Private vulnerability reporting is enabled and its link works.
- [ ] Public security features and the repository's final public metadata are
  verified.

## Rollback

If a transition-only check fails, immediately return the repository to private while
the problem is corrected. Do not weaken the publication criteria merely to keep the
repository visible.
