# Evidence & Evaluation Standard

## Why this exists
AI demos can look impressive while hiding failure modes. This portfolio therefore separates demonstration from evidence.

## Evidence levels
| Level | Meaning |
|---|---|
| L0 | Idea / hypothesis |
| L1 | Specification |
| L2 | Prototype |
| L3 | Reproducible test |
| L4 | Measured evaluation |
| L5 | Real-world validation |

A project must not imply L4 or L5 evidence when only L0–L2 exists.

## Minimum evaluation record
Capture:
- objective
- environment
- input
- expected behaviour
- actual behaviour
- pass/fail criteria
- logs
- limitations
- next action

## Example
~~~text
Experiment: tool-selection test

Input:
  User asks for a calculation.

Expected:
  Calculation tool selected.

Observed:
  ...

Result:
  PASS / FAIL / INCONCLUSIVE

Evidence:
  test-case ID + execution record
~~~

A documented failure can become a reproducible engineering result rather than something hidden.
