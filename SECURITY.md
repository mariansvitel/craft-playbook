# Security Policy

## Reporting a vulnerability

For a public release, use GitHub's private **Report a vulnerability** flow in the
Security tab. Do not open a public issue containing exploit details, credentials,
personal data, or sensitive logs.

This learning repository does not promise a production security-response service.
Reports will be acknowledged and assessed as capacity allows. If the private report
button is unavailable, open only a minimal issue asking the maintainer to establish a
private channel; do not include vulnerability details.

## Public-release transition

GitHub makes private vulnerability reporting available to public repositories. The
release sequence is therefore:

1. complete the [Publication Gate](docs/PUBLICATION-GATE.md);
2. obtain explicit human approval for public visibility;
3. change the repository to public;
4. immediately enable private vulnerability reporting and verify the link;
5. revert to private, or document a working private alternative, if enablement fails.

## Supported versions

Only the current default branch is maintained. Archived examples and historical
commits are not supported releases.
