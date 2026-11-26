# Contributing to Docqet

Thanks for your interest in Docqet. Contributions are welcome: questions, bug
reports, ideas, docs, examples, tests and code.

This guide covers what applies across every Docqet repository. It builds on
Exalynt's [contributing guide](https://github.com/exalynt/community/blob/main/CONTRIBUTING.md),
which applies to every Exalynt project, and each repository's own
`CONTRIBUTING.md` adds what's specific to it, such as how to set it up and
test it. By taking part, you agree to follow the
[Code of Conduct](CODE_OF_CONDUCT.md).

## Where things go

- **Questions and open-ended ideas** go in [Discussions](../../discussions).
- **Bugs and concrete changes** go in the issues of the repository they're
  about.
- **Small fixes** (typos, broken links, clear bugs) can go straight to a pull
  request.
- **Anything larger** (a new command, a change to the format, a new
  dependency) should start as an issue or discussion, so we can agree on the
  problem before you put time into a solution.
- **Vulnerabilities** never go in public. Follow the affected repository's
  `SECURITY.md`.

## Before you start

Docqet is a **Prototype**, so the format, the commands and the UI may all
change a lot. Two things help an idea land:

- **[Docqet's principles](https://github.com/docqet/docqet/blob/main/docs/principles.md)**
  say what Docqet is and isn't, and how to tell whether an idea belongs in
  it.
- **Open decisions** in [Docqet's own docs](https://github.com/docqet/docqet/tree/main/docqet)
  are questions nobody has settled yet. If your idea touches one, say so.

When you propose something, start with the problem it solves and who has it.
A clear problem is worth more than a finished solution to the wrong one.

## Docqet is documented with Docqet

Docqet's repositories use their own format. When you change what the
software does, must do or still lacks, update its Docqet docs and
`docqet:` annotations in the same pull request, and finish with
`docqet check --changed` reporting no problems. The repository's
`CONTRIBUTING.md` says how.

Some things are for maintainers to decide, not contributors:

- **Stability levels.** Leave them alone; maintainers set them.
- **Changes to the format.** Propose them in an issue or discussion first.

## Pull requests

- **Keep each one focused** on one problem, and link its issue.
- **Say what changed and why**, how you tested it, and what it changed in
  the Docqet docs.
- **Include tests** for bug fixes and new behavior where practical.
- **Write commit messages** as one plain sentence saying what the change
  does, such as "Show every read's loading and failure". No prefixes needed.
  We may squash when merging.

A draft pull request is a fine way to ask for early feedback.

## Using AI agents

Agents are welcome, and Docqet is built with them. Its repositories have the
Docqet agent kit installed, so an agent reads the rules before changing code
and keeps the docs current as it goes.

Whatever tools you use, you're responsible for what you submit: understand
it, test it, and check any intention an agent inferred before it goes into
the Docqet docs. Nothing an agent writes counts as declared until a person
confirms it.

## License

Docqet is [MIT licensed](https://github.com/docqet/docqet/blob/main/LICENSE).
By contributing, you agree that your contribution is licensed under the terms
of the repository you contribute to.

## Questions

If you're unsure where to start, ask in [Discussions](../../discussions).
Asking a good question, pointing out something confusing, or fixing
something small are all good ways in.
