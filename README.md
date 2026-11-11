# withclaude skills

Two small Claude Code skills I give my withclaude students: **check-in** and **check-out**.

They do what I do at the start and end of every work session with Claude. Check-in gets Claude up to speed before any work starts. Check-out writes down what happened, so the next session (with you or with a fresh Claude) picks up right away instead of starting from zero.

## What they do

**check-in** reads your project's `CLAUDE.md`, your latest handoff, `PLAN.md` and `TASKS.md`, then tells you in plain words what the project does, what you did last time, what's next, and if you have work that isn't saved or backed up. It doesn't change anything.

**check-out** writes one handoff per session in a `handoffs/` folder (done, decided, next, open questions), adds a line to `handoffs/INDEX.md`, updates your tasks, makes a save point and backs it up to GitHub.

If your project already has a `HANDOFF.md`, the first check-out moves it into `handoffs/` and updates your `CLAUDE.md`, so nothing is lost.

## Install

Open Claude Code and paste this:

```
Install the check-in and check-out skills from https://github.com/tehlowkeywiz/withclaude-skills as personal skills, so they work in all my projects. Show me where you put them.
```

Works on Mac and Windows. Claude puts them in your personal skills folder (`~/.claude/skills/` on a Mac, `C:\Users\<your name>\.claude\skills\` on Windows).

## Use

Open Claude Code in your project folder.

- At the start: type `/check-in`, or just say "check in".
- At the end: type `/check-out`, or say "check out".

## Make them yours

Each skill is one plain-text file, `SKILL.md`. Read it. If you want check-out to also note how long you worked, or check-in to read another file, change the steps. Claude follows what's written there.

## License

MIT. Copy them, change them, share them. Just keep the license file.

-Phil
