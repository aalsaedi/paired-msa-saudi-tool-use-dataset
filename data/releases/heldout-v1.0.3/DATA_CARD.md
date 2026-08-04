# Dataset Card: Paired MSA-Saudi Arabic Tool-Use Test Set

## Release

- Version: `heldout-v1.0.3`
- Date: `2026-08-04`
- Records: 150
- Semantic pairs: 75
- Split: `test`
- Data license: CC BY 4.0

This release contains the fixed test data used in the accompanying study.
Operational logs, individual review files, identity mappings, and other
working materials are not included.

## Content

Each scenario has one Modern Standard Arabic request and one Saudi Arabic
request under the same English tool registry and expected behavior. Saudi
Arabic is used here as an operational label for broadly intelligible,
non-region-specific informal writing. The legacy machine value
`saudi_general` is retained for compatibility and is not a linguistic claim.

The 75 pairs are evenly divided across valid calls, confusable tools, missing
required arguments, no-tool requests, and unavailable capabilities. The set
contains 30 simple, 30 compositional, and 15 adversarial pairs.

The package uses deterministic synthetic fixtures. It does not contact
external services or perform real actions.

## Construction and review

Two different assigned human request authors produced the realizations: one
authored the MSA requests and the other authored the Saudi Arabic requests.
Two independent human reviewers accepted the final language quality, semantic
equivalence, and expected behavior. Personal names and item-level review
records are not included.

Because one request author is associated with each variety, author style and
language variety cannot be separated in this dataset.

## Included files

The package includes paired records, the tool registry, deterministic
fixtures, answer contracts, record and prediction schemas, and checksums.

## Intended use

The set supports controlled evaluation of Arabic tool decisions, structured
calls, deterministic execution, clarification, and grounded final responses.

## Limitations

- One request author produced each variety, so author style and variety are
  confounded.
- The sample is not nationally representative of Saudi speakers or regions.
- Deterministic fixtures omit the variability of external services.

## Attribution

> Anonymous Dataset Authors. Paired MSA-Saudi Arabic Tool-Use Test Set,
> version 1.0.3 (2026).
