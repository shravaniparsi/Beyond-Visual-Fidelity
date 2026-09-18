# Beyond Visual Fidelity

Research artifacts for:

**Beyond Visual Fidelity: A Systematic Evidence Synthesis of Construct Validity in AI UI-to-Code Evaluation**

**Authors:** Vishwak Thatikonda and Shravani Parsi  
**Repository:** https://github.com/shravaniparsi/Beyond-Visual-Fidelity

## Purpose

This repository contains the shareable research artifacts supporting a systematic evidence synthesis and construct-validity audit of evaluation practices in AI UI-to-code research.

The review focuses on what evaluation instruments directly measure, how they are operationalized, what validity and reliability evidence supports them, how denominator and failure policies affect reported results, how benchmark/evaluator reuse creates empirical dependencies, and which inferences are justified from reported scores.

## Recommended repository structure

```text
.
├── README.md
├── LICENSE
├── CITATION.cff
├── protocol/
│   ├── review_protocol.docx
│   └── protocol_amendment.md
├── data/
│   ├── study_register.xlsx
│   ├── instrument_register.xlsx
│   ├── validation_evidence.xlsx
│   ├── dependency_register.xlsx
│   └── human_verification_register.md
├── search/
│   ├── search_strategy.md
│   ├── update_search_log.md
│   └── search_accounting_note.md
├── analysis/
│   ├── numerical_claim_audit.md
│   └── reporting_framework.md
├── figures/
│   ├── figure1_measurement_design.svg
│   ├── figure2_task_construct_map.svg
│   └── figure3_dependency_map.svg
└── supplement/
    └── supplementary_material.docx
```

## Reproducibility and scope

The repository documents the review protocol, evidence coding, validation and dependency audit, targeted human-verification decisions, numerical claim checks, and evidence-derived reporting framework.

The project does **not** claim that every released artifact reproduces the historical experiments reported by the reviewed primary studies. Artifact availability, procedure inspectability, historical-run equivalence, and independent reproduction are treated as distinct states in the review.

The review also does not reconstruct unsupported conventional PRISMA identification counts where complete native-database export and global deduplication records were not retained.

## Human oversight and AI assistance

AI-assisted tools supported literature organization, source localization, preliminary evidence extraction, consistency and arithmetic checks, and language refinement. The authors retained responsibility for the review design, interpretation, verification of conclusion-critical evidence, and final manuscript. The human-verification register records the scope and limitations of targeted non-blinded checks.

## Copyright

This repository does **not** redistribute copyrighted copies of reviewed publications. Users should obtain primary papers from their publishers, authors, institutional repositories, or lawful preprint sources.

## Citation

A `CITATION.cff` file is provided for repository citation. If this repository is archived with Zenodo, cite the archived DOI for the exact release used by the manuscript.

## Authors

- **Vishwak Thatikonda** — Independent Researcher, Dublin, CA, USA. ORCID: 0009-0009-5828-5903
- **Shravani Parsi** — Independent Researcher, Dublin, CA, USA. ORCID: 0009-0004-0084-4657
