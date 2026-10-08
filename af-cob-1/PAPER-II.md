# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology II

Bernd Johannes Wuebben · First version 30 September 2026 · This version 8 October 2026 · 106 pages

- [Read Paper II](cobordism-maps-and-atiyah-floer-isomorphisms-ii.pdf)
- [LaTeX source](cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex)
- [Paper I: coefficients in 𝔽₂](README.md)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We prove that the mixed isomorphisms of Daemi, Fukaya and Lipyanskiy type
between framed instanton homology and the Lagrangian Floer homology of a
Heegaard splitting intertwine the integral instanton cobordism maps,
oriented by almost-complex structures, with signed symplectic cobordism
maps, up to chain homotopy and one overall sign for each cobordism. This
holds for every connected cobordism between connected three-manifolds
carrying a framed arc and an SO(3) bundle trivialized along the ends and
the arc. Where the integral framed instanton homology is nonzero, the
symplectic maps are signed counts of holomorphic triangles, with the
Lagrangian correspondence of a compression body as one boundary condition
for one- and three-handles. At three-manifolds whose integral framed
instanton homology vanishes, the complexes are contractible and the maps
are zero. The orientations are transported from the gauge theory through
the mixed anti-self-duality and holomorphic curve equation. Consequently
these maps form a projective functor on homology, independent of the
handle decomposition up to sign. The unsigned analysis is that of the
comparison modulo two; the new input is that two degenerations of the
mixed equation, the collapse of a compression body and excision along a
torus, preserve orientations, and that where this homology is nonzero the
sign by which the orientations change when a sphere is attached to a strip
is constant under small perturbations and invariant under reversing the
splitting. The relation with homology-oriented integral instanton maps is
left open.

## Main results

- **Theorem A (integral comparison).** The mixed maps are isomorphisms of
  finite free integral complexes and intertwine the integral gauge
  cobordism maps with the signed symplectic maps, up to chain homotopy and
  one sign for each cobordism. On homology the symplectic maps form a
  projective functor, and reduction modulo two recovers the maps of
  Paper I.
- **Theorem B (orientations under collapse).** The collapse bijection of
  Paper I, between mixed solutions at small collapse scale and solutions
  of the limiting problem, preserves the transported orientations,
  compatibly with gluing and in families.
- **Theorem C (oriented torus excision; Theorem 8.15).** After the
  conversion at the cut, the mixed map of the folded pair composed with
  reverse excision is chain homotopic over ℤ, up to one sign, to the
  tensor product of the mixed maps of the two sides.
- **Theorem D (reflection and the diagonal cup).** Where the integral
  framed instanton homology is nonzero, the sign of attaching a sphere to
  a strip does not depend on the small perturbation and is unchanged when
  the two compression bodies are exchanged. The resulting duality between
  the complexes of the splitting and its reverse identifies the
  compression cup of the trivial compression body with continuation, up
  to chain homotopy and one sign.

## Status and scope

**Not yet independently refereed.** The proof uses the unsigned analytic
results of Paper I: compactness, gluing, the collapse theorem and torus
excision.

- **Proved here.**
  - The analytic foundations on the mixed domains and their completed
    limits (Proposition 2.1, proved in Appendix A).
  - Relative preparation and shifting of mixed configurations in
    families (Proposition 2.2, proved in Appendix B).
  - Ordinary integral excision: determinant-one self-gluing along the
    torus cut, and the fact that the Kronheimer–Mrowka excision and
    reverse excision maps are inverse over ℤ up to one sign
    (Proposition 2.3 and Proposition D.3, proved in Appendix D).
- **Orientation convention.** The almost-complex convention for the gauge
  maps is part of the statement. The paper does not identify it with
  Scaduto's homology-oriented integral cobordism maps, does not identify
  the integral mixed isomorphism with the integral Daemi–Fukaya–Lipyanskiy
  isomorphism, and does not compare the transported orientations with the
  relative-spin orientations of quilted Floer theory.
- **Coefficients.** Objects with vanishing integral homology are treated
  in the chain homotopy category: their complexes are contractible and the
  maps incident to them are zero.
- **Objects and cobordisms.** The paper treats connected objects with
  trivial bundles, and connected cobordisms carrying a framed arc and a
  bundle trivialized at the ends and along the arc. Disconnected objects,
  units, counits and closed pairings are not treated.

## Build

The source is self-contained and has an internal bibliography. With
TeX Live and latexmk installed, run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex
```

The distributed source and PDF belong to the same manuscript version.
