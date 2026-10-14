# Educators — LEGAL_BERT

**Project:** LEGAL_BERT  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `721e9b229054333de4054f96b323f31ffc5d35ab`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `195bcac8b1fb5b463bf9eabb1f91a76d14ef3d4db9f6c3266d882cd407c13609`  
**Date:** October 2026

## Teaching with LEGAL_BERT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `195bcac8b1fb5b463bf9eabb1f91a76d14ef3d4db9f6c3266d882cd407c13609` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
