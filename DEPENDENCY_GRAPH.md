# Dependency and Citation Graph

```mermaid
flowchart TD
    A[Constructible cubic trisection] --> B[Proportional-subtended cubic refinement]

    C[N-Series pi acceleration] --> D[Scaling-cancellation principle]
    C --> E[Scale-optimized polygonal pi acceleration]
    D --> E
    D --> S[Spherical N-Series area law]
    E --> S
    C --> F[Constructible tower approaching pi]

    C --> G[Geometric pi verification]
    G --> H[Classical appearances of pi_g]
    C --> I[Ramanujan pi vs N-Series]

    J[AGM prefactor coefficient law] --> K[Ramanujan-Landen N-Series refinement]
    D --> K

    L[Universal ellipse scaling law] --> M[Ramanujan ellipse comparison]
    M --> N[Ramanujan ellipse residual geometry]
    L --> N
```

## Spherical dependency note

The spherical-area paper depends on the general conditional scale-cancellation theorem, but its geometric even-power law remains conjectural outside the tested regular families. Numerical evidence does not replace an analytic proof for arbitrary spherical domains or meshes.

## Citation principles

- Distinguish cubic angular refinement from fixed-resolution scale cancellation.
- Attribute Richardson-Romberg extrapolation as classical arithmetic.
- Treat the spherical 2-4-6-8 ladder as numerical evidence for regular families.
- Do not describe perturbed-mesh diagnostic quotients as stable high-order convergence when the asymptotic regime is unclear.
- Keep Ramanujan, Landen, and AGM comparisons guarded against claims of numerical equivalence.
- Verification repositories support evidence and reproducibility; they do not replace proofs.
