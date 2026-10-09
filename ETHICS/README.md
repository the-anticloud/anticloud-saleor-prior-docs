# Ethics — SALEOR_PRIOR_DOCS

**Project:** SALEOR_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/saleor/saleor  
**Pinned commit:** `bb75f87973abe24056a5d0dff1708ca097e95599`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dc7cf21cb85c3a9dae325aec9dbbdb87f3b28bba8f4e50b49af5071a10057f8d`  
**Date:** October 2026

## Position

SALEOR_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
