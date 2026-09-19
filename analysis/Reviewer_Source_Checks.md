# Targeted source checks — 18 September 2026

These dated source checks resolve bounded decisions. Shravani’s full-paper reading and evaluation are separately recorded in the current methods; these checks do not count the extent of that review. Unreported or ambiguous details remain unknown. P20 is boundary-only; P26’s repair-only classification is finalized in v13.

## P03 — WebCode2M

Source: [inspected preprint v2; publication equivalence unverified](https://arxiv.org/html/2404.06369v2); §3.2–3.3, Appendix A.

TreeBLEU uses sets of height-one DOM subtrees excluding attributes. The visual-score footnote distinguishes an earlier Design2Code implementation from its later color component. Recitation failures affect roughly a third of Gemini cases; their aggregate treatment remains unresolved. Retain operational-definition and version-sensitivity claims, not a complete failure denominator.

## P07 — Sketch2Code

Source: [published NAACL 2025](https://aclanthology.org/2025.naacl-long.198.pdf); §§3.2, 4.5, 5; Appendix D.

Externally supplied sketches define the reconstruction task. Expert interviews address workflow preferences and expected utility; simulated-user feedback checks address feedback quality. Neither establishes observed productivity gains or item-level validity of the visual metric. Derived webpage ancestry links this study to Design2Code.

## P16 — Figma2Code

Source: [published ICLR 2026](https://proceedings.iclr.cc/paper_files/paper/2026/file/8ff8b17225ccfc53d13b805d8e909702-Paper-Conference.pdf); §§2, 4.1; appendix evaluation.

Figma JSON, assets and design images constrain generation; the inspected evaluation uses Tailwind HTML. Relative CSS units and absolute/fixed positioning are responsiveness proxies. Semantic-tag and arbitrary-value proportions are code proxies, not measured maintenance effort, viewport adaptation or accessibility conformance.

## P19 — UI2Code^N

Source: [inspected preprint v1; later ICML-title equivalence unverified](https://arxiv.org/html/2511.08195v1); §3.1; Appendix A3.1.

Reference images constrain drafting, polishing and editing. Reported accuracy is the share reaching a visual-judge threshold, not functional accuracy. Reward/selection and final judging have distinct roles. Claims are restricted to this version rather than silently transferred to the later renamed report.

## P20 — FrontCoder

Source: [published Findings of ACL 2026](https://aclanthology.org/2026.findings-acl.220.pdf); §§2, 3.1.1–3.1.3; Limitations.

Inspected text-to-code tasks use internally rendered screenshots for criticism; a separable externally supplied visual-target subset is not established. Retain only as a boundary comparator. The reported judge-to-judge association is distinct from human-criterion validity; ArtifactsBench alignment is inherited. The limitations exclude interaction/dynamic-responsiveness assessment.

## P22 — ComUICoder

Source: [inspected preprint v1](https://arxiv.org/html/2602.19276v1); §§2.1, 5.1, 6.1; Appendices A5.3, A6.

External mockups constrain multi-page generation. Reuse and repetition scores are structural proxies. The main text describes a one-third human-study sample while the appendix describes 100 pages; these accounts are not reconciled. Annotator reliability and agreement in method preference do not establish item-level validity of each automatic metric. Reuse wording and its appendix formula also require caution.

## P25 — EfficientUICoder

Source: [inspected preprint v1; publication equivalence unverified](https://arxiv.org/html/2509.12159v1); §§2.1, 5.2–5.3.

Screenshot-to-code evaluation combines visual/reference measures with efficiency outcomes. Compression is the retained-token ratio. FLOPs cover the LLM backbone and exclude the visual encoder; timing depends on the stated hardware. Quality preservation is restricted to the tested measures, not demonstrated functional equivalence. WebCode2M sampling wording is not used to infer an additional exact denominator.

## P26 — DesignRepair

Source: [inspected preprint v1; ICSE publication equivalence unverified](https://arxiv.org/html/2411.01606v1); §III; §IV A–C.

Retain only in the supplied-fault-state repair stratum: existing frontend code and its rendered state, with design-guideline constraints, define the repair task. This is not external-target screenshot reconstruction. Baseline comparisons use hard-constraint subsets of the annotated violations. Guideline detection/repair outcomes do not establish universal accessibility conformance. The v13 consistency review applies the existing repair rule and closes the task classification without asserting publication-version equivalence or new independent human verification.

## P31 — Prototype2Code

Source: [inspected preprint v1; publication equivalence unverified](https://arxiv.org/html/2405.04975v1); §§4.3–4.4.

Prototype-constrained generation uses visual scores and a small developer assessment. Five frontend engineers each review ten pages. Availability is based on the proportion of code not changed to satisfy basic requirements, then mapped to a scale; it is not runtime uptime. Ratings and bounded edits are not longitudinal maintainability evidence.

## P32 — Vision2Web

Source: [inspected preprint v1](https://arxiv.org/html/2603.26648v1); §§2.1, 3.2, 4.1, 4.4; Appendix A2.2.

External prototypes constrain static and interactive tasks. Functional validation reports 218/250 correct node judgments sampled within approximately 100 workflows across 64 tasks: nodes are clustered. Visual-judge agreement is a separate prototype-ranking exercise. Deployment permits retries; precise contributions of missing/unreached nodes remain unresolved. Planned evaluator updates make version pinning necessary.

## P33 — UIPress

Source: [inspected preprint v1](https://arxiv.org/pdf/2604.09442v1); §§4.2–4.5; Table 1, PDF p6.

Table 1 reports the 50-page validation split and a checkpoint selected by validation CLIP, not the 435 pages described as reserved for final evaluation. Its stated 485-page dataset also differs from the usual 484-page Design2Code count; do not silently reconcile this. CLIP and bootstrap uncertainty are not new human-criterion validation. Latency and memory are hardware- and procedure-specific.

## P49 — VisRefiner

Source: [inspected preprint v1](https://arxiv.org/html/2602.05998v1); Reward definition; §6.2; reward/evaluation appendix.

External reference screenshots constrain refinement. Training CLIP reward and the masked layout evaluation variant are distinct implementations. The appendix minimum-improvement threshold differs from the main text's strict-positive condition. Human refined-versus-initial preference supports method improvement on the tested comparisons, not independent validation of every accompanying metric.

## P52 — WebIGBench

Source: [inspected preprint v1](https://arxiv.org/pdf/2606.00154v1); §3.1; Appendices A1, B5–B7; Table 8, PDF pp12–18.

State images and optional actions define generation. Table 8 valid-evaluation counts vary from 92 to 103 across configurations. Match scoring is conditional on matched steps; Full scoring carries the last available screenshot forward. Zero-match/no-screenshot handling remains unresolved. Main-text matcher validation and appendix sequence-extraction annotation describe different units and must not be conflated. Cross-LLM matching agreement is stability evidence, not another human criterion.

## P57 — RILA

Source: [inspected preprint v1](https://arxiv.org/pdf/2609.02088v1); Method; benchmark evaluation; Table 4, PDF p7.

Reference video constrains generation. The composite used for best-so-far selection is distinct from final inherited benchmark metrics. Table 4 reports interaction rate over 375 tasks and similarity over 301 jointly triggered tasks; the denominators must remain separate. Reuse of IWR-Bench and Interaction2Code does not provide new independent validation of those instruments.
