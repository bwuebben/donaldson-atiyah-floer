# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology II: integer coefficients

Bernd Johannes Wuebben · 26 September 2026 · 38 pages · First draft

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
explicit analytic hypotheses on completed mixed domains and oriented
gluing, we obtain a projective natural isomorphism for connected
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

**This is a conditional first draft.** The principal comparison assumes
Paper I's analytic results and three additional hypotheses in Section 2:
uniform regularity and compatible Fredholm realizations on completed
mixed domains; an oriented mixed torus-completion comparison; and
nonseparating determinant-one self-gluing. Verifying these hypotheses
remains necessary for an unconditional integral theorem.

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

## Build

The source is self-contained and has an internal bibliography. With
TeX Live and latexmk installed, run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error cobordism-maps-and-atiyah-floer-isomorphisms-ii.tex
```

The distributed source and PDF belong to the same manuscript version.
