# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology I

Bernd Johannes Wuebben · First version 25 September 2026 · This version 7 October 2026 · 151 pages

- [Read the paper](cobordism-maps-and-atiyah-floer-isomorphisms.pdf)
- [LaTeX source](cobordism-maps-and-atiyah-floer-isomorphisms.tex)
- [Paper II: integer coefficients](PAPER-II.md)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

We prove that isomorphisms of the type constructed by Daemi, Fukaya and
Lipyanskiy, between framed instanton homology and the Lagrangian Floer
homology of a Heegaard splitting, intertwine the cobordism maps of
Kronheimer and Mrowka with maps defined by holomorphic curves alone, over
the field of two elements. This holds for every connected cobordism between
connected three-manifolds carrying a framed arc between its ends and an
SO(3) bundle trivialized along the ends and the arc. The symplectic maps
count holomorphic triangles in moduli spaces of flat connections on
surfaces, with the correspondence of a compression body as boundary
condition for one- and three-handles. Consequently these maps are
independent of the handle decomposition and of the Heegaard data, and form
a functor isomorphic to framed instanton homology; where both are defined,
our isomorphisms agree with those of Daemi, Fukaya and Lipyanskiy modulo
two. The proof rests on two analytic results for the mixed
anti-self-duality and holomorphic curve equation: an adiabatic limit in
which a compression body collapses next to a holomorphic strip and becomes
the Lagrangian boundary condition of its flat connections, and an excision
theorem along a torus.

## Scope

- **Coefficients.** The theorem is stated over 𝔽₂. Over ℤ the symplectic
  counts would need coherent orientations, compared with the homology
  orientations of the gauge side. The homological algebra used to pass from
  homology to chain homotopy also requires a field. Integer coefficients are
  treated in [Paper II](PAPER-II.md), the comparison over ℤ
  up to one sign for each cobordism, which builds on the unsigned
  analysis of this paper and states its gauge orientation convention explicitly.
- **Objects.** The objects are connected and carry the trivial bundle on
  the original three-manifold. Disconnected objects, units and counits, and
  closed pairings are not treated.
- **The isomorphisms.** They are constructed by the method of Daemi, Fukaya
  and Lipyanskiy, with perturbations invariant under the framed symmetry.
  Where both constructions are defined, they coincide with the
  Daemi–Fukaya–Lipyanskiy isomorphism reduced modulo two, as chain maps. At
  admissible presentations with such data, the main theorem therefore holds
  for that isomorphism itself. Such presentations exist at the fixed metric
  data used here, without rescaling the metric (Appendix C): the
  perturbations are built from holonomy traces of disjoint solid tori, and a
  unique continuation argument on torus collars supplies the transversality.

## Build

The manuscript is a self-contained source file with an internal
bibliography. From this directory, with TeX Live and latexmk installed,
run:

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error cobordism-maps-and-atiyah-floer-isomorphisms.tex
```

The distributed PDF and source belong to the same manuscript version.
