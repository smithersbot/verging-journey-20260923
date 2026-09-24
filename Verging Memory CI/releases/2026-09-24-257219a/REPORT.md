# Regression Report for your product 257219a

Activation act_ug8g7gs

| **Tested** | your product 257219a, your first release on this environment |
|---|---|
| **Release verdict** | Baseline recorded: 17 of 17 tests passing on Hermes · GPT-5.6 Luna · documented integration. The release verdict starts with your next release. |
| **Date** | 2026-09-24 |
| **Environment** | Hermes · GPT-5.6 Luna · documented integration |
| **Test suites** | Onboarding and Core Recall |
| **Environments tested** | 2 (Hermes · GPT-5.6 Luna · documented integration: Onboarding, Core Recall) |
| **Stage** | Preliminary report (the final report follows) |

Test suites not run: Preference Adherence, Truth Maintenance, History Migration, Memory at Scale, Long-Horizon Retention.

## Results at a glance

**Accuracy:** No failures: all 17 tests passed. That is 100.0 out of 100.

**Speed:** 16m 38s (first release: no comparison yet)

**Tokens:** Tokens used: 483,034 of your 750,000 allowance; no token overage.

This is your first release on this environment, so there is nothing to compare these figures with yet: the row above records the baseline instead of a verdict. Your next release on this environment shows what changed, and whether speed and tokens moved outside expected variation.

| Test suite | Accuracy /100 | Pending | Tokens | Speed |
|---|---|---|---|---|
| Onboarding | 100.0 | 0 | not recorded | 7m |
| Core Recall | 100.0 | 0 | Tokens used: 483,034 of your 750,000 allowance; no token overage. | 9m 37s |
| **All suites** | **100.0** | **0** | **Tokens used: 483,034 of your 750,000 allowance; no token overage.** | **16m 38s** |

## Accuracy

| Test type | Accuracy /100 | Pending |
|---|---|---|
| Onboarding | 100.0 | 0 |
| Direct Recall | 100.0 | 0 |
| Updated Facts | 100.0 | 0 |
| Synthesis | 100.0 | 0 |
| False memory check | 100.0 | 0 |

All 17 tests passed.

Every test here is tested for the first time, so none of them is a regression yet. Your next report on this environment names any test that passed here and fails there.

## Speed

The 17 tests ran in 16m 38s. There is nothing to compare that with yet, so it is reported as measured, with no verdict.

| Test type | 257219a |
|---|---|
| Onboarding | 7m |
| Core Recall (all test types) | 9m 37s |
| All 17 tests | 16m 38s |

## Tokens

The 17 tests used 483k tokens: 472k input and 11k output. There is nothing to compare that with yet, so it is reported as measured, with no verdict.

| Test type | 257219a |
|---|---|
| Core Recall (all test types) | 483k |
| All 17 tests | 483k |

## Limitations

The test agent installed and used the memory tool from its public docs. Giving fresh files for each test sequence and removing them afterwards was done by our outer test harness. The tool keeps its data in local files, so a fresh copy of those files per sequence keeps the test fair.

## Next steps

1. **Test your next release before it ships.** See what broke before your users do.
2. **Wait for the final report before gating a release on these numbers:** this is the preliminary report; the final report follows and lists exactly what changed under "What changed since the preliminary report".

---

Terms used in this report are defined in the reading guide: https://verginglabs.com/memory-ci/reading-guide

Next activation: set `activation_id: act_mku68cy`. It costs 20 activation environments, plus any usage above your included allowances.

