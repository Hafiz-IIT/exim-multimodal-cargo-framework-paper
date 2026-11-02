# EXIM AI Co-Pilot: A Multimodal Cargo Scanning and Customs Automation Framework

**Status: architecture manuscript in preparation; not submitted or published.**

This repository describes an evidence-preserving architecture for EXIM document processing, cargo-observation comparison, discrepancy review, and human escalation.

## Files
- paper/main.tex — manuscript source
- paper/EXPERIMENT_PROTOCOL.md — synthetic scenario families, metrics, governance checks, and data boundaries
- paper/system_architecture.md and evidence_model.md — architecture and evidence notes
- paper/claims.md, limitations.md, reproducibility.md — claim and validation boundaries
- Makefile — local PDF build target

## Build
Requires LaTeX with geometry, AMS math, booktabs, and hyperref packages.

    make pdf
    make clean

## Evidence boundary
This is not a deployed customs integration, certified cargo scanner, regulatory approval, or validated operational system. No X-ray/THz/RFID hardware is claimed. Use synthetic or lawfully licensed/de-identified data; never commit client customs records or commercially sensitive documents.

Related implementation work: https://github.com/Hafiz-IIT/exim-copilot-core and https://github.com/Hafiz-IIT/cargo-scan-consistency-lab
