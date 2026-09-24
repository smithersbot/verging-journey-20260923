# Regression Report for your product 598ed84

Activation act_mku68cy

| **Tested** | your product 598ed84, against 793777a (Onboarding against 257219a) |
|---|---|
| **Release verdict** | Not ready: tokens up 81.2% |
| **Date** | 2026-09-24 |
| **Environment** | Hermes · GPT-5.6 Luna · documented integration |
| | We set this setup up again from the vendor's docs: docs changed at https://github.com/basicmachines-co/basic-memory |
| **Test suites** | Onboarding and Core Recall |
| **Environments tested** | 2 (Hermes · GPT-5.6 Luna · documented integration: Onboarding, Core Recall) |
| **Stage** | Preliminary report (the final report follows) |

Test suites not run: Preference Adherence, Truth Maintenance, History Migration, Memory at Scale, Long-Horizon Retention.

## Results at a glance

**Accuracy:** No failures: all 17 tests passed. That is 100.0 out of 100, up 5.9 points from 94.1 on 793777a.

**Speed:** 7m 46s, down 20.3% (within expected variation)

**Tokens:** Tokens used: 561,096 of your 750,000 allowance; no token overage.

| Test suite | Accuracy /100 | Pending | Tokens | Speed |
|---|---|---|---|---|
| Onboarding | 100.0 (→ 0.0) | 0 | not recorded | 5m 11s (↓ 26%) |
| Core Recall | 100.0 (↑ 6.2) | 0 | Tokens used: 561,096 of your 750,000 allowance; no token overage. | 2m 34s (↓ 6%) |
| **All suites** | **100.0 (↑ 5.9)** | **0** | **Tokens used: 561,096 of your 750,000 allowance; no token overage.** | **7m 46s (↓ 20%)** |

## Accuracy changes

| Test type | Accuracy /100 | Pending |
|---|---|---|
| Onboarding | 100.0 (→ 0.0) | 0 |
| Direct Recall | 100.0 (→ 0.0) | 0 |
| Updated Facts | 100.0 (→ 0.0) | 0 |
| Synthesis | 100.0 (↑ 33.3) | 0 |
| False memory check | 100.0 (→ 0.0) | 0 |

| Failure type | 598ed84 | 793777a |
|---|---|---|
| Wrong Answer | 0 | 1 |

### What regressed

Nothing. Every test that passed on 793777a still passes on 598ed84.

### What improved

1 test moved from failing to passing:
- Synthesis: 1 test, Wrong Answer on 793777a, passes on 598ed84 (id cr1c08).

### Still failing

Nothing else is failing.

## Speed changes

The 17 tests ran in 7m 46s, down 20.3% from 9m 44s: within expected variation.

| Test type | 598ed84 | 793777a | Change |
|---|---|---|---|
| Onboarding | 5m 11s | 7m | -25.9% |
| Core Recall (all test types) | 2m 34s | 2m 44s | -5.9% |
| All 17 tests | 7m 46s | 9m 44s | -20.3% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Tokens changes

The 17 tests used 234k tokens: 231k input and 2k output. That is up 81.2% from 129k: outside expected variation.

| Test type | 598ed84 | 793777a | Change |
|---|---|---|---|
| Core Recall (all test types) | 234k | 129k | +81.2% |
| All 17 tests | 234k | 129k | +81.2% |

### What regressed

All 17 tests used 81.2% more tokens, outside expected variation.

Core Recall (all test types) used 81.2% more tokens, outside expected variation.

### What improved

Nothing outside expected variation.

## Next steps

1. **Review the token increase:** all 17 tests used 81.2% more tokens and Core Recall (all test types) used 81.2% more tokens, outside expected variation. The token record shows why: 598ed84 read 82.5% more input per test than 793777a (output up 4.1%).
2. **Test your next release before it ships.** See what broke before your users do.
3. **Wait for the final report before gating a release on these numbers:** this is the preliminary report; the final report follows and lists exactly what changed under "What changed since the preliminary report".

---

Terms used in this report are defined in the reading guide: https://verginglabs.com/memory-ci/reading-guide

Next activation: set `activation_id: act_ugaukjx`. It costs 20 activation environments, plus any usage above your included allowances.
Earlier activations: `act_ug8g7gs` on 2026-09-24.

