# Scenario-wise virtual sensing and severity screening in simulated tunnel fires

This repository contains the author-approved revision of the manuscript **“Scenario-wise assessment of sparse virtual sensing and interpretable severity screening in simulated tunnel fires.”** The current target is *Engineering Applications of Artificial Intelligence (EAAI)*. The manuscript has not yet been resubmitted or accepted.

## Contents

- `paper/manuscript.tex`, `paper/references.bib`, `paper/tables/`, and `paper/figures/`: the manuscript source and its local assets.
- `releases/eaai-2026-11-14/`: the complete manuscript bundle and the separate reproducibility archive.
- `docs/reproducibility.md`: the reproduction sequence and limits.
- `paper/STATUS_EAAI_2026-11-14.md`: revision and submission status.

The reproducibility archive contains the corrected FDS cases and outputs, datasets, analysis scripts, frozen protocols, audit records, and results for six development scenarios and three reserved scenarios.

## Study in brief

The study evaluates contemporaneous reconstruction of temperature, visibility, and carbon monoxide at six omitted virtual measurement sites using four observed sites. It compares nearest-site and spatial-linear baselines with Ridge and random-forest regression across nine CFD cases: six development cases and three cases evaluated once under a protocol frozen before the reserved data were opened.

The results do not establish general machine-learning superiority or a novel inference algorithm. The four-band severity rule is a local research criterion; it has not been validated as a human-safety limit, alarm threshold, or operational risk level. The work has no physical fire-test validation, mesh-convergence analysis, second geometry, or operational evaluation.

## Funding

This work was carried out with support from the National Council for Scientific and Technological Development (CNPq), Brazil, under Funding Code 131754/2025-4.

## Release status

Prof. Saulo approved the revised manuscript modifications on 14 November 2026. The archive is available from this repository, but no DOI-registered archival deposit has been created. The manuscript has not yet been resubmitted to EAAI.
