# Contributing

Baixada welcomes careful improvements to its games, rules, study tools,
documentation, and infrastructure. Contributions can be small. A precise bug
report, a corrected rule explanation, or a focused test is useful work.

## Before starting

Search the target repository's issues and pull requests before opening
something new.

For a contained fix, open a pull request when it is ready. For a new feature,
public interface change, rules interpretation, large dependency, or change that
spans repositories, open an issue first so the scope and ownership are clear.
Security vulnerabilities follow [the security policy](SECURITY.md), never a
public issue.

Repository-specific `README.md`, `CONTRIBUTING.md`, and `AGENTS.md` files take
precedence over this shared guidance.

## Preparing a change

1. Fork the repository or create a focused branch.
2. Follow the repository's setup and testing instructions.
3. Keep the change narrow enough to review as one idea.
4. Add or update tests when behavior changes.
5. Update public documentation when an interface, rule, setup step, or
   user-visible behavior changes.
6. Run the relevant checks before requesting review.

Avoid drive-by formatting, generated-file churn, and unrelated refactors.
Explain new dependencies and prefer the smallest durable addition.

Baixada treats Portuguese and English as first-class languages. Do not
translate the names `Baixada`, `Truco`, `Escopa`, or `Bisca`. The mode name is
written `· Lab`, with spaces around the middle dot, in both languages.

## Pull requests

A useful pull request explains:

- the problem or opportunity;
- the chosen approach and meaningful tradeoffs;
- how the change was verified;
- any follow-up work intentionally left out.

Include screenshots or recordings for visible interface changes. Link the
issue when one exists. Draft pull requests are welcome for early technical
feedback, but should identify what remains.

Reviews consider correctness, scope, maintainability, accessibility, security,
and fit with the relevant game or research contract. A maintainer may ask that
an oversized change be divided into smaller pieces.

## Licensing

By submitting a contribution, you agree that it may be distributed under the
license of the repository to which you contribute. Only submit work that you
have the right to license, and identify material adapted from another source.

Participation in Baixada project spaces is governed by the
[Code of Conduct](CODE_OF_CONDUCT.md).
