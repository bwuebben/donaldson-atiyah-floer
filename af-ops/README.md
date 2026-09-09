# Point operations and matching-line bubbles in the Atiyah–Floer comparison

Bernd Johannes Wuebben · 8 September 2026 · 219 pages

- [Read the paper](point-operations-and-matching-line-bubbles.pdf)
- [LaTeX source](point-operations-and-matching-line-bubbles.tex)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We prove compatibility of the integral point operations in the
admissible SO(3) Atiyah–Floer comparison of Daemi, Fukaya,
and Lipyanskiy, in their embedded-Lagrangian setting.
In the positive p₁ normalization, the
symplectic point operation is shifted by 8, 4, or 0
according as the marked component has genus one, two, or
at least three. One coherent orientation system works
for both matching components. Together with the known
surface and loop comparisons and integral operation
relations, this gives the corrected observable-algebra
action over every commutative coefficient ring.
When four is invertible, quarter-Pontryagin normalization
gives the shifts 2, 1, and 0.

An index-four mixed sequence can develop a matching bubble
of normalized energy one-half. Holomorphic doubling and the
converse estimates identify compact limiting models:
degree-one stable families and single elementary modifications
of constant families. A Dirichlet construction reconstructs
these models and glues them to regular index-zero mixed
solutions. Converse gluing and the incidence conditions
identify every bubbling end of the chosen point cut.
The relative incidence degrees are eight and four in
genera one and two. Comparing the actual gluing derivative
with determinant-line excision determines their signs.
Ordinary reference orientations agree for the two homologous
matching surfaces; a local sphere comparison and a stabilized
torus example fix the genus-two normalization even when the
ambient rational Floer homology vanishes. The resulting
boundary identity uses the original integral geometric count
as its homotopy.

## Scope

The theorem retains the admissibility, irreducibility, and
embedded-Lagrangian hypotheses of the Daemi–Fukaya–Lipyanskiy comparison.
It establishes the point-operation comparison and the corrected
observable-algebra action in that setting. The bubbling analysis concerns
the ends of the chosen index-four point cut; a general ambient
compactification and higher-coherence extensions are outside the result.

The integral normalization uses the positive Pontryagin class p₁ and gives
corrections 8, 4, and 0. The corresponding quarter-Pontryagin corrections
2, 1, and 0 require a coefficient ring in which four is invertible.

## Build

The manuscript is a self-contained source file with an internal bibliography
and a separate linked contents page. From this directory, with TeX Live
and latexmk installed, run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error point-operations-and-matching-line-bubbles.tex
```

The distributed PDF and source belong to the same manuscript version.
