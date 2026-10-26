<!-- This description becomes the squash commit's message, so write it as Writing style: Commit messages and pull requests describes, and delete this comment: https://awesome-humans.net/conventions/writing-style/#commit-messages-and-pull-requests

     Saves a `research-topic` topic. Title the pull request `research: <topic>`. Replace the text after each label. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## Question

The question, as the person asked it, and the `research/` file that holds the topic.

## Recommendation

The recommendation, in one or two sentences, and its maturity: GA, or preview with the release it waits for.

## Sources

One line per claim, as `- <claim>: <source> (<standing>)`. The standing is citable, with its roster ID, watch-list, or not on the roster. Only citable claims can be promoted. The topic file holds the full evidence.

## For `resolve-research`

**Proposed outcome:** promote, partly promote, or discard, and why.

**Target files:** each `opinions/` or `templates/` file and section the promotion plan names, or "none" for a discard.

**Blockers:** each claim that needs `vet-source` or a GA release first.

## Checked

That the topic has the metadata a topic carries, as `AGENTS.md: Metadata` defines, and that `just check` passes.

Then these three checks. For each, say what you ran, or write "Doesn't apply" and why.

- **Code:** the toolchain or SDK, and the package versions, that every code example compiles with against the declared `targets:`.
- **Advisories:** whether each package the topic recommends has an open security advisory at the version it names, the tool or advisory database you checked, and each advisory you found.
- **Claims:** that each claim the recommendation rests on has a citable roster source, or is marked in the topic as unsupported.
