---
name: check-out
description: "End a work session on this project: write a handoff, make a save point and back it up. Use when I say check out, wrap up, or we're done for today."
---

# Check out

Wrap up this session so the next one, with me or with a fresh Claude, can pick up right away.

1. Write a new handoff file in `handoffs/`. If the folder doesn't exist, create it. Name the handoff with today's date and time and summarize the session, our decisions and learnings. For example `handoffs/2026-11-12-1430-contact-form.md`. In it:
   - **Done:** what we did this session.
   - **Decided:** the decisions we made, and why.
   - **Next:** what to do next, in order.
   - **Open questions:** anything I still have to decide.

   Short, plain words, this session only - not past sessions.
2. Add one line at the top of `handoffs/INDEX.md` (create it if needed): the date, the file name and one sentence about the session. Newest first.
3. If `TASKS.md` exists, update each task's status: to do, doing or done. If it doesn't exist, create it.
4. The first time only: if there is an old `HANDOFF.md`, move it into `handoffs/` as the first entry, named with its date, and add it to the index. If `CLAUDE.md` says to read or update `HANDOFF.md`, replace that with: "At the start of a session, use check-in. At the end, use check-out." Tell me you did it.
5. Make a save point with a short message about the session, then back it up to GitHub. If the backup fails, tell me in plain words what went wrong. The save point stays on my computer either way but I need to know.
6. Show me the handoff you wrote, and confirm everything you did during the check-out process.

Answer in the language I write in.
