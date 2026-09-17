# Geometric Approximation Theory - Repository Index

**Author:** C. Wayne Baker  
**GitHub account:** `CWBaker360`  
**Status:** Research-portfolio index  
**Repository count:** 16 paper and verification repositories  
**Last updated:** September 17, 2026

This repository is the master index for the **Geometric Approximation Theory** archive. It records the scope, dependency structure, publication status, and claim boundaries of a connected program in geometric approximation, error cancellation, constructibility, curved geometric refinement, spherical area refinement, AGM/Ramanujan comparison, and ellipse geometry.

## Current status

The 16 repositories below are maintained as distinct, claim-bounded research archives. Public repositories are available directly. **Staged** repositories are intentionally private and are not implied to be scheduled for public release; they may remain private while their role, synchronization, reproducibility records, cross-citations, or release metadata are reviewed.

| No. | Repository | Track | Current status |
|---:|---|---|---|
| 1 | [`constructible-cubic-trisection`](https://github.com/CWBaker360/Constructible-Cubic-Trisection) | Angle division | **Public** |
| 2 | [`proportional-subtended-cubic-refinement`](https://github.com/CWBaker360/proportional-subtended-cubic-refinement) | Angle division | **Public** |
| 3 | [`nseries-pi-acceleration`](https://github.com/CWBaker360/N-Series-pi-acceleration) | N-Series core | **Public** |
| 4 | [`scaling-cancellation-principle`](https://github.com/CWBaker360/scaling-cancellation-principle) | N-Series core | **Public - revised v2 released 2026-09-11** |
| 5 | [`scale-optimized-polygonal-pi-acceleration`](https://github.com/CWBaker360/scale-optimized-polygonal-pi-acceleration) | N-Series core | **Public** |
| 6 | [`spherical-nseries-area-law`](https://github.com/CWBaker360/spherical-nseries-area-law) | Spherical geometry | **Public** |
| 7 | [`constructible-tower-approaching-pi`](https://github.com/CWBaker360/constructible-tower-approaching-pi) | Constructibility | Staged |
| 8 | [`baker-geometric-pi-verification`](https://github.com/CWBaker360/baker-geometric-pi-verification) | Verification | Staged |
| 9 | [`classical-appearances-of-pi-g`](https://github.com/CWBaker360/classical-appearances-of-pi-g) | Exposition | Staged |
| 10 | [`ramanujan-pi-nseries-geometric-constant`](https://github.com/CWBaker360/ramanujan-pi-nseries-geometric-constant) | Ramanujan comparison | Staged |
| 11 | [`agm-prefactor-coefficient-law`](https://github.com/CWBaker360/agm-prefactor-coefficient-law) | AGM and modular structure | Staged |
| 12 | [`ramanujan-landen-nseries-refinement`](https://github.com/CWBaker360/ramanujan-landen-nseries-refinement) | AGM and modular structure | Staged |
| 13 | [`universal-scaling-law-ellipse-perimeters`](https://github.com/CWBaker360/universal-scaling-law-ellipse-perimeters) | Ellipse geometry | Staged |
| 14 | [`ramanujan-ellipse-nseries-comparison`](https://github.com/CWBaker360/ramanujan-ellipse-nseries-comparison) | Ellipse geometry | Staged |
| 15 | [`ramanujan-ellipse-residual-geometry`](https://github.com/CWBaker360/ramanujan-ellipse-residual-geometry) | Ellipse geometry | Staged |
| 16 | [`curvature-deformed-arcsine`](https://github.com/CWBaker360/curvature-deformed-arcsine) | Curved geometric refinement | **Public** |

> **Access note.** A staged repository may return a not-found page to visitors because it remains private by design.

## Research architecture

The archive separates seven mathematical lanes:

1. **Angle division:** constructible approximate trisection, proportional-subtended transfer, and local cubic residual refinement.
2. **N-Series core:** conditional even-power scale cancellation, multi-scale Lagrange weights, geometric-node hierarchies, recursive extrapolation ladders, stability, and scale optimization.
3. **Curved geometric refinement:** intrinsic geodesic side laws, curvature-deformed linearizing coordinates, and curved cubic coefficient lifting.
4. **Spherical geometry:** curved-surface area refinement, regular-grid superconvergence, and mesh-regularity limits.
5. **Constructibility and verification:** finite constructible approximants, algebraic generation, and numerical consistency audits.
6. **AGM and Ramanujan structure:** dynamic coefficient laws, Landen contraction, and guarded modular comparisons.
7. **Ellipse geometry:** exact chord factorization, universal polygonal scaling, Ramanujan comparison, and residual recovery.

The spherical track extends the N-Series framework from planar length and perimeter approximation to area approximation on curved surfaces. It includes spherical caps, chordal spherical triangles, latitude-longitude cells, fixed irregular spherical polygon domains, and perturbed-mesh diagnostics.

The curved-refinement track extends the cubic geometric-refinement program from flat geometry to intrinsic curved-surface geometry through a curvature-deformed arcsine coordinate and associated local side-law expansions.

## September 2026 revision checkpoint

The revised **Scaling-Cancellation Principle** now develops the fixed-scale mechanism beyond the original two-scale theorem. In addition to

\[
\widehat Q_{N,k}=\frac{k^2Q_{kN}-Q_N}{k^2-1},
\qquad
Q-\widehat Q_{N,k}=-\frac{C_4}{k^2}N^{-4}+O(N^{-6}),
\]

it gives the unique multi-scale Lagrange weights and, for geometric nodes
\(N,bN,\ldots,b^sN\), the surviving-error law

\[
Q-\widehat Q_N^{(s)}
=
(-1)^s C_{2s+2}b^{-s(s+1)}N^{-2s-2}
+O(N^{-2s-4}).
\]

The revision also records the equivalent recursive Richardson-style ladder, makes the ellipse factorization an explicitly cited imported input, and keeps the fixed-resolution mechanism separate from the nonlinear proportional-subtended cubic residual law.

As of September 17, 2026, the public portfolio also includes **Scale-Optimized Geometric Acceleration of Polygonal Approximations to Pi**, **A Spherical N-Series Area Law for Regular Refinement Families**, and **A Curvature-Deformed Arcsine Coordinate for Cubic Geometric Refinement**. Their public status does not imply that the remaining staged repositories will be released.

## Navigation

- [`PAPERS.md`](PAPERS.md): annotated repository list
- [`PUBLICATION_ROADMAP.md`](PUBLICATION_ROADMAP.md): dependency-aware portfolio roadmap
- [`DEPENDENCY_GRAPH.md`](DEPENDENCY_GRAPH.md): theorem and citation structure
- [`docs/SPHERICAL_GEOMETRY_TRACK.md`](docs/SPHERICAL_GEOMETRY_TRACK.md): scope of the spherical program
- [`docs/SUPERSEDED_DRAFTS.md`](docs/SUPERSEDED_DRAFTS.md): drafts that should not become duplicate repositories
- [`docs/REPOSITORY_STANDARDS.md`](docs/REPOSITORY_STANDARDS.md): packaging conventions

## Rights

Copyright © 2026 C. Wayne Baker. All rights reserved unless a specific repository states otherwise.
