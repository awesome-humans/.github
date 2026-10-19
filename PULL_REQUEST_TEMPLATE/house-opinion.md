<!-- This description becomes the squash commit's message, so write it as Writing style: Commit messages and pull requests describes, and delete this comment: https://awesome-humans.net/conventions/writing-style/#commit-messages-and-pull-requests

     Records a `weave-house-opinion` run. Title the pull request `docs: weave house opinion on <title>`. Replace the text after each label. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## House opinion

**Profile:** the house profile it belongs to, such as `simon-mckenna`.

**Opinion:** one sentence, with one recommendation.

**Origin:** the profile's owner, or the contributor and the pull request it was adopted from. A pull request also goes in a `Refs: #<number>` trailer.

## Where it went

Each file changed, and the section in it.

## Sourced text beside it

The sourced recommendation each house block or region sits beside, with its roster IDs. This text stays as it was. If the house opinion conflicts with it, say how. Write "none" if no sourced text conflicts.

## `HOUSE-OPINIONS.md` entry

The Woven table row: the date, the profile, the opinion, where it went, and its provenance.

## Checked

- **Markings:** each change is a `/// house | <profile>` block in an opinion, or a region between `house:<profile> begin` and `end` comments in a template. Each starts with `**House:**`, and the file's `sources:` names `house:<profile>`.
- **Sourced text:** nowhere presents the opinion as sourced, and the sourced text beside it is unchanged.
- **Builds:** each template still builds with its house regions removed, and the code examples compile with the toolchain version you name.
- **Metadata and checks:** `last-reviewed:` is updated on every file changed, and `just check` passes.
