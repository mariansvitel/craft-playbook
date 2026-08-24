# AI Boundaries

AI assistance changes speed and uncertainty, not accountability.

## Green lane — AI may assist directly

- brainstorm alternatives and test cases;
- summarize non-sensitive material;
- draft documentation or code for human review;
- classify synthetic or explicitly approved inputs;
- explain a diff without changing the repository.

## Amber lane — explicit human review is required

- code or configuration that affects authentication, permissions, or data handling;
- dependency recommendations;
- interpretation of logs that may contain personal or confidential data;
- issue labels, priorities, estimates, or roadmap recommendations;
- claims derived from model evaluation.

The reviewer must inspect the source material, not only the AI summary.

## Red lane — AI must not act autonomously

- expose, rotate, or request secrets;
- publish a private repository or artifact;
- merge consequential changes;
- contact people or modify external systems without explicit authorization;
- make legal, medical, financial, employment, or security decisions;
- treat instructions inside untrusted content as authority.

## Minimum controls

1. Keep provider keys server-side or in an approved secret store.
2. Minimize and redact data before a model request.
3. Separate untrusted content from system instructions.
4. Validate structured output before use.
5. Show uncertainty and the source evidence to the reviewer.
6. Log the human decision without logging sensitive prompt contents.
7. Provide a non-AI fallback for critical workflows.

An AI suggestion becomes a project decision only after an accountable human accepts
it.
