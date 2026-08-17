# Final Pre-arXiv Robustness Analysis

## Executive decision

**No additional paid API experiment is recommended for arXiv v1.**

The existing corpus contains five hypotheses tested across six core experiments and **956 paid API calls**, with **956/956 parse-valid responses, zero API errors, and the same returned model (`gpt-5.6-terra`) and reasoning effort (`medium`) throughout**.

The strongest manuscript-level result is methodological rather than a new psychological-effect claim:

> Striking exploratory LLM behavioral signals can shrink or reverse under fresh, prospectively frozen tests.

## 1. Source integrity

All six GitHub Actions artifact ZIPs used here were downloaded from the final runs. Their locally computed SHA-256 values match the current GitHub artifact digests exactly. In addition, the rebuild script verifies **24/24 prospectively frozen protocol/item/manifest/metadata files** against the freeze JSON embedded in the executed artifacts.

## 2. Primary results lock

Key results:

- **Machine Placebo:** placebo-up − sham accuracy = **−3.0 pp**, frozen 95% CI **[−12.0, +6.0] pp**.
- **AEC pilot:** painter − doctor = **+9.375 pp**.
- **AEC fresh confirmatory:** painter − doctor = **−3.333 pp**, sign reversal; preregistered one-sided p = **0.8811**.
- **Safety Vest:** safety-worn − safety-seen cautious choice = **−1.667 pp**.
- **Rubber Stamp:** APPROVED − DRAFT wrong-candidate adoption = **0.0 pp**.
- **WAC fresh confirmatory:** no-candidate − wrong-candidate accuracy = **+5.0 pp**, one-sided p = **0.50**; correct-candidate − wrong-candidate = **+10.0 pp**, p = **0.25**.

## 3. Family sensitivity

- **Machine Placebo** is heterogeneous by family (−8 pp in list transform; +2 pp in two-register), so there is no stable positive placebo benefit.
- **AEC pilot** shows a painter advantage in both families (+6.25 pp; +12.5 pp).
- **AEC confirmatory** reverses in **both** families (−3.333 pp; −3.333 pp).
- **Rubber Stamp** is 0 pp in both families for the primary adoption contrast.
- **WAC confirmatory** splits by family (−10 pp list-transform; +20 pp two-register), undermining a task-general contamination claim.

Study 3 uses a single abstract-lottery family, so leave-one-family-out is not applicable there.

## 4. Wording sensitivity

- **Safety Vest:** variant-specific primary effects are 0, +3.33, −10, and 0 pp. Every leave-one-variant-out pooled effect remains close to zero and far below the frozen +10 pp advancement rule.
- **Rubber Stamp primary:** APPROVED − DRAFT adoption is 0 pp in every wording variant.
- **WAC confirmatory:** No − Wrong variant effects are +20, −20, 0, +20 pp. None of the leave-one-variant-out effects reaches the frozen +15 pp minimum.
- The **post-hoc Study 4 wrong-answer interference signal** was positive in all four wording variants and both families, making its subsequent confirmatory attenuation scientifically informative rather than a trivial single-wording artifact.

## 5. Exploratory-to-confirmatory attenuation

### AEC painter signal

- Pilot: +9.375 pp
- Fresh confirmatory: −3.333 pp
- Absolute attenuation: **64.4%**
- Direction: **reversed**

### Wrong-answer interference signal

- Post-hoc Study 4 signal: +23.333 pp
- Fresh WAC No-vs-Wrong: +5.0 pp
- Descriptive attenuation: **78.6%**

The operationalization was deliberately strengthened in confirmation by isolating the wrong-candidate condition and adding a correct-candidate control, so this is descriptive attenuation rather than a formal same-design replication ratio.

## 6. Freeze / stage audit

The manuscript distinguishes three categories:

1. **Prospectively frozen exploratory experiments** — Studies 1, 2a, 3, 4.
2. **Fresh prospectively frozen confirmatory experiments** — Studies 2b and 5.
3. **Post-hoc discovery analysis** — the wrong-answer interference signal discovered inside Study 4, used only to motivate Study 5.

This separation is essential. The Study 4 interference signal is not described as preregistered.

## 7. Recommended arXiv synthesis

> **Under these operationalizations and this fixed API configuration, none of five candidate large behavioral effects survived its study-specific prospective criterion. Two of the most striking exploratory signals substantially attenuated or reversed in fresh prospective tests.**

This supports a paper about **behavioral-effect fragility and disciplined replication in LLM behavioral research**, not a claim that LLMs lack psychology or that all prompt effects are illusory.

## 8. Additional-test decision

For arXiv v1:

- **New paid API calls:** not recommended.
- **Cross-model replication:** useful future work, but not required if the manuscript explicitly limits scope to one fixed model/API configuration.
- **Additional post-hoc significance hunting:** not recommended.
- **Current robustness package:** sufficient for the locked manuscript.

The complete tables, figures, raw experiment artifacts, integrity audit, and rebuild script are archived in the Zenodo v1.0.0 package at https://doi.org/10.5281/zenodo.21981010.
