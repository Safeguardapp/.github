# Developing Safeguard

## Git Guidelines

We have very precise rules over how our git works. This leads to **more
readable messages** that are easy to follow when looking through the **project history**.  But also,
we use the git commit messages to **generate the change log**.

### Branches
For every functionality, we use a different branch. These branches follow the format `<type>/<subject>`, where `subject` is a description of the issue (preferable the same as Jira, but in English). `type` can be any of the following, and are the same `type`s used in Pull Requests:

* **feature**: A new feature
* **fix**: A bug fix
* **hotfix**: A hotfix
* **docs**: Documentation only changes
* **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing
  semi-colons, etc)
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **performance**: A code change that improves performance
* **test**: Adding missing or correcting existing tests
* **dependency**: Updating dependencies
* **maintenance**: General maintenance
* **chore**: Changes to the build process or auxiliary tools and libraries such as documentation
  generation

### Pull Requests
We use a Pull Request template (that can be found [here](https://github.com/Safeguardapp/.github/blob/master/PULL_REQUEST_TEMPLATE.md)) which should be used when submitting Pull Requests. These are used to generate the changelog.

Pull requests should require at least 1 approved review before being merged, and should pass all checks.

