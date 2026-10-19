<!-- This description becomes the squash commit's message, so write it as Writing style: Commit messages and pull requests describes, and delete this comment: https://awesome-humans.net/conventions/writing-style/#commit-messages-and-pull-requests

     Records a `refresh-<ecosystem>-versions` run. Replace the text after each label. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## Versions

Write each as `<before> to <after>`, or "unchanged".

- **Framework or runtime:** the versions.
- **Language:** the versions.
- **Toolchain band or minimum:** the versions.
- **Package pins:** each pin that changed, with its version before and after. Then the date the pins were verified against the registry, which changes even when no pin does.
- **Why a minimum moved:** the feature the repository needs from the new band, for each toolchain minimum raised.

## Opinions

**Changed:** each `opinions/` file, and the feature or release that changed it.

**Verified unchanged:** each file checked against the new targets with no change to its guidance.

## Samples

**Build and test:** the toolchain version, the commands run, and the result, including the number of tests that ran. Zero tests is a failure. Without a toolchain, write "Unverified" and the reason.

## TODOs

Each stub, `TODO`, or follow-up the run left, and where it is.

## Checked

That `targets:` and `last-reviewed:` are updated on every file changed or verified unchanged, and that `just check` passes. Say so if a target is a preview or release candidate, which belongs in a "Coming next" note, or if the run changes a house block or region.
