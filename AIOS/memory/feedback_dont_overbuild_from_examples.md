---
name: feedback-dont-overbuild-from-examples
description: Don't turn a small inconsistency in the user's illustrative example into a whole new structural design layer — ask directly whether it was a typo first
metadata:
  type: feedback
---

When the user gives a quick illustrative example (a word, a spelling, a one-off form) to make a point, and it doesn't quite match an already-established fact, don't run with an elaborate structural interpretation that reconciles the mismatch. Ask directly whether it was a typo/loose stand-in first.

**Why:** On 2026-09-18, the user illustrated the OCS-vs-vernacular register contrast with "scribes write *svěća*/*međa* but say *svěča*/*meja*" — but real OCS actually has *svěšta*/*mežda* (št/žd), not ć/đ, per [[reference_south_slavic_palatalization|the OCS page itself]]. Instead of asking "did you mean svěšta?", the assistant took the mismatch at face value and built out a whole third register tier (a "Sisician conservative literary spelling" layer distinct from both the merged vernacular and true OCS) to reconcile it — flagged as an inference pending confirmation, but still fully written into `Sources/Old Church Slavonic.md` before being asked about. The user's response: "You made too much out of my typo, yes." It was a loose stand-in, not a signal. The extra tier had to be written and then un-written.

**How to apply:** When an example the user gives conflicts with an established fact elsewhere in the vault, the cheap move is to ask ("did you mean X, or is Y intentional?") *before* building structure around either reading — not after. This is especially true when the "intentional" reading would add a new design layer (a new register, a new phoneme, a new rule) rather than just correcting a detail. Reserve the effort of designing around an inconsistency for cases where the user has confirmed it's deliberate.
