# :sparkles:

> Work in progress. Check #2 for status.

### Table of Contents

## Getting started

## Workflow

### Issues

### Branching strategy

> Based on [GitHub Flow](https://guides.github.com/introduction/flow/)

- Anything in the `develop` branch is deployable
- To work on something new, create a descriptively named branch off of `develop` (ie: new-oauth2-scopes)
- Commit to that branch locally and regularly push your work to the same named branch on the server
- When you need feedback or help, or you think the branch is ready for merging, open a pull request
- ~~After someone else has reviewed and signed off on the feature,~~ you can merge it into `develop`
- ~~Once it is merged and pushed to `develop`, you can and should deploy immediately~~
- Use `master` branch for branding, e.g. tagged releases, GitHub pages, etc.

##### Environment branches

- `master` - for production
- `develop` - for integration

##### Topic branches

> Naming conventions

- Choose short and descriptive names (e.g `refactor-authentication`)
- Consider prefixing branches for specific packages (as in monorepo) w/ package id

#### Notes

- https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows
- https://backlog.com/git-tutorial/using-branches/ - Not suitable strategy by
  good example of documentation
- https://github.com/agis/git-style-guide
- https://gist.github.com/jbenet/ee6c9ac48068889b0912
- https://softwareengineering.stackexchange.com/questions/263164/why-squash-git-commits-for-pull-requests

### Commits

> Format of messages

```
<type>: <subject>

<body>

<footer>
```

##### `<subject>`

Imperative, present tense summary under 50 characters.

##### `<type>`

> Allowed values:

- `feat` - feature
- `fix` - bug fix
- `docs` - documentation
- `style` - formatting, missing semi colons
- `refactor` - refactoring production code
- `test` - adding missing tests, refactoring tests; no production code change
- `chore` - maintain; no production code change

> Example usage

```
chore: add Oyster build script
docs: explain hat wobble
feat: add beta sequence
fix: remove broken confirmation message
refactor: share logic between 4d3d3d3 and flarhgunnstow
style: convert tabs to spaces
test: ensure Tayne retains clothing
```

##### `<body>`

The body should provide a meaningful commit message, which includes motivation for the change, and contrasts its implementation with previous behaviour.

##### `<footer>`

Closed bugs should be listed on a separate line in the footer prefixed with "Closes" keyword

```
Closes #123, #245, #992
```

#### Notes

- https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
- http://karma-runner.github.io/0.10/dev/git-commit-msg.html
- https://seesparkbox.com/foundry/semantic_commit_messages


### Pull requests

## Development

### Coding conventions

> Code should be optimized for readability. Attach some custom style guide or reference some. i.e.:

In order to sanitize coding standards, please follow [this style guide](https://github.com/airbnb/javascript).

### Common practices

### Testing

### Documentation

### Style guide

## Footnotes
