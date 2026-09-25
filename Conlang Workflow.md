# Conlang Workflow

Design method and process rules for building Sisician. Read this before starting any construction work (phonology, grammar, or lexicon). See [[Sisician]] for the hub page and [[Culture/History]] for the con-history this design method is meant to produce.

## The Core Idea

Sisician is conceived as a **Slavic-Romance language**: a fundamentally South Slavic language whose historical development parallels English in one crucial respect. English is fundamentally Germanic, but centuries of French influence made its vocabulary so heavily Romance that English is sometimes mistaken, superficially, for a Romance language. Its Germanic grammar and core vocabulary remain, while Norman French and later Latin/Greek profoundly reshape its lexicon.

Sisician reverses the basic historical intuition:

> **Slavic grammar + Romance vocabulary + Orthodox Christian civilization.**

The Romance source is **Dalmatian Romance**, the now-extinct Romance language historically spoken along the eastern Adriatic (see [[Culture/Geography and Economy]] § Why Dalmatian) — chosen over an earlier, more generic "French army conquers somewhere south of Bohemia" idea specifically because Dalmatian was already a real Romance language geographically embedded beside the South Slavic world, giving the project a genuine historical anchor rather than a transplanted one:

> **English:** Germanic + French/Latin/Greek
> **Sisician:** South Slavic + Dalmatian Romance + Greek/Church Slavonic

The result should not be "Slavic vocabulary with Romance words pasted in." The language should feel like a genuine historical language whose strange properties arose because of centuries of bilingualism, political domination, intermarriage, trade, religion, and language shift. The governing conlang principle:

> **Every weird feature should have a historical reason.**

Do not design a modern feature first and retrofit an etymology. Instead ask: "What happened between 1050 and 1400 that would produce this?" The modern language should feel **discovered rather than invented**.

## The Linguistic Analogies

**Yiddish** (an earlier "Jewish Slavic language" idea, considered and dropped before Sisician) supplied the one methodological insight worth keeping: Yiddish isn't merely German-with-Hebrew-words, it's a Germanic language whose own historical ecology produced Germanic grammar, Hebrew/Aramaic religious vocabulary, Slavic influence, and its own writing tradition — a whole system, not a word-list overlay. Sisician works the same way, minus the Jewish layer: South Slavic grammar + Dalmatian Romance urban/court vocabulary + Greek/Church Slavonic Orthodox vocabulary + regional Hungarian/German/Italian contact + its own historical orthography.

**English** is the analogy that actually drives day-to-day word-coining decisions (see § Current Priority below). Sisician shouldn't replace half the Slavic dictionary with Romance words arbitrarily — English became Romance-looking because *particular historical domains* were disproportionately Frenchified, not a flat percentage. See [[Etymology/Semantic Domains]] for the operative domain breakdown (grammar overwhelmingly South Slavic, core vocabulary overwhelmingly Slavic, urban/civic vocabulary heavily Dalmatian, learned vocabulary Greek/Church Slavonic + Dalmatian/Latin, political vocabulary Hungarian + Dalmatian; total lexicon perhaps 30–40% demonstrably Romance-derived). **The important thing is not the percentage — it is the semantic distribution.**

## Where the Six-Phase Plan Stands Now

The original plan called for building historically rather than top-down: Phase 1 (pre-founding sources) → Phase 2 (Old Sisician, c. 1000–1150) → Phase 3 (the sound-change chain) → Phase 4 (Middle Sisician, c. 1150–1350, the hybrid emerges) → Phase 5 (Early Modern Sisician, c. 1350–1650, Dalmatian dies) → Phase 6 (Modern Standard). That ordering mattered for *bootstrapping* — it's why phonology and sound changes got built before vocabulary — and it did its job:

- **Phase 1 and Phase 3 are done** — all four source varieties exist ([[Sources/Vulgar Latin]], [[Sources/Dalmatian]], [[Sources/Late Common Slavic]], [[Sources/Old Church Slavonic]]), and [[Etymology/Sisician Sound Changes]] bridges them to the modern target.
- **Phases 2, 4, 5, and 6 were done target-first, out of the original order, deliberately** — grammar (nominal morphology, the full pronoun/demonstrative/numeral system, the verbal system including two auxiliaries, the imperative, evidentiality, negation) and a substantial lexicon (well over 100 `Words/` entries) already exist as *modern-target* forms with their own historical derivations attached, not built in the strict 1000→1650 sequence. This deviation was acknowledged and accepted early on, not a drift to correct.

**What this means practically: the six phases are no longer the operative to-do list.** They describe how the foundation got built, and remain the right frame if a genuinely new grammatical or phonological layer needs bootstrapping from scratch. For everything else — which is most remaining work — see below.

## Current Priority: Lexicon, and Where the Real Decisions Are

**The main task of any conlang is word-coining, and this project now has a mature, proven method for it** — check [[Etymology/Swadesh List]] and [[Etymology/Semantic Domains]] before coining, verify any real Slavic/Dalmatian/Greek citation via search rather than assume it, apply the already-established sound-change chain rather than re-deriving from scratch, follow [[AIOS/memory/reference_word_entry_format]]'s template, and flag honestly what's cited vs. extended. That process doesn't need redesigning; it needs running.

**Most of core (Swadesh-type) vocabulary is going to be Slavic, and that's mostly mechanical.** Body parts, kinship, basic verbs, nature, numerals, function words — [[Etymology/Semantic Domains]]'s "Layer I — Slavic Earth" — inherit directly from Common Slavic through the already-built sound-change chain. These words are worth coining (the Swadesh list is a real scaffold, not busywork), but the *design* decisions in them are usually small: which dialect-fork to lean on when Croatian/Slovene/Serbian genuinely diverge, which real citation to trust, whether a specific consonant cluster needs a repair. Two exceptions already on record — [[Words/фамаља|фамаља]] "family" and [[Words/респонџати|респонџати]] "to answer" — show even Layer I isn't absolutely sealed against Dalmatian, but they're the exception precisely because Layer I is the default.

**The real decisions live in the "fancy" words — the non-core, register-differentiated vocabulary where Sisician's own three-way split (native Slavic / Dalmatian Romance / Greek-Church-Slavonic) is a live, meaningful choice rather than a foregone conclusion.** This is [[Etymology/Semantic Domains]]'s Layer II (Dalmatian City: law, trade, government, military, architecture, money, urbanity, court culture) and Layer III (Greek/Slavonic Heaven: God, Church, liturgy, theology, philosophy, saints, Scripture) — and, sitting between them, the genuinely interesting judgment calls: does *this* abstract or learned concept feel more civic-Dalmatian or more liturgical-Greek? Does it split into two registers the way "home" did across four words ([[Words/дом|дом]]/[[Words/каза|каза]]/[[Words/скинија|скинија]]/[[Words/икос|икос]])? Is this a case where the Greek concept arrived *through* Church Slavonic or *directly*, and does that pathway itself carry meaning (as it did for скинија vs. икос)? These are the coinages that actually define Sisician's character, the same way English's Latinate/Germanic split (not its raw vocabulary count) is what makes English feel the way it does. Prioritize these over grinding through the rest of the Swadesh list.

**Two other live threads, smaller but real:**
- **Proper names, derived from the phonology rather than invented.** [[Culture/Founding Myth and Naming]] tracks status — the founder (Vitalis Madius de Corinio), the endonym ([[Words/сисачки|сисачки]]), and the people's name ([[Words/сишчани|сишчани]]) are decided; the polity, the dynasty, and the lord's title are not, and should get the same derive-then-verify-against-the-real-record treatment those three did.
- **Grammar gaps that surface as they're needed**, rather than as a standing checklist: the passive participle, present participles, aorist/imperfect endings, the да-construction's own internal syntax. Build these when a sentence or a design question actually needs one, the way [[Grammar/Imperative]] and [[Grammar/Hteti (To Want) and the Future]] got built when [[Texts/Conlang Syntax Test Cases]] needed them.

## Remaining Historical/Cultural Tasks — Real, Just Not the Main Thread Right Now

[[Culture/History]] stops at 1300; nothing yet covers the Ottoman period, the Habsburg Military Frontier, Austro-Hungarian rule, or [[Culture/Sociolinguistic History]]'s own "Modern Sisician (c. 1650–present)" stage. [[Culture/Founding Myth and Naming]] still lists its ten candidate legendary motifs (a banner, a sword, an oath, a Roman stone, a storm, a monk, a prophecy, a Byzantine seal, a lost charter) as undecided — a real legend, not just a premise, hasn't been written. Material and daily-life culture (cuisine, dress, architecture, iconography, law, customs) is still just [[Culture/Political Identity]]'s own wishlist. None of this blocks lexicon work, and none of it needs to happen before the lexicon work continues — pick it up when it's wanted, not on a schedule.

## What Not To Do

- Do not paste modern Italian into Croatian, or French into Serbian.
- Do not make every noun Romance.
- Do not give Romance words Romance morphology (see [[Grammar/Design Principles]] — "Romance nouns become Slavic nouns").
- Do not make the language conveniently regular.
- Do not make the orthography perfectly phonemic.
- Do not make every historical borrowing obvious.
- Do not ignore semantic domains, social class, or religion when deciding where a loanword lands.
- Do not make Dalmatian survive unchanged until 1800 — it must die as a community language (by ~1300, see [[Culture/History]]).
- Do not invent a word or a name without grounding it in the sound-change chain or a real, verified citation — the Phase-ordering concern this line used to name is resolved (Phase 3 is done), but the underlying discipline (derive, don't invent) is permanent, not phase-bound.
- Do not assume all Romance influence comes directly from Latin — route it through Dalmatian.
- Do not treat Greek and Church Slavonic as interchangeable (see [[Culture/Religion]]).
- Do not treat the language as a creole without historical justification — the demographic situation is a majority Slavic population + a prestigious but numerically small Romance elite + long-term bilingualism, not two equally sized speech communities with catastrophic grammatical breakdown. The language should retain a robust inherited Slavic grammatical structure; Romance influence should be substantial but historically constrained. The result is a language-contact evolution, not an artificial mixed grammar.

The language should contain fossils, doublets, irregularities, register distinctions, dead etymologies, and historical accidents.

## The Central Design Constraint

> **Sisician must be the language that this history would produce, not the language we think would be aesthetically cool.**

If the history produces an ugly sound change, keep it. If a Romance word becomes irregular, keep it. If a Hungarian loan gets displaced, let it disappear. If an old Dalmatian term survives in one province but not another, preserve the dialect difference. If Church Slavonic creates an archaic literary register, preserve it. If speakers misunderstand the original etymology, allow folk etymology. The objective is historical depth.

## The Deep Structural Analogy

```text
                 ANCIENT WORLD
                      │
                 Roman Siscia
                      │
       ┌──────────────┴──────────────┐
       │                             │
 Adriatic Romance              South Slavic
   (Dalmatian)                  population
       │                             │
       └──────────────┬──────────────┘
                      │
                 Siscia dynasty
                      │
          bilingual elite society
                      │
       ┌──────────────┼──────────────┐
       │              │              │
    Dalmatian       Slavic       Latin/Greek
       │              │              │
       └──────────────┼──────────────┘
                      │
               Byzantine turn
                      │
                Church Slavonic
                      │
              Hungarian frontier
                      │
             Mongol catastrophe
                      │
               political survival
                      │
                language shift
                      │
                   SISICIAN
```

## The Core Formula

A Dalmatian-speaking noble household gets stranded in the Slavic interior. The household becomes a dynasty. The dynasty becomes a city. The city becomes a polity. The polity becomes a culture. The culture becomes a language. That is the creative engine.

## The Intended End Result

A modern Sisician sentence should ideally make a linguist think: "That looks strangely Romance." Then: "Wait. Why are all these nouns declining?" Then: "Why does the verb system look Slavic?" Then: "Why is this theological vocabulary Greek?" Then: "Why is the whole thing written in Cyrillic?" Then: "What happened here?" The answer is the entire history of Siscia. That is the conlang.
