# Changes

## v1.2.0 (2026-11-23)

This update improves data preprocessing and quality.

- VLSQ-8: correct the total-score calculation; totals decrease by 5 and individual answers are unchanged.
- Experience log: preserve all checkbox selections in nine additional columns. Existing first-choice summaries remain available and are labelled accordingly.
- Wellbeing diary: clarify the adapted score labels and ranges (1–25 raw; 4–100 scaled). Numeric scores are unchanged.
- Health: retain the selected assessments for RISE_S007 and RISE_S011, and exclude the unmatched literal IDs 1 and 2.
- Reproducibility: bundle the metadata helpers and codebooks, refresh affected summary tables, and remove superseded importers and stale generated reports.

Comparison baseline: [v1.1.0](https://github.com/MeLiDosProject/NilssonTengelinEtAl_Dataset_2026/releases/tag/v1.1.0).
