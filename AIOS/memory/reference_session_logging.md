---
name: reference-session-logging
description: Append-only session log convention at logs/log.md — what to record and how, since this vault has no git history
metadata:
  type: reference
---

This vault is not a git repository, so there is no commit history to reconstruct what changed and why across sessions. `logs/log.md` is an append-only log: each session adds a new dated entry at the **bottom** of the file and never edits or deletes a prior entry.

Entry format:

```markdown
## 2026-09-18

- Created AIOS/ memory system and logs/log.md, copying the pattern from ../gweddish.
- [any word/page created, deleted, or restructured this session, one bullet each]
```

**Why:** Without git, the only record of "what got created/deleted/restructured and when" is whatever gets written down. A flat append-only log is cheap to maintain and never needs reconciling with anything else.

**How to apply:** At the end of any session that creates, deletes, or restructures pages (not routine single-word additions unless notable), add one dated entry to `logs/log.md`. Keep entries terse — bullet points, not prose. Never rewrite or remove a past entry, even if it turns out to be wrong; add a new entry that corrects it instead. This is a log, not a memory — don't duplicate durable rules here, just record what happened and when. Durable rules belong in `AIOS/memory/` and the index at `AIOS/memory-index.md`.

## Rotation

Roll `logs/log.md` to a numbered archive (`logs/archive/log-NNN.md`) when it grows unwieldy, mirroring the convention in `../gweddish/logs/`. The user decides when to roll — don't roll unprompted. First rolled 2026-09-26 (`log.md` → `archive/log-001.md`, covering 2026-09-18 through 2026-09-26).

To roll:
1. `cp logs/log.md logs/archive/log-NNN.md` (verbatim, zero-padded, next sequential number — the first is `log-001.md`).
2. Replace `logs/log.md` with just the standard header plus a line pointing at the new archive: `Previous entries (<start date> through <end date>): [[archive/log-NNN]]. See [[index]] for a summary of what's in each archived file.`
3. **Add a new entry to `logs/index.md`** (created 2026-09-26 alongside the first roll) — one paragraph summarizing the archived file's contents by date-section, oldest-file-first, appended above the file's own trailing "add a new entry here" marker line.

Never edit the archived copy afterward — it's frozen at the moment of the roll, same append-only-forever rule as the live log. The index, by contrast, is *not* append-only in the same strict sense — its entries describe frozen archive files, but nothing stops improving an existing entry's wording later if it turns out unclear (unlike the archive files themselves, or the live log's own past entries).

**Why:** A single flat file eventually gets too large to read/search comfortably in one pass; archiving keeps the live log fast to scan while preserving full history losslessly, without needing git. The index exists because archive files themselves get too numerous to scan by filename alone once there are several — a one-paragraph-per-file summary lets a future session find the right archive without opening each one.
