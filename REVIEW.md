# Review instructions

These instructions tune automated pull request review in this repository: Claude Code Review reads this file from `main`, and CodeRabbit reads it as a guideline. A change to this file takes effect once it merges.

This repository holds the organisation's defaults: the pull request templates, `SECURITY.md`, the organisation profile, and the `Attribution` workflow that every repository calls. A change here reaches every repository at once, so a finding matters when it would break another repository's pull requests or misdirect a contributor.

## What Important means here

Reserve Important for these. Everything else is Nit at most.

- **A template that breaks the attribution check.** A pull request template whose filled-in body would fail `attribution / check`, for example by keeping a table, a checkbox, or an inline link outside the `<!-- … -->` guidance comment.
- **A template that drops a section a skill fills in.** Each template under `PULL_REQUEST_TEMPLATE/` is named by a skill in `dotnet` or `rust`. A renamed or removed template, or a removed section, needs the matching skill change. Name the skill.
- **An ecosystem-specific line.** A toolchain name, path, or check that applies to only one ecosystem. Those stay in each repository's `AGENTS.md`.
- **A weakened check.** A change to `attribution.yml` that lets a `Co-authored-by` trailer or a "Generated with" line through, or that runs the pull request's code under `pull_request_target`.
- **A wrong security route.** A change to `SECURITY.md` that removes private vulnerability reporting or the `contact@awesome-humans.net` fallback.

## Cap the nits

Report at most three Nits per review. Writing-style findings, from [awesome-humans/website: Writing style](https://github.com/awesome-humans/website/blob/main/pages/conventions/writing-style.md), are Nit at most.

## Do not report

- An issue the pull request didn't introduce or make worse.
- A missing lint or CI check. This repository has none on purpose, beyond `Attribution`.

## Evidence

Cite `file:line` for every finding, and name the repository and skill a template change affects.
