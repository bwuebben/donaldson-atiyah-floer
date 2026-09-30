# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology II

Bernd Johannes Wuebben · Revised 29 September 2026 · 72 pages · Conditional draft

- [Read Paper II](cobordism-maps-and-atiyah-floer-isomorphisms-ii.pdf)
- [LaTeX source](cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex)
- [Paper I: coefficients in 𝔽₂](README.md)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We study the extension to integer coefficients of the cobordism
comparison between framed instanton homology and the Lagrangian Floer
homology of a Heegaard splitting. Orientations are transported from
almost-complex orientations on the gauge side through moduli spaces of
the mixed anti-self-duality and holomorphic curve equation. Subject to
an explicit analytic hypothesis on uniform Fredholm realizations and
regularity of the mixed domains, we obtain a projective natural
isomorphism for connected
cobordisms with a framed arc and a bundle trivialized at the ends.
The symplectic maps are signed counts of the triangles, compression
cups and caps used in the mod-two comparison. The principal additional
arguments concern the constancy of sphere-gluing signs, reflection of
coherent orientations, and the identification of the diagonal
compression cup with continuation. We keep the grading signs in the
gauge orientation convention explicit. The result allows one overall
sign per cobordism; comparison with homology-oriented integral instanton
maps and with relative-spin quilt orientations is left open.

## Status and scope

**This is a revised conditional draft.** The principal comparison assumes
Paper I's analytic results and one additional hypothesis in Section 2:
uniform regularity and compatible Fredholm realizations on the mixed
domains and their completed limits, including relative shifting
(Hypothesis 2.1). The oriented comparison at torus completion is not
assumed; Section 8 proves it from Hypothesis 2.1 and the unsigned analysis
of Paper I. Verifying Hypothesis 2.1 remains necessary for an
unconditional integral theorem. Ordinary determinant-one self-gluing is
proved separately as Proposition 2.2 for the stated regular excision
data.

The comparison uses the geometric symplectic maps of Paper I, with
transported orientations and one overall sign for each cobordism.
Its gauge convention places orientation-conversion lines after generator
lines. It is not identified here with Scaduto's homology-oriented
integral cobordism maps, nor is the integral mixed isomorphism identified
with the integral Daemi–Fukaya–Lipyanskiy isomorphism. Exact composition
signs and comparison with relative-spin quilt orientations remain open.
The treatment of objects with vanishing integral homology takes place
in the chain homotopy category.

The paper treats connected objects with trivial bundles and connected
cobordisms carrying a framed arc and a bundle trivialized at the ends
and along the arc. It does not treat disconnected objects, units,
counits, or closed pairings.

## Revision of 29 September 2026

The integral mixed excision theorem (Theorem 8.17) is now proved from
Hypothesis 2.1 and Paper I, with an explicit chain homotopy whose terms
are signed counts in actual one-parameter families. Sections 8.5--8.11
construct the orientation maps on the torus domains and at the closed
cut, compare them with the split reference orientations, and prove that
the folding identification is a closed map of the conversion parity.
Lemma 8.7 gives the linear gluing of determinant lines across the torus
bridge, where the cross-section runs into the mixed ends. The remaining
steps are the signed counts at large torus length, the boundary
orientation of the comparison families, and the closed-neck
identification. The oriented torus-completion hypothesis of the
previous revision is removed. Section 2.3 now states that on a completed
domain the torus tail is an end with limit the odd flat connection, and
Hypothesis 2.1 names the estimates for the weak adjoints and the
finite-width joined torus domains explicitly.

## Revision of 27 September 2026

Proposition 5.3 compares physical solution counts and determinant lines
throughout the permitted end-weight gaps. Proposition 6.4 constructs
the actual chain homotopies for changes of ordinary gauge and symplectic
end data at fixed primary data. Proposition 7.3 proves the affine-center
Fredholm square at fixed positive collapse scale, retaining nonsolutions,
moving stationary limits and both operator rows. The limiting triangle
orientations are defined by inverse collapse with the ordered cap and
strip diagrams retained. These are partial advances toward Hypotheses
2.1 and 2.2; both complete hypotheses remain assumptions.

Former Hypothesis 2.3 became Proposition 2.3 (now Proposition 2.2). Its
proof gives ordinary
nonseparating determinant-one self-gluing for the regular excision data
used in the paper, with the exact lifting multiplicity and graded trace.
The parameter-orientation conversion and the unperturbed unit-cap
calculation are explicit. The capped and inverse-excision comparisons
use the same torus end data. These ordinary gauge-theoretic arguments do
not discharge the two remaining mixed hypotheses.

The auxiliary integer grading now uses the relative class after
subtracting the endpoint action from symplectic area. For moved
primary data, these are the actual critical actions, with signs fixed
by the ordered Lagrangian pair.

The definition of an operator realization now applies a chart change
to both the equation and gauge-fixing rows. The canonical determinant
orientation assertion is restricted to regular zeros of index zero.
The affine-center comparison uses a common sufficiently small weight
in its actual indicial gaps. Uniform full mixed inverses as collapse
scale tends to zero are not asserted. Physical solution weight
independence is distinguished from the smaller admissible range of
slow nonsolution reference paths.

## Build

The source is self-contained and has an internal bibliography. With
TeX Live and latexmk installed, run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex
```

The distributed source and PDF belong to the same manuscript version.
