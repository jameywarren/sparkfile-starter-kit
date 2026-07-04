# Bonus playbook: Build your VOICE.md from what Claude already knows about you

**The job it does:** Builds a real VOICE.md from an existing Claude
history, or through a few questions if you're starting fresh.

If you've been talking to Claude for a while already, in a project or a
long-running chat, use this first. Claude has likely seen more of your
actual writing than you'd guess.

```
I need you to write my VOICE.md file: a memory file that captures how I
actually write, so future drafts sound like me. You have a long history
of me typing to you directly here. Use it.

1. Look back through our conversation history and find two or three
   places where I wrote something substantial in my own words, not a
   quick one-line instruction. Quote them verbatim if you can find them.
2. Beyond direct quotes, tell me honestly what patterns you've noticed:
   sentence length, structure, favorite words or phrases, what I say
   often, what I never say.
3. List words and phrases I'd never use, based on what you've seen me
   edit out or react badly to.

Write VOICE.md directly: real quotes where you have them, your honest
characterization where you don't, and the avoid list. Label anything
that's your observation rather than my exact words, so I can tell the
difference.
```

No history to draw on yet? Start fresh instead:

```
I need to build a VOICE.md file: a short memory file that captures how I
actually write, so drafts sound like me instead of a generic assistant.

Ask me these questions one at a time, waiting for my answer before the
next one:

1. Paste two or three things you've written yourself, unaided: an email,
   a post, a message, anything real.
2. What are three words or phrases you'd never use? What do you cut on
   sight when you see it in a draft?
3. Is there a real person or publication whose writing you'd point to and
   say "closer to that"?

Once I've answered, write VOICE.md: the real samples, the avoid list, and
a short "not me" section I can add to over time. Don't invent or smooth
over anything. If an answer is thin, say so instead of padding it out.
```

**What to watch for:**
- The history-mining version usually works better if you've genuinely been using Claude a lot. The blank-page version is the fallback, not the default.
- Treat the first version as a draft. Add to the "not me" list the next time a Claude draft comes back sounding wrong.
- A quick chat reply can be a legitimate sample. Real and rough beats polished and generic every time.
