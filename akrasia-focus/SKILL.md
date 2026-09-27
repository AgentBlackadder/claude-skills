---
name: akrasia-focus
description: >
  Use when the user can't hold attention on one task: drifting to tabs, phone,
  email or messages, switching between tasks, starting many things and finishing
  none. Also use when they ask for a focus session, pomodoro, deep-work block or
  help with distraction. Sets up one timeboxed session with a finish line, a
  distraction capture list and a parking note, and deals with the cost of
  switching context. Part of the akrasia skill set (hub: akrasia-plan).
metadata:
  version: "1.0.0"
---

# One focused session

**Focus is mostly settled before the session starts**: by whether the task is
defined and what's within reach. Willpower in the moment is the most expensive
and least reliable lever, so spend it last.

## How to run it

Walk the user through **Before**, then send them off. Don't stay chatting
during the block, because a chat with Claude is a tab too. When they come back,
run **After**.

## Before (two minutes)

1. **One task, one finish line.** "Done means ___" should describe something
   you can see. If it can't be finished in this block, name the piece that can.
2. **Empty your head.** Write every open loop (the email to send, the thing to
   buy) on a **capture list**. A written plan for an unfinished task quiets its
   intrusions (Masicampo & Baumeister, 2011).
3. **Remove the cues.** Phone in another room, one window, notifications off,
   other tabs closed. Friction beats willpower. Checklist:
   [distraction-audit.md](references/distraction-audit.md).
4. **Pick a length.** Take 25 minutes if resistance is high and 50 once warmed
   up. The ending should feel near.
5. **One if-then** for the distraction the user expects: "If I feel the pull
   to ___, then I ___" (`akrasia-contrast`).
6. **Start the timer, then do the first physical action.**

## During

- **An urge to switch** → write it on the capture list and return. Don't act on
  it and don't fight it: note it, then go back.
- **Stuck** → write down the question you're stuck on and stay in the task.
  Switch sub-task, not task.
- **Something truly urgent** → write a parking note (below), then switch
  cleanly.

## After (two minutes)

1. **Parking note**: one line on where you stopped and the exact next action.
   It makes restarting cheap and reduces attention residue (Leroy, 2009). Stop
   mid-flow where you can; Hemingway stopped when he knew what came next.
2. **A real break**: stand up, away from screens.
3. **Log it**: minutes focused, number of urges written down, finished yes or
   no. That's the data for `akrasia-review`.

## Context switching

Every switch leaves part of your attention on the last task. Three rules:
**finish or park before switching**, **batch shallow work** (email and messages)
into set windows, and **never interleave** two demanding tasks. The mechanism
and how to batch: [context-switching.md](references/context-switching.md).

Session formats (pomodoro variants, warm-up, a three-block day, shutdown ritual):
[session-protocols.md](references/session-protocols.md).
