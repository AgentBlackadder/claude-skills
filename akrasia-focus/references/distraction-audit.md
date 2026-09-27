# Distraction audit

The aim is to find the user's **specific** leaks, not distraction in general,
and remove the cue before the session rather than resisting it during.

## Step 1: the log (one or two days)

During normal work, each time attention leaves the task, write one line:

```
Time | What I switched to | What the task was asking of me just before | Trigger
```

Triggers usually fall into four kinds:

| Kind          | Examples                                             | Main fix                              |
| ------------- | ---------------------------------------------------- | ------------------------------------- |
| **External**  | notification, message, someone talking to you        | turn off, close, move                 |
| **Visual cue** | phone on the desk, open email tab, icon badge       | take it out of sight                  |
| **Internal**  | boredom, difficulty, dread, "let me just check"      | if-then plan; switch sub-task         |
| **Physical**  | hunger, fatigue, needing to move                     | schedule breaks; don't fight the body |

The third column, what the task was asking just before, is the most useful.
Patterns usually show up fast: "every time I had to decide something", "every
time I had to write the opening".

## Step 2: the environment checklist

Handle each item once, before the session, not during it.

**Phone**

- [ ] in another room, or at least out of sight and out of reach
- [ ] on silent, not vibrate
- [ ] if it's needed as a timer, use a separate timer instead

**Computer**

- [ ] one window, full screen
- [ ] unrelated tabs closed; parked tabs saved to a list if needed
- [ ] email and chat apps fully quit, not minimised
- [ ] system notifications off (a focus mode or do-not-disturb setting)
- [ ] a site blocker for known time sinks, ideally one you can't disable
      mid-session (see `akrasia-commit`)

**Space**

- [ ] the place used for focus is used for little else, if possible
- [ ] water within reach, so thirst isn't an exit
- [ ] the materials for the first action are already open

**People**

- [ ] a visible signal that you're in a block (door closed, headphones on, a
      status message)
- [ ] anyone who might need you knows when the next shallow window is

## Step 3: make the good default easy

Friction works in both directions. Make the focus task the thing that's easiest
to start:

- leave the file open at the exact spot when you stop (the parking note)
- set the browser to open to a blank page, not to email or a feed
- keep a "focus launch" routine: the same sequence every time, so starting
  takes no decisions

## Step 4: re-audit when it stops working

Distractions adapt. Blocking one site often moves the leak to another. If
session logs show urges rising again, repeat step 1 for a day and look at column
three: the underlying discomfort is usually the same, even when the escape
route has changed. Deal with the discomfort (`akrasia-unstick`), not just the
route.
