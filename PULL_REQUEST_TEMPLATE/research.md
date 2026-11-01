<!-- This description becomes the commit message. Follow Writing style: Commit messages and pull requests, then delete this comment: https://awesome-humans.net/conventions/writing-style/#commit-messages-and-pull-requests

     Saves a `research-topic` topic. Title the pull request `research: <topic>`. Replace the text after each label. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## Question

The question, word for word, and the topic's file name under `research/`.

## Recommendation

The recommendation, in one or two sentences, and its maturity: GA, or preview with its expected GA release.

## Sources

One line per claim, as `- <claim>: <source> (<standing>)`. The standing is one of: citable (with the source's roster ID), watch-list, or not on the roster. Only citable claims can be promoted. The evidence is in the topic file.

## For `resolve-research`

**Proposed outcome:** promote, partly promote, or discard, and why.

**Target files:** each `opinions/` or `templates/` file and section the promotion plan names, or "none" for a discard.

**Blockers:** each claim that needs `vet-source` or a GA release first.

## Checked

The topic has the metadata `AGENTS.md: Metadata` defines, and `just check` passes.

For each check below, say what you ran, or write "Doesn't apply" and why.

- **Code:** the toolchain or SDK, and the package versions, that every code example compiles with against the declared `targets:`.
- **Advisories:** whether each package the topic recommends has an open security advisory at the version it names, the tool or advisory database you checked, and each advisory you found.
- **Claims:** whether each claim behind the recommendation has a citable roster source, or is marked in the topic as unsupported.
