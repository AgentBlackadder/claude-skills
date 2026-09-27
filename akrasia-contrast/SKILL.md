---
name: akrasia-contrast
description: >
  Use when the user has a goal they keep not acting on, feels excited about a
  plan but isn't moving, can't decide whether a goal is worth pursuing, or asks
  for mental contrasting, WOOP, MCII or if-then / implementation-intention
  plans. Runs Wish → Outcome → Obstacle → Plan: set the wished future against
  the inner obstacle in the present, then pre-decide the response. Part of the
  akrasia skill set (hub: akrasia-plan).
metadata:
  version: "1.0.0"
---

# Mental contrasting (WOOP)

Dreaming about a good outcome feels like progress, and that feeling can drain
the energy needed to act (Oettingen). **Mental contrasting** sets the wished
future against the obstacle in the present. That turns a daydream into a problem
to solve, or shows that the goal isn't worth solving. An **if-then plan** then
settles the response before the tempting moment arrives. Research and caveats:
[woop-guide.md](references/woop-guide.md).

## How to run it

Ask **one step at a time, in this order**, and let the user write each answer.
Don't write the WOOP for them: working out their own obstacle is the part that
does the work. It takes five to ten minutes.

1. **Wish.** What do you want to get done (today, this week, or within four
   weeks)? It should be challenging but feasible. One line.
2. **Outcome.** What is the single best result of fulfilling it? Imagine it
   for a moment. What does it feel like?
3. **Obstacle.** What is it **in you** that most gets in the way? An emotion, a
   habit, a belief or an urge. Imagine the moment it shows up.
4. **Plan.** "If <that obstacle>, then I will <specific action>."

The order matters: future first, then reality. Reversing it weakens the effect.

## Push back on these

- **An external obstacle.** "No time" or "my phone" names a circumstance, not
  the obstacle. Ask what happens inside at that moment: "the pull to check the
  phone when a sentence gets hard".
- **A vague plan.** "Then I'll focus" isn't an action. "Then I'll write the urge
  on the capture list and finish the sentence" is.
- **Several obstacles at once.** Take the main one. Add a second if-then only if
  the user asks.

## The feasibility checkpoint

After step 3, ask: **"Now that you've seen the obstacle, is this still worth
it?"** Mental contrasting is meant to build commitment to goals that can be
reached and to loosen commitment to ones that can't. If the honest answer is no,
help the user shrink, reshape or drop the wish. Dropping a goal on purpose ends
the loop of intending and not doing, and that counts as success.

## Output

```
Wish:      <one line>
Outcome:   <the best result, in the user's words>
Obstacle:  <an inner obstacle, specific to a moment>
If-then:   If <obstacle>, then I will <action>.
```

The if-then goes into the plan's `If-then:` line (`akrasia-plan`). Ready-made
patterns for focus, starting and avoidance:
[if-then-library.md](references/if-then-library.md).
