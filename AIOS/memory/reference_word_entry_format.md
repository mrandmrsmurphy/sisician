---
name: reference-word-entry-format
description: Standing frontmatter schema and body section order for Words/ entries, established by каза.md — follow this for every future word page
metadata:
  type: reference
---

[[../../Words/каза|Words/каза]] is the template (set 2026-09-19) — read it, don't just read this summary, before creating a new word page.

## Frontmatter Schema

```yaml
---
word: <Cyrillic citation form>
ipa: /phonemic transcription, stress marked/
pos: noun | verb | adjective | ...
gender: feminine | masculine | neuter (for nouns; omit for other POS)
declension: e-declension | a-declension | i-declension (for nouns; verbs will need their own field once conjugation classes exist)
english: comma-separated gloss(es) — short, not the full Meaning section (mirrors the sibling ../gweddish vault's own "english:" field and its documented rule: this is a gloss/tag hit, not the word's full meaning — see body's Meaning section for that)
source-lang: Slavic (native) | Dalmatian | Greek | Church-Slavonic | Hungarian | ... (per Etymology/Semantic Domains's layers)
source-form: the etymon, in its source language
period: which of Sociolinguistic History's stages the word enters at (Old/Middle/Early Modern/Modern Sisician), or "native" if inherited rather than borrowed
register: a short tag combining source-layer + tone, e.g. dalmatian-formal, native-warm, greek-liturgical
status: exploratory | confirmed (see below)
tags: [domain tags — matches Etymology/Semantic Domains's categories where possible, e.g. architecture, kinship, liturgy]
```

Not every field applies to every word (a native word has no `source-form` distinct from its Common Slavic ancestor; a fossil-only vocative form needs its own notation once that's built out) — omit what doesn't apply rather than forcing empty values.

**Pronoun extension** (added 2026-09-19, first used by [[../../Words/јаз|Words/јаз]]): for `pos: pronoun`, drop `gender`/`declension` (pronouns aren't full independent declensions) and add `person: 1st|2nd|3rd`, `number: singular|plural`, `case:` (whichever case this specific cell/page represents — a pronoun's full paradigm is a *set* of pages, one per case-form, not one page with a table the way a noun works). See [[../../Grammar/Personal Pronouns|Grammar/Personal Pronouns]] for the paradigm these individual pages plug into.

**Stress in declension tables:** apply root-anchored stress (decided 2026-09-19, see [[../../Phonology/Modern Inventory|Phonology/Modern Inventory]] § Prosody) — stress stays on the noun's root across the whole paradigm, not recomputed as "the penultimate syllable" of each surface form. For most 2-syllable forms this coincides with penultimate placement anyway; it only becomes visible as a distinct choice once a paradigm has a 3+-syllable form (case endings, plural stem extensions like *-ov-*, etc.).

**Standing sound-change rules get their own page, not a re-explanation per word:** [[../../Etymology/Fall of the Jers|Etymology/Fall of the Jers]] is the first of these (2026-09-19) — any native word whose derivation depends on it should link there rather than re-deriving Havlík's Law inline (see [[../../Words/дом|Words/дом]] for the pattern: one linked sentence, not a paragraph). If another sound change turns out to be similarly "always followed" and reused across many future words, give it the same treatment: its own page, linked from wherever it applies.

## Body Section Order

1. **Opening status line** — bolded, one line, pointing to this reference and to the word's siblings if it's part of a worked set.
2. **Meaning** — the full gloss/sense, register connotation, contrast with near-synonyms. (This is the "full meaning," as opposed to frontmatter's `english:` tag-level gloss.)
3. **Declension** (nouns) or the equivalent paradigm section (conjugation, for verbs, once that exists) — a real table, built from the relevant [[../../Grammar/Declension Classes|Grammar/Declension Classes]] pattern. **Only living forms — no mention of dead cases at all, not in the table and not in prose** (corrected 2026-09-19, twice over: first the user removed the dead locative/vocative table rows, then asked for дом to skip mentioning them entirely, prose included). The case losses are documented centrally in [[../../Grammar/Nominal Morphology|Grammar/Nominal Morphology]] — a word page just presents the living paradigm as the language's real case system, full stop, rather than re-explaining what isn't there. Flag real inherited syncretisms among the living forms as such (not bugs).
4. **Etymology** — full derivation chain through the relevant [[../../Sources|Sources/]] page(s), citing which specific decided sound changes apply and why (or why none apply).
5. **Register** — cross-reference to [[../../Etymology/Semantic Domains|Etymology/Semantic Domains]]'s layer and, where relevant, [[../../Grammar/Word Order and Register|Word Order and Register]]'s syntactic-register predictions.
6. **Related** — links to sibling words in the same worked concept-set, if any.
7. **Closing status note** — honest accounting of what's solid vs. speculative in this specific entry (a word resting on a universal sound law like the Fall of the Jers is on firmer ground than one rebuilt via a single proposed adaptation rule — say so, don't flatten the difference).

## `status:` Values

- **exploratory** — filed ahead of a formal lexicon-building pass, per the user's own initiative (this is where every word so far sits, as of 2026-09-19 — see [[reference_construction_workflow]]'s lexicon thread).
- **confirmed** — reviewed and locked in as a real, load-bearing vault fact rather than a sketch. No word has reached this status yet; don't mark one `confirmed` without the user explicitly saying so.

**Why:** The user asked specifically for каза to "set the precedent for future word pages and what they should aspire to be" — this file exists so that precedent survives being read once and forgotten, the same role [[reference_construction_workflow]] and [[reference_south_slavic_palatalization]] play for their own topics.

**How to apply:** Before creating any new `Words/*.md` page, read [[../../Words/каза|Words/каза]] itself as the live example, plus this file for the schema in the abstract. Keep this file's schema in sync if a future word page needs to extend it (e.g. a verb entry will need conjugation-class frontmatter this schema doesn't cover yet) — update here, don't let каза.md and this reference drift apart.
