# Contributing

The Podlite specification evolves through community discussion. The
maintainer integrates approved changes after consensus is reached.

## Pull requests are not accepted

This repository does not accept external pull requests, including
typo and bug fixes. All proposed changes (spec design, errata,
clarifications, examples) start as a discussion or issue.

Specification design needs deliberation. A "small" clarification
often surfaces unresolved design questions. A typo fix in one
location often implies wording changes elsewhere. Reviewing the
full picture happens in discussion, not in diff comments.

## How to propose a change

1. Open a thread in [Discussions](https://github.com/podlite/podlite-specs/discussions)
2. Describe the proposal, motivation, and any alternatives considered
3. Wait for community feedback and maintainer response
4. Approved proposals are integrated by the maintainer

## How to report a bug

For typos, broken examples, or contradictions in the spec, open an
[issue](https://github.com/podlite/podlite-specs/issues) with the
affected line numbers or section name. The maintainer will fix it
and reference the issue in the commit.

For ambiguities or questions about interpretation, open a thread in
[Discussions Q&A](https://github.com/podlite/podlite-specs/discussions/categories/q-a) instead.

## Implementation projects

This repository hosts the specification only. Parsers, renderers,
and tooling live in separate repositories under the [podlite
organization](https://github.com/podlite). Implementations have
their own contribution conventions.
