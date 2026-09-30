# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology II

Bernd Johannes Wuebben · 30 September 2026 · 86 pages · Draft

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
projective natural isomorphism for connected cobordisms with a framed
arc and a bundle trivialized at the ends. The symplectic maps are
signed counts of the triangles, compression cups and caps used in the
mod-two comparison. The principal additional arguments concern the
constancy of sphere-gluing signs, reflection of coherent orientations,
and the identification of the diagonal compression cup with
continuation. We keep the grading signs in the gauge orientation
convention explicit. The result allows one overall sign per cobordism;
comparison with homology-oriented integral instanton maps and with
relative-spin quilt orientations is left open.

## Status and scope

**Draft, not yet independently refereed.** The main theorem assumes the
unsigned analytic results of Paper I and no further hypothesis.

- **Proved here.**
  - The analytic foundations on the mixed domains and their completed
    limits (Proposition 2.1, proved in Appendix A).
  - Relative preparation and shifting of mixed configurations in
    families (Proposition 2.2, proved in Appendix B).
  - Ordinary determinant-one self-gluing for the regular excision data
    (Proposition 2.3).
  - The oriented torus excision theorem (Theorem 8.17), with an
    explicit integral chain homotopy whose terms are signed counts.
- **Orientation convention.** The gauge convention places conversion
  lines after generator lines. The paper does not identify it with
  Scaduto's homology-oriented integral cobordism maps, and does not
  identify the integral mixed isomorphism with the integral
  Daemi–Fukaya–Lipyanskiy isomorphism. Exact composition signs and the
  comparison with relative-spin quilt orientations remain open.
- **Coefficients.** Objects with vanishing integral homology are treated
  in the chain homotopy category.
- **Objects and cobordisms.** The paper treats connected objects with
  trivial bundles, and connected cobordisms carrying a framed arc and a
  bundle trivialized at the ends and along the arc. Disconnected
  objects, units, counits and closed pairings are not treated.

## Build

The source is self-contained and has an internal bibliography. With
TeX Live and latexmk installed, run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex
```

The distributed source and PDF belong to the same manuscript version.
