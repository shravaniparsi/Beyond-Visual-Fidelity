# Public evidence tables

This directory contains cleaned, shareable tables supporting the manuscript.

- `study_register.csv`: primary/boundary studies cited as evidence in the manuscript, with manuscript reference number and task stratum.
- `instrument_register.csv`: construct-level instrument-family map and inference boundaries.
- `validation_evidence.csv`: representative conclusion-driving validation/reliability evidence.
- `dependency_register.csv`: benchmark/evaluator dependency families used in the sensitivity analysis.
- `human_verification_register.md`: scoped non-blinded human verification decisions.

These are public synthesis tables, not raw primary-study datasets. They intentionally omit copyrighted full texts and internal acquisition/workflow notes.

## Identity and coverage

The study register uses stable project study IDs. Manuscript reference numbers and bibliographic text are mapped to `IST_manuscript_reviewer_fixed_v7.md`; they are not study IDs and must be remapped if the bibliography is reordered. The table contains 35 manuscript-cited primary/boundary study families, not the full 66-record legacy working inventory or a PRISMA inclusion count.

The other public CSV files are summaries: nine construct-family rows, eight representative validation-evidence rows, and six dependency-family rows. They do not replace the legacy 369-entry instrument queue or 86-link evidence queue. Those legacy inventories require reconciliation with the later manuscript and late-update register before being described as final analytic datasets.
