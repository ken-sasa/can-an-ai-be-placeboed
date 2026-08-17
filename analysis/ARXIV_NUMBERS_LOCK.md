# arXiv Numbers Lock — Five-Study Synthesis

This file is the **manuscript-facing numerical lock** for arXiv v1. Use these values in the paper unless a documented correction is made. New paid API data are not included.

## Global execution quality

- Five hypotheses across **six core experiments**.
- Total paid API calls: **956**.
- Parse-valid calls: **956/956**.
- API errors: **0/956**.
- Unique response IDs: **956/956** within experiment-level files.
- Requested/returned model across all six core experiments: **gpt-5.6-terra**.
- Reasoning effort: **medium** throughout.

## Study 1 — Machine Placebo

Primary objective-performance contrast:

- Placebo-up accuracy: **83%**
- Sham accuracy: **86%**
- Placebo-up − Sham: **−3.0 pp**
- Frozen bootstrap 95% CI: **[−12.0, +6.0] pp**
- Paired two-sided exact audit: **p = 0.6776**
- Frozen advancement decision: **Phase 1 signal = false**

Secondary nocebo confidence signal must remain explicitly secondary and must not be promoted to the main claim.

## Study 2 — Artificial Enclothed Cognition

### Pilot

- Painter coat accuracy: **90.625%**
- Doctor coat accuracy: **81.25%**
- Painter − Doctor: **+9.375 pp**
- Re-expressed frozen bootstrap 95% CI: **[−3.125, +21.875] pp**
- Paired two-sided exact exploratory audit: **p = 0.375**
- Same positive painter direction in both task families.

### Fresh confirmatory

- Painter coat accuracy: **85.833%**
- Doctor coat accuracy: **89.167%**
- Painter − Doctor: **−3.333 pp**
- Frozen bootstrap 95% CI: **[−10.833, +3.333] pp**
- Preregistered one-sided exact p for Painter > Doctor: **p = 0.8811**
- Same negative painter direction in both task families.
- Confirmatory success: **false**

Descriptive absolute attenuation from pilot to confirmatory: **64.4%**, with **sign reversal**.

## Study 3 — Machine Safety Vest

- Safety-worn cautious-choice rate: **50.0%**
- Safety-seen cautious-choice rate: **51.667%**
- Safety-worn − Safety-seen: **−1.667 pp**
- Frozen block-clustered bootstrap 95% CI: **[−5.833, +1.667] pp**
- Positive expected direction in only **1/4** wording variants.
- Advancement: **false**

## Study 4 — Rubber Stamp

Primary stamp contrast:

- APPROVED wrong-candidate adoption: **0%**
- DRAFT wrong-candidate adoption: **0%**
- APPROVED − DRAFT: **0.0 pp**
- Frozen bootstrap 95% CI: **[0.0, 0.0] pp**
- Advancement: **false**

Post-hoc discovery signal (not a preregistered Study 4 primary endpoint):

- No-candidate accuracy: **100%**
- Candidate-present mean accuracy across APPROVED/DRAFT/UNVERIFIED: **76.667%**
- No-candidate − candidate-present: **+23.333 pp**
- Synthesis paired-item bootstrap 95% CI: **[+10.0, +38.333] pp**
- Positive in both task families and all four wording variants.
- This signal generated Study 5 and must be labeled **exploratory/post-hoc**.

## Study 5 — Wrong Answer Contamination fresh confirmatory

- Wrong-candidate accuracy: **75%**
- Correct-candidate accuracy: **85%**
- No-candidate accuracy: **80%**

Preregistered primary contrasts:

1. No candidate − Wrong candidate:
   - **+5.0 pp**
   - Frozen bootstrap 95% CI: **[−15.0, +25.0] pp**
   - One-sided exact paired **p = 0.50**

2. Correct candidate − Wrong candidate:
   - **+10.0 pp**
   - Frozen bootstrap 95% CI: **[0.0, +25.0] pp**
   - One-sided exact paired **p = 0.25**

Robustness:
- No > Wrong in **1/2** task families.
- No > Wrong in **2/4** wording variants.
- Confirmatory success: **false**.

Descriptive attenuation of the post-hoc Study 4 interference signal (+23.333 pp) to the fresh Study 5 No-vs-Wrong contrast (+5.0 pp): **78.6%**. This is descriptive only because the confirmatory operationalization deliberately added a correct-candidate control and isolated the wrong-candidate condition.

## Cross-study wording for the manuscript

Preferred:
> Under these operationalizations and this fixed API configuration, none of the five candidate large behavioral effects survived its study-specific prospective criterion.

Avoid:
> LLMs do not have human psychological effects.

Avoid:
> We proved that psychological effects in LLMs are false.

The paper concerns **fragility under fresh prospective testing**, not the universal absence of prompt-context effects.
