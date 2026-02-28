# HydraPQ-v1 (Experimental)

HydraPQ-v1 is an **experimental** hybrid post-quantum authenticated key exchange (AKE) + AEAD record protocol draft.

**Status:** unaudited research draft (v0.1).  
**Do not use in production.**  
This repo exists to invite **cryptanalysis and critique**.

## What’s here
- [HydraPQ-v1 Spec PDF](./HydraPQ-v1_Specification_v0.1.pdf)
- [HydraPQ-v1 Spec (Markdown)](./SPEC.md)

## Threat model (high level)
- Active network attacker (Dolev–Yao)
- Adaptive message manipulation
- Post-session long-term key compromise
- No side-channel claims

## What I want feedback on
- Hybrid composition / secret mixing
- Transcript binding and downgrade resistance
- KCI resistance
- Nonce construction and misuse resistance
- Rekey rationale and limits
- Any protocol/state-machine flaws

## How to respond
Open a GitHub Issue with:
1) The section you’re referencing  
2) Attack idea / proof sketch / counterexample  
3) Suggested fix (if you have one)

Tag it with: `cryptanalysis`, `protocol`, or `implementation`.

## Disclaimer
This is a learning/research exercise. No security guarantees are made.
