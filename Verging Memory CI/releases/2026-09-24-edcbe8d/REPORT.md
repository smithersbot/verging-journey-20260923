# Regression Report for your product edcbe8d

Activation act_ugaukjx

| **Tested** | your product edcbe8d, against 598ed84 |
|---|---|
| **Release verdict** | Ready |
| **Date** | 2026-09-24 |
| **Environment** | Hermes · GPT-5.6 Luna · documented integration |
| | We set this setup up again from the vendor's docs: docs changed at https://github.com/basicmachines-co/basic-memory |
| **Test suites** | Onboarding and Core Recall |
| **Environments tested** | 2 (Hermes · GPT-5.6 Luna · documented integration: Onboarding, Core Recall) |
| **Stage** | Preliminary report (the final report follows) |

Test suites not run: Preference Adherence, Truth Maintenance, History Migration, Memory at Scale, Long-Horizon Retention.

## Results at a glance

**Accuracy:** No failures: all 17 tests passed. That is 100.0 out of 100, matching 598ed84.

**Speed:** 14m 20s, down 1.6% (within expected variation)

**Tokens:** Tokens used: 407,866 of your 750,000 allowance; no token overage.

| Test suite | Accuracy /100 | Pending | Tokens | Speed |
|---|---|---|---|---|
| Onboarding | 100.0 (→ 0.0) | 0 | not recorded | 5m 23s (↑ 4%) |
| Core Recall | 100.0 (→ 0.0) | 0 | Tokens used: 407,866 of your 750,000 allowance; no token overage. | 8m 56s (↓ 5%) |
| **All suites** | **100.0 (→ 0.0)** | **0** | **Tokens used: 407,866 of your 750,000 allowance; no token overage.** | **14m 20s (↓ 2%)** |

## Accuracy changes

| Test type | Accuracy /100 | Pending |
|---|---|---|
| Onboarding | 100.0 (→ 0.0) | 0 |
| Direct Recall | 100.0 (→ 0.0) | 0 |
| Updated Facts | 100.0 (→ 0.0) | 0 |
| Synthesis | 100.0 (→ 0.0) | 0 |
| False memory check | 100.0 (→ 0.0) | 0 |

### What regressed

Nothing. Every test that passed on 598ed84 still passes on edcbe8d.

### What improved

Nothing moved from failing to passing in this release.

### Still failing

Nothing else is failing.

## Speed changes

The 17 tests ran in 14m 20s, down 1.6% from 14m 33s: within expected variation.

| Test type | edcbe8d | 598ed84 | Change |
|---|---|---|---|
| Onboarding | 5m 23s | 5m 11s | +3.8% |
| Core Recall (all test types) | 8m 56s | 9m 22s | -4.5% |
| All 17 tests | 14m 20s | 14m 33s | -1.6% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Tokens changes

The 17 tests used 408k tokens: 398k input and 10k output. That is down 27.3% from 561k: within expected variation.

| Test type | edcbe8d | 598ed84 | Change |
|---|---|---|---|
| Core Recall (all test types) | 408k | 561k | -27.3% |
| All 17 tests | 408k | 561k | -27.3% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Next steps

1. **Test your next release before it ships.** See what broke before your users do.
2. **Wait for the final report before gating a release on these numbers:** this is the preliminary report; the final report follows and lists exactly what changed under "What changed since the preliminary report".

---

Terms used in this report are defined in the reading guide: https://verginglabs.com/memory-ci/reading-guide

Next activation: set `activation_id: act_23k7m97`. It costs 20 activation environments, plus any usage above your included allowances.
Earlier activations: `act_ug8g7gs` on 2026-09-24; `act_mku68cy` on 2026-09-24.

