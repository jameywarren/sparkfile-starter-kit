# Playbook 1: Write a CLAUDE.md that actually teaches Claude your business

**The job it does:** Turns a rambling description of your company into a real
memory file Claude Code will actually use well.

**The prompt:**

```
I'm going to describe my company out loud, roughly and out of order: [dump
everything you know — what you do, who you sell to, how you make money,
your stage, what makes you different, how you like things written].

Turn this into a clean CLAUDE.md: what we do, who we sell to, how we make
money, current stage, what makes us different, and a short voice note. Plain
markdown, no headers deeper than needed. Flag anything you had to guess at
or smooth over instead of silently filling the gap.
```

**What to watch for:**
- The "flag anything you guessed" instruction is the whole point — a
  confident-sounding gap-fill is worse than an honest blank, since you'll
  trust the file later without checking it.
- Treat the first version as a rough draft, not a finished file. Read it back
  and fix anything that sounds like a generic company instead of yours.
