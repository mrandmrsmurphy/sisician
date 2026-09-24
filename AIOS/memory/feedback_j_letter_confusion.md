---
name: feedback-j-letter-confusion
description: Recurring self-caught typo — Cyrillic й (U+0439) vs ј (U+0458) — always use ј in this vault
metadata:
  type: feedback
---

**Always use ј (U+0458, "je"), never й (U+0439, "short i") when writing Sisician Cyrillic text.** [[../../Phonology/Orthography|Phonology/Orthography]] states explicitly that ј was deliberately adopted from the Latin alphabet specifically to distinguish Sisician's /j/ from Russian's own й — the two letters look nearly identical in most fonts, which is exactly why this keeps slipping through.

**Why this matters enough for its own memory file:** this exact confusion recurred at least four separate times in one session (2026-09-23), in four different forms — the actual filename `Words/ној.md` (created as `ной.md` with й, only caught during a routine post-build contamination scan), a fresh file's own wikilink (`Words/куи.md`), that same session's own `logs/log.md` entry describing the fix, and even a bare Latin "j" substituted for either Cyrillic letter in running prose (`Etymology/Sisician Sound Changes.md`). Each instance was typed fresh, not copy-pasted forward from an earlier mistake — a live, recurring production error, not a one-off that got fixed and stayed fixed.

**How to apply:** when writing or reviewing any Cyrillic word containing /j/, don't trust visual inspection alone — the two letters are genuinely hard to tell apart by eye. The vault's own contamination-scan convention (grep for mixed Latin/Cyrillic runs) does **not** catch this, since both й and ј are valid Cyrillic codepoints — it silently produces a wrong-but-plausible-looking word. Run a targeted codepoint check (`grep -oP '[йЙ]'` or a Python codepoint dump) on any newly-written file containing /j/-sound words before considering a build finished, in addition to the regular mixed-script scan.
