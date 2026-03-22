# Camera (pleme-io fork)

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
