# Evaluation protocol — EXIM multimodal cargo and document framework

## Evaluation separation
Measure document extraction, cross-document consistency, cargo-observation comparison, evidence provenance, and final review decisions as separate tasks. Do not collapse them into one accuracy score.

## Synthetic scenario families
- missing invoice or packing-list fields
- OCR substitutions and numeric parsing errors
- inconsistent quantities, weights, package counts, and identifiers
- stale authorization or reference data
- copied documents with correlated upstream errors
- declaration-versus-observation mismatches
- low-quality or missing cargo observations
- conflicting sources requiring human escalation

## Metrics
Field-level precision/recall, discrepancy precision/recall, false escalation, missed discrepancy, calibration, evidence completeness, and traceability coverage.

## Governance checks
Verify that every alert links to source evidence, consequential actions require an authorized reviewer, and low-confidence or conflicting cases are escalated rather than silently resolved.

## Data boundary
Begin with synthetic or lawfully licensed/de-identified data. Do not upload client customs records, personal data, or commercially sensitive documents to a public repository.

## Current evidence
This repository contains a manuscript/architecture scaffold. It does not claim a deployed customs integration, physical scanner, real-world accuracy, or operational validation.
