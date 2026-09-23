---
name: feedback-never-destroy-existing-files
description: Never overwrite any file, anywhere, without reading its existing content first — no exceptions for "scratch" purposes, even at the vault root
metadata:
  type: feedback
---

Never write to any file — anywhere in this vault, including the root — without first reading its current content, even for a quick throwaway check. There is no such thing as a "safe to blindly overwrite" file in this vault. Use the dedicated scratchpad directory (provided in the environment info at session start) for every piece of scratch/temporary content — never a file that lives in the actual vault tree, no matter how generic or unimportant its name looks.

**Why:** This rule is carried over from the sibling conlang vault (`../gweddish`), where `README.md` — real, documented vault infrastructure — was twice used as an ad-hoc scratch file via a raw file write that bypassed the Write tool's "must read first" safety check, destroying its actual content with no git history or backup to recover it from. This vault has no git repository either, so the same failure mode would be equally unrecoverable here. Applying the rule preemptively, before an equivalent incident happens in Sisician.

**How to apply:**
- Before writing to ANY file for a quick check, scratch note, or visual-confirmation purpose, use the scratchpad directory path given in the environment info at the start of every session — never a file inside the actual vault folder, even at the root, even a file that sounds generic (README.md, notes.md, scratch.md, etc.).
- Never use Bash/Python to directly `open(path, "w")` a file in the vault as a shortcut around the Write tool — the Write tool's requirement to Read an existing file first exists specifically to catch this failure mode, and bypassing it via Bash defeats that protection entirely.
- If a file must genuinely be created or edited inside the vault tree (not scratch — a real, intentional content change), always Read it first regardless of whether it "seems empty" or "seems like it wouldn't have anything important" — check, don't assume.
