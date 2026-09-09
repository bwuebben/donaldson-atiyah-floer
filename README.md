# Donaldson Theory and the Atiyah–Floer Program

Gauge-theoretic compactification, gluing, and operations in four-manifold and
Floer theory.

This repository collects research manuscripts on analytic and algebraic
structures arising in Donaldson theory, SO(3)-monopole theory, and the
Atiyah–Floer program. Each paper is distributed as a self-contained LaTeX
source file together with its compiled PDF.

## Papers

### Point operations and matching-line bubbles in the Atiyah–Floer comparison

Daemi, Fukaya, and Lipyanskiy proved the admissible embedded-Lagrangian
Atiyah–Floer comparison and its surface and loop operation compatibilities.
This paper proves compatibility of the integral point operations in that
setting. It identifies the bubbling ends of the index-four point cut,
proves converse gluing, and compares the actual gluing orientations.
In the positive integral Pontryagin normalization, the symplectic point
operation is shifted by 8, 4, or 0 when the marked component has genus one,
two, or at least three. One coherent orientation system works for both
matching components, and the original geometric count supplies the chain
homotopy. Together with the surface and loop comparisons and integral
operation relations, this gives the corrected observable-algebra action
over every commutative coefficient ring. When four is invertible,
quarter-Pontryagin normalization gives the shifts 2, 1, and 0.

The manuscript concerns the stated admissible embedded-Lagrangian setting
and does not assert a general ambient compactification or higher-coherence
extension. The current version is dated **8 September 2026** and has
**219 pages**, including a separate linked contents page.

- [PDF](af-ops/point-operations-and-matching-line-bubbles.pdf)
- [LaTeX source](af-ops/point-operations-and-matching-line-bubbles.tex)

### One-bubble neighborhoods in SO(3)-monopole moduli spaces

This paper proves an oriented neighborhood theorem at the first Uhlenbeck
level of SO(3)-monopole moduli spaces, over compact regular Seiberg–Witten
bases of arbitrary dimension whose solutions have nonzero spinor. The
obstruction zero set parametrizes an Uhlenbeck-open neighborhood of the
ideal stratum. The proof establishes strong approximation in critical
norms for arbitrary convergent one-bubble sequences, recovers the relative
frame across the neck, and identifies the standard monopole orientation
by comparison with Donaldson's instanton-addition map.

The construction supplies the analytic neighborhood input to the published
Feehan–Leness level-one link pairing. The polynomial pairing and its
low-degree consequences retain their stated topological hypotheses,
including abundance, effectiveness, and simple type for the degree
comparison. The theorem concerns one charge-one bubble over a regular
nonzero-spinor base; higher levels and collision strata require further
arguments. The current version is dated **9 September 2026** and has
**57 pages**.

- [PDF](w-glue-1/one-bubble-neighborhoods-of-seiberg-witten-strata.pdf)
- [LaTeX source](w-glue-1/one-bubble-neighborhoods-of-seiberg-witten-strata.tex)
- [Paper overview and build instructions](w-glue-1/README.md)

## Building the papers

Both manuscripts are self-contained and use standard LaTeX packages. With a
current TeX Live installation:

```bash
cd af-ops
latexmk -pdf point-operations-and-matching-line-bubbles.tex

cd ../w-glue-1
latexmk -pdf one-bubble-neighborhoods-of-seiberg-witten-strata.tex
```

The compiled PDFs are versioned intentionally so that readers can access the
papers without a local TeX installation.

## Status

These are active research manuscripts and may be revised as they receive
specialist feedback. The repository records public manuscript snapshots; the
PDF and corresponding LaTeX source in each subdirectory belong to the same
version.

## Author

Bernd Johannes Wuebben

Copyright © 2026 Bernd Johannes Wuebben. All rights reserved.
