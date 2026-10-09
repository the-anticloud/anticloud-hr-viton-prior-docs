# Students — HR_VITON_PRIOR_DOCS

**Project:** HR_VITON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/sangyun884/HR-VITON  
**Pinned commit:** `2715bdd687b3a07b8b8bcb3e44aa5533b28c1f15`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1b65532248d9c499cfd0dc1e539c7153fb445e96320e628d9e97eb351e8486cc`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2715bdd687b3a07b8b8bcb3e44aa5533b28c1f15`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `1b65532248d9c499cfd0dc1e539c7153fb445e96320e628d9e97eb351e8486cc`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
