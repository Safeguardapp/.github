<!---

Provide a general summary of your changes in the Title above using this format:
`[<type>] <jiraId> - <subject>`

<type> must be one of the following and should be capitalized:
Feature: A new feature
Fix: A bug fix
Hotfix: A hotfix
Docs: Documentation only changes
Style: Changes that do not affect the meaning of the code (whitespace, formatting, missing semi-colons, etc)
Refactor: A code change that neither fixes a bug nor adds a feature
Performance: A code change that improves performance
Test: Adding missing or correcting existing tests
Dependency: Updating dependencies
Maintenance: General maintenance
Chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

<jiraId> is the ticket number from Jira, for example: SG-1337
<subject> is a concise description of the PR. This will be put into the Changelog, so get this right. 

-->

## Description
<!--- Describe your changes in detail -->


## Code review priority
First, determine impact and complexity for the PR. More info can be found [here](https://app.gitbook.com/o/-MUKYLddTYNN3QEkR5JF/s/-MUhmjf5u2K1v39Mh4Ic/internal-processes-and-tools/code-reviews).

Impact:
- [ ] **Critical**: Users are blocked, data can be lost, or lives could literally be put at risk.
- [ ] **Major**: Core flow breaks but a kludgy workaround exists. Bad, but not life‑threatening.
- [ ] **Moderate**: Noticeable mis‑behaviour that irritates but doesn’t block the main task.
- [ ] **Minor**: Cosmetic, edge‑case or pure convenience issue.

Complexity:
- [ ] **High**: ≥ 200 LOC or new architectural pattern, multi‑service migration, data back‑fill, heavy concurrency.
- [ ] **Medium**: 20 – 200 LOC, contained to one module, no schema change.
- [ ] **Low**: < 20 LOC, straightforward logic, no branching paths.
- [ ] **Internal-only**: Change affects tooling, CI, scripts, feature flags toggled off, or super‑admin views.

Then, we use a matrix to determine the priority of the Code Review. **Attach** the corresponding **label** to the PR, and the corresponding **team** as revievers.

| Impact / Complexiteit | High | Medium | Low  | Internal-only |
|-----------------------|:----:|:------:|:----:|:-------------:|
| **Critical**          | CR1  |  CR1   | CR2  |     CR2       |
| **Major**             | CR1  |  CR2   | CR2  |     CR3       |
| **Moderate**          | CR2  |  CR2   | CR3  |     CR3       |
| **Minor**             | CR2  |  CR3   | CR4  |     CR4       |

## Information Security
- [ ] Described changes in Privacy/Security, if any.
<!-- Describe changes in Privacy/Security in detail -->
<!-- Contact the Security Officer for risk analysis -->
- [ ] Added a dependency. If checked, fill in the form using this link: https://sfgrd.nl/3srsd6B, and then choose the 'Nieuwe dependency toevoegen' form. They can then be found here: https://sfgrd.nl/3VMfisF

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] I have added tests to cover my changes.
