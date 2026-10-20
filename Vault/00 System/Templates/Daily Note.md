---
type: periodic
subtype: daily
date: "{{DATE:YYYY-MM-DD}}"
day: "{{DATE:dddd}}"
week: "[[{{DATE:GGGG-[W]WW}}]]"
previous: "[[{{DATE:YYYY-MM-DD-1}}]]"
next: "[[{{DATE:YYYY-MM-DD+1}}]]"
location: "{{VALUE:Location|label:Location|default:Home}}"
sleep: "{{VALUE:Sleep hours|label:Sleep (hours)}}"
energy: "{{VALUE:1,2,3,4,5|label:Energy (1-5)|default:3}}"
---

# {{DATE:dddd, YYYY-MM-DD}}

## Intent
*The one thing that makes today a success.*

## Outcome
*What actually happened? Done / not done, one line each.*

## Friction
*What slowed me down? Was it external, or my own behavior?*

## Signal
*One thing worth remembering from today (an insight, a mistake, a fact).*

## State
*End-of-day snapshot: mood, body, mind. Be literal.*

## Tomorrow
*The single thing that matters most.*
