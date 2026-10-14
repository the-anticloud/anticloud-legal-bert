# Students — LEGAL_BERT

**Project:** LEGAL_BERT  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `721e9b229054333de4054f96b323f31ffc5d35ab`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `195bcac8b1fb5b463bf9eabb1f91a76d14ef3d4db9f6c3266d882cd407c13609`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `721e9b229054333de4054f96b323f31ffc5d35ab`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `195bcac8b1fb5b463bf9eabb1f91a76d14ef3d4db9f6c3266d882cd407c13609`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
