---
name: feedback-update-the-old-page
description: When a newer page resolves an older page's open question, the older page must be updated too — the vault's characteristic consistency failure is stale "not yet built" prose surviving on the page where a question was first raised
metadata:
  type: feedback
---

**The vault's characteristic consistency failure is not wrong decisions — it's stale framing left behind when decisions get made elsewhere.** When a newer page resolves an older page's flagged open item, the resolution reliably gets recorded on the *newer* page, but the *older* page's "not yet built / hasn't been decided / this is blocking X" prose is often never revisited. Found the hard way in the 2026-10-05 full-vault audit: `Grammar/Design Principles.md` still opened with "No grammar has been constructed yet" long after ~21 grammar pages existed; `Grammar/Clitic Ordering.md` called the бити paradigm unbuilt on the same page whose Open Items section already pointed to the built paradigm; `Grammar/Verbal Categories.md` still called the l-participle "blocking"; three Sources pages attributed a superseded "penultimate stress, with many exceptions" rule to `Phonology/Modern Inventory.md` after that page had moved to root-anchored stress (and Modern Inventory's own header contradicted its own § Prosody).

**Why:** the user found this the most appalling finding of the audit — "sweeping for that, finding the kind of inconsistencies you already described and nuking them is most important to me." A vault whose whole design principle is cross-checked consistency can't have pages contradicting each other about what's been decided.

**How to apply:**
- When you resolve an open item on page B, grep for the pages that *raised* it (the item is almost always flagged somewhere on page A first) and update page A in the same work session. Silently, in place, per [[feedback_no_changelog_in_pages]] — no "previously this said X" narration.
- Before writing "X hasn't been built yet" anywhere, check whether it has. Before writing "decided" anywhere, check that the decision page and the pages citing it tell the same story.
- Big consolidations (a new sound-change entry, a new paradigm, a reframed rule) are exactly when this happens — treat "who else cites the old version?" as a mandatory step, not a nice-to-have.
- Periodic full-vault staleness sweeps (like the 2026-10-05 one) are worth doing deliberately after any burst of cross-cutting decisions.
