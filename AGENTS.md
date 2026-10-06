# Sisician

This is an Obsidian vault for **Sisician**, a constructed language (conlang), plus any conculture/worldbuilding material tied to it. It is not a software project — no build/tests/CI. This file guides how Claude should work in this vault.

**Read [AIOS/memory-index.md](AIOS/memory-index.md) first, every session, before touching anything.** It points to every durable memory (project identity, and — once established — phonology, grammar, writing system, word-entry format, workflow feedback from past sessions). Do not skip it and re-derive things from scratch.

For the full page hierarchy and where content belongs, see [AIOS/site-map.md](AIOS/site-map.md). Start reading the vault itself at [Sisician.md](Sisician.md) (hub page).

**Durability warning:** Never write anything meant to persist to `~/.claude/projects/.../memory/` or anywhere outside this vault folder. Everything meant to survive across sessions goes in [AIOS/memory/](AIOS/memory/), indexed in [AIOS/memory-index.md](AIOS/memory-index.md). Session-by-session history of what was created/deleted/restructured goes in [logs/log.md](logs/log.md) (append-only — see [reference_session_logging](AIOS/memory/reference_session_logging.md)).

This pattern (`AIOS/` + `logs/`) is copied from the sibling conlang vault at `../gweddish`, which is worth checking for structural precedent (word-entry format, navbox conventions, etc.) even though its linguistic content is unrelated.

## Vault structure

Keep top-level folders by domain, not by date. Suggested structure (create folders as content warrants — don't pre-create empty ones):

- `Sources/` — real ancestor/contact languages (Vulgar Latin, Dalmatian, Late Common Slavic, Old Church Slavonic) that Sisician is derived *from*; real comparative linguistics plus flagged open design choices, not Sisician's own phonology/grammar
- `Phonology/` — Sisician's own sound inventory, phonotactics, stress/tone rules, romanization scheme
- `Grammar/` — morphology, syntax, one note per topic (e.g. `Verb Conjugation.md`, `Noun Cases.md`)
- `Words/` — one file per word, filename = the Cyrillic citation form (matching the sibling `../gweddish` vault's own convention of filename = the word's own script)
- `Etymology/` — word origins and derivations, if Sisician has in-fiction history
- `Texts/` — sample sentences, translated passages, glossed texts
- `Culture/` — worldbuilding notes for speakers of the language, con-history, political identity, etc.
- `Sisician.md` — the hub/splash page linking out to every major section (already exists)

## Conventions

- **Wikilinks**: link liberally with `[[Note Name]]` — words to their lexicon entries, grammar rules to the phonology/morphology they depend on, etc. A word or rule mentioned more than once should become a link, not repeated prose.
- **Romanization vs. IPA**: once a romanization scheme and IPA transcription convention are established, apply them consistently. Flag inconsistencies rather than silently picking one.
- **Glossing**: for example sentences, use interlinear gloss format (word line / gloss line / free translation), following [Leipzig Glossing Rules](https://en.wikipedia.org/wiki/Leipzig_Glossing_rules) abbreviations unless the vault defines its own.
- **Frontmatter**: prefer YAML frontmatter on notes for structured fields (e.g. part of speech, pronunciation, tags) once a schema is established, so notes stay queryable via Dataview if that plugin gets added later.

## How to help

- **Consistency checking is the priority.** Before adding a new word, grammar rule, or phonological pattern, check existing notes for conflicts (a sound not in the established inventory, a case ending that contradicts an existing paradigm, a gloss abbreviation used differently elsewhere).
- When something is genuinely new (first word using a sound, first instance of a grammatical category), just add it — don't block on there being no precedent yet.
- Don't invent linguistic content (words, rules, sounds) unprompted. Ask, or work from what the user gives you. This vault is the user's conlang; treat it as authored content, not something to fill in generatively.
- When restructuring or renaming notes, update all `[[wikilinks]]` that point to them.
- Keep an eye on `Index.md` (once it exists) and suggest updates when new major sections are added.
