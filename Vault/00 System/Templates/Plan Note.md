---
type: plan
plan_type: "{{VALUE:Project,Strategic,Personal development,Action|label:Plan type|default:Project}}"
status: "{{VALUE:Planning,Active,Paused,Done|label:Status|default:Planning}}"
priority: "{{VALUE:Low,Medium,High,Critical|label:Priority|default:Medium}}"
created: "{{DATE:YYYY-MM-DD}}"
modified: "{{DATE:YYYY-MM-DD}}"
area: "{{VALUE:Career,Relationships,Health,Finance,Studies,Writing,Personal|label:Area|custom}}"
deadline: "{{VDATE:deadline,YYYY-MM-DD|optional}}"
people: "{{VALUE:people|label:People involved or affected|optional}}"
parent: "{{VALUE:parent|label:Parent plan|optional}}"
nav_hidden: true
---

# {{NAME}}

## Objective
*What does "done" look like? Concrete and checkable.*

## Definition of Done
- [ ] 
- [ ] 

## Why Now
*What is at stake if I don't act?*

## Current Situation
*Starting point: resources, context, constraints.*

## Strategy

| Step | Action | Deadline | Status |
| ---- | ------ | -------- | ------ |
| 1    |        |          |        |
| 2    |        |          |        |
| 3    |        |          |        |

## Resources
*Skills, contacts, information, timing working in my favor.*

## Risks & Contingencies
*What could go wrong → what I'll do if it does.*

## Next Action
*The single next physical step.*

## Tasks
- [ ] 

## Blockers

## Log

| Date | Update |
| ---- | ------ |
| {{DATE:YYYY-MM-DD}} | Plan created |
