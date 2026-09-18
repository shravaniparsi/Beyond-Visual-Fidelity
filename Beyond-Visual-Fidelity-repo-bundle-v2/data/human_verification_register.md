# Targeted human-verification register

Reviewer: Shravani Parsi  
Method: Non-blinded human verification of AI-assisted extraction through chat.  
Coverage: Nine scoped checks (H01–H09). No whole-paper independent dual-human extraction is certified.

| Check | Study | Human-approved scope | Retained limitation |
|---|---|---|---|
| H01 | P06 LayoutCoder | Human evaluation is reported. | Participant count unresolved: one section says 3, another 4. |
| H02 | P01 Design2Code | 79.9% is held-out prediction of human pairwise preference by a combined predictor. | Not functional correctness or separate validation of every metric. |
| H03 | P50 MM-WebAgent | Checked specification is text-led; screenshot is internal refinement feedback. | External supplied visual target not established by checked passages. |
| H04 | P41 UI-UG | Preserve author label “Interface & Interactivity”; checked prompt assesses image appearance/consistency. | Executed interaction not established by that prompt. |
| H05 | P18 1D-Bench | Human–metric alignment is reported on controlled perturbations with a visual-closeness criterion. | Transfer to ordinary generated outputs and tuning/confirmation independence not established. |
| H06 | P65 From Code to Compliance | 90.91% is treated as resolution of manually identified errors. | Not percentage of all WCAG requirements satisfied; conformance not established. |
| H07 | P66 HFG / honeypot framework | HIR includes bounded frontend action/readiness checks. | No complete backend, end-to-end, or security guarantee. |
| H08 | P23 WebCompat | 139/203 is conditional on retained empirical pages; 2,032 observations are page × environment pairs. | Not all generation attempts and not independent webpages. |
| H09 | P67 ScreenCoder | Human comparative/workflow evidence is retained as reported. | Does not separately validate every automatic metric; retry/provenance limits remain. |
