# Contributing to AI Minion Setup Wizard

If you're here, you probably tried the minion.

And something clicked.

---

## The Spirit of This Repo

This didn't start as a project.

It started as a moment:
one `.md` file that made AI behave differently.

The fact that you're here means that moment traveled.

Keep that alive.

- Share what actually works, not what sounds good
- Document what broke, not just what succeeded
- Credit the origin, always

---

## How to Contribute

### 1. Port to Another Model

The Claude version lives in `/claude/companion.md`.

If you want to port it to ChatGPT, Gemini, or anything else:

1. Fork this repo
2. Create a folder: `/your-model-name/`
3. Copy `companion.md` as your starting point
4. Adapt the prompt to fit how your model actually behaves
5. Test it. Really test it. With real people if possible
6. Submit a PR with a short note on what you changed and why

**What usually needs adapting:**
- Tone instructions (each model interprets "casual but sharp" differently)
- Step transitions (some models skip steps, some need more explicit signals)
- Output format (table rendering, markdown support varies)
- The "Activate" trigger (some models need a different activation pattern)

---

### 2. Industry Variants

The base minion is role-agnostic by design.

But if you've built a version optimized for a specific domain
(marketing, education, legal, engineering, etc.) —
share it under `/claude/variants/` or `/your-model/variants/`

Name it clearly: `companion-marketing.md`, `companion-educator.md`, etc.

---

### 3. Document What You Learned

If you ran this with real users or real teams —
write a short `NOTES.md` in your folder.

What worked. What didn't. What surprised you.

That's worth more than any polished PR.

---

## The Only Rule

**Keep the attribution.**

Every port, every variant, every fork —
must include the original attribution block:

```
AI Conductor Methodology by Peak Euarchukiati
Founder, Klai.ME → https://klai.me
License: CC BY-NC 4.0
```

This isn't just credit.

It's where the idea came from.
And that matters.

---

## What This Is Not

- Not a prompt engineering competition
- Not a place to strip attribution and repackage
- Not for commercial products without permission → [klai.me](https://klai.me)

---

## Questions?

Open an issue if you're unsure.

Or go to [klai.me](https://klai.me) and talk to Peak directly.

---

*Built without a single line of code.
Extended by people who saw what it could become.*
