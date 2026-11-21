---
already_read: true
link: https://github.com/CocoSgt/riemann-hypothesis-lean
read_priority: 0
relevance: 5
source: lemondd
tags:
- Mathematics
type: Content
upload_date: '2026-11-21'
---

https://github.com/CocoSgt/riemann-hypothesis-lean

## Summary

A claimed formal proof of the Riemann Hypothesis and Generalized Riemann Hypothesis (for Dirichlet L-functions) in Lean, authored by Levent Alpöge with assistance from Claude, has been published as a 17.4M-line codebase.

**Proof claims**
- Proves `RiemannHypothesis` (Mathlib’s definition: all non-trivial zeros of the Riemann zeta function have real part 1/2).
- Proves `DirichletLZerosOnLine` and `PrimitiveDirichletLZerosOnLine` (GRH for Dirichlet L-functions).
- Proves `DirichletLNonvanishingRightOfHalf` (no zeros of Dirichlet L-functions with Re(s) > 1/2, excluding trivial cases).
- Proof terms: `rhOfAll`, `allChi`, `critAll`, `claimAll.2.1` in `Supplements/Kernels/MainTheorems.lean`.

**Repository scale**
- 175,187 `.lean` files, ~17.4M lines.
- Largest directories: `Development/` (12.2M lines), `Formalism/` (3.2M), `GroundTheory/` (1.1M).
- Uses Lean 4.33.1, Mathlib pinned at `0df444a360eaa60ab8c11dca51a86af692955474`.
- Build options: `maxHeartbeats = 4000000`, `--tstack=400000`.

**Verification steps**
- No `sorry`, `admit`, `axiom`, `native_decide`, or unsafe constructs found in static scan.
- `lake build Main` compiles the full proof; `#print axioms` on main theorems should list only `propext`, `Classical.choice`, `Quot.sound`.
- Recommended: independent kernel replay (e.g., `lean4checker`).
- Author’s outline of the mathematical argument in [remark.pdf](https://alpo.ge/remark.pdf) (Stepanov-style multiplicity, theta lifts, Iwasawa towers, Rallis seesaw, Bost slope inequality).

**Access**
- Mirror repo: [github.com/CocoSgt/riemann-hypothesis-lean](https://github.com/CocoSgt/riemann-hypothesis-lean) (234 MB packed, 1.3 GB checked out).
- Original archive: 14-part tarball at [alpo.ge/lean.tar.gz.part01..14](https://alpo.ge/lean.tar.gz.part01) (SHA-256: `9631b4f020199e580ba86178cb56c6e9b09f690c2369a80dc4334aa93f49c7fc`).
- Announcement: [alpo.ge/remark.pdf](https://alpo.ge/remark.pdf) (4 pages).

**Status**
- As of 2026-11-20, no independent build or review published; treat as unverified until compiled and checked.

## Links

- [Levent Alpöge's Riemann Hypothesis Proof Announcement](https://alpo.ge/remark.pdf) : A 4-page announcement by Levent Alpöge detailing the claimed proof of the Riemann Hypothesis and Generalized Riemann Hypothesis (for Dirichlet L-functions), including high-level insights into the proof strategy (e.g., Stepanov-style multiplicity, theta lifts, Iwasawa towers, and Bost slope inequality).
- [Lean 4 Proof Repository for Riemann Hypothesis](https://github.com/CocoSgt/riemann-hypothesis-lean/releases/tag/v2026-11-20) : A merged archive release of the Lean 4 formalization of the Riemann Hypothesis proof, including all source code and dependencies. This is a byte-for-byte mirror of the original proof published by Levent Alpöge.
- [Lean 4 External Proof Checker](https://github.com/leanprover/lean4checker) : A tool for independently verifying Lean 4 proofs by replaying the compiled environment, ensuring the proof does not depend on the elaborator or custom metaprograms. Recommended for validating the formalized Riemann Hypothesis proof.


## Topics

![[topics/Model/Riemann Hypothesis]]

![[topics/Model/Generalized Riemann Hypothesis]]

![[topics/Library/Lean]]

![[topics/Library/Mathlib]]