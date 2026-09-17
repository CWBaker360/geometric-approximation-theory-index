# Working Publication Roadmap

_Last updated: September 17, 2026._

This is a dependency-aware research and release map. All staged repositories listed here are intended for eventual public release, but their timing is deliberately staggered rather than fixed. A roughly one-at-a-time cadence can be used to give each paper its own release, infographic, and public-facing discussion, while preserving the option to reorder releases after a fresh pre-release audit.

## Phase I - Cubic angle division

1. `constructible-cubic-trisection` - **Public**
2. `proportional-subtended-cubic-refinement` - **Public**

These establish the constructible seed construction and the generalized local cubic law.

## Phase II - Core N-Series geometry

3. `nseries-pi-acceleration` - **Public**
4. `scaling-cancellation-principle` - **Public; revised v2 released 2026-09-11**
5. `scale-optimized-polygonal-pi-acceleration` - **Public**
6. `spherical-nseries-area-law` - **Public**
7. `constructible-tower-approaching-pi` - Staged

The revised scaling-cancellation paper contains the two-scale theorem, the full multi-scale Lagrange-weight formulation, the geometric-node surviving factor \(b^{-s(s+1)}\), and the equivalent recursive fixed-base ladder. Its claim boundary explicitly identifies the arithmetic as Richardson-Romberg extrapolation while separating that mechanism from nonlinear cubic residual refinement.

The scale-optimized polygonal paper develops the general scale-\(b\) architecture, stability bounds, remainder control, scale optimization, and constructibility boundaries. The spherical paper applies the same conditional moment-cancellation mechanism to curved-surface area; its general spherical even-power law remains conjectural outside the tested regular families.

The constructible tower records a related field-theoretic consequence of the polygonal hierarchy and remains staged until selected for a future release slot.

## Phase III - Verification and exposition

8. `baker-geometric-pi-verification` - Staged
9. `classical-appearances-of-pi-g` - Staged
10. `ramanujan-pi-nseries-geometric-constant` - Staged

These repositories are planned future releases. Their relative order may be adjusted to keep the public sequence coherent and to ensure each archive passes a current metadata, licensing, citation, and reproducibility audit.

## Phase IV - AGM and modular comparisons

11. `agm-prefactor-coefficient-law` - Staged
12. `ramanujan-landen-nseries-refinement` - Staged

## Phase V - Ellipse sequence

13. `universal-scaling-law-ellipse-perimeters` - Staged
14. `ramanujan-ellipse-nseries-comparison` - Staged
15. `ramanujan-ellipse-residual-geometry` - Staged

## Phase VI - Curved cubic refinement

16. `curvature-deformed-arcsine` - **Public**

This branch extends the cubic-refinement program from flat geometry to intrinsic curved-surface geometry. The public manuscript develops an exact spherical curvature-deformed arcsine and analytic variable-curvature structure through geometric weight five. The general weight-six side law is supported by high-precision rational reconstruction, with an independent analytic degree-eight two-point geodesic-distance derivation remaining open.

## Current public-release checkpoint

As of September 17, 2026, the public research repositories represented in this index are:

- `constructible-cubic-trisection`;
- `proportional-subtended-cubic-refinement`;
- `nseries-pi-acceleration`;
- `scaling-cancellation-principle`;
- `scale-optimized-polygonal-pi-acceleration`;
- `spherical-nseries-area-law`;
- `curvature-deformed-arcsine`.

The next staged release is selected separately from this dependency map. The intended cadence is deliberately spaced rather than simultaneous, and no calendar date is committed until the selected repository passes its release audit.

## Minimum release package

Before a staged repository is made public, confirm:

- synchronized authoritative TeX/PDF pair;
- repository identity and title match across README, paper, `CITATION.cff`, and any Zenodo deposit;
- explicit rights/license files, with GitHub and Zenodo license metadata consistent;
- reproducibility instructions and retained verification artifacts where applicable;
- explicit claim-boundary statement;
- current checksums regenerated after final metadata changes;
- final cross-repository citations;
- working internal and external links;
- no copied metadata or files from another repository;
- Zenodo DOI added back to citation metadata after deposit when applicable.
