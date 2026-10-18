<!-- Records a `refresh-<ecosystem>-versions` run. Fill in every section. If a section doesn't apply, write "Doesn't apply" and the reason, instead of deleting it. -->

## Versions

| What                      | Before | After |
| ------------------------- | ------ | ----- |
| Framework or runtime      |        |       |
| Language                  |        |       |
| Toolchain band or minimum |        |       |

**Package pins:** each pin that changed, with its version before and after. Then the date the pins were verified against the registry, which changes even when no pin does.

**Why a minimum moved:** the feature the repository needs from the new band, for each toolchain minimum raised.

## Opinions

**Changed:** each `opinions/` file, and the feature or release that changed it.

**Verified unchanged:** each file checked against the new targets with no change to its guidance.

## Samples

**Build and test:** the toolchain version, the commands run, and the result, including the number of tests that ran. Zero tests is a failure. Without a toolchain, write "Unverified" and the reason.

## TODOs

Each stub, `TODO`, or follow-up the run left, and where it is.

## Checklist

- [ ] `targets:` and `last-reviewed:` are updated on every file changed or verified unchanged.
- [ ] No preview or release candidate is a target. Previews go in "Coming next" notes.
- [ ] No house block or region is removed, weakened, or unmarked.
- [ ] `npm run check` passes.
