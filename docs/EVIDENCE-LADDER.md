# Evidence Ladder

The ladder prevents strong claims from resting on weak demonstrations. Move upward
only when the evidence actually exists.

| Level | Evidence | Safe wording example |
| --- | --- | --- |
| 0 — Intent | Goal or issue exists | “Planned” |
| 1 — Observation | One manual run or screenshot | “Demonstrated once” |
| 2 — Checked | Repeatable checks cover expected behavior | “Verified for documented cases” |
| 3 — Challenged | Failure, boundary, and adversarial cases were exercised | “Tested against listed failure modes” |
| 4 — Reproducible | Another person can run the documented setup and checks | “Publicly reproducible” |
| 5 — Operated | Maintained evidence exists across time and real use | “Operated under documented conditions” |

## Evidence entry

For each meaningful claim, record:

- **Claim:** the narrow statement being supported;
- **Level:** the current ladder level;
- **Artifact:** commit, PR, test output, decision record, or sanitized report;
- **Conditions:** environment, data type, and assumptions;
- **Failures tested:** important negative cases;
- **Limitations:** what the evidence does not establish;
- **Next stronger proof:** the smallest step to move one level higher.

Do not inflate the level because the work was difficult. The ladder measures the
strength of public evidence, not effort or personal value.
