---
name: akrasia-plan
description: >
  Use whenever the user asks to plan a day, a week or a project, says they keep
  not doing what they planned, or mentions akrasia, procrastination, willpower
  or "I know what to do but I don't do it". Entry point for the akrasia skill
  set: diagnoses which lever is failing, writes a plan built for the tempted
  present-moment self rather than the calm planning self, and routes to
  akrasia-contrast (goal vs obstacle), akrasia-focus (holding attention),
  akrasia-unstick (cannot start right now), akrasia-commit (binding the future
  self) and akrasia-review (weekly calibration).
metadata:
  version: "1.0.0"
---

# Plan for the self who has to do it

**Akrasia** is knowing the better course and taking another. Plans rarely fail
for lack of knowing what to do. They fail because the calm self who writes the
plan is not the tempted self who has to carry it out. So treat every plan as a
message to that later self. It has to be small, concrete, decided in advance and
cheap to start. See [akrasia explained](references/akrasia-explained.md).

## How to run this skill

Ask one question at a time, keep your replies short, and finish with the plan
block below. Don't lecture. The user came for a plan, not a theory.

## 1. Diagnose (one minute)

Steel's procrastination equation says motivation rises with **expectancy ×
value** and falls with **impulsiveness × delay**. Ask which one is weakest today:

| Weak lever        | Sounds like                         | Go to                                           |
| ----------------- | ----------------------------------- | ----------------------------------------------- |
| Expectancy low    | "I'm not sure I can do this well"   | shrink the task → `akrasia-unstick`             |
| Value low         | "It's boring / what's the point"    | connect it to a wish → `akrasia-contrast`       |
| Impulsiveness high | "I start, then I drift"            | `akrasia-focus`, then `akrasia-commit`          |
| Delay long        | "It's not due for weeks"            | a near deadline → `akrasia-commit`              |

Depth: [procrastination-equation.md](references/procrastination-equation.md).

## 2. Write the plan

```
ONE THING:     <if only this gets done, the day was a win>
Done means:    <a finish line you can see, not "work on">
First action:  <physical, under two minutes: "open draft.md, write the heading">
When / where:  <a time block and a place>
If-then:       If <likely obstacle>, then I will <response>.
Guard:         <one friction change or commitment device>
Then (max 2):  <only once ONE THING is done>
```

Rules:

- **One must-win, three tasks at most.** A twelve-item list is a wish list, and
  the later self ignores it.
- Every task starts with a verb and names its first physical action.
- Put the hardest task in the user's sharpest hours. **Ask** when those are,
  don't assume.
- Estimates run optimistic, so scale them by the user's own ratio from
  `akrasia-review`. If there isn't one yet, use ×1.5 as a stand-in.
- Plan the night before or first thing in the morning, not after the day has
  already got away.

Templates for the day, the week and a project:
[planning-templates.md](references/planning-templates.md).

## 3. Hand off

Once the plan exists, send the user to the skill for the lever you found. If the
if-then line is weak, run `akrasia-contrast`. If a session is about to start,
run `akrasia-focus`.

## Guard rails

- **Don't moralise.** Self-criticism predicts more procrastination, not less
  ([emotion-regulation.md](../akrasia-unstick/references/emotion-regulation.md)).
- **Not everything is akrasia.** If focus trouble has been lifelong, shows up in
  every area of life and does real damage, suggest seeing a GP about an ADHD
  assessment. Say it once, plainly, and don't diagnose.
- Keep plans in the chat. If the user wants a running log, ask where it should
  live. Don't create files unasked.
- Every citation in this set is listed, with how strong its evidence is, in
  [sources.md](references/sources.md).
