# Declension Classes

Decided 2026-09-19. See [[Nominal Morphology]] for the number/gender/case categories these classes inflect for, and [[Design Principles]] for why loanwords take native declension rather than keeping foreign patterns. See [[../Sisician|Sisician]] for the hub page.

## Keeping Croatian's Three Classes

**Decided: no deviation from the real Croatian three-way declension system beyond the case losses already established** (locative gone, vocative fossilized — see [[Nominal Morphology]]). Croatian's traditional classification is by **genitive singular** ending, not nominative (nominative endings overlap across classes, so gen.sg. is the clean diagnostic):

- **a-declension** (gen.sg. **-a**) — masculine nouns (*grad* → *grada*) **and** neuter nouns (*selo* → *sela*), already grouped together in real Croatian.
- **e-declension** (gen.sg. **-e**) — most feminine nouns, nom.sg. **-a** (*žena* → *žene*).
- **i-declension** (gen.sg. **-i**) — feminine nouns, nom.sg. consonant-final, mostly abstract/body-part nouns (*kost* → *kosti*, *noć* → *noći*).

## Why the Neuter Merger Barely Needs New Machinery

[[Nominal Morphology]] decided neuter takes masculine agreement in the singular and feminine agreement in the plural, paralleling Romanian. That decision turns out to need almost no new invention, because Croatian's own declension-class structure already does most of the work:

**Singular:** masculine and neuter are **already the same declension class** (a-declension, shared gen.sg. -a) in real Croatian. Sisician's merger doesn't create a new formal overlap — it just lets a pre-existing formal overlap (both classes sharing a-declension endings) become a full functional/agreement merger too. Old neuter nouns don't need new singular endings; they were already inflecting like masculine nouns in the singular.

**Plural:** here's the actual historical trigger. Common Slavic/Croatian neuter plural nominative ends in **-a** (*selo* → pl. *sela*, "villages") — and that -a is **formally identical** to the e-declension's own nom.sg. -a (*žena*). This is the same kind of formal homophony that, in real Vulgar Latin → Romance, caused neuter plural *-a* to be reanalyzed as a new feminine singular (Latin *folia* "leaves" → Italian *foglia* "leaf," feminine singular).

### The Neuter Plural, Corrected (2026-09-23)

**This section originally claimed old neuter nouns "take e-declension plural endings" wholesale — checked for the first time against a real neuter noun ([[../Words/сунце|сунце]], "sun") and found not quite right.** Real Serbo-Croatian *sunce* (confirmed via Wiktionary) shows plural nominative/accusative **sunca**, not the e-declension's own plural shape (*sunce*, matching *žene*) — meaning the "reanalyzed into e-declension-class membership" story overclaimed. The real, simpler picture:

- **Nominative/accusative plural keeps its own distinct, genuinely old inherited collective *-a* ending** — not borrowed from e-declension at all, just the same neuter collective *-a* that was always there (real Common Slavic *-a*, unrelated in origin to e-declension's own *-a*, the two just happen to look alike, per the formal-homophony point above).
- **Genitive and dative/instrumental plural coincide with ordinary a-declension's own oblique plural endings** — **-а**/-аца (with a functional-load-motivated filler vowel where it usefully disambiguates, per [[../Words/сунце|сунце]]'s own page) and **-има**, the same endings [[../Words/дом|дом]]'s домова/домовима show once дом's own conditional *-ов-* stem extension (a monosyllabic-root-specific insertion, not a case ending) is set aside. Unsurprising, given the singular already established that neuter shares a-declension with masculine — it turns out a good chunk of the plural oblique cases carry that sharing forward too.

**Net effect:** neuter nouns don't need a borrowed paradigm at all, in the singular *or* the plural — they need almost nothing invented, just their own real, inherited collective plural nominative/accusative ending sitting alongside a-declension's ordinary oblique endings. A cleaner, more minimal story than the one this section originally proposed, corrected rather than quietly overwritten — see [[../Words/сунце|сунце]]'s own page for where the mismatch first surfaced.

## The Abstract a-Declension Paradigm (added 2026-09-23)

**Both worked examples now exist — [[../Words/дом|дом]] (hard-stem masculine) and [[../Words/сунце|сунце]] (soft-stem neuter) — closing this page's own long-flagged "not yet built" status for at least one of the three classes.**

**Hard stem, masculine, monosyllabic root (conditionally takes the *-ов-* plural extension):**

| Case | Singular | Plural |
|---|---|---|
| Nominative | *(bare stem)* | *(stem)*+ов+и |
| Genitive | *(stem)*+а | *(stem)*+ов+а |
| Dative | *(stem)*+у | *(stem)*+ов+има |
| Accusative | inanim. = nom.; anim. = gen. | *(stem)*+ов+е |
| Instrumental | *(stem)*+ом | *(stem)*+ов+има |

**Soft stem (ц дз ч џ ш ж љ њ ј-final), neuter, no *-ов-* extension (extension is a masculine-monosyllabic-specific feature, not general to the class):**

| Case | Singular | Plural |
|---|---|---|
| Nominative | *(stem)*+е | *(stem)*+а |
| Genitive | *(stem)*+а | *(stem)*+а(ца) |
| Dative | *(stem)*+у | *(stem)*+има |
| Accusative | = nominative | = nominative plural |
| Instrumental | *(stem)*+**ем** | *(stem)*+има |

**The one place hard and soft genuinely diverge**: instrumental singular, **-ом** vs. **-ем** — everywhere else, the two patterns differ only in whether the *-ов-* plural extension applies (a separate, root-shape-conditioned fact, not part of the hard/soft split itself) and in whether the noun is masculine (bare nominative singular) or neuter (nominative singular in *-е* or *-о*, per its own historical ending, orthogonal to hard/soft).

**The *-ов-* extension's conditioning, tentatively widened (2026-09-24):** [[../Words/денајр|денајр]] ("money," bisyllabic) is the first non-monosyllabic hard-stem masculine noun built, and it takes the extension too (денајрови, not †денајри) — provisional evidence that "monosyllabic" was never the exclusive trigger, just the first-tested case; real Croatian generally extends most masculine nouns this way regardless of syllable count. Held loosely, not independently re-confirmed against a specific real citation for this word.

**The extension is itself hard/soft-conditioned, confirmed 2026-09-25 via [[../Words/респонџ|респонџ]] ("answer," soft-stem, џ-final):** real Croatian doesn't just use one *-ов-* shape — soft-stem masculine nouns take **-ев-** instead (*muž→muževi*, *kralj→kraljevi*, never *mužovi*/*kraljovi*), the identical o/e alternation already stated for the instrumental singular (-ом/-ем) showing up in a second cell rather than being a separate fact. This page previously only mentioned the instrumental-singular half of this alternation; респонџ (респонџеви, not †респонџови) is what surfaced the plural-extension half and prompted stating both together.

**The abstract i-declension paradigm now has a worked example**: [[../Words/читвот|читвот]] ("city," 2026-09-24) — feminine, consonant-final, with a functional-load-motivated extended genitive plural (-ију, matching real Croatian *kostiju*-type nouns) and dative/instrumental plural -има (confirmed to match a-declension and e-declension's own plural endings). Not yet generalized into its own class-level table here the way a-declension's is above. e-declension's own abstract table remains unbuilt too (каза, фамаља, and монајта all give concrete examples, just not yet generalized to a class-level statement here).

## Loanwords: Which Class They Land In

Per [[Design Principles]] ("Romance nouns become Slavic nouns"), Dalmatian loans get sorted into these same three classes — most land in **e-declension**, since Dalmatian a-final feminine nouns match its nom.sg. -a pattern exactly. [[../Words/каза|каза]] already confirms this: its original placeholder declension (kaza/kaz**e**/kazi/kazu/kazom/kazi) already follows the e-declension gen.sg. -e pattern (*kaza → kaze*, exactly like *žena → žene*) — this was implicit in that page before this decision made it explicit.

## Status

Category-level: settled. **A-declension's full paradigm table (both hard and soft variants, all cases × both numbers) is now built (2026-09-23), above.** Still not built: e-declension's and i-declension's own class-level abstract paradigm tables (каза already gives a concrete e-declension worked example on its own page, just not generalized here yet), and how [[Nominal Morphology]]'s numeral-residue ("paucal") irregularity interacts with each class specifically.
