# Students — SALEOR_PRIOR_DOCS

**Project:** SALEOR_PRIOR_DOCS  
**Category:** CLOTHING_RETAIL  
**Upstream:** https://github.com/saleor/saleor  
**Pinned commit:** `bb75f87973abe24056a5d0dff1708ca097e95599`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dc7cf21cb85c3a9dae325aec9dbbdb87f3b28bba8f4e50b49af5071a10057f8d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `bb75f87973abe24056a5d0dff1708ca097e95599`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `dc7cf21cb85c3a9dae325aec9dbbdb87f3b28bba8f4e50b49af5071a10057f8d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
