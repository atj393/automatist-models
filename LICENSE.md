# automatist-models — Licensing

This repository is a **distribution point** for on-device model files
used by the Automatist Android application. It contains two distinct
kinds of material, each governed by a different licence:

1. **Original repository content** — README, documentation, scripts,
   build/packaging tools, release metadata, and any other files
   authored for this repository by Alexis Johnson. This material is
   proprietary (see Section A below).

2. **Third-party model weights** — the compiled model task files
   (for example `gemma3-1b-it-int4.task`) attached as release assets
   or redistributed here. These are **not** original to this
   repository and **not** proprietary to Alexis Johnson. Their
   licences are the licences issued by their upstream publishers
   (see Section B below).

Nothing in Section A modifies, restricts, or overrides the licence
terms that govern the third-party model weights. In case of any
conflict, the upstream third-party licence controls with respect to
that third-party material.

---

## Section A — Original repository content (proprietary)

**Copyright © 2026 Alexis Johnson. All Rights Reserved.**

The original content authored for this repository (including but not
limited to the README, any build or packaging scripts, release
metadata, issue templates, and this LICENSE file itself) is proprietary
software and documentation. Except to the limited extent expressly
granted below, no licence is granted to copy, redistribute, or reuse
this content.

### Grant (original content only)

Subject to the restrictions below, the Licensor grants you a limited,
personal, non-exclusive, non-transferable, non-sublicensable,
revocable licence to:

1. view and clone this repository for evaluation, security review, or
   integrity verification of Automatist releases; and
2. download the model asset files published as GitHub Release assets
   of this repository, **on the strict understanding that those assets
   are governed by their upstream third-party licences (Section B),
   not by this Section A**.

### Restrictions (original content only)

You may not, without the Licensor's prior written permission:

1. copy, fork, mirror, or redistribute the original content of this
   repository (other than the third-party model files, which are
   governed by their upstream licence);
2. modify or create derivative works of the original content;
3. rebrand or republish this repository under any brand other than
   those operated by the Licensor;
4. use the "Automatist" name, logo, or trade dress in a way that
   suggests affiliation or endorsement that does not exist.

---

## Section B — Third-party model weights (upstream licence applies)

The model asset files redistributed here (in releases, the
`offline-models-v1` tag, or similar) are **not** original to this
repository and are **not** licensed by Alexis Johnson.

### Gemma 3 and Gemma 3 derivatives

Model files including, without limitation,
`gemma3-1b-it-int4.task` and `gemma3-1b-it-int4.litertlm` are
derivatives of Google's Gemma models.

- **Copyright:** © Google LLC.
- **Licence:** Gemma Terms of Use —
  https://ai.google.dev/gemma/terms
- **Prohibited use policy:** Gemma Prohibited Use Policy —
  https://ai.google.dev/gemma/prohibited_use_policy

By downloading, copying, or using a Gemma-derived model file
redistributed via this repository, you agree to the Gemma Terms of
Use and the Gemma Prohibited Use Policy. Those terms include
(among other things) obligations relating to prohibited uses,
attribution of the upstream model, and use of the Gemma name.

**This repository does not grant you any rights in the Gemma model
weights beyond those you already have under the Gemma Terms of
Use.** The Licensor of this repository is redistributing a permitted
variant of a third-party model and makes no claim of ownership or
re-licensing over those weights.

The canonical copies of the Gemma licence texts applicable to these
files are available at the URLs above and are reproduced in this
repository as [`GEMMA_TERMS.md`](GEMMA_TERMS.md) and
[`GEMMA_PROHIBITED_USE_POLICY.md`](GEMMA_PROHIBITED_USE_POLICY.md)
for convenience; the authoritative texts are the ones published by
Google.

### Other third-party models

Any other third-party model files distributed here in the future will
be listed in [`THIRD_PARTY_MODELS.md`](THIRD_PARTY_MODELS.md) together
with their upstream publisher, licence, and link. Those licences will
apply to those files in the same way the Gemma terms apply to the
Gemma files.

---

## Section C — What this repository does **not** claim

To avoid any ambiguity, Alexis Johnson and this repository do **not**:

- claim authorship of the Gemma model weights;
- claim to sublicense the Gemma weights under a different licence;
- assert that the proprietary terms in Section A override, replace,
  or restrict the Gemma Terms of Use or any other upstream model
  licence;
- warrant the accuracy, safety, or suitability of model outputs.

---

## Contact

**Alexis Johnson**
Email: alexistoby393@gmail.com
Automatist: https://automatist.cloud
