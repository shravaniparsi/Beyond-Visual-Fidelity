# Beyond Visual Fidelity

Research artifacts for **Beyond Visual Fidelity: A Systematic Evidence Synthesis of Construct Validity in AI UI-to-Code Evaluation**.

**Authors:** Vishwak Thatikonda and Shravani Parsi.

## Current evidence package

This v14-aligned package contains 35 cited study families, nine construct-family summaries, 13 representative validation/reliability records and 15 typed dependency groups. Thirty-three families are retained within task-specific scopes; FrontCoder (P20) and ReLook (P21) are boundary comparators. DesignRepair (P26) is repair-only and is excluded from screenshot-reconstruction interpretations.

The manuscript and journal correspondence remain in the authors’ submission package pending final approval. This repository contains supporting research artifacts, not an accepted publication. Archival deposition and a verified dataset DOI remain pending. No release tag or DOI is implied by “v14”.

## Files and reading order

1. [Data guide](data/README.md): register identities, evidence scope and historical-record interpretation.
2. [Study register](data/study_register.csv): bibliography, task strata and permitted claims.
3. [Supplementary material](supplement/supplementary_material.docx): synthesis methods, selected checks, dependency and sensitivity summaries.
4. [Source checks](analysis/Reviewer_Source_Checks.md) and [version reconciliation](analysis/Source_Version_Reconciliation.md): source locators and version limits.
5. [Sensitivity matrix](analysis/Supplementary_Sensitivity_Matrix_v2.md) and [detailed-record reconciliation](analysis/Detailed_Record_Reconciliation.md).
6. [Figure sources and captions](figures/README.md): editable SVG and separate vector PDF artwork.
7. [Original protocol](protocol/ui_to_code_review_protocol_v0_1.docx) and [procedure amendment](protocol/protocol_amendment.md).
8. [Search accounting](search/search_accounting_note.md), [search strategy](search/search_strategy.md) and [update log](search/update_search_log.md).

The [release notes](RELEASE_NOTES.md) describe this update. `MANIFEST.json` records SHA-256 hashes and sizes for the released files, excluding itself.

## Review process and evidence boundaries

Shravani Parsi read and studied all included papers and evaluated the evidence and interpretations. H01–H09 are selected documented checks, not the extent of author review. The review did not use independent dual coding.

ChatGPT (OpenAI) supported literature organization and retrieval, source localization, preliminary extraction, consistency and arithmetic checks, synthesis support, language refinement and programmatic figure preparation. The authors retain responsibility for the content and conclusions.

Artifact availability, procedure inspectability, historical-run equivalence and independent reproduction remain distinct. Benchmark reuse does not establish independent construct validation. The project does not reconstruct conventional PRISMA identification counts from incomplete native-database export and deduplication records.

## Citation and copyright

[CITATION.cff](CITATION.cff) identifies the authors and dataset. The manuscript-linked archival DOI will be added after the exact release is deposited and verified. Until then, identify the Git commit used when referring to this evolving package.

Authored research artifacts are licensed under [CC BY 4.0](LICENSE). Copyrighted copies of reviewed papers are not redistributed; the license does not cover third-party publications.

## Authors

- Vishwak Thatikonda — Independent Researcher, Dublin, CA, USA. ORCID: [0009-0009-5828-5903](https://orcid.org/0009-0009-5828-5903).
- Shravani Parsi — Independent Researcher, Dublin, CA, USA. ORCID: [0009-0004-0084-4657](https://orcid.org/0009-0004-0084-4657).
