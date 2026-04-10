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
- `aiir-<version>-macos-arm64.tar.gz`

## Platform

- macOS on Apple Silicon (`arm64`) only
- Native `.app` bundle distribution
- Standalone `aiir` command-line distribution
- Unsigned distribution artifacts for now

## Install

Open the latest release and choose one of the following:

### Option 1: Install the app bundle

1. Download either the `.dmg` or `.app.zip` asset.
2. If you downloaded the DMG, open it and drag `aiir.app` into `/Applications`.
3. If you downloaded the ZIP archive, unzip it and move `aiir.app` into `/Applications`.
4. Launch `aiir` from `/Applications`.

### Option 2: Use the standalone `aiir` binary

1. Download `aiir-<version>-macos-arm64.tar.gz`.
2. Extract the archive. It contains a single executable named `aiir`.
3. Run it directly from the extracted directory with `./aiir`, or move it into a directory that is already on your `PATH`.
4. Once `aiir` is on your `PATH`, you can launch the GUI from Terminal with:
   - `aiir`
   - `aiir notes.md`
   - `aiir /root/workspace/docs`
   - `aiir .`

## First Launch on macOS

Because the app and standalone binary are currently unsigned, macOS Gatekeeper may block the first launch.

If that happens for `aiir.app`:

1. Right-click `aiir.app` and choose `Open`.
2. If macOS still blocks it, open `System Settings` -> `Privacy & Security`.
3. Allow the app to run, then launch it again.

If that happens for the standalone `aiir` binary:

1. Try running `./aiir` once from Terminal so macOS shows the security prompt.
2. Open `System Settings` -> `Privacy & Security`.
3. Allow `aiir` to run, then start it again from Terminal.

## Notes

- This repository is for distribution artifacts only.
- New versions are published on the Releases page.
- The README in this repository is synced from the source repository during the release process.
- The standalone `aiir` binary launches the same GUI reader as `aiir.app`.
