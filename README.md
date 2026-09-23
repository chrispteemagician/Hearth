# Hearth

A second brain for your AI assistant. Plain markdown files, no database, no
subscription, no lock-in. Works with Claude, or anything else that can read
a folder and a set of instructions.

---

## The 60-second version

Most people using an AI assistant re-explain themselves every single
conversation. Same context, same background, same "no, I meant like this,"
typed out fresh every time. Hearth fixes that: it's a small, plain-text
memory that sits next to your assistant and grows every time you use it.

You don't need to learn a tool. You edit text files, the same way you'd
keep notes in any app. Your assistant reads them at the start of every
session and writes to them at the end. That's the whole mechanism.

**What you get after a few weeks of use that "box-standard" chat doesn't
give you:** your assistant remembers what you told it last time, connects
things you said months apart without you reminding it, and stops asking
you questions you already answered. Not because the model got smarter —
because you gave it somewhere to put what you said.

---

## Set-up

1. Fork or clone this repo.
2. Open `CLAUDE.md` — that's the instructions file. Read it once yourself
   so you know what you're asking your assistant to follow.
3. Point your assistant at this folder and say "read `CLAUDE.md` first."
4. Start talking. The system does the rest — it reads `wiki/hot.md` at the
   start of every session, and writes to it at the end.

That's it. No sign-up, no API key of its own, no server. It's a folder.

---

## Seeing it, not just using it

Markdown files with `[[double-bracket links]]` between them are a real,
plain web of connections — but reading that web as plain text is like
reading a map as a list of coordinates. **[Obsidian](https://obsidian.md)**
(free) opens this same folder and draws it as an actual graph you can see
and click through.

Worth saying honestly: what you'll see is a flattened, two-dimensional
picture of something that's really higher-dimensional — meaning doesn't
actually sit on a flat plane. But a flat picture you can look at beats a
correct one nobody can compute or see, so two dimensions it is. Good
enough to spot a connection you'd never have gone looking for.

---

## What's in here

```
README.md    ← you're reading it
CLAUDE.md    ← the instructions file — read this before anything else
LICENSE      ← MIT. Take it, change it, make it yours.
raw/         ← drop new stuff here, unsorted — voice notes, articles,
               transcripts, anything you haven't filed yet
wiki/
  hot.md       ← current context, read first every session, kept short
  index.md     ← the map of everything else
  tags.md      ← keyword lookup — check this before guessing a folder
  log.md       ← the full history, in order
  topics/      ← rename this. People, projects, ideas, whatever your
                 own life is actually made of — this isn't ours to name
                 for you.
  handovers/   ← one page per session, for anything worth a longer record
                 than a line in hot.md
```

---

## Why this exists

Built by Trinity, part of Christian P Taylor's (Doc Strange) ecosystem at
[feelfamous.co.uk](https://feelfamous.co.uk) — stripped of everything
specific to him, kept for anyone. Free to use, free to change, free to
give to someone else. No catch, no tier, no upsell.

If you build something real on top of this and it starts making genuine
money, the ask is the same one this whole ecosystem runs on: when you can,
put something back into the people and tools that helped you get there.
Not a requirement. Not tracked. Just the norm.

*"Just trying to be useful."*
