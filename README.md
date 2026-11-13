# withclaude skills

Two small skills, **check-in** and **check-out**, from my live course at [withclaude](https://withclaude.io).

I'm Phil Rivard. I've coached 350+ founders, and I now teach coaches, consultants and founders to build their own tools with Claude, in small live groups. My students install these skills in class. They're public so anyone can use them.

They do what I do at the start and end of every work session with Claude. Check-in gets Claude up to speed before any work starts. Check-out writes down what happened, so the next session (with you or with a fresh Claude) picks up right away instead of starting from zero.

These are the simple version. Mine do a lot more, because they grew with how I work. Start with these, then change them until they fit your own projects and habits.

## What they do

**check-in** reads your project's `CLAUDE.md`, your latest handoff, `PLAN.md` and `TASKS.md`, then tells you in plain words what the project does, what you did last time, what's next, and if you have work that isn't saved or backed up. It doesn't change anything.

**check-out** writes one handoff per session in a `handoffs/` folder (done, decided, next, open questions), adds a line to `handoffs/INDEX.md`, updates your tasks, makes a save point and backs it up to GitHub.

If your project already has a `HANDOFF.md`, the first check-out moves it into `handoffs/` and updates your `CLAUDE.md`, so nothing is lost.

## Install

Open a new chat in the Claude app and paste this:

```
I'm going to give you 2 links to skills on GitHub. Please install these 2 skills for me.
https://github.com/tehlowkeywiz/withclaude-skills/tree/main/check-in
https://github.com/tehlowkeywiz/withclaude-skills/tree/main/check-out
```

Claude shows you each skill before it saves it. Read it, then click Save. Code execution needs to be on in your settings for skills to work.

Installed from the app, the skills also show up in Claude Code when you're signed in with the same account. Already in Claude Code? You can also install them from there:

```
Install the check-in and check-out skills from https://github.com/tehlowkeywiz/withclaude-skills as personal skills, so they work in all my projects. Show me where you put them.
```

## Use

Open Claude Code in your project folder.

- At the start: type `/check-in`, or just say "check in".
- At the end: type `/check-out`, or say "check out".

## Make them yours

Each skill is one plain-text file, `SKILL.md`. Read it. If you want check-out to also note how long you worked, or check-in to read another file, change the steps. Claude follows what's written there. Even better, ask Claude to change it with you.

## Want to go further?

These two skills are one small piece of what we build together in the course. If you want to learn to build your own tools with Claude, in a small live group, have a look at [withclaude.io](https://withclaude.io). You can sign up there to hear when the next one opens.

## License

MIT. Copy them, change them, share them. Just keep the license file.

withclaude isn't endorsed or sponsored by Anthropic. Claude is a trademark of Anthropic.

-Phil
