# Evidence data — v14

These shareable research records support manuscript v14. Stable study IDs link all registers; manuscript reference numbers are a separate identifier and follow the v14 first-appearance order.

| File | Coverage and use |
|---|---|
| study_register.csv | 35 cited study families: 33 within task-specific scopes and two boundary comparators (P20/P21). P26 is repair-only. This is not a count of screenshot reconstruction studies. |
| instrument_register.csv | Nine construct-family summaries; not unique instrument counts. |
| validation_evidence.csv | 13 representative evidence rows; absence from this summary does not imply absent validation. |
| dependency_register.csv | 15 typed groups, including benchmark ancestry, conceptual role comparisons and within-study dependence. |
| human_verification_register.md | Nine selected author verification decisions, alongside the full-paper review statement. |
| membership.json | Study-level scope, source assessment and publication-linked sensitivity membership. |
| dependencies.json | Typed relationship membership and inference limits. |
| manuscript_reference_map.json | All 49 v14 bibliography entries, keyed by current citation number. |
| reference_crosswalk_v14.json | Mapping from v13 reference numbers to v14 numbers. |
| detailed_records/ | Preserved original records with current membership, scope and linkage fields. |

## Detailed-record interpretation

The detailed ledgers contain 369 instrument-queue rows, 86 evidence-queue rows, 13 claim cases and 53 extraction rows. Respectively, 180, 43, 8 and 48 rows belong to the 35-family cited set. These are heterogeneous records, not independent samples, unique metrics or included-study totals. Thirty-five instrument IDs have exact links to retained extraction rows; all explicit evidence-to-instrument IDs resolve within the same study.

`original_record` preserves historical text and identifiers. Current study scope and claim decisions control interpretation; historical reference numbers must not be treated as current v14 numbers. `new_human_signoff: false` means that the reconstruction did not add a new record-level sign-off. It does not negate Shravani Parsi’s full-paper reading and evaluation.

C02 (P07 metric alignment) and C05 (P15 no-memorization) remain held and unused. The 25-family `segregate_inspected_preprint` category identifies retained claim sources without checked publication anchors; it does not mean all 25 studies are unpublished. None of the source-status categories is a quality score.

See `../analysis/Detailed_Record_Reconciliation.md`, `../analysis/Reviewer_Source_Checks.md`, `../analysis/Source_Version_Reconciliation.md` and `../analysis/Supplementary_Sensitivity_Matrix_v2.md` for scope decisions and source locators. This release is not a complete native-database search archive and does not certify every historical extraction row against its publication version.
