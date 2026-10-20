# Writing a useful security report

## Lead with the boundary

Describe the permission or isolation rule that should hold. A maintainer can triage a concise boundary statement faster than a long sequence of observations without context.

## Make the evidence reproducible

Give the exact version and configuration, an authorized test environment, a control case, and the observed result. Use synthetic data. Keep large traces or artifacts in a private attachment and point to the relevant lines.

## Distinguish evidence from inference

Use **confirmed** for behavior you observed. Use **possible** for consequences that depend on untested conditions. Correct earlier statements promptly if new testing narrows the finding.

## Keep one report coherent

Send related evidence as a follow-up in the same private thread. If a new finding has a different root cause or security boundary, open a separate report and explain the relationship.

## Agree on publication and credit

Use the maintainer's process for patches, CVEs, and advisories. Before publication, check the public name, GitHub account, and credit type. A GitHub account is the target for platform credit; a company name can be included separately in the advisory text when the maintainer agrees.
