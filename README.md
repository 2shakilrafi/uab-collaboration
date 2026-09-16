# UAB Collaboration Research Archive

This repository is a working archive for a University of Alabama at Birmingham research collaboration. It collects project metadata, meeting materials, presentations, microbiome analyses, and self-report analyses under [`uab-collaboration/`](uab-collaboration/).

## Repository map

- `Metadata/` — project metadata and supporting documentation
- `Microbiome data/` — microbiome-related analyses and outputs
- `minutes/` — collaboration notes and meeting records
- `presentations/` — presentation source files and rendered outputs
- `self-report-data/` — analyses organized by study wave and measure

## Reproducibility

This is a research workspace rather than a packaged software project. Start from the source `.R`, `.Rmd`, or `.qmd` file nearest the output you want to reproduce, review its input paths, and install the packages named in that document. Rendered `*_files/` directories are retained because tracked HTML reports may depend on them.

R workspace files (`.RData`) are also retained conservatively: some may contain project state that is not reconstructible from the repository alone. New work should prefer scripted imports and an explicit dependency lockfile.

## Data responsibility

Before adding or reusing data, confirm that it is de-identified, approved for this repository's visibility, and handled under the collaboration's data-use and institutional requirements. Do not infer clinical or causal conclusions from exploratory outputs without validating the study design and analysis assumptions.
