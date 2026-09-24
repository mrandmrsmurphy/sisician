# Modern Sisician: Consonant and Vowel Inventory

**Status: tentative target.** This is the *target* modern-Sisician phoneme inventory, sketched ahead of the historical derivation — [[../Conlang Workflow|Conlang Workflow]] Phase 1 (the pre-founding South Slavic base) and Phase 3 (the sound-change chain) haven't been built yet, so there is currently no historical pathway connecting c. 1000 South Slavic to this inventory. Treat everything on this page as provisional and subject to revision once that derivation is worked out. See [[Design Principles]] for the design goals this was sketched against.

## Vowels

Five vowels: **/a e i o u/**. No length, tone/pitch-accent, or stress system has been specified yet — open question, not yet decided (Serbo-Croatian-style South Slavic languages typically have pitch accent and vowel length, so this is worth a deliberate decision rather than a silent omission).

### No Separate Diphthong Inventory — Vj Is Just V + Consonant /j/ (clarified 2026-09-24)

**Prompted by a direct question once [[../Words/тај|тај]], [[../Words/ној|ној]], [[../Words/денајр|денајр]], and [[../Words/монајта|монајта]] had all quietly used -aj-/-oj- without the phonology page ever stating a position on it.** Sisician doesn't need a Romance-style phonemic diphthong inventory (the way Latin/Dalmatian's ie/uo/ai genuinely are single complex nuclei) — /j/ is already an ordinary Sisician consonant, so **any vowel + j sequence is simply that vowel followed by /j/ in coda position**, phonotactically unremarkable in exactly the way any other V+C coda is. This matches how real BCS itself analyzes *kraj*, *moj*, *tvoj*, *trofej*: plain VC, not a special diphthong class.

**Consequence: aj/ej/oj/uj/ij are all equally legal, not a graded or restricted set.** aj, oj, and ij are already independently attested ([[../Words/тај|тај]], [[../Words/денајр|денајр]], [[../Words/монајта|монајта]] for aj; [[../Words/ној|ној]], [[../Words/тој|тој]], [[../Words/овој|овој]] for oj; [[../Words/који|који]], [[../Words/скинија|скинија]] for ij) — ej and uj simply haven't come up in a coined word yet, not because anything bans them (cf. real Croatian *trofej*, *obuj* for exactly these two).

**The real constraint is on the *other* kind of glide, and it's absolute: no vowel+/w/ sequence survives as such, because /w/ isn't a Sisician phoneme at all** (§ Consonants above — only /j/ is listed as a glide; this is also the standing South Slavic norm, not a Sisician-specific gap). This isn't a new decision — it's the same principle already twice applied in practice ([[../Sources/Dalmatian|Dalmatian]]'s *mwart→мварт*, [[../Words/читвот|читвот]]'s *cituot→читвот*), stated here explicitly for the first time as a general rule rather than a per-word coincidence: whenever Dalmatian source material would hand Sisician a w-final diphthong (au, eu, ou, or a closed-syllable *wa/wo*-type onset-glide), the /w/ **hardens to a full consonant /v/** instead of surviving as an offglide — becoming an onset consonant of the following syllable, not a diphthong nucleus. **Sisician has zero tolerance for w-glides in any position**, not just a preference against them.

## Consonants

|           | Bilabial | Labiodental | Alveolar | Postalveolar | Palatal | Velar |
| --------- | -------- | ----------- | -------- | ------------ | ------- | ----- |
| Stop      | p b      |             | t d      |              |         | k ɡ   |
| Affricate |          |             | ts dz    | tʃ dʒ        |         |       |
| Fricative |          | f v         | s z      | ʃ ʒ          |         | x     |
| Nasal     | m        |             | n        |              | ɲ       |       |
| Liquid    |          |             | l r      |              | ʎ       |       |
| Glide     |          |             |          |              | j       |       |

- **[ŋ]** is an allophone of /n/ before velars (place assimilation), not a separate phoneme.
- 24 consonants + 5 vowels = 29 phonemes total (not counting [ŋ]).

## Prosody

**Decided (2026-09-19): for nouns, stress is root-anchored, not a mechanical syllable-count rule.** Stress stays on the noun's root/stem as case endings are added, rather than migrating to track "the penultimate syllable" of whatever the current surface form happens to be. This most often *coincides* with penultimate position, since most case endings are a single syllable — which is exactly why the original "penultimate stress, with many exceptions" description (2026-09-18) looked right at first. But the root is the real anchor, not the penult; penultimate placement is just what root-anchored stress looks like on short words. Established via [[../Words/каза|Words/каза]] (казама keeps root-initial ˈkazama rather than recomputing penultimate ka.ˈza.ma) and independently confirmed by [[../Words/дом|Words/дом]] (домовима keeps root stress across four syllables, never migrating into the *-ov-* extension or case endings) — both matching real Common Slavic's "fixed accent paradigm" noun class and real Croatian pronunciation of these exact word-types.

**Scope: nouns only, for now.** Verb stress, and finer-grained rules (e.g. real Slavic's mobile accent-paradigm classes, where *some* words genuinely do shift stress between root and ending rather than staying fixed) are explicitly deferred — root-anchored-by-default is the working rule until more specific patterns are worked out.

## Syllabic Sonorants — Colloquial Only, Not Standard (Revised 2026-09-20)

**Syllabic /r/ (and /l/) is real and alive in colloquial/fast speech** — the ordinary vowel-syncope outcome real South Slavic shows in exactly these words (*vrt* "garden," *smrt* "death," *prst* "finger" are real, unremarkable BCS words with syllabic /r/, no epenthetic vowel at all). **But standard Sisician spelling and careful/prestige speech avoid it**, per [[../Culture/Sociolinguistic History|Culture/Sociolinguistic History]] § Orthographic History's "eye-spelling" tradition: an epenthetic **a** is inserted instead — *vrt* → **vart**, *smrt* → **smart** — a real, live register alternation, not just a spelling quirk divorced from pronunciation. Casual speech still says the bare syllabic consonant; careful speech (and everything written) uses the epenthetic-vowel form. This is presented explicitly as this vault's own invented sociolinguistic development, not a real attested BCS standardization fact — real BCS keeps syllabic /r/ in its own standard without any such correction; Sisician's version is a class/prestige-driven divergence specific to this project, motivated by [[../AIOS/memory/project_prestige_register_principle|the prestige-register principle]] (syllabic consonants read as "vulgar Slavic," avoided by the Dalmatian-philic prestige norm) rather than cited from anywhere real.

- **Syllabic /r/, /l/ — colloquial/fast-speech only.** Standard register replaces with epenthetic **a** + the consonant (vrt→vart, smrt→smart pattern). See [[../Culture/Sociolinguistic History|Culture/Sociolinguistic History]] and [[../Culture/Accent and the Slavic Boogeyman|Culture/Accent and the Slavic Boogeyman]] for the social mechanism.
- **Very rarely syllabic**, and specifically attested in slang register: /ʎ/, /n/, /m/, /ɲ/ — unaffected by the above; these were never a standard-register form to begin with.

## /x/ Softening to [ç] — A Register Marker, Not Free Variation (New 2026-09-20)

**Modeled on real German dialectal ich-Laut/ach-Laut allophony** (the same phoneme surfacing as palatal [ç] near front vowels and velar [x] elsewhere), but repurposed here as a **social**, not purely phonological, split. The phonological conditioning is real and present in every register — /x/ is naturally more fronted, closer to [ç], adjacent to front vowels/consonants — but **prestige ("Dalmatian-philic") speech generalizes the soft [ç] to every position**, smoothing over the phoneme almost everywhere, while unmarked or deliberately "vulgar-coded" speech keeps the harder [x] even in fronting environments — and mocking/caricature speech (see [[../Culture/Accent and the Slavic Boogeyman|Culture/Accent and the Slavic Boogeyman]]) pushes it further back still, into a harsh, exaggerated uvular **[χ]**. The three-way range — prestige [ç], neutral [x], caricatured [χ] — is a single phoneme's register spectrum, not three phonemes.

This connects to a real structural asymmetry already implicit in [[Design Principles]]: /x/ is "consistent with the Slavic norm" precisely because real Vulgar Latin/Dalmatian has no velar or uvular fricative at all (see [[../Sources/Vulgar Latin|Sources/Vulgar Latin]], [[../Sources/Dalmatian|Sources/Dalmatian]]) — /x/ is the one common, everyday sound the Dalmatian prestige layer never touched, which is exactly why it became available as the register's whole battleground.

## Open Design Notes

- This inventory has no phonemic palatalized-stop series (no distinct /kʲ/, /gʲ/, /tʲ/, /dʲ/), and it shouldn't — a pervasive plain/palatalized pairing across the whole consonant inventory is an East Slavic (Russian-style) feature, not a South Slavic one (see [[Design Principles]] § Palatalization, corrected 2026-09-18). Sisician's /ɲ ʎ/ plus the postalveolar affricates/fricatives /tʃ dʒ ʃ ʒ/ are the standard South Slavic pattern instead: a fixed, closed set of phonemes descending from Common Slavic's historical palatalizations, not a live hard/soft alternation.
- No /h/ — only the voiceless velar fricative /x/, consistent with the Slavic norm.
- Whether this inventory needs vowel length, pitch accent, or a stress system is still undecided.
- **Held loosely.** This is a fun target sketch, not a commitment — per the user (2026-09-18), phonemes here can be dropped or new ones added if no legitimate historical/phonological process turns out to produce them once Phase 1/3 work starts. The affricate and fricative series (/ts dz/, /tʃ dʒ/, /ʃ ʒ/, /x/) will eventually want a historical account — which come from inherited Slavic palatalization, which from Dalmatian loans reshaped by Slavic phonotactics, which (if any) from later Hungarian/German/Greek contact — but the inventory itself is free to change shape in the meantime.
