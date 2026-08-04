# Paired MSA-Saudi Arabic Tool-Use Test Set

This repository contains a controlled test set for tool use in Modern
Standard Arabic (MSA) and Saudi Arabic.

## Current release

- Version: `heldout-v1.0.3`
- Date: `2026-08-04`
- Records: 150
- Semantic pairs: 75
- Split: `test`
- Records SHA-256: `1239ae0cdf24f6343d574c9b04477259650221a1f1bfa932b38c7f139af41e34`
- License: CC BY 4.0

Each scenario has one MSA request and one Saudi Arabic request with the same
tool environment and expected behavior. The pairs are evenly divided across
valid calls, confusable tools, missing required arguments, no-tool requests,
and unavailable capabilities.

Two different assigned human request authors produced the two varieties, one
author per variety. Two independent human reviewers accepted the final pairs.
Personal identities and individual review files are not included.

The current repository intentionally contains only the release manifest and
the files needed to use and validate the test set.

See `data/releases/heldout-v1.0.3/DATA_CARD.md` for scope and limitations.
