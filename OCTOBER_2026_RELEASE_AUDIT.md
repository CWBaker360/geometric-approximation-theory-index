# October 29, 2026 — Release synchronization audit

This is a packaging/status audit, **not** an independent proof review or a Zenodo deposit. Source: repository inventory and the author's local `UpdatedPapers.zip` provided October 29.

## Repository census
20 GitHub repositories, including this index; 19 research/software repositories. 15 public repositories including this index, five private repositories: `constructible-tower-approaching-pi`, `classical-appearances-of-pi-g`, `ramanujan-pi-nseries-geometric-constant`, `ramanujan-ellipse-residual-geometry`, and `primitive-spectrum-zne`. These are visibility facts, not publication-readiness determinations.

## Local revised manuscripts requiring synchronization
- `constructible-tower-approaching-pi`: local v1.3 TeX but no matching v1.3 PDF in supplied archive; README specifically says October clarifications not merged.
- `ramanujan-ellipse-nseries-comparison`: local v1.2 TeX but only v1.1 PDF; README says October clarifications not merged.
- `ramanujan-landen-nseries-refinement`: local v1.2 TeX and v1.1 PDF; existing README describes a reviewed v1.1 nine-page pair and later unmerged clarifications.
- `spherical-nseries-area-law`: local v2.2 TeX and v2.2 PDFs; verify source/PDF match, numerical scope and existing Zenodo version before replacing authoritative paper.
- Directional curvature expansion: local v2.4 TeX, PDF, and closeout material; **distinct** from the existing frozen `curvature-deformed-arcsine` manuscript. Do not overwrite the August curvature-deformed-arcsine paper with this independent work.
- Exact chord factorization: local revised v1.2 TeX/PDF; determine its appropriate repository and publication identity rather than replacing another ellipse paper by title alone.
- AGM prefactor law: local v1.1 TeX, unversioned PDF; check source/PDF agreement and existing Zenodo status.
- `ramanujan-ellipse-residual-geometry`: README currently describes and links the *Universal Scaling Law for Ellipse Perimeters* rather than a distinct residual-geometry manuscript. Resolve before separate publication.

## Potential new first-time Zenodo deposits
- `classical-appearances-of-pi-g`: existing source/PDF and demonstration script; explicitly expository, verify license, checksum, and metadata.
- `ramanujan-pi-nseries-geometric-constant`: existing source/PDF and numerical verification script; verify current material and metadata.

## Release gates
1. Confirm authoritative source and matching built PDF.
2. Preserve history; prepare revisions on a branch or as new versions rather than silently replacing frozen research records.
3. Re-run appropriate numerical/symbolic scripts, reconcile evidence and claim boundaries.
4. Update checksums, citation metadata, title and version references.
5. Check DOI before creating a new Zenodo record; use versioning for an existing record.

## Independent-review requests for Claude
- Check the proposed tower v1.3 asymptotic digit coefficient and derive finite-index remainder/error estimates; confirm all corrected statements in source.
- Independently compare the new ellipse comparison v1.2 claims against the exact sinc-midpoint factorization, including near-degenerate axis ratios and finite-N crossover scope.
- Verify spherical v2.2 cap parity, conditional even-power cancellation, weights and residuals; distinguish proved regular-family statements from general-mesh conjectures.
- Verify directional-curvature v2.4 joint smoothness and uniform remainder assumptions and the independent Brewin transcription/torus tests.
- Verify that the AGM v1.1 revised manuscript respects the unresolved finite-index bound for the prefactor remainder `Delta_n`.

**Status:** This file is a coordination ledger. None of these candidates is declared peer-reviewed or independently certified by this audit.
