---
type: ti-note
created: "{{DATE:YYYY-MM-DD}}"
modified: "{{DATE:YYYY-MM-DD}}"
system: "{{VALUE:System/App name|label:System / App}}"
ticket: "{{VALUE:Ticket or reference|label:Ticket / reference|optional}}"
status: "{{VALUE:Open,Resolved,Monitoring|label:Status|default:Resolved}}"
tags:
  - ti/log
---

# {{VALUE:Short summary|label:Short summary}}

## Issue
*What was happening, who or what was affected, and since when?*

{{VALUE:Problem or context|label:Problem or context}}

## Root Cause
*Known, suspected, or unknown. Say which.*

## Action Taken
*Steps in order, so they can be repeated.*

{{VALUE:Action taken or solution|label:Action taken or solution}}

## Verification
*How did I confirm it worked?*

## Follow-up
- [ ] {{VALUE:Pending items|label:Pending items (or None)|default:None}}
