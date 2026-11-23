# Contributing and learning workflow

This is a personal learning program, but every change should follow a professional
engineering workflow.

## Branches

Use short-lived branches:
- `feat/<topic>`
- `exp/<experiment>`
- `docs/<topic>`
- `fix/<topic>`

## Commits

Prefer Conventional Commits:
- `feat: add tokenization experiment`
- `test: cover input validation`
- `docs: explain transformer inference`
- `refactor: isolate provider adapter`

## Pull requests

A pull request should state:
1. Problem or learning objective.
2. Implementation summary.
3. Tests and experiments executed.
4. Results, including metrics where relevant.
5. Known limitations and next steps.

## Quality gates

Run the repository's documented checks before opening a PR.
Do not commit secrets, API keys, private datasets, generated model weights,
or personal information.

## Learning evidence

Do not mark a unit complete based only on reading. Link implementation,
tests, experiment output, and a short explanation of trade-offs.
