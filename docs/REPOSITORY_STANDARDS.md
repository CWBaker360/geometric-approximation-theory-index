# Repository Standards

Each paper repository should use the following baseline release structure, adjusted where a particular archive does not require every directory:

```text
README.md
CITATION.cff
REPRODUCIBILITY.md
CHANGELOG.md
SHA256SUMS.txt
paper/
scripts/        # where computational verification is used
output/         # where retained outputs are distributed
docs/
```

Every repository must also contain an explicit rights statement. The exact file layout may vary by release, for example:

```text
LICENSE_NOTICE.md
```

or

```text
LICENSE.md
```

or a split model such as

```text
LICENSE
LICENSE-PAPER.md
```

or equivalent code/content license files.

The `paper/` directory contains one authoritative synchronized LaTeX/PDF pair. Historical variants belong under `docs/` and must be clearly labeled. Claims should be labeled as proved, constructively realized, numerically verified, conditional, conjectural, or historical.

## Pre-release audit

A staged repository remains private until it is selected for release and passes a fresh audit. Before changing visibility, confirm:

- the authoritative paper title, author, version, and date agree across the manuscript, README, and `CITATION.cff`;
- the repository URL in citation metadata points to the correct repository;
- license terms are explicit and consistent with the intended Zenodo license;
- the paper/source pair is the correct one for that repository and is not copied from a neighboring archive;
- reproducibility commands and retained outputs still work or are clearly scoped;
- claim boundaries are current;
- checksums are regenerated after the final content and metadata edits;
- any Zenodo DOI is added to citation metadata after the deposit is minted;
- public-facing links are tested from an unauthenticated view.

Staging is intentional: repositories may be released one at a time on a spaced cadence so each paper receives its own final audit and public presentation.
