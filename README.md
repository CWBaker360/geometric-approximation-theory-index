# Geometric Approximation Theory - Repository Index

**Author:** C. Wayne Baker  
**GitHub account:** `CWBaker360`  
**Status:** Research-portfolio index  
**Repository count:** 15 paper and verification repositories  
**Last updated:** September 11, 2026

This repository is the master index for the **Geometric Approximation Theory** archive. It records the scope, dependency structure, publication order, and release status of a connected program in geometric approximation, error cancellation, constructibility, curved-surface refinement, AGM/Ramanujan comparison, and ellipse geometry.

## Current status

All 15 repositories below have been prepared as distinct, claim-bounded research archives. Public repositories are available directly; staged repositories remain private while their synchronized TeX/PDF pairs, reproducibility records, cross-citations, and release metadata are finalized.

| No. | Repository | Track | Current status |
|---:|---|---|---|
| 1 | [`constructible-cubic-trisection`](https://github.com/CWBaker360/Constructible-Cubic-Trisection) | Angle division | **Public** |
| 2 | [`proportional-subtended-cubic-refinement`](https://github.com/CWBaker360/proportional-subtended-cubic-refinement) | Angle division | **Public** |
| 3 | [`nseries-pi-acceleration`](https://github.com/CWBaker360/N-Series-pi-acceleration) | N-Series core | **Public** |
| 4 | [`scaling-cancellation-principle`](https://github.com/CWBaker360/scaling-cancellation-principle) | N-Series core | **Staged - revised manuscript verified 2026-09-11** |
| 5 | [`scale-optimized-polygonal-pi-acceleration`](https://github.com/CWBaker360/scale-optimized-polygonal-pi-acceleration) | N-Series core | Staged |
| 6 | [`spherical-nseries-area-law`](https://github.com/CWBaker360/spherical-nseries-area-law) | Spherical geometry | Staged |
| 7 | [`constructible-tower-approaching-pi`](https://github.com/CWBaker360/constructible-tower-approaching-pi) | Constructibility | Staged |
| 8 | [`baker-geometric-pi-verification`](https://github.com/CWBaker360/baker-geometric-pi-verification) | Verification | Staged |
| 9 | [`classical-appearances-of-pi-g`](https://github.com/CWBaker360/classical-appearances-of-pi-g) | Exposition | Staged |
| 10 | [`ramanujan-pi-nseries-geometric-constant`](https://github.com/CWBaker360/ramanujan-pi-nseries-geometric-constant) | Ramanujan comparison | Staged |
| 11 | [`agm-prefactor-coefficient-law`](https://github.com/CWBaker360/agm-prefactor-coefficient-law) | AGM and modular structure | Staged |
| 12 | [`ramanujan-landen-nseries-refinement`](https://github.com/CWBaker360/ramanujan-landen-nseries-refinement) | AGM and modular structure | Staged |
| 13 | [`universal-scaling-law-ellipse-perimeters`](https://github.com/CWBaker360/universal-scaling-law-ellipse-perimeters) | Ellipse geometry | Staged |
| 14 | [`ramanujan-ellipse-nseries-comparison`](https://github.com/CWBaker360/ramanujan-ellipse-nseries-comparison) | Ellipse geometry | Staged |
| 15 | [`ramanujan-ellipse-residual-geometry`](https://github.com/CWBaker360/ramanujan-ellipse-residual-geometry) | Ellipse geometry | Staged |

> **Access note.** A staged repository may return a not-found page to visitors until it is made public.

## Research architecture

The archive separates six mathematical lanes:

1. **Angle division:** constructible approximate trisection, proportional-subtended transfer, and local cubic residual refinement.
2. **N-Series core:** conditional even-power scale cancellation, multi-scale Lagrange weights, geometric-node hierarchies, recursive extrapolation ladders, stability, and scale optimization.
3. **Spherical geometry:** curved-surface area refinement, regular-grid superconvergence, and mesh-regularity limits.
4. **Constructibility and verification:** finite constructible approximants, algebraic generation, and numerical consistency audits.
5. **AGM and Ramanujan structure:** dynamic coefficient laws, Landen contraction, and guarded modular comparisons.
6. **Ellipse geometry:** exact chord factorization, universal polygonal scaling, Ramanujan comparison, and residual recovery.

The spherical track extends the N-Series framework from planar length and perimeter approximation to area approximation on curved surfaces. It includes spherical caps, chordal spherical triangles, latitude-longitude cells, fixed irregular spherical polygon domains, and perturbed-mesh diagnostics.

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

## Navigation

- [`PAPERS.md`](PAPERS.md): annotated repository list
- [`PUBLICATION_ROADMAP.md`](PUBLICATION_ROADMAP.md): dependency-aware release order
- [`DEPENDENCY_GRAPH.md`](DEPENDENCY_GRAPH.md): theorem and citation structure
- [`docs/SPHERICAL_GEOMETRY_TRACK.md`](docs/SPHERICAL_GEOMETRY_TRACK.md): scope of the spherical program
- [`docs/SUPERSEDED_DRAFTS.md`](docs/SUPERSEDED_DRAFTS.md): drafts that should not become duplicate repositories
- [`docs/REPOSITORY_STANDARDS.md`](docs/REPOSITORY_STANDARDS.md): packaging conventions

## Rights

Copyright © 2026 C. Wayne Baker. All rights reserved unless a specific repository states otherwise.
