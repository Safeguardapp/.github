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


## How to test
<!--- For the reviewer, who functionally tests this change as part of the
review. Describe the steps to follow, required test data or setup, and the
expected result. Write it for someone who does not know the code. These
instructions are also used for functional testing of the ticket. -->


## Code review priority
A bot labels this pull request on the two axes of the [risk matrix](https://app.notion.com/p/Code-Reviews-f84774e68457473fa97e1275ef90e3cc#98dc1650c44d466aa61afc910482cb56):

- `impact:*` is an estimate. **Check it and change the label when you know the change better**, downgrading included. Impact is "what happens if this goes wrong?": critical (users blocked, data lost, lives at risk), major (a core flow breaks, workaround exists), moderate (irritates, does not block), minor (cosmetic, edge case, or internal-only: tooling, CI, scripts, feature flags toggled off, super-admin views).
- `complexity:*` is measured from the diff (code lines, migrations, dependencies, spread, concurrency).

The `CR*` label and the required approvals follow from the two labels: CR1 needs 2 approvals of which 1 senior, CR2 needs 1, CR3 and CR4 none. Add the corresponding **team** as reviewers.

## Information Security
- [ ] Described changes in Privacy/Security, if any.
<!-- Describe changes in Privacy/Security in detail -->
<!-- Contact the Security Officer for risk analysis -->
- [ ] Added a dependency. If checked, fill in the form using this link: https://sfgrd.nl/3srsd6B, and then choose the 'Nieuwe dependency toevoegen' form. They can then be found here: https://sfgrd.nl/3VMfisF

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] I have added tests to cover my changes.

## Reviewer checklist:
<!--- To be ticked by the reviewer, not the author. -->
- [ ] I have functionally tested this change using the 'How to test' instructions.
