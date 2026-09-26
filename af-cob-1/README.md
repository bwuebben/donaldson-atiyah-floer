# Cobordism maps and Atiyah–Floer isomorphisms for framed instanton homology

Bernd Johannes Wuebben · 25 September 2026 · 136 pages

- [Read the paper](cobordism-maps-and-atiyah-floer-isomorphisms.pdf)
- [LaTeX source](cobordism-maps-and-atiyah-floer-isomorphisms.tex)
- [Paper II: integer coefficients, conditional first draft](PAPER-II.md)
- [Donaldson and Atiyah–Floer manuscript collection](../README.md)

## Abstract

Daemi, Fukaya and Lipyanskiy proved that the framed instanton homology
of a closed oriented three-manifold is isomorphic to the Lagrangian Floer
homology of the two handlebody Lagrangians of a Heegaard splitting. The
Lagrangians live in the moduli space of flat SO(3) connections with
w₂ ≠ 0 on the surface obtained from the Heegaard surface by adding a torus
summand. Their isomorphism counts solutions of a mixed equation, which
couples the anti-self-duality equation to the holomorphic curve equation.

We construct isomorphisms of the same type. They count solutions of the
mixed equation whose holonomy perturbations respect the ℤ/2 symmetry that
defines the framed theory. We prove that, with coefficients in 𝔽₂, they
intertwine the cobordism maps of the two theories. On the gauge side the
maps are those of Kronheimer and Mrowka. On the symplectic side they are
defined by holomorphic curves alone:

- counts of holomorphic triangles in the moduli space of the Heegaard
  surface;
- for one- and three-handles, counts in a product of two such spaces, with
  the correspondence of the compression body as a boundary condition.

The statement holds for every connected cobordism between connected
three-manifolds. The cobordism is equipped with an embedded arc joining the
ends, a framing of the arc's normal bundle, and an SO(3) bundle trivialized
over the ends and along the arc. As a consequence, the symplectic cobordism
maps are independent of the handle decomposition and of the Heegaard data,
and form a functor isomorphic to framed instanton homology. At the data where
both constructions are defined, with secondary perturbations invariant under
the ℤ/2 symmetry, our isomorphisms coincide with those of Daemi, Fukaya and
Lipyanskiy reduced modulo two.

The analytic input consists of two new results for the mixed equation.

1. **An adiabatic limit.** The metric on a compression body collapses next
   to a holomorphic strip. In the limit:
   - the compression body becomes the Lagrangian boundary condition of its
     flat connections;
   - two ends appear along which the matching surface runs to infinity;
   - the index-zero counts are unchanged;
   - a single affine relation between energy and index holds at every
     scale.

   This is a version, for the mixed equation, of the handlebody
   degeneration proposed in the programme of Salamon and Wehrheim.
2. **An excision theorem along a torus**, in a situation where no closed
   three-manifold separates the two sides.

## Scope

- **Coefficients.** The theorem is stated over 𝔽₂. Over ℤ the symplectic
  counts would need coherent orientations, compared with the homology
  orientations of the gauge side. The homological algebra used to pass from
  homology to chain homotopy also requires a field. Integer coefficients are
  treated in [Paper II](PAPER-II.md), a conditional first draft of the
  comparison over ℤ up to one sign for each cobordism, with its gauge
  orientation convention stated explicitly.
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
