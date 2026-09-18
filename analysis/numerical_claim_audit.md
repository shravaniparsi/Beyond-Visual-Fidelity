# UI-to-Code manuscript numerical-claim audit — v1

Scope: conclusion-driving numerical statements currently present in manuscript v0.7. This audit records what can be stated now, what must remain qualified, and what is deliberately not inferred.

| Manuscript claim | Source / locator retained in project | Audit status | Locked interpretation |
|---|---|---|---|
| Design2Code combined predictor: 79.9% held-out test accuracy | P01, §4.3; appendices C/F; human verification H02 | PASS | Predicts tested human pairwise visual preferences; not functional correctness and not separate validation of each component metric. |
| MRWeb: 600 screenshot pairs, 14 raters; MAE 0.542, NEMD 0.508, CLIP 0.340; human 0.640 | P12, §6.1 Table 2; Appendices D–E | PASS | Condition-specific visual criterion associations; 0.640 is rater consistency, not an automatic metric. |
| WebUIBench full framework reported mean correlation 0.83 on 100 sampled cases with 3 experts | P08, §4.2 Table 2 | PASS WITH LIMIT | Preserve author-reported “correlation”; estimator/aggregation unresolved. Do not infer Pearson/Spearman or a hidden observation count. |
| DesignBench edit/repair judge accuracy 95.54% / 91.89%; kappa 0.8648 / 0.8428 | P15, §5.4 | PASS WITH LIMIT | Supports tested edit/repair judge agreement and human-label reliability only. Kappa variant/ordinal conversion remains source-limited. |
| 1D-Bench human preference study: 50 instances, 20 annotators | P18, §3.3 and Appendix B; human verification H05 | PASS | Controlled perturbation criterion is visual closeness; transfer to ordinary model outputs not established. |
| WebCompat empirical incompatibility 139/203 = 68.5% | P23, Table III / empirical subset; human verification H08 | PASS | Conditional on retained empirical pages; not 480 generation attempts. |
| WebCompat 2,032 observations | P23 + H08 | PASS | These are page × environment rendering pairs, not independent webpages. |
| WebCompat held-out XCompat F1 = 0.903 | P23 abstract/results; H08 | PASS | Detector performance against annotated compatibility labels, not general generation success. |
| WebVR rubric-guided Code+Video mean agreement 86.7%; one condition 96.0% | P71 late-update dossier | PASS WITH SCOPE | Specific rubric/model/evidence configuration on 50 instances with five UI/UX experts; not a field-wide judge-validity rate. |
| WebCompat source population: 60 designs → 480 candidates → 254 retained → 203 empirical | P23 + H08 | PASS | Use only when explaining denominator conditioning. |
| ScreenCoder ScreenBench = 1,000 pairs | P67 late-update register / H09 | PASS WITH PROVENANCE LIMIT | Benchmark size supported; source-pool independence from Screen-10K remains unresolved. |
| Animation2Code = 1,069 video–code pairs; 600-comparison human study with 65 annotators | P70 late-update register v2 | PASS WITH PREPRINT LIMIT | Positive dimension-specific validation evidence; temporal similarity is not generic functional correctness. |

## Statements deliberately excluded from quantitative synthesis

- No corpus-wide “most studies” percentage unless a frozen, task-applicable denominator is explicitly constructed.
- No universal visual-versus-functional performance gap obtained by subtracting unlike metric scales.
- No pooled validity coefficient across correlations, kappas, accuracies, ranking statistics, and human-preference designs.
- No conventional PRISMA identification counts reconstructed from incomplete native-database history.
- No conversion of unavailable/not-reported validation into zero validation.
