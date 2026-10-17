<!-- Fill in every section. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## Proposed opinion

**Opinion (one sentence, one recommendation):**

**Why (the reasoning, the trade-offs, and what it replaces):**

**Where it belongs (an `opinions/` or `templates/` file):**

## Provenance: pick one

- [ ] **Sourced:** It traces to a vetted source in the repository's `AWESOME-HUMANS.md` roster. Source IDs and links:
- [ ] **Candidate source:** It traces to a source that isn't on the roster yet. The source must pass the `vet-source` skill before the opinion can merge. Source and evidence of its track record:
- [ ] **Experience-based:** It comes from my own practice, with no published source. If the owner accepts it, they **adopt** it as a house opinion and take responsibility for it, as the repository's `HOUSE-OPINIONS.md` describes, and the Woven table credits this pull request and its author.

## Skill run

<!-- A person proposing an opinion writes "Doesn't apply". -->

**Skill:** `harvest-sources` or `resolve-research`.

**`harvest-sources`:** The sweep window. For each source, the posts read and what each changed, or "nothing notable". Where vetted sources disagree, both positions and the one chosen. `Closes #<number>` for the `Harvest due` issue.

**`resolve-research`:** The `research/` topic, and whether it's promoted, partly promoted, or discarded. For each claim the recommendation rests on, the roster ID behind it, or why it was dropped or held.

## Checklist

- [ ] The opinion comes first: the recommendation in the first sentence, then the rationale, then the sources. For details, see the repository's `AGENTS.md`.
- [ ] Code examples compile against the declared `targets:`. State the toolchain version you built with.
- [ ] Every `opinions/`, `research/`, or `templates/` file you changed has complete metadata, as `AGENTS.md: Metadata` defines. CI checks this.
- [ ] Every new, renamed, or removed `opinions/` file is indexed in `README.md`, with a linked **Scope** bullet and a **Repository layout** entry, each in order, and no stale entries. CI checks this.
- [ ] `npm run check` passes. It checks formatting, lint, and spelling at the versions pinned in `package.json`.
- [ ] No preview feature is stated as an opinion. Previews go in "Coming next" notes.
- [ ] No house content is removed, weakened, or unmarked.
