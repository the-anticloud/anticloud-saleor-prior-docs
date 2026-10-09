# Educators — SALEOR_PRIOR_DOCS

**Project:** SALEOR_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/saleor/saleor  
**Pinned commit:** `bb75f87973abe24056a5d0dff1708ca097e95599`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dc7cf21cb85c3a9dae325aec9dbbdb87f3b28bba8f4e50b49af5071a10057f8d`  
**Date:** October 2026

## Teaching with SALEOR_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `dc7cf21cb85c3a9dae325aec9dbbdb87f3b28bba8f4e50b49af5071a10057f8d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
