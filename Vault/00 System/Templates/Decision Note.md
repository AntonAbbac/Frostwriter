---
type: decision
status: "{{VALUE:Open,Decided,Reviewed|label:Status|default:Open}}"
created: "{{DATE:YYYY-MM-DD}}"
modified: "{{DATE:YYYY-MM-DD}}"
decide_by: "{{VDATE:decide_by,YYYY-MM-DD|optional}}"
reversible: "{{VALUE:Yes,Partly,No|label:Reversible?|default:Yes}}"
project: "{{VALUE:project|label:Related project|optional}}"
---

# {{NAME}}

## Decision to Make
*One sentence, phrased as a question.*

## Context
**Situation:**

**Constraints:**

**Unknowns:**
*What would change my mind if I knew it?*

## Options

| Option | Description | Benefits | Risks | Effort | Long-term impact |
| ------ | ----------- | -------- | ----- | ------ | ---------------- |
| A      |             |          |       |        |                  |
| B      |             |          |       |        |                  |
| C (do nothing) |     |          |       |        |                  |

## Decision
**Chosen:**

**Why:**

**Trade-offs accepted:**

**Immediate actions:**
- [ ] 

**Review date:** 

## Review
*Fill in after the outcome.*

**What happened:**

**What worked / failed:**

**What I'd decide differently, and why:**
