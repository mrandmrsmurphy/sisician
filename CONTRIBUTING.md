# Contributing

Corrections, source checks and questions about Sisician are welcome. Sisician is an authored constructed language, not a shared standard: the maintainer makes the design decisions, and contributions are about accuracy and evidence.

## How it works

1. **Propose through a pull request** (or an issue, for a question or suggestion). Describe what you changed and why.
2. **The maintainer reviews all contributions.** Nothing is merged unseen. A design decision may already be settled (see [AIOS/memory-index.md](AIOS/memory-index.md) for the standing rulings) or may be one the maintainer wants to make.
3. **Vetted contributors can be given direct access** once their work has been reviewed and found careful.

## Where help is most useful

- **Checking sources.** Real Dalmatian, Vulgar Latin, Late Common Slavic, Old Church Slavonic, Serbo-Croatian and Slovene forms cited on word and `Sources/` pages. Cite where you checked.
- **Checking derivations.** A sound change applied in the wrong order, a step that does not follow from [Etymology/Sisician Sound Changes](Etymology/Sisician%20Sound%20Changes.md), or a form that breaks the [phonotactics](Phonology/Phonotactics.md).
- **Real-language claims.** Anything said about how a real language behaves that is wrong or unsourced.
- **Errors.** A broken link, a gloss that disagrees with its word page, a stale "not yet built" note.

New words, rules and sounds are the maintainer's to decide. Open an issue to suggest one rather than adding it.

## Standards

- **Check before adding.** Look for conflicts with the existing inventory, paradigms and gloss abbreviations before changing anything.
- **Follow the entry format** in [AIOS/memory/reference_word_entry_format.md](AIOS/memory/reference_word_entry_format.md): one file per word, named by its Cyrillic citation form.
- **Use ј (U+0458), never й (U+0439).** The two look alike and the Sisician letter is ј.
- **Cite evidence.** Do not invent an attestation to fill a gap. Where a form is inferred, say so tersely on the page.
- **Content pages describe the current state only.** No dates, "corrected on" notes or process commentary. History goes in [logs/log.md](logs/log.md), which is append-only.
- **Gloss with the Leipzig Glossing Rules** unless the vault defines its own abbreviation.
- **Keep `CLAUDE.md` and `AGENTS.md` byte-identical** if you change either.
- **Say if AI helped.** Parts of this vault are built with Claude Code. If you used an assistant, note it in the pull request, and check what it gave you.

## Licence

By contributing you agree that your contribution is licensed under [CC BY-SA 4.0](LICENSE.md), like the rest of the repository. Do not contribute text or images you do not have the right to share under that license.
