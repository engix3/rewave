# ReWave Releases

This repository is prepared for hosting `ReWave` release assets through GitHub Releases.

## Current Prepared Version

- `release-assets/1.0.0/ReWave-win-x64.zip`
- `release-assets/1.0.0/app-update.json`
- `release-assets/1.0.0/SHA256.txt`

## Recommended Release Flow

1. Create a Git tag like `v1.0.0`.
2. Create a GitHub Release from that tag.
3. Upload `ReWave-win-x64.zip` as a release asset.
4. Upload `app-update.json` as a release asset, or host the same JSON somewhere stable.
5. Put the manifest URL into `ReWave/app-content.json` as `appUpdateManifestUrl`.

## Example Manifest URL

If you upload `app-update.json` as a release asset for `v1.0.0`, the app can use a URL like:

`https://github.com/engix3/rewave/releases/download/v1.0.0/app-update.json`
