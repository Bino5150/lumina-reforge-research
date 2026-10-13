# Lumina Reforge — Research Preprint

*Clean the workbench. Keep the blueprint.*

[![Zenodo DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23328779.svg)](https://doi.org/10.5281/zenodo.23328779)

**Paper:** *Lumina Reforge: Transactional Context Reconstruction for Long-Lived AI Agents*

| | |
|---|---|
| Author | Jason “BINO” Malik — Independent Developer, Lumina Project |
| Version | Working preprint v1.0 · 12 October 2026 · **Not peer reviewed** |
| Research repository | https://github.com/Bino5150/lumina-reforge-research |
| Lumina implementation | https://github.com/Bino5150/lumina |
| Research DOI (preprint v1.0) | [10.5281/zenodo.23328779](https://doi.org/10.5281/zenodo.23328779) |

**Read the research:** [PDF](Lumina_Reforge_Preprint_v1.pdf) · [Editable Markdown manuscript](manuscript.md) · [Evidence index](EVIDENCE_INDEX.md)

## Abstract in brief

Lumina Reforge is an owner-triggered transactional reconstruction mechanism that replaces an execution-heavy active workbench with a bounded context derived from an unchanged durable conversation and a provenance-aware continuity checkpoint. Exact checkpoint and state binding, machine-grounded facts, and transactional guards prevent stale or invalid rebuilds from replacing the active working state.

In two retrospectively documented operational cases, estimated **total active context** fell by **62.2% and 76.6%**. A separate owner-operated shakedown measured an **82.8% reduction in estimated live-history tokens**, a different denominator. The durable transcript remained unchanged in the reported tests. A blind continuity probe recovered durable identifiers and declined to invent missing telemetry but **failed to preserve one task-critical exact ephemeral detail**.

These are reported measurements from operational evaluation, **not independent replication or a controlled comparison** against other compaction methods. No lossless-preservation, repeat-cycle fidelity, measured billing-savings, or latency-improvement claim is made.

## Figures and evidence

- [Figure 1 — Transactional reconstruction pipeline](figures/figure1_reconstruction_pipeline.png)
- [Figure 2 — Reported context reductions](figures/figure2_reductions.png)
- [Evidence and reproducibility boundaries](EVIDENCE_INDEX.md)
- [Lumina software and implementation](https://github.com/Bino5150/lumina)

The original experimental reports are maintained by the Lumina project. This repository does not claim to release every underlying private receipt or a fully reproducible evaluation harness.

## Citation

For the archived **version 1.0**, cite the Zenodo preprint ([10.5281/zenodo.23328779](https://doi.org/10.5281/zenodo.23328779)):

> Malik, Jason “BINO” (2026). *Lumina Reforge: Transactional Context Reconstruction for Long-Lived AI Agents*. Working preprint, version 1.0. Zenodo. https://doi.org/10.5281/zenodo.23328779

See [`CITATION.cff`](CITATION.cff) for machine-readable citation metadata. The linked Zenodo DOI identifies the deposited version 1.0; future versions may have their own version-specific DOIs.

## AI assistance and responsibility

ChatGPT assisted with literature identification, editorial drafting, figures, and layout. The human author is responsible for reviewing the accuracy, evidence, and submission. No additional experiments were run solely to prepare the manuscript.

## License

Copyright © 2026 Jason “BINO” Malik.

The **original research manuscript, original figures, and original research documentation** in this repository are available under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), subject to the terms in [LICENSE](LICENSE). Third-party material retains its own rights.

**Software is separate:** this document license does not apply to the Lumina application's source code at https://github.com/Bino5150/lumina, which is governed by its own applicable license terms.

Subsequent paper revisions should clearly identify their version, preserve the historical record, and document any newly collected evidence.
