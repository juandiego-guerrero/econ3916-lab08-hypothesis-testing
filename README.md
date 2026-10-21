# econ3916-lab08-hypothesis-testing
Lab 08 Submission

# Hypothesis Testing — Is Job Training Worth It?

## Objective
I tested whether the National Supported Work (NSW) job training program raised participants' 1978 earnings, and how large and reliable that effect was.

## Methodology
- I loaded the LaLonde NSW job training experiment, which has 445 people: 185 trainees and 260 controls.
- I ran a one-sample t-test and a two-sample Welch's t-test on 1978 earnings to compare trainees with controls.
- I wrote my own function for Welch's t-statistic, `welch_t()`, and checked its output against scipy on the full sample and on five subgroups.
- I computed Cohen's d to judge the size of the effect, not only whether it was statistically significant.
- I ran a power analysis to find the power of this study and the sample size needed to detect an effect of d = 0.3.
- I tested the treatment effect in 5 overlapping demographic subgroups, then applied Bonferroni and Benjamini-Hochberg corrections to account for running multiple tests.
- I simulated p-value distributions under two conditions, one where the null hypothesis is true and one where it is false, to see how p-values behave in each case.

## Key Findings
- Trainees earned $[YOUR VALUE] more in 1978 than controls (Welch's t = [YOUR VALUE], p = [YOUR VALUE]).
- The effect size was a Cohen's d of [YOUR VALUE].
- [YOUR VALUE] of the 5 subgroup effects were significant before correction, and [YOUR VALUE] remained significant after the Bonferroni correction.
