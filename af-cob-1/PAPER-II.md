# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology II

Bernd Johannes Wuebben · Revised 30 September 2026 · 82 pages · Draft

- [Read Paper II](cobordism-maps-and-atiyah-floer-isomorphisms-ii.pdf)
- [LaTeX source](cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex)
- [Paper I: coefficients in 𝔽₂](README.md)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We study the extension to integer coefficients of the cobordism
comparison between framed instanton homology and the Lagrangian Floer
homology of a Heegaard splitting. Orientations are transported from
almost-complex orientations on the gauge side through moduli spaces of
the mixed anti-self-duality and holomorphic curve equation. Assuming
the unsigned analytic results of the companion paper, we obtain a
projective natural isomorphism for connected
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

**This is a revised draft.** The principal comparison assumes the
unsigned analytic results of Paper I and no further hypothesis. The
analytic foundations on the mixed domains and their completed limits
(Proposition 2.1) are proved in Appendix A, relative preparation and
shifting in families (Proposition 2.2) in Appendix B, the oriented
comparison at torus completion in Section 8, and ordinary determinant-one
self-gluing, for the stated regular excision data, in Proposition 2.3.
The manuscript has not yet been independently refereed.

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

## Revision of 30 September 2026

The two analytic hypotheses of the previous revision are now proved.
Proposition 2.1 (Appendix A) supplies the charts, Fredholm realizations,
weights and invertibility on the mixed domains and their completed
limits, uniformly on the preglued families, together with the pure
symplectic domains and interior nodes. Proposition 2.2 (Appendix B) is
the family version of the preparation and shifting lemmas of
Daemi–Fukaya–Lipyanskiy on the domains of this paper: a collar gauge and
chart cutoffs at the ends, a positive extension of the section to the
gauge side, translation, and a straightening step. The shift ends in the
subspace of constant pairs built from any representative of the output
critical point; a single fixed constant pair cannot absorb configurations
of different topological energy. A localized form of the shift treats
triangles, folded triangles and the joined torus domains. Lemma 9.1
proves the folded form of the triangle comparison used in the cup
formula (Proposition 9.2).

## Revision of 29 September 2026

The integral mixed excision theorem (Theorem 8.17) is now proved from
the analytic inputs and Paper I, with an explicit chain homotopy whose terms
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

Former Hypothesis 2.3 became Proposition 2.3. Its
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
