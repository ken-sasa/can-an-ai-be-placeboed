# Can an AI Be Placeboed, Dressed, Stamped, and Contaminated?

Reproducibility materials for:

**Can an AI Be Placeboed, Dressed, Stamped, and Contaminated? Five Prospective Tests of Human-Like Context Effects in a Large Language Model**

Author: **Kento Sasano** (Okayama University)

Canonical public repository: **https://github.com/ken-sasa/can-an-ai-be-placeboed**

Release: **v1.0.0 (arXiv v1 reproducibility package)**

## Contents

- `paper/` — compiled arXiv manuscript and LaTeX source.
- `analysis/` — final cross-study analysis package, locked manuscript numbers, tables, figures, and rebuild script.
- `artifacts/` — six final GitHub Actions experiment artifacts used in the manuscript (956 paid API calls total).
- `CITATION.cff` — citation metadata for GitHub.
- `.zenodo.json` — Zenodo deposit metadata.
- `LICENSE` — MIT License for code.
- `DATA_LICENSE.md` — CC BY 4.0 notice for data, documentation, tables, and figures unless otherwise noted.
- `SHA256SUMS.txt` — file integrity manifest.

## Reproducibility boundary

This public package is a curated research compendium. It intentionally excludes private repository history, credentials, GitHub Actions secrets, and operational paid-run gates. All manuscript-facing numerical values are locked in the included `ARXIV_NUMBERS_LOCK.md` and are rebuildable from the archived experiment artifacts without additional API calls.

## Model scope

All six core experiments used the API model identifier `gpt-5.6-terra` with reasoning effort `medium`. The package records the returned model identifiers, task banks, manifests, result summaries, and run-freeze metadata available at execution time. It does not imply permanent reproducibility of a proprietary hosted model.

## Citation and DOI

The version-specific Zenodo DOI for release `v1.0.0` is **[10.5281/zenodo.21981010](https://doi.org/10.5281/zenodo.21981010)**. Cite this DOI for exact reproducibility.
