<div align="center">
  <img src="assets/disclosure-banner.svg" alt="Muted Cybersecurity — disclosure templates" width="100%">

  # Disclosure templates

  **Clear reports for coordinated security work**
</div>

These Markdown templates help researchers and maintainers exchange the information needed to triage and fix a vulnerability. They are deliberately product neutral. Keep actual vulnerability details in the recipient's approved **private** channel.

## Choose a template

| When | Template | Purpose |
| --- | --- | --- |
| First contact | [Initial report](templates/initial-report.md) | Explain the boundary, impact, environment, and evidence. |
| New evidence or a correction | [Follow-up](templates/follow-up.md) | Add a result without losing the original report context. |
| Reviewing a proposed fix | [Fix review](templates/fix-review.md) | Separate tested behavior from open questions. |
| Preparing publication | [Disclosure checklist](templates/disclosure-checklist.md) | Align dates, credit, links, and confidentiality. |

Read the [writing guide](docs/writing-guide.md) before filling out a template.

## Use responsibly

1. Confirm that testing is authorized and limited to your own or approved environment.
2. Find the project's `SECURITY.md`, private reporting form, or security contact.
3. Replace placeholders with verified facts. Mark assumptions and untested possibilities clearly.
4. Remove credentials, personal data, and unrelated logs before sharing evidence.
5. Keep the report private until the maintainer coordinates publication.

The templates are starting points, not a substitute for a project's reporting policy. They do not set a universal disclosure deadline.

## Attribution and contact

Prepared by [Muted Cybersecurity](https://github.com/MutedCybersecurity). For questions about these templates, contact [cybersec@mut3dcybersecurity.com](mailto:cybersec@mut3dcybersecurity.com). Send vulnerabilities in third-party products to the relevant maintainer through their private channel.

Original text and artwork are available under the [MIT License](LICENSE).
