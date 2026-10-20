# Private security report: [short, neutral title]

> **Send privately** using the project's designated security channel. Remove this note before sending.

## Contact and coordination

- Reporter or team: [name]
- Preferred reply address: [email]
- Product and version or commit: [exact version]
- Report date: [YYYY-MM-DD]
- Disclosure status: Private; please coordinate publication with us.

## Summary

[Two or three sentences describing the security boundary, what was observed, and why the result matters. Avoid claims beyond the evidence.]

## Expected and observed behavior

| | Behavior |
| --- | --- |
| Expected | [What the lower-privilege actor should be allowed to do.] |
| Observed | [What happened in the authorized test environment.] |

## Preconditions and scope

- Required role or access: [role]
- Relevant configuration: [settings]
- Tested environment: [local or otherwise authorized environment]
- Test data: [synthetic data description]
- Versions tested: [versions]
- Versions not tested: [versions, if relevant]

## Reproduction evidence

1. [Set up the authorized test environment.]
2. [Perform the control case.]
3. [Perform the test case.]
4. [Record the difference and the specific output that supports the claim.]

Evidence files: [private attachment names, hashes, or private link]. Do not include live secrets, personal data, or unrelated records.

## Impact and limits

- Confirmed impact: [what was directly observed]
- Potential impact requiring validation: [if any]
- Known limits or assumptions: [what the test does not establish]

## Suggested area for investigation

[Optional: relevant component or trust-boundary check. Avoid presenting an untested fix as certain.]

## Coordination request

Please confirm receipt and let us know whether another private channel or additional evidence would help your triage. We can review a candidate fix in an isolated environment if useful.

Researcher credit, if appropriate: **[preferred public name]** ([GitHub username or profile URL]).
