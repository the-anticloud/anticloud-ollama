# Students — OLLAMA

**Project:** OLLAMA  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `531946e9967ec00116ae12908e96ed0411f24ec5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `aa5ccf1823d64478ce2210ac76bc173badb43916888db807c69f2a86ac454660`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `531946e9967ec00116ae12908e96ed0411f24ec5`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `aa5ccf1823d64478ce2210ac76bc173badb43916888db807c69f2a86ac454660`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
