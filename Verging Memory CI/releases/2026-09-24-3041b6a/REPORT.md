# Regression Report for Journey Rehearsal 3041b6a

Activation act_ug8g7gs

| **Tested** | Journey Rehearsal 3041b6a, against 257219a |
|---|---|
| **Release verdict** | Ready |
| **Date** | 2026-09-24 |
| **Environment** | Hermes · GPT-5.6 Luna · documented integration |
| **Test suites** | Core Recall |
| **Environments tested** | 1 (Hermes · GPT-5.6 Luna · documented integration: Core Recall) |
| **Stage** | Preliminary report (the final report follows) |

Test suites not run: Onboarding, Preference Adherence, Truth Maintenance, History Migration, Memory at Scale, Long-Horizon Retention.

## Results at a glance

**Accuracy:** No failures: all 16 tests passed. That is 100.0 out of 100, matching 257219a.

**Speed:** 3m 7s, up 7.5% (within expected variation)

**Tokens:** Tokens used: 196,062 of your 750,000 allowance; no token overage.

| Test suite | Accuracy /100 | Pending | Tokens | Speed |
|---|---|---|---|---|
| Core Recall | 100.0 (→ 0.0) | 0 | Tokens used: 196,062 of your 750,000 allowance; no token overage. | 3m 7s (↑ 8%) |
| **All suites** | **100.0 (→ 0.0)** | **0** | **Tokens used: 196,062 of your 750,000 allowance; no token overage.** | **3m 7s (↑ 8%)** |

## Accuracy changes

| Test type | Accuracy /100 | Pending |
|---|---|---|
| Direct Recall | 100.0 (→ 0.0) | 0 |
| Updated Facts | 100.0 (→ 0.0) | 0 |
| Synthesis | 100.0 (→ 0.0) | 0 |
| False memory check | 100.0 (→ 0.0) | 0 |

### What regressed

Nothing. Every test that passed on 257219a still passes on 3041b6a.

### What improved

Nothing moved from failing to passing in this release.

### Still failing

Nothing else is failing.

## Speed changes

The 16 tests ran in 3m 7s, up 7.5% from 2m 54s: within expected variation.

| Test type | 3041b6a | 257219a | Change |
|---|---|---|---|
| Core Recall (all test types) | 3m 7s | 2m 54s | +7.5% |
| All 16 tests | 3m 7s | 2m 54s | +7.5% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Tokens changes

The 16 tests used 196k tokens: 194k input and 2k output. That is up 9.5% from 179k: within expected variation.

| Test type | 3041b6a | 257219a | Change |
|---|---|---|---|
| Core Recall (all test types) | 196k | 179k | +9.5% |
| All 16 tests | 196k | 179k | +9.5% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Next steps

1. **Test your next release before it ships.** See what broke before your users do.
2. **Wait for the final report before gating a release on these numbers:** this is the preliminary report; the final report follows and lists exactly what changed under "What changed since the preliminary report".

---

Terms used in this report are defined in the reading guide: https://verginglabs.com/memory-ci/reading-guide

