# Repository Standards

Each paper repository uses the baseline structure:

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

The `paper/` directory contains one authoritative synchronized LaTeX/PDF pair. Historical variants belong under `docs/` and must be clearly labeled. Claims should be labeled as proved, constructively realized, numerically verified, conditional, conjectural, or historical.
