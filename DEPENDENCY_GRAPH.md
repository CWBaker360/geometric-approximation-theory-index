# Dependency and Citation Graph

```mermaid
flowchart TD
    A[Constructible cubic trisection] --> B[Proportional-subtended cubic refinement]
    A --> D[Scaling-cancellation principle]
    B --> D

    C[N-Series pi acceleration] --> D
    C --> E[Scale-optimized polygonal pi acceleration]
    D --> E
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

## Citation principles

- The angle-division papers should not cite polygonal N-Series cancellation as
  though it were the same convergence mechanism.
- The N-Series papers may cite Richardson/Romberg for the algebraic
  extrapolation and identify the geometric contribution separately.
- The Ramanujan and Landen papers must retain the guarded distinction between
  polynomial resolution acceleration and modular or AGM convergence.
- The ellipse residual paper should cite the broader ellipse comparison but
  avoid reproducing its complete numerical survey.
- Verification papers provide evidence and reproducibility; they do not replace
  analytic proofs.
