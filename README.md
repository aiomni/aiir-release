# aiir Releases

`aiomni/aiir-release` is the public release repository for `aiir`.

It only exists to host published macOS release artifacts through GitHub Releases. The application source code is maintained in a separate private repository and is not mirrored here.

## What This Repository Contains

- Release assets for public downloads
- Versioned macOS Apple Silicon builds
- Minimal documentation for installation and first launch

Current release asset names:

- `aiir-<version>-macos-arm64.dmg`
- `aiir-<version>-macos-arm64.app.zip`

## Platform

- macOS on Apple Silicon (`arm64`) only
- Native `.app` bundle distribution
- Unsigned app bundle for now

## Install

1. Open the latest release and download either the `.dmg` or `.app.zip` asset.
2. If you downloaded the DMG, open it and drag `aiir.app` into `/Applications`.
3. If you downloaded the ZIP archive, unzip it and move `aiir.app` into `/Applications`.
4. Launch `aiir` from `/Applications`.

## First Launch on macOS

Because the app is currently unsigned, macOS Gatekeeper may block the first launch.

If that happens:

1. Right-click `aiir.app` and choose `Open`.
2. If macOS still blocks it, open `System Settings` -> `Privacy & Security`.
3. Allow the app to run, then launch it again.

## Notes

- This repository is for distribution artifacts only.
- New versions are published on the Releases page.
- The README in this repository is synced from the source repository during the release process.
