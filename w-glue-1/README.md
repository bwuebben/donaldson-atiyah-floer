# One-bubble neighborhoods in SO(3)-monopole moduli spaces

Bernd Johannes Wuebben · 9 September 2026 · 57 pages

- [Read the paper](one-bubble-neighborhoods-of-seiberg-witten-strata.pdf)
- [LaTeX source](one-bubble-neighborhoods-of-seiberg-witten-strata.tex)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We prove an oriented neighborhood theorem at the first Uhlenbeck level
of SO(3)-monopole moduli spaces, over a compact regular
Seiberg–Witten moduli space of arbitrary dimension whose solutions have
nonzero spinor. A finite-dimensional obstruction model admits an
equivariant compactified embedding that maps the obstruction zero set
homeomorphically onto an Uhlenbeck-open neighborhood of the ideal stratum;
its restriction to that zero set at
positive scale is a diffeomorphism onto its image. The principal analytic
step is a strong approximation theorem in critical norms for arbitrary
convergent one-bubble monopole sequences. Uniform gauge estimates and
summable decay along the neck recover the gluing parameters, including
the relative frame, and give reverse uniqueness. A global equivariant
stabilization treats the background family without requiring a
constant-rank spectral cutoff. Comparison with Donaldson's
instanton-addition map identifies the induced orientation with the
standard monopole orientation. Under the additional topological
hypotheses of Feehan and Leness, the construction supplies the analytic
neighborhood input to their level-one link pairing. We state the
resulting polynomial formula and its low-degree consequences for
abundant, effective manifolds of Seiberg–Witten simple type.

## Scope

The four-manifold hypotheses include b₁(X)=0 and odd b₂⁺(X)≥3, with
generic perturbations and a compact regular Seiberg–Witten stratum of
nonzero-spinor solutions. Transversality holds on the positive-scale and
middle zero-scale strata. The obstruction section vanishes identically
on the lowest stratum, where no transversality is asserted.

The degree comparison additionally assumes abundance, effectiveness, and
Seiberg–Witten simple type, with the characteristic data specified in the
paper. Effectiveness retains a hypothesis about link pairings at all
relevant levels. Nonregular bases, zero-spinor solutions, collision strata,
and higher-level neighborhood theorems are outside the present result.

## Build

The manuscript is a self-contained source file with an internal bibliography.
From this directory, with TeX Live and latexmk installed, run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error one-bubble-neighborhoods-of-seiberg-witten-strata.tex
```

The distributed PDF and source belong to the same manuscript version.
The artifact filenames are retained for continuity with earlier versions.
