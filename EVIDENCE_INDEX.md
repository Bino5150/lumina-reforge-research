# Evidence index and disclosure boundary

This index is an orientation aid for readers, not a released raw dataset.

- **Implementation repository:** https://github.com/Bino5150/lumina
- **Owner-facing `/context rebuild` release commit:** https://github.com/Bino5150/lumina/commit/3c72e016490a8672478f18ae27dc8f08465d3905
- **Foundational context-lifecycle commit:** https://github.com/Bino5150/lumina/commit/2682ce31b713ffdbc8be4105128555a6c09bb9a2
- **Source-vetted transaction code:** https://github.com/Bino5150/lumina/blob/fa1202b136c0ef2446bd208a41517057b0cea2e5/core/context_transaction.py
- **Source-vetted reconstruction kernel:** https://github.com/Bino5150/lumina/blob/fa1202b136c0ef2446bd208a41517057b0cea2e5/core/context_reconstruction.py

## Retrospective case reports described in the manuscript

| Case | Metric | Reported result | Limitation |
|---|---|---|---|
| A6M shakedown | Estimated live-history tokens | ~31.9k → ~5.5k (82.8%) | Different denominator from total active context |
| Chat 134 | Estimated total active context | ~239.1k → ~90.4k (62.2%) | Before-test answers had entered durable history |
| Cycle 02 | Estimated total active context | ~519.6k → ~121.5k (76.6%) | Strict B missed exact ephemeral continuation detail |

The original technical reference lists privately held artifacts such as `LUMINA_REFORGE_CYCLE_02_EMPIRICAL_VALIDATION_2026-09-14.md`. These private files are **not** included in this public package and have not been represented as independently released datasets.

## Evidence claims explicitly NOT made

- No measured superiority over prompt compaction or another agent-memory system.
- No guarantee of lossless factual/semantic/code preservation.
- No controlled repeated-cycle fidelity benchmark.
- No measured GPU memory, latency, provider billing, or cache-cost savings.
- No claim of peer review or independent experimental replication.

**Evidence reconciliation:** The headline numbers and documented limitations were checked against the original retained A6M, Chat 134, and Cycle 02 evaluation reports on 2026-10-13. This is source-report reconciliation, **not independent experimental replication from raw runtime logs**; the private experiment artifacts are not included in this public repository.
