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
We use a matrix to determine the priority of the Code Review. **Attach** the corresponding **label** to the PR, and the corresponding **team** as revievers.

| Impact / Complexiteit | High | Medium | Low  | Internal-only |
|-----------------------|:----:|:------:|:----:|:-------------:|
| **Critical**          | CR1  |  CR1   | CR2  |     CR2       |
| **Major**             | CR1  |  CR2   | CR2  |     CR3       |
| **Moderate**          | CR2  |  CR2   | CR3  |     CR3       |
| **Minor**             | CR2  |  CR3   | CR4  |     CR4       |

More info can be found [here](https://app.gitbook.com/o/-MUKYLddTYNN3QEkR5JF/s/-MUhmjf5u2K1v39Mh4Ic/internal-processes-and-tools/code-reviews).

## Information Security
- [ ] Described changes in Privacy/Security, if any.
<!-- Describe changes in Privacy/Security in detail -->
<!-- Contact the Security Officer for risk analysis -->
- [ ] Added a dependency. If checked, fill in the form using this link: https://sfgrd.nl/3srsd6B, and then choose the 'Nieuwe dependency toevoegen' form. They can then be found here: https://sfgrd.nl/3VMfisF

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] I have added tests to cover my changes.
