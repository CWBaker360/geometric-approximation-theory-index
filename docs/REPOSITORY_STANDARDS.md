# Repository Standards

Each paper repository uses the following baseline structure where applicable:

```text
README.md
CITATION.cff
REPRODUCIBILITY.md
LICENSE_NOTICE.md
CHANGELOG.md
SHA256SUMS.txt
.gitignore
paper/
scripts/
output/
docs/
```

## Authoritative paper rule

The `paper/` directory contains exactly one clearly identified authoritative
LaTeX/PDF pair. Historical drafts belong under `docs/` and must be labeled as
superseded, original, or provenance-only.

## Mathematical-status labels

Claims should be marked, where relevant, as:

- proved analytically;
- constructively realized;
- numerically verified;
- conditional;
- conjectural;
- historical or expository.

## Reproducibility rule

Numerical values in a paper should be reproducible from a named script and
archived output. Reference constants used only for post-construction
verification must be distinguished from data used to generate the
construction.

## GitHub settings

- Initial visibility: private
- Initial commit message: `Initial repository upload`
- Do not initialize a new remote repository with another README, license, or
  `.gitignore` before uploading the prepared package.
