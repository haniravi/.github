# :sparkles:

> Work in progress. Check #2 for status.

### Table of Contents

## Getting started

## Workflow

### Issues

### Branching strategy

### Commits

> Format of messages

```
<type>: <subject>

<body>

<footer>
```

##### Subject (first line)

Imperative, present tense summary under 50 characters.

> Allowed `<type>` values:

- `feat` - feature
- `fix` - bug fix
- `docs` - documentation
- `style` - formatting, missing semi colons
- `refactor` - refactoring production code
- `test` - adding missing tests, refactoring tests; no production code change
- `chore` - maintain; no production code change

> Examples

```
chore: add Oyster build script
docs: explain hat wobble
feat: add beta sequence
fix: remove broken confirmation message
refactor: share logic between 4d3d3d3 and flarhgunnstow
style: convert tabs to spaces
test: ensure Tayne retains clothing
```

##### Body

The body should provide a meaningful commit message, which includes motivation for the change, and contrasts its implementation with previous behaviour.

##### Footer

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
