# Automatist Models

Downloadable AI model assets for the [Automatist](https://play.google.com/store/apps/details?id=com.automatist.app) Android app.

> **Two kinds of content, two different licences.** The original
> repository content (README, metadata, this file) is proprietary —
> © 2026 Alexis Johnson, All Rights Reserved. The redistributed model
> weight files are **not** proprietary: each one remains governed by
> its upstream licence (e.g. the Gemma Terms of Use for Gemma weights).
> See [LICENSE.md](LICENSE.md) for the full split.

## Distribution

Models are distributed as **GitHub Release assets**. The app downloads them on-demand over HTTPS — no authentication required.

## Available Models

| Model | File | Format | Size | Release |
|-------|------|--------|------|---------|
| Gemma 3 1B IT (int4) | `gemma3-1b-it-int4.task` | MediaPipe Task Bundle | ~529 MB | [offline-models-v1](https://github.com/atj393/automatist-models/releases/tag/offline-models-v1) |

See [THIRD_PARTY_MODELS.md](THIRD_PARTY_MODELS.md) for the full catalogue with upstream publisher and licence per file.

## Integrity Verification

Each release includes SHA-256 checksums. The app verifies file integrity after download automatically. Release tags are considered permanent — Automatist pins the SHA-256 in `OfflineModelCatalog` before shipping, and deleting or renaming a tag breaks downloads for existing installs.

## Licensing

This repository contains two distinct kinds of material, each governed by a different licence. The separation is deliberate and must not be collapsed.

**1. Original repository content** (README, docs, metadata, release notes, this file) — **proprietary**. © 2026 Alexis Johnson. All Rights Reserved. See [LICENSE.md](LICENSE.md), Section A.

**2. Third-party model weights** (e.g. `gemma3-1b-it-int4.task`) — **not** proprietary to this repository. Each file remains governed by the licence issued by its upstream publisher. For the Gemma files, those licences are:

- [Gemma Terms of Use](https://ai.google.dev/gemma/terms)
- [Gemma Prohibited Use Policy](https://ai.google.dev/gemma/prohibited_use_policy)

By downloading a Gemma-derived model file from this repository, you agree to the upstream Gemma terms. Alexis Johnson does not claim ownership of Gemma, does not re-license Gemma weights, and does not grant any rights in those weights beyond those already granted by the upstream Gemma licence. See [LICENSE.md](LICENSE.md), Section B and [THIRD_PARTY_MODELS.md](THIRD_PARTY_MODELS.md).

## Adding Models

New models are added as assets to new or existing releases. Older releases are preserved to avoid breaking existing app versions. Before attaching a new asset:

1. Add a row to [THIRD_PARTY_MODELS.md](THIRD_PARTY_MODELS.md) with filename, upstream model, publisher, and upstream licence link.
2. If the upstream publisher does not offer a public, linkable licence for the file, do **not** redistribute it here.
3. Coordinate the SHA-256 pin in the app's `OfflineModelCatalog`.

## Contact

Licensing, permission, and commercial enquiries:

**Alexis Johnson** — alexistoby393@gmail.com — https://automatist.cloud
