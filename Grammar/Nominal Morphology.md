# Nominal Morphology: Number, Gender, Case

First real grammar decisions (2026-09-19) — see [[Design Principles]] for the general constraints these satisfy (South Slavic skeleton retained, not a creole) and [[../Conlang Workflow|Conlang Workflow]] for the overall method. See [[../Sisician|Sisician]] for the hub page.

## Number

Two grammatical numbers: **singular and plural** — no living dual. However, Common Slavic (and [[../Sources/Late Common Slavic|Sources/Late Common Slavic]] by inheritance) had a real, attested dual, and Sisician shows "hanky-panky" residue from it: case/number irregularities specifically in small-numeral contexts, echoing the real "paucal" phenomenon found in Russian and Serbo-Croatian, where nouns after 2/3/4 take a special form (historically dual-derived, often resembling a genitive singular) distinct from the ordinary plural. This residue is plausible enough that in-universe observers/grammarians could reasonably posit an ancient paucal category, even though Sisician functionally has only two numbers. **Open:** the exact residual forms/rules haven't been worked out — a task for later, once declension paradigms exist to apply it to.

## Gender

Three historical genders (masculine, feminine, neuter) reduce to two living/productive ones: the neuter doesn't disappear uniformly — it **splits by number**. Old neuter nouns take **masculine agreement/declension in the singular** and **feminine agreement/declension in the plural**.

**Deliberately matches the real Romanian parallel** (corrected 2026-09-19 — the user's intent all along was to parallel Romanian, not mirror it; the direction was flipped in the first pass and is now fixed). Romanian's neuter nouns take masculine agreement in the singular and feminine in the plural, and Sisician now does exactly the same thing, for the same underlying reason: a former neuter class splitting allegiance by number rather than merging into one gender uniformly, in a fellow Balkan language shaped by deep Romance-Slavic contact. Given how much Romance contact runs through Sisician already (see [[../Sources/Vulgar Latin|Sources/Vulgar Latin]]/[[../Sources/Dalmatian|Dalmatian]]), this is a clean, well-grounded parallel rather than a coincidence to explain away. **See [[Declension Classes]] for the mechanism** — it turns out to need almost no new invention, since Croatian's own declension-class structure already groups masculine and neuter together in the singular, and neuter's own plural ending is formally identical to the feminine e-declension's singular ending.

## Case: From Seven to Five-Plus-Fossils

The original hypothetical inventory ([[Design Principles]]) was nominative, genitive, dative, accusative, instrumental, locative, vocative (7), explicitly flagged there as reducible once historical phonology/sound-change work suggested it. Decided now:

### Vocative — lost except fossils

Lost as a productive case, surviving only in a small number of fossilized forms, chiefly in **religious/exclamatory address**. Real parallel: Russian lost its productive vocative the same way, keeping only fossils like *Боже!* ("God!") and *Господи!* ("Lord!") in precisely this niche. Given Sisician's own heavy Orthodox liturgical register (see [[../Culture/Religion|Culture/Religion]]), expect its vocative fossils to cluster the same way — likely candidates once real liturgical vocabulary exists in [[../Words|Words/]] (e.g. a fossilized vocative of [[../Words/скинија|скинија]]-type or God/Lord-address words). **Open:** which specific forms survive isn't decided yet.

### Locative — lost, absorbed by preposition + accusative/genitive/dative

The locative is the most vulnerable of the seven Slavic cases, for a simple reason: it's the only case in Common Slavic never used without a preposition. Every other case has at least some bare use — nominative for subjects, accusative for direct objects, genitive for possession, dative for indirect objects, instrumental for means, vocative for address. The locative always needs *vъ*, *na*, *pri*, or similar. When a language starts simplifying its case system, the locative typically goes first, its functions absorbed by: accusative after prepositions of motion (already overlapping in many contexts); genitive after *pri* and other locational prepositions; dative in some fixed expressions.

**Decided:** the locative merges away entirely; locational meaning redistributes to preposition + accusative, preposition + genitive, or (in fixed expressions) dative, on a preposition-by-preposition basis.

**Resolved (2026-09-23), via [[Interrogatives]]'s where/whither/whence set:** **location and goal both land on preposition+accusative** — they already shared accusative even under the old seven-case system (*u kući* "in the house," locative, vs. *u kuću* "into the house," accusative — once locative dies, the goal use simply absorbs the location use too, since nothing else was holding them apart). **Source alone stays preposition+genitive**, entirely unchanged by the locative's own loss, since genitive-after-*od* ("from") was never locative territory to begin with. See [[../Words/абкле|абкле]] for where this surfaces concretely (the word itself later underwent its own replacement, but the genitive-marking pattern this section describes survived that change unaltered).

**Net result: six historical cases survive as forms, five fully productive** (nominative, genitive, dative, accusative, instrumental), plus vocative's narrow fossil remnant. Locative is gone as a case, not merely reduced.

**The payoff — why this is a good choice, not an arbitrary one:** this is exactly what happened in **Romanian** (lost the locative), in **Bulgarian and Macedonian** (lost the case system almost entirely), and in **Dalmatian Romance itself** — [[../Sources/Dalmatian|Sisician's own founding elite's language]]. All three are real Balkan Sprachbund effects. Citing them places Sisician's case simplification inside a genuine regional trend rather than an arbitrary conlang simplification — it makes the language feel **Balkan**, not just Slavic, and ties the grammar-level change to the same areal pressures that already shaped its neighbors and its own ancestral Romance source.

## Status Summary

| Case | Status |
|---|---|
| Nominative | Living |
| Genitive | Living |
| Dative | Living |
| Accusative | Living — also absorbs locative-after-motion uses |
| Instrumental | Living |
| Locative | **Lost** — redistributed by preposition: location and goal → accusative; source → genitive (delineated 2026-09-23, see [[Interrogatives]]) |
| Vocative | **Lost** — fossils only, chiefly religious address; exact fossils not yet chosen |

Not yet addressed on this page: actual declension paradigms/endings for any noun class (including how [[../Words/дом|дом]], [[../Words/каза|каза]], [[../Words/скинија|скинија]], [[../Words/икос|икос]] would actually decline) — this page settles the *category system*, not the *forms*.

## A General Principle Worth Reusing: Functional Load

[[Personal Pronouns]] (2026-09-19) worked out something worth remembering for any future gender/case decision, not just pronouns: **losing a category (here, the neuter) doesn't just simplify the slot where the loss happened — it can remove the whole system's only remaining way to disambiguate something, creating systemic pressure that resurfaces elsewhere.** Where that pressure actually resolves is a *functional*, not purely phonological, question: new distinctions catch on where the communicative payoff is high (accusative objects and genitive possessors, in the pronoun case — high referential-tracking load) and fail to catch on even where an equally good formal model exists, if the payoff is low (dative/instrumental). Worth checking future gender/case-related decisions (adjective agreement, noun declension endings) against this same lens once they come up.
