# Ethics — LEGAL_BERT

**Project:** LEGAL_BERT  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `721e9b229054333de4054f96b323f31ffc5d35ab`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `195bcac8b1fb5b463bf9eabb1f91a76d14ef3d4db9f6c3266d882cd407c13609`  
**Date:** October 2026

## Position

LEGAL_BERT is packaged for offline deployment with a verifiable audit trail. The
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
