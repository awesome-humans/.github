<!-- Records a `weave-house-opinion` run. Title the pull request `docs: weave house opinion on <title>`. Fill in every section. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## House opinion

**Profile:** the house profile it belongs to, such as `simon-mckenna`.

**Opinion (one sentence, one recommendation):**

**Origin:** the profile's owner, or the contributor and pull request it was adopted from.

## Where it went

Each file changed, and the section in it.

## Sourced text beside it

The sourced recommendation each house block or region sits beside, with its roster IDs. This text stays as it was. If the house opinion conflicts with it, say how. Write "none" if no sourced text conflicts.

## `HOUSE-OPINIONS.md` entry

<!-- Copy the Woven table row: the date, the profile, the opinion, where it went, and its provenance. -->

## Checklist

- [ ] Each change is a `/// house | <profile>` block in an opinion, or a region between `house:<profile> begin` and `end` comments in a template. Each starts with `**House:**`, and the file's `sources:` names `house:<profile>`.
- [ ] Nowhere is the opinion presented as sourced, and the sourced text beside it is unchanged.
- [ ] Each template still builds with its house regions removed.
- [ ] Code examples compile against the declared `targets:`. State the toolchain version you built with.
- [ ] `last-reviewed:` is updated on every file changed.
- [ ] `npm run check` passes.
