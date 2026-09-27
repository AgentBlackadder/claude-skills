# claude-skills

Personal [Claude Code](https://claude.com/claude-code) skills. Each folder is one
skill: a short `SKILL.md`, with a `references/` folder for the depth.

## The akrasia set

_Akrasia_ is knowing the better course and taking another. These six skills plan
for the self who has to do the work (tempted, in the moment) rather than the self
who writes the plan. They lean hardest on **focus** and **mental contrasting**.

| Skill              | Use it when                                           | What you get                                  |
| ------------------ | ----------------------------------------------------- | --------------------------------------------- |
| `akrasia-plan`     | planning a day, week or project. **Start here.**      | a diagnosis and a one-priority plan           |
| `akrasia-contrast` | a goal keeps not happening; WOOP / mental contrasting | Wish, Outcome, Obstacle and an if-then rule   |
| `akrasia-focus`    | drifting to tabs, phone or other tasks                | a session set-up, capture list, parking note  |
| `akrasia-unstick`  | stuck right now: dread, overwhelm, guilt              | one first action, started                     |
| `akrasia-commit`   | plans you meant but broke                             | a commitment device, lightest first           |
| `akrasia-review`   | weekly                                                | hit rate, the repeating cause, one experiment |

Every citation, with how much evidence stands behind it, is in
[`akrasia-plan/references/sources.md`](akrasia-plan/references/sources.md). They
were written from memory and haven't been checked against the original papers,
so check one before quoting it.

## Install

Personal skills live in `~/.claude/skills/` and are available in every project.

If that folder doesn't exist yet, clone straight into it:

```sh
git clone https://github.com/AgentBlackadder/claude-skills.git ~/.claude/skills
```

If you already have skills there, clone elsewhere and link each one in:

```sh
git clone https://github.com/AgentBlackadder/claude-skills.git ~/src/claude-skills
for d in ~/src/claude-skills/*/; do ln -sf "${d%/}" ~/.claude/skills/; done
```

Then run `/akrasia-plan` in any Claude Code session, or just describe the problem
("I keep drifting off this task") and let the right skill trigger.

To update, run `git pull` in the clone. If you used the symlink install, run the
loop again afterwards to link any new skills. It's safe to repeat.
