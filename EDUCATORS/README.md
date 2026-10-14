# Educators — OLLAMA

**Project:** OLLAMA  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `531946e9967ec00116ae12908e96ed0411f24ec5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `aa5ccf1823d64478ce2210ac76bc173badb43916888db807c69f2a86ac454660`  
**Date:** October 2026

## Teaching with OLLAMA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `aa5ccf1823d64478ce2210ac76bc173badb43916888db807c69f2a86ac454660` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
