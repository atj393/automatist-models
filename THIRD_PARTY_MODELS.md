# Third-Party Models Distributed Here

This repository redistributes compiled / converted variants of
third-party machine-learning models as GitHub Release assets so that
the Automatist Android application can download them on demand.

The model files are **not** original work of this repository. Each file
remains governed by the licence issued by its upstream publisher. The
table below lists the files, their upstream model, publisher, and
licence. For the full legal text, follow the licence links.

---

## Catalogue

| File | Upstream model | Publisher | Licence | Prohibited-use policy |
|------|----------------|-----------|---------|-----------------------|
| `gemma3-1b-it-int4.task` | Gemma 3 1B (instruction-tuned, int4, MediaPipe `.task` package) | Google LLC | [Gemma Terms of Use](https://ai.google.dev/gemma/terms) | [Gemma Prohibited Use Policy](https://ai.google.dev/gemma/prohibited_use_policy) |
| `gemma3-1b-it-int4.litertlm` | Gemma 3 1B (instruction-tuned, int4, LiteRT LM format) | Google LLC | [Gemma Terms of Use](https://ai.google.dev/gemma/terms) | [Gemma Prohibited Use Policy](https://ai.google.dev/gemma/prohibited_use_policy) |

### Notes

- **Derivative of Gemma.** The files above are compiled / quantized
  variants of Google's Gemma 3 model. Per the Gemma Terms of Use, the
  obligations that apply to Gemma also apply to these variants.
- **No re-licensing.** These files are redistributed under the Gemma
  Terms of Use, not under the proprietary licence that governs the
  original content of this repository.
- **Integrity.** The Automatist app verifies the SHA-256 of
  `gemma3-1b-it-int4.task` against a value pinned in the app
  (`OfflineModelCatalog`). Do not replace the release asset without
  also updating the pinned hash in the app.

---

## Adding a new third-party model

If a future release publishes an additional third-party model, add a
row to the table above **before** attaching the release asset. Each
entry must include:

1. the exact filename as released,
2. the upstream model name and version,
3. the upstream publisher,
4. the licence name with a direct link to the authoritative upstream
   text, and
5. any applicable prohibited-use / acceptable-use policy.

If an upstream publisher does not offer a public, linkable licence for
the file you intend to redistribute, **do not** release it here. The
entire purpose of this repository is to be honest about upstream
licensing.
