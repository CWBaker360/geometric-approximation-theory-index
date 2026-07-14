# Spherical Geometry Track

The active spherical repository is:

- `spherical-nseries-area-law`

It studies geometric area approximations on the unit sphere at scales `N, 2N, 4N, 8N`. Under an even-power error expansion, the fixed N-Series operators raise the nominal order from 2 to 4, 6, and 8.

## Tested families

- geodesic-polygon approximations of spherical caps;
- chordal triangulations of right spherical triangles;
- chordal latitude-longitude cells;
- fixed irregular spherical polygon domains with regular fan refinement;
- smoothly perturbed interior grids as a regularity diagnostic.

## Scope

The general spherical area law is conjectural. The clean high-order ladder is supported numerically for regular, scale-consistent refinement families. Boundary irregularity can be compatible with the ladder, but geometrically ill-posed domains or loss of coherent refinement can destroy its interpretation.

## Application language

The work is relevant to spherical grids, geodesy, curved-surface area approximation, and mesh-refinement analysis. It is not presented as a production geodesy algorithm or a universal repair method for arbitrary meshes.
