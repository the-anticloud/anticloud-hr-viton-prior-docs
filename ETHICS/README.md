# Ethics — HR_VITON_PRIOR_DOCS

**Project:** HR_VITON_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/sangyun884/HR-VITON  
**Pinned commit:** `2715bdd687b3a07b8b8bcb3e44aa5533b28c1f15`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1b65532248d9c499cfd0dc1e539c7153fb445e96320e628d9e97eb351e8486cc`  
**Date:** October 2026

## Position

HR_VITON_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
