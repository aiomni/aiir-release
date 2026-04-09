# aiir Releases

This repository only hosts published release artifacts for `aiir`.

The source code is not stored here. `aiomni/aiir-release` exists so the public macOS installer and app bundle can be distributed through GitHub Releases, while the source repository remains private.

## Download

Download either of these assets from the Releases page:

- `aiir-*-macos-arm64.dmg`
- `aiir-*-macos-arm64.app.zip`

## Platform

- macOS Apple Silicon only
- arm64 build only
- unsigned app bundle for now

## Install

1. Either open the DMG, or unzip `aiir-*.app.zip`.
2. Move `aiir.app` into `/Applications`.
3. Launch `aiir` from `/Applications`.

## Unsigned App Notice

Because the app is currently unsigned, macOS may block the first launch. If that happens, right-click the app and choose `Open`, or allow it from `System Settings` -> `Privacy & Security`.
