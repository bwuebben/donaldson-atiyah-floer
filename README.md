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
This paper treats the remaining point operation. It compactifies the
index-four matching-line boundary, proves converse gluing, and computes the
oriented contribution. In the positive quarter-Pontryagin normalization, the
symplectic point operation must be shifted by 2, 1, or 0 when the marked point
lies on a component of genus one, two, or at least three. Together with the
surface and loop results, this gives the full corrected observable-algebra
action in the admissible setting.

- [PDF](af-ops/point-operations-and-matching-line-bubbles.pdf)
- [LaTeX source](af-ops/point-operations-and-matching-line-bubbles.tex)

### One-bubble neighborhoods of Seiberg–Witten strata in SO(3)-monopole moduli spaces

Feehan and Leness constructed local gluing and obstruction maps near
Seiberg–Witten strata. Their level-one calculation also requires continuity,
embedding, surjectivity onto an Uhlenbeck-open neighborhood, and orientation
properties assigned to a companion gluing theorem and retained as a
hypothesis. This paper proves those properties at the one-bubble level over a
compact regular Seiberg–Witten moduli space of nonzero-spinor solutions, under
the stated four-manifold hypotheses. The proof combines global equivariant
stabilization, a scale-uniform augmented parametrix, parameter recovery, a
two-sided no-neck estimate, reverse gluing, and determinant-line excision.
Substitution into the published cohomological calculation yields the
arbitrary-dimensional Jacobi-polynomial pairing, with the zero-dimensional
and low-degree formulas as corollaries.

- [PDF](w-glue-1/one-bubble-neighborhoods-of-seiberg-witten-strata.pdf)
- [LaTeX source](w-glue-1/one-bubble-neighborhoods-of-seiberg-witten-strata.tex)

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
