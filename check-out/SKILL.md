---
name: check-out
description: "End a work session on this project: write a handoff, make a save point and back it up. Use when I say check out, wrap up, or we're done for today."
---

# Check out

Wrap up this session so the next one, with me or with a fresh Claude, can pick up right away.

1. Write a new handoff file in `handoffs/`, named with today's date and time and a few words about the session, for example `handoffs/2026-11-12-1430-contact-form.md`. Create the folder if it doesn't exist. In it:
   - **Done:** what we did this session.
   - **Decided:** the decisions we made, and why.
   - **Next:** what to do next, in order.
   - **Open questions:** anything I still have to decide.

   Short, plain words, this session only. Don't copy older handoffs.
2. Add one line at the top of `handoffs/INDEX.md` (create it if needed): the date, the file name and one sentence about the session. Newest first.
3. If `TASKS.md` exists, update each task's status: to do, doing or done.
4. The first time only: if there is an old `HANDOFF.md`, move it into `handoffs/` as the first entry, named with its date, and add it to the index. If `CLAUDE.md` says to read or update `HANDOFF.md`, replace that with: "At the start of a session, use check-in. At the end, use check-out." Tell me you did it.
5. Make a save point with a short message about the session, then back it up to GitHub. If the backup fails, tell me in plain words what went wrong. The save point stays on my computer either way.
6. Show me the handoff you wrote, and confirm the save point and the backup.

Answer in the language I write in.
