---
name: akrasia-review
description: >
  Use weekly, or whenever the user asks to review their week, plan the next one,
  or understand why their plans keep failing. Compares what the planning self
  promised with what the doing self did, without blame. Finds the repeating
  cause of misses, adjusts time estimates to the user's real ratio, and picks
  one experiment for next week. Part of the akrasia skill set (hub:
  akrasia-plan).
metadata:
  version: "1.0.0"
---

# Weekly review

The review is where the planner learns what the doer is really like. **A miss is
information about the plan, not a verdict on the person.** A planner who never
reviews keeps writing plans for someone who doesn't exist.

## How to run it

About twenty minutes, ideally at a fixed time such as Friday afternoon or Sunday
evening. Ask for the raw material first, and keep judgement out of the
language: "missed", not "failed".

## The protocol

1. **Collect.** Gather the week's daily plans, the focus-session log, and what
   actually happened (the calendar and what was finished).
2. **Score.** Count, for each day, whether the ONE THING was done: a hit rate
   out of the days planned. Don't rate the self.
3. **Find the cause.** For each miss, pick **one** cause:
   - _over-planned_: more was planned than the time allowed
   - _no first action_: the task was a topic, not a step
   - _focus leak_: which trigger (from the session log)
   - _avoidance_: which feeling (`akrasia-unstick`)
   - _external_: a real, unforeseeable interruption

   Look for the cause that **repeats**. That's the week's finding.
4. **Calibrate.** Actual time ÷ estimated time, across tasks where both are
   known, gives the user's real ratio. Next week, scale estimates by it.
   Reasoning: [planning-fallacy.md](references/planning-fallacy.md).
5. **One experiment.** Pick exactly **one** change aimed at the repeating
   cause: a device (`akrasia-commit`), an if-then (`akrasia-contrast`) or a
   schedule move. One change, so you can tell whether it worked.
6. **Plan the week.** Use the weekly template in `akrasia-plan`, including a
   "not doing" line.

## Adjusting the load

- If the hit rate on the ONE THING is below about 70%, **plan less**. The plan
  is too big for the week you actually have.
- At 100% every day, **plan a little more**, or make the ONE THING harder.
- The 70% line is a heuristic, not a finding. Tune it to the user.

## Output

```
Week:           Hit rate: _/_ days
Repeating cause:
Estimate ratio (actual ÷ planned):
Last week's experiment → keep / adjust / drop:
This week's one experiment:
```

Full template with prompts: [review-template.md](references/review-template.md).
