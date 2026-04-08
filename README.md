# aiir Releases

This repository only hosts published release artifacts for `aiir`.

The source code is not stored here. `aiomni/aiir-release` exists so the public macOS installer can be distributed through GitHub Releases, while the source repository remains private.

## Download

Download the latest `aiir-*-macos-arm64.dmg` asset from the Releases page.

## Platform

- macOS Apple Silicon only
- arm64 build only
- unsigned app bundle for now

## Install

1. Open the DMG.
2. Drag `aiir.app` into `/Applications`.
3. Launch `aiir` from `/Applications`.

## Unsigned App Notice

Because the app is currently unsigned, macOS may block the first launch. If that happens, right-click the app and choose `Open`, or allow it from `System Settings` -> `Privacy & Security`.
