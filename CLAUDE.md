# Camera (pleme-io fork)

> **★★★ CSE / Knowable Construction.** This repo operates under **Constructive Substrate Engineering** — canonical specification at [`pleme-io/theory/CONSTRUCTIVE-SUBSTRATE-ENGINEERING.md`](https://github.com/pleme-io/theory/blob/main/CONSTRUCTIVE-SUBSTRATE-ENGINEERING.md). The Compounding Directive (operational rules: solve once, load-bearing fixes only, idiom-first, models stay current, direction beats velocity) is in the org-level pleme-io/CLAUDE.md ★★★ section. Read both before non-trivial changes.


GrapheneOS privacy camera app. CameraX-based, EXIF stripping by default,
QR code scanning, no network access.

## Build

```bash
nix develop                      # enter Android dev shell
./gradlew assembleRelease        # build release APK
```

## Upstream

Forked from [GrapheneOS/Camera](https://github.com/GrapheneOS/Camera).
MIT license. Sync: `git fetch upstream && git merge upstream/main`.
