# Commitment device menu

A commitment device is anything the planner sets up **now** that changes what
the doer will face **later**, by removing an option, making it costlier, or
making the good option cheaper. Economists define them as arrangements people
choose that restrict their own future choices (Bryan, Karlan & Nelson, 2010).

Pick the lightest device that fits the failure pattern, then escalate one step
at a time only if the review shows it isn't holding.

## 1. Friction: make the wrong thing harder

**What:** add steps between you and the temptation. Log out of the site after
every use. Delete the app and use the browser version only. Put the phone in a
drawer in another room. Hide the games folder.

**Why it works:** present bias is strongest when the temptation is instant. Even
20 seconds of effort gives the planner's preference a chance to show up.

**Backfires when:** the friction is trivially bypassed on autopilot (a
logged-out site whose password is auto-filled). Make sure the friction takes
real effort.

## 2. Easy default: make the right thing easier

**What:** the mirror of friction. Leave the document open at the exact line
before stopping. Lay out gym clothes the night before. Set the browser's start
page to the project, not email.

**Why it works:** starting is the costliest moment, so every decision removed
from it helps.

**Backfires when:** rarely. This is the cheapest device and should almost always
be in place.

## 3. Social commitment: say it to someone

**What:** tell a specific person a specific commitment with a date: "I'll send
you the draft by Thursday 5pm."

**Why it works:** it adds a reputational cost to defecting and a referee who
isn't you.

**Backfires when:** the person won't actually check, or the commitment is too
vague to check ("I'll work on it"). Also some people feel as though they've made
progress just by announcing a goal. Commit to a **deliverable**, not an
identity ("I'm going to be a writer").

## 4. Co-working and body doubling

**What:** a set time to work alongside someone, in person or on a video call,
each doing their own work. Say your goal at the start and report at the end.

**Why it works:** a light social presence plus a fixed start time. It combines
an easy default (the session exists) with a social commitment.

**Backfires when:** the session turns into chatting. Keep talk to the opening
and closing two minutes. Formal evidence is thin, so treat it as something to
try. Check what current co-working services offer before recommending one.

## 5. Self-set deadlines with a referee

**What:** break a distant deadline into spaced milestones, each with an output
and someone who sees it on the date.

**Why it works:** it shortens the delay lever directly. In Ariely & Wertenbroch
(2002), people who set their own deadlines did better than those with none but
worse than those given evenly spaced deadlines, because self-set deadlines tended
to be too late. So **space them evenly**, and don't let the tempted self pick
the dates.

**Backfires when:** there's no consequence and no referee, so the milestone
quietly slides.

## 6. Stakes: put something on the line

**What:** money or something else you value, forfeited if a checkable
commitment is missed. Services exist for this. stickK (founded by economists
including Dean Karlan and Ian Ayres) and Beeminder (built by Daniel Reeves and
Bethany Soule explicitly as an anti-akrasia tool) are the best known. A
low-tech version: give a friend $50 to return only if you deliver.

**Why it works:** it brings the cost of defecting into the present, where
present bias can feel it.

**Backfires when:**

- the stake is so large that it causes anxiety, which is itself an aversive
  feeling to avoid (see `akrasia-unstick`)
- the referee is you, so it's easy to fudge
- the commitment is vague, so arguments about whether it was met replace doing
  it

Check each service's current terms, pricing and currency support before
recommending it. Don't quote them from memory.

## 7. Hard block: remove the option

**What:** a website or app blocker that can't be turned off until a set time, a
time-locked container for the phone, or a router schedule.

**Why it works:** there's no option to defect, so no willpower is needed.

**Backfires when:** it blocks something genuinely needed, so the user learns to
disable it. Or the leak simply moves to another site or device. Pair blocks
with the distraction audit (`akrasia-focus`) to find where the leak goes next.

## Choosing: failure pattern → device

| Pattern (from `akrasia-review`)                 | Start with                         | Escalate to            |
| ----------------------------------------------- | ---------------------------------- | ---------------------- |
| drifts mid-session to the same sites or apps    | friction                           | hard block             |
| never gets started                              | easy default + co-working          | social commitment      |
| everything happens in the last-minute sprint    | spaced self-set deadlines + referee | stakes                |
| plans kept for a week, then abandoned           | never-miss-twice exception rule    | stakes                 |
| the task has low value to the user             | social commitment (someone who values it) | reconsider the goal |

## A caution

Devices treat symptoms of present bias, and that's legitimate. But if a goal
needs heavy devices week after week, run `akrasia-contrast` on it again. It may
be someone else's goal, or one the user doesn't actually want at this price.
