# Educators — HR_VITON_PRIOR_DOCS

**Project:** HR_VITON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/sangyun884/HR-VITON  
**Pinned commit:** `2715bdd687b3a07b8b8bcb3e44aa5533b28c1f15`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1b65532248d9c499cfd0dc1e539c7153fb445e96320e628d9e97eb351e8486cc`  
**Date:** October 2026

## Teaching with HR_VITON_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `1b65532248d9c499cfd0dc1e539c7153fb445e96320e628d9e97eb351e8486cc` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
