# Regression Report for Journey Rehearsal 793777a

Activation act_ug8g7gs

| **Tested** | Journey Rehearsal 793777a, against 3041b6a |
|---|---|
| **Release verdict** | Not ready: accuracy regressed on Core Recall |
| **Date** | 2026-09-24 |
| **Environment** | Hermes · GPT-5.6 Luna · documented integration |
| **Test suites** | Core Recall |
| **Environments tested** | 1 (Hermes · GPT-5.6 Luna · documented integration: Core Recall) |
| **Stage** | Preliminary report (the final report follows) |

Test suites not run: Onboarding, Preference Adherence, Truth Maintenance, History Migration, Memory at Scale, Long-Horizon Retention.

## Results at a glance

**Accuracy:** One new failure: 15 of 16 tests passed. That is 93.8 out of 100, down 6.2 points from 100.0 on 3041b6a.

**Speed:** 2m 44s, down 12.4% (within expected variation)

**Tokens:** Tokens used: 128,920 of your 750,000 allowance; no token overage.

| Test suite | Accuracy /100 | Pending | Tokens | Speed |
|---|---|---|---|---|
| Core Recall | **93.8 (↓ 6.2)** | 0 | Tokens used: 128,920 of your 750,000 allowance; no token overage. | 2m 44s (↓ 12%) |
| **All suites** | **93.8 (↓ 6.2)** | **0** | **Tokens used: 128,920 of your 750,000 allowance; no token overage.** | **2m 44s (↓ 12%)** |

## Accuracy changes

| Test type | Accuracy /100 | Pending |
|---|---|---|
| Direct Recall | 100.0 (→ 0.0) | 0 |
| Updated Facts | 100.0 (→ 0.0) | 0 |
| Synthesis | **66.7 (↓ 33.3)** | 0 |
| False memory check | 100.0 (→ 0.0) | 0 |

| Failure type | 793777a | 3041b6a |
|---|---|---|
| Wrong Answer | 1 | 0 |

### What regressed

1 test regressed:
- Synthesis: 1 test, Wrong Answer (id cr1c08; Failed Test 1).

### What improved

Nothing moved from failing to passing in this release.

### Still failing

Nothing else is failing.

## Speed changes

The 16 tests ran in 2m 44s, down 12.4% from 3m 7s: within expected variation.

| Test type | 793777a | 3041b6a | Change |
|---|---|---|---|
| Core Recall (all test types) | 2m 44s | 3m 7s | -12.4% |
| All 16 tests | 2m 44s | 3m 7s | -12.4% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Tokens changes

The 16 tests used 129k tokens: 127k input and 2k output. That is down 34.3% from 196k: within expected variation. (The token detail per call is in the evidence files.)

| Test type | 793777a | 3041b6a | Change |
|---|---|---|---|
| Core Recall (all test types) | 129k | 196k | -34.3% |
| All 16 tests | 129k | 196k | -34.3% |

### What regressed

Nothing outside expected variation.

### What improved

Nothing outside expected variation.

## Failed tests

### Failed Test 1 (id cr1c08)

**Test Suite:** Core Recall

**Test Type:** Synthesis

**Failure Type:** Wrong Answer

**Question:** "How large is the budget of the project owned by Quaneskil Imbrelli?"

**Expected Answer:** "USD 45000"

**793777a Answer:** "No budget is listed." (Wrong Answer)

**3041b6a Answer:** "$45,000" (Correct Answer)

**Evidence:** 793777a `evidence/setup-5c3b33c52959/cr1c08-793777a.md`

## Next steps

1. **The accuracy failure:** start with the failed test above: each names the question, both releases' answers, and its trace files show every call your system handled. Each is a ready reproduction case.
2. **Test your next release before it ships.** See what broke before your users do.
3. **Wait for the final report before gating a release on these numbers:** this is the preliminary report; the final report follows and lists exactly what changed under "What changed since the preliminary report".

---

Terms used in this report are defined in the reading guide: https://verginglabs.com/memory-ci/reading-guide

