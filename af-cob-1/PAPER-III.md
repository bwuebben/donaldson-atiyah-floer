# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology III

Bernd Johannes Wuebben · First version 26 October 2026 · This version 29 October 2026 · 32 pages

- [Read Paper III](cobordism-maps-and-atiyah-floer-isomorphisms-iii.pdf)
- [LaTeX source](cobordism-maps-and-atiyah-floer-isomorphisms-iii.tex)
- [Abstract and citation](https://bwuebben.github.io/papers/af-cobordism-iii/)
- [Paper I](README.md) · [Paper II](PAPER-II.md)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We construct integral chain homotopy equivalences intertwining the usual
framed instanton cobordism maps in the singular Hopf-link construction
with symplectic cobordism maps oriented by transport from gauge theory.
At common regular small data, the equivalences are represented by the
Daemi–Fukaya–Lipyanskiy mixed count with a specified coherent
orientation. For connected framed cobordisms, they are natural up to
integral chain homotopy and one overall sign, with an explicit grading
conversion, and extend by geometric changes of presentation. We also
construct equivalences to the normalization in which attachment of a
generating sphere in the surface moduli space preserves orientation, for
every closed connected oriented three-manifold. Surgery generation gives
a finite model built from one-generator complexes for the three-sphere.
Counts through the three-sphere realize its grading-preserving matrix
entries, so an algebraically chosen normalization becomes a finite
integer linear combination of products of geometric counts. A polynomial
in forward and reflected mixed counts transfers this construction to the
symplectic complex. The proof uses the companion analytic and naturality
results and the stated ordinary surgery and oriented gluing inputs.
Identification with prescribed relative-spin maps and the nonsingular
cap convention remains open.

## Results and scope

Theorem A compares the usual singular Hopf-link gauge maps with the
actual DFL mixed count in a gauge-calibrated coherent orientation
system. It gives projective naturality in the integral chain homotopy
category, after an explicit strict-to-graded conversion. The comparison
at common data extends by geometric changes of presentation.

Theorem B constructs sphere-positive normalization for every closed
connected oriented three-manifold with the stated framing data,
including nonempty acyclic complexes. Its maps are finite integer
linear combinations of products of ordinary gauge counts, parameterized
surgery counts, geometric symplectic words, and forward and reflected
mixed counts. The coefficients are algebraic and noncanonical. The
surgery generation input is Ni's published Theorem 1.4.

The results use Papers I–II's analytic and naturality constructions,
the ordinary surgery triangle, and the oriented gluing inputs stated
in Section 7.1, including the augmented determinant factorization at
the reducible cut. The paper specifies the common smallness and
regularity hypotheses; it does not extend the DFL mixed problem
outside its analytic domain.

Two further projects remain: comparison with Scaduto's nonsingular
cap convention and with a prescribed compatible relative-spin system
for strips, cups, caps, triangles and stabilization. The constructed
positive presentation maps do not identify those prescribed operations.
The manuscript remains a preprint awaiting specialist refereeing.

## Reading route

The introduction states both main theorems, separates the contributions
of DFL and Papers I–III in a table, and gives a proof-dependency figure.
Sections 3–5 prove Theorem A. Sections 6–11 construct and transport the
normalization in Theorem B. Section 9.3 gives a two-generator integral
example with torsion homology and its realization through sphere
factors. Section 12 states the two remaining comparisons.

## Build

The source is self-contained with an internal bibliography and a
TikZ dependency figure. With TeX Live and latexmk:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error cobordism-maps-and-atiyah-floer-isomorphisms-iii.tex
```

The source and PDF belong to the same manuscript version.

Copyright © 2026 Bernd Johannes Wuebben. All rights reserved.
