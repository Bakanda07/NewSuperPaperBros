# About this fork

This is a fork of [josiahg2502-glitch/NewSuperPaperBros](https://github.com/josiahg2502-glitch/NewSuperPaperBros), maintained by Bakanda07 as a continuation of the open-source project. It carries the upstream work as it stood on the date below.

- Game / target: Super Paper Mario (Wii, PowerPC), built on WiiCompiled
- Licence: GPL-3.0. The licence file and the author notices of the upstream repository are kept as they are.
- Base commit: `1f961e7db18586655f647f1027eb86ca706088cc` (1f961e7, 2026-11-01: "v1.0.8")
- Base tag: `upstream-base-2026-11-07` marks that commit in this repository.
- Default branch: `main`

## What differs from upstream

None. `main` is identical to upstream at the base commit.

## Releases and mirrors

Release v1.0.8 is mirrored on this account, unchanged. Its launcher and updater still point at the upstream repository; they have not been repointed.

Releases published here before any change of ours are copies of the upstream builds. They are not built from this repository.

## Following upstream

```sh
git fetch upstream
git log --oneline main..upstream/main
git merge --ff-only upstream/main
```

## Rules for this fork

- No game data, keys, extracted files or code generated from a game goes into this repository.
- A release built from this fork must say so in its name or notes and give the base tag it started from.
- Changes of ours are listed in the section above when they are merged.
