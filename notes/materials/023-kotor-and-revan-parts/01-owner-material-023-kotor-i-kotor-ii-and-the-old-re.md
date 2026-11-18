# Owner Material 023 — KOTOR I, KOTOR II and The Old Republic: Revan: notes from the other agent (reference copy, reviewed) — part 1 of 11

[All parts](README.md) · [Next](02-kotor-revan-player-character.md)

# Owner Material 023 — KOTOR I, KOTOR II and The Old Republic: Revan: notes from the other agent (reference copy, reviewed)

**Imported 2026-10-21** (Oct 21, 2026) from the other agent's MEGA "Grok Notes" ([member]'s export), text files only. Source folder: `[local path]`. Only the current files were copied, not the `.bak-*` / `.pre-*` versions (`kotor-1-notes.md.pre-deep`, `.pre-super`, `kotor-*-characters.md.pre-fullquotes`, `.pre-gapfix`, and so on). Every file here is a byte-for-byte copy of its source, with nothing summarized, trimmed or edited.

**Story order:** *Knights of the Old Republic* (game, 3,956 BBY) → *KOTOR II: The Sith Lords* (game, 3,951 BBY) → *The Old Republic: Revan* (Drew Karpyshyn, Del Rey 2011; Part One ~3,954 BBY, Part Two ~3,951 BBY, right after KOTOR II, Epilogue ~50 years later). The combined PDF and the tables below follow this order.

**Status: reference copy only.**
- **Our own notes win on any conflict.** That covers `[local path]` (including the 2026-10-21 Darth Nihilus section), `verdicts.md` (the Nihilus vs Sion/Traya/Obi-Wan/Bane entries and the Legends Sith top-tier list), materials 002–007 and the Suspect Insight debate notes. Where this folder disagrees with them, ours stands until we check the primary source ourselves.
- **Its verdicts are opinion, not feats.** "Verdict impact", "Verdict implications", "Proposed verdicts.md changes", diff leans, tier placements and confidence numbers are the other agent's judgments. Treat them like a forum opinion. Line references such as "verdicts.md L346" point to **the other agent's** verdicts.md, not ours.
- **Secondhand reads.** They do not count toward our own MASTERY tier for any character. For KOTOR, they are not even reads of the games (see below).
- Paths inside the notes (`raw/kotor/…`, `dialog/ALL.tsv`, `ALL2.tsv`, `digest/K1-narr.txt`, `[local path]`, `research/_revan-work/…`, `chargen/…`) belong to the other agent's box. The KOTOR transcript copies and the Revan novel text are **not** on this box.

Combined PDF (this README, then the five notes in story order): `../023-kotor-and-revan.pdf`, built from `../023-kotor-and-revan.md`. Each note also has its own PDF next to it in this folder (pandoc → WeasyPrint, then linearized with qpdf, no images). The two ~2.9 MB character files have a single `# ` heading, so they were rendered with `tools/md2pdf-h2split.py`. That is the same md2pdf renderer and CSS; it only lets the build split into chunks at `## ` headings.

## Files (5, in story order)

| File | Size (bytes) | PDF pages | What it is |
|---|---|---|---|
| `kotor-1-notes.md` | 29,427 | 11 | KOTOR I summary: plot by planet, ~20 key quotes, a boss-fight table, Force powers, short character analyses, then a "DEEP PASS" second read (backstory, scene plot, statement compilation, 24 one-paragraph analyses). |
| `kotor-1-characters.md` | 2,922,918 | 863 | KOTOR I "super-deep" write-ups for 24 characters. Each has a short hand-written synthesis, then script-built quote banks: the character's own lines, lines naming them, pronoun lines, lines addressed to them, and walkthrough narration. |
| `kotor-2-notes.md` | 39,719 | 14 | KOTOR II summary in the same layout, plus a Restored Content Mod (RCM) note and gaps. It covers the Exile, Kreia/Traya, Nihilus, Sion, Atris, Visas, the Jedi Masters and the companions. |
| `kotor-2-characters.md` | 2,840,445 | 851 | KOTOR II "super-deep" write-ups for 24 characters, built the same way as the KOTOR I file. |
| `revan-novel-notes.md` | 1,141,933 | 303 | *The Old Republic: Revan* (Karpyshyn, 2011), read in full from an encoding-damaged text. It has the cast, chapter plot, version-tagged feats and statements, ~25 character profiles, a ladder, verdict leans V-1 to V-6, proposed verdicts.md changes, a quote-verification report, a raw reading log (Appendix L) and an auto-harvested quote bank (Appendix Q). |

## Extras (`extras/`, 5)

## Critical review (most important first)

Spot checks on this box, 2026-10-21: I pulled all 302 current StrategyWiki KOTOR I/II pages through the public API (156 K1 + 146 K2) and re-ran a quote check on all four KOTOR files. The Revan novel text is not available here, so its quotes could not be re-checked.

1. **The KOTOR files are walkthrough-wiki notes, not game reads. The CATALOG is right.** Both notes files say so up front: "the source is a game walkthrough wiki (StrategyWiki…) … **not the game itself**". Everything cites `K1/<Page>`/`K2/<Page>` wiki subpages. Fight outcomes come from walkthrough narration (e.g. "Kreia drains them, and they collapse"), and stat blocks are gameplay mechanics. By our standard this is below a primary read: we verified our Nihilus lines against the LP Archive transcript, and our MASTERY bar is a full game-dialogue pass.
2. **About 98% of each character file is auto-generated quote banks.** In `kotor-1-characters.md` the hand-written synthesis is ~53 KB of 2.92 MB, and in `kotor-2-characters.md` it is ~50 KB of 2.84 MB. Much of the bank is noise:
   - The player characters' "own lines" are **player dialogue options**: 7,223 for Revan and 8,677 for the Exile, e.g. «Fine, here's your 20 credits.». The file labels them as player choices, but they carry no scaling value.
   - Bank C "walkthrough narration" is full of gameplay tips (pazaak wagers, "You can pause game to level up…").
   - 722 bank "quotes" contain raw wiki markup (`[[../Ahto West#…`, `{{control…`).
   - In `revan-novel-notes.md`, Appendix Q (the auto-harvest) is ~989 KB of 1.14 MB, and the curated analysis is ~128 KB.
3. **The "about X" banks misattribute lines through loose aliases.** Nihilus's "what others say about him" bank matches on "my Master". It therefore files HK-47 on Revan («my Master had his ups and downs…»), Sion addressing Kreia («I sense you, my Master. Faint... weak.»), the Twi'lek Domo's Hutt master, droid TT-32's owner, Bastila's "our master" and the Disciple's lost master as statements about Nihilus. About a third of that bank is wrong. "Script-verified" here means the words exist on the wiki, **not** that the speaker or subject is right. Don't cite a bank line without reading its context.
4. **A misused Malak quote in the Discord summary.** `discord-summary-kotor-2026-10-19.txt` offers «Once you were stronger than me, Revan» as evidence for Revan over Malak. In context, that line goes on «But as your apprentice I surpassed you», so it is Malak's claim to have *surpassed* Revan. On StrategyWiki it is one of three alternative dialogue branches (marked `C=2`/`C=3`), next to «Perhaps you are too powerful to be my apprentice…». The line that actually helps Revan is the opening «You are stronger than I thought; stronger than you ever were during your reign as the Dark Lord», and the "-diff" version of the post uses that one. The KOTOR I files also put the "surpassed you" line under "Power-scaling statements" for Revan without flagging that it cuts the other way.
5. **The two Discord summaries contradict each other on Exile vs Nihilus.** v1 says Nihilus "reels back, collapsing" *before Visas does anything* and raises the Exile's neutral-rematch lean. v2 says the win "leans on Visas cutting his link" and that a neutral rematch is "close to a coin flip". On the wiki both readings are overstated:
   - The "reels back, collapsing" line follows one dialogue branch (after an Intelligence/Wisdom "Kreia has lied to you" option). It is not an unconditional event.
   - Visas only acts once Nihilus is already **below 50% Vitality**. "Disrupting the link" stuns him for **one combat round**. Her self-sacrifice (dark-side choice; she must be wearing clothing and using a melee weapon) cuts him to 20% Vitality. These are mechanics. `kotor-2-notes.md` calls her sacrifice "the decisive move in that fight", which goes beyond the source.
   - This also bears on **our** `verdicts.md` Nihilus vs Sion reasoning ("fell only to a designed hard counter plus the broken Visas bond"). Our entry stands, but the "broken Visas bond" part rests on a conditional mid-fight mechanic. It's worth re-wording when we do the KOTOR II dialogue pass.
6. **Internal contradictions about the Restored Content Mod.**
   - `kotor-2-notes.md` §6 says the RCM page "was fetched but not mined". §D5 and the Discord summary say it was checked and changes nothing.
   - D5 says the RCM pages have "no Nihilus-Sion meeting". The Nihilus owed post (extras) knows of "the cut-content scene of Nihilus blasting Sion", and our legends-feats also excludes that cut scene.
   - `kotor-1-notes.md` says K1 has "no Restored Content Mod", yet every K1 character entry carries an empty "Cut content (RCM)" section.
7. **Quote fidelity is good where it can be checked.** All 97 «quotes» in `kotor-1-notes.md` and all 153 in `kotor-2-notes.md` are exact matches on the current wiki. In the character files, 18,530 and 19,316 quotes (excluding the 722 markup fragments) all match once wiki templates and links are stripped. No KOTOR quote fails. The other agent's own verifier (`verify_kotor_quotes.py`) checks against its local copy, which isn't here. The stats checked out exactly too: Nihilus L21 / 1004 VP / 615 FP / Def 48; Traya L23 / 1180 / 1221 / 51; Sion L20 / 322 (Korriban) and L23 / 488 (Malachor); Atris L21 / 252 / 513; Malak 327 VP.
   - The Revan note reports 4,419/4,419 quotes verified, but against a text file we can't see. It discloses that the file is encoding-damaged (every quote mark and dash is U+FFFD) and that the punctuation was "restored" in the note. Its own fix list says "five L-number slips" and then lists seven line numbers.
8. **Reasoning that we question (critical, not agreeing).**
   - *Revan novel, V-1 "Vitiate, mid diff, high confidence (8/10)".* The note's own account is that Revan loses the lightning clash outright, is "helpless within about 8 exchanges", leaves the Emperor with only "singed robes" and is saved by T3 and Meetra. That reads as low-mid diff at most. Material 004 (opinion) reads the same fight as "12 bolts which overwhelm Revan nigh-instantly", material 003 (opinion) calls Revan "genuinely a threat", and our legends-feats § Revan has "overwhelmed by Vitiate's lightning" (#52). Our entry stands. Treat 023's "mid diff" as the generous end.
   - *V-3/V-4 use transitive chains* (Revan ≫ Nyriss > Meetra) from a 2v1 fight (Nyriss vs Scourge + Meetra). That is weak evidence for any 1v1 placement. The note half-admits this ("tension with the tier list").
   - *Sion's «I have come farther than any of her apprentices since Revan… even you»* is read as "implicitly places Revan above Sion". It is a [Success] persuasion-branch line addressed to the Exile. It ranks Sion against Traya's apprentices since Revan's time, not against Revan. Their K2 Traya analysis rightly flags the companion line «She… cannot be defeated» as persuasion-branch rhetoric, but not this one.
   - *Numbers mean different things in different files.* "8/10" is a confidence score in the Revan note but a diff score in the Nihilus owed post ("Nihilus beats Sion mid diff, about 8/10"). Don't compare them.
   - *Statements filed as feats.* K1 Revan "Feats: Kills Mandalore [K1/Canderous]" is Canderous's statement, not an on-screen feat.
9. **Factual slips and gaps.**
   - `kotor-1-notes.md` §6 says KOTOR I stat blocks "came from the prose" because the template differs. The K1 wiki pages do use `{{KotOR/NPC|…|Vitality=…}}` blocks (Malak's 327 VP is one), so the missing Bastila and Uthar/Yuthura numbers were extractable.
   - Coverage is thin for the KOTOR II villains because the wiki is thin. Nihilus has 0 own lines (true to the game). Sion has 82 own lines and only 2 NPC lines naming him. Treat their Sion and Nihilus profiles as summaries, not deep reads.
   - The K2 Jedi Masters are called "council-level" and Kreia's drain of all three is treated as a clean feat. The note does add "they were mid-ritual and distracted". Our legends-feats § Darth Traya (#55) adds that cut content shows a TK hold on all three.
10. **How it lines up with our notes.**
    - **Agrees:** Nihilus > Sion. Our verdict is mid diff, moderate. Their analyses put Nihilus at tier 5 and Sion at tier 7, while their owed post says "mid diff (about 8/10)", which by its own diff scale is the low-diff end. A slight Nihilus > Traya lean, low confidence, matches ours. Both sides use Atris's "the greatest of her apprentices" line (verified on K2/Telos). They also agree on Traya draining the three Masters, Meetra beating Traya, Bastila holding off Malak on the Leviathan, Revan bending Nyriss's lightning (our #4, now on-page at novel L5419–5425 per 023) and "infinitely more powerful than Darth Nyriss" (our #10/#52).
    - **Differs:** their tiering puts Revan, Nihilus and the Exile in "tier 5" and Sion in "tier 7". Our top-tier list puts Revan and Nihilus in the contested band below Kun, with no tiers for the Exile or Sion. Ours stands.
    - **Our exclusion holds:** our Nihilus section excludes the party-wide bridge Force Wave as un-animated cut content (LP Archive Part 54). 023 doesn't use it, which is correct. It does list "Nihilus roars, hurling Visas across the room" (wiki narration, on one branch) as a feat, and we have not confirmed that it is animated.
11. **Useful material we didn't have.**
    - The exact KOTOR I Viewing Platform wording and branch structure of Malak's lines. Our legends-feats § Revan (#114) paraphrases the "stronger than he ever was" line.
    - The speaker of our § Darth Malak quote «The Star Forge feeds the power of your old apprentice…» is the **Rakatan Elder Councillor** (K1/Temple_Summit, one branch). Our entry gives no speaker.
    - Nihilus: Kreia's «It is not something he can direct or focus» (hunger as a weakness). 023 also has Tobin's «He holds it together» and Visas's «seam in the fabric of the Force» line, which match what our 2026-10-21 session notes already verified in the LP transcript.
    - The owed post cites the Campaign Guide line "They turn on her and drain her Force powers" for Traya's fall, which we have not verified. It names Sion and Nihilus jointly, so it would not flip our Nihilus vs Traya entry, which needs a source naming Nihilus alone.
    - The Revan novel's on-page timeline anchors (Prologue «two standard years after…» L83; Part Two ≈ 3,951 BBY), the Nathema void persisting after ~1,000 years, Vitiate feeding on the imprisoned Revan (Ch29) and Meetra's death as a backstab by Scourge while she faced the Emperor (L6069–6071). That last point is a useful caveat for any "Meetra lost to Scourge" claim.

---

<!-- 023-kotor-and-revan/kotor-1-notes.md (verbatim copy) -->

# Star Wars: Knights of the Old Republic (KOTOR 1): power-scaling notes (Oct 19, 2026)

**Method:** the source is a game walkthrough wiki (StrategyWiki, 156 K1 content pages fetched via api.php on Oct 19, 2026; raw copies in `raw/kotor/`). That makes it intermediate depth: it transcribes most dialog and describes cutscenes, but it is **not the game itself**. Gameplay stats (Vitality, Defense, Force points) are game mechanics, not lore, and get low weight. Quotes are copied from the wiki's dialog templates. The citation `K1/<Page>` means the StrategyWiki subpage `Star Wars: Knights of the Old Republic/<Page>`. Gender-variant lines exist; one variant is quoted.

## 1. Plot by planet
- **Endar Spire** (Command Module, Starboard Section): the Republic ship is attacked over Taris. Bastila is aboard. The player (an amnesiac "soldier") escapes with Carth.
- **Taris** (Upper/Lower City, Undercity, Sewers, Black Vulkar Base, Davik's Estate): the player rescues Bastila via a swoop race and allies with Mission, Zaalbar and Canderous, then steals the Ebon Hawk from Davik Kang. Calo Nord is buried by rubble during the escape. Malak orders Taris destroyed: «The search for Bastila is taking too long. We cannot risk her escaping Taris. Destroy the entire planet.» and «Wipe this pathetic planet from the face of the galaxy.» (K1/Davik's_Estate).
- **Dantooine** (Jedi Enclave, Grove, Ruins): the Council (Vandar, Vrook, Zhar, Dorak) retrains the player. Trial: the fallen Juhani in the Grove, the player's first lightsaber duel; she is slain or redeemed. The ruins hold the first Star Map, seen in a dream the player shares with Bastila of Revan and Malak there. Vision line: «The dark side is strong in this place – I can feel its power!... Are the secrets of the Star Forge so valuable?» (Malak, K1/Jedi_Enclave).
- **Quest for the Star Forge:** four Star Maps.
  - **Tatooine**: Sand People, the krayt dragon cave map, HK-47 bought in the droid shop.
  - **Kashyyyk**: the Shadowlands map, the Zaalbar/Chuundar plot, Jolee Bindo recruited.
  - **Manaan**: Ahto City, the Sith base, the Hrakert Rift map, the sea-floor kolto plot.
  - **Korriban**: the Sith Academy under Uthar Wynn and Yuthura Ban. The final test is in the Tomb of Naga Sadow, where the player sides with one master. Other tombs: Ajunta Pall, Marka Ragnos, Tulak Hord.
  - Darth Bandon and Calo Nord ambush the party at varying points.
- **Leviathan** (Prison Block, Command Deck, Bridge, Hangar): the party is captured. Admiral Saul Karath is defeated on the bridge. In the hangar Malak reveals the player is Revan; the player duels him, and Bastila holds Malak off while the party escapes. She is captured.
- **Star Forge System** (Rakatan beaches, Temple of the Ancients): on the Temple Summit, a dark-sided Bastila confronts Revan. This is the light/dark choice point.
  - Light side: Bastila flees to the Star Forge.
  - Dark side: Bastila joins Revan, who then kills Jolee and/or Juhani and possibly others (K1/Temple_Summit).
- **Star Forge** (Deck 1, Deck 2, Command Center, Viewing Platform):
  - Command Center: Revan faces Bastila again, who is redeemed or killed.
  - Viewing Platform: Revan kills Malak. Light ending: the Republic fleet destroys the Star Forge. Dark ending: Revan is Dark Lord, with Bastila addressing the Sith (K1/Viewing_Platform).
- **Yavin Station**: optional side shop (no plot significance).

## 2. Key quotes (verified against fetched text)
- Malak, on Revan's restored strength: «Well done, Revan. I was certain the defenses of the Star Forge would destroy you, but I see there is more of your old self in you than I expected. You are stronger than I thought; stronger than you ever were during your reign as the Dark Lord. I did not think that was possible.» (K1/Viewing_Platform)
- Malak: «Once you were stronger than me, Revan. But as your apprentice I surpassed you. The Master must always be stronger than the apprentice... that was why I betrayed you.» (K1/Viewing_Platform)
- Malak: «Perhaps you are too powerful to be my apprentice. I betrayed you when I realized my own strength was greater than yours» (K1/Viewing_Platform)
- Malak on the captive Jedi: «You cannot beat me, Revan. Not here on the Star Forge. Not when I can draw upon the power of all these Jedi!» (K1/Viewing_Platform)
- Malak, dying: «You are the one who deserves... who deserves to be the Dark Lord... It was you who lead us on our quest for the Star Forge. I only followed in your wake.» (K1/Viewing_Platform)
- Malak (Leviathan): «A small part of me has always regretted betraying you from afar. I always knew there were some who would think I acted out of fear, that I did not want to face you.» (K1/Hangar)
- Malak (Command Center): «You may have reclaimed your identity, Revan, but you have lost the power you once wielded!» and «The Star Forge fuels my command of the dark side. You are no match for me here.» (K1/Command_Center)
- Malak (Deck 2): «Strange. I did not think there were any among the Order who could survive an attack by an army of the Star Forge's battle droids.» then «Revan always was strong in the Force.» (K1/Deck_2)
- Vandar: «Revan was always the leader, the more powerful of the pair... But Malak quickly assumed Revan's role, and embraced the dark side power as fully as his old master ever did.» (K1/Jedi_Enclave)
- Canderous: «We lost to the greatest single warrior the Republic has ever known.» (K1/Canderous). Also: «Mandalore himself was killed at the hands of the Jedi Revan. The best of us could not defeat him!» (K1/Hangar) and «You, Revan, are the single greatest warrior of this age» (K1/Star_Forge).
- Canderous: «Ha! I was the best! Except for Mandalore of course. He was the only person alive except Revan who could have beat me.» (K1/Canderous)
- Bastila (dark, Command Center): «Even though you are only a shell of your former self, you are still a formidable opponent. I can't even imagine the power you must have wielded when you were the Dark Lord.» (K1/Command_Center)
- Bastila (dark): «The dark side has made me stronger than I ever was before! I have a greater command of the Force than all but the most powerful Jedi Masters.» (K1/Command_Center)
- Vandar on Battle Meditation: «With this power she can swing the tide of nearly any battle in our favour.» (K1/Jedi_Enclave). Vrook: «Without her skill in Battle Meditation the Sith armada would have conquered the galaxy long ago.» (K1/Jedi_Enclave)
- Jolee, on Exar Kun's war: «Pupil against master. In my case... it was a long and terrible battle, but I defeated her» (K1/Jolee_Bindo)
- Uthar on Naga Sadow: «the greatest of Korriban's Sith Lords, in fact» (K1/Sith_Academy)
- Yuthura: «Malak is the strongest of us, and the strongest always rules» (K1/Sith_Academy_Entrance). Also: «In the end, Revan was outshone by his pupil. Such is the way of the Sith.» (K1/Hangar)

## 3. Boss fights and duels (outcomes)
| Fight | Page | Outcome / notes |
|---|---|---|
| Juhani (Grove) | K1/Grove | The player's "first ever lightsaber duel". Juhani puts the party in stasis and fights the player alone. The player wins and Juhani is slain or redeemed. Juhani concedes: «when you bested me so easily». |
| Calo Nord + Davik (Davik's Estate) | K1/Davik's_Estate | Combat ends at 50% of Calo's Vitality. Rubble buries Calo. He returns later on Tatooine, Kashyyyk or Manaan and is killed. |
| Darth Bandon (Malak's apprentice) | K1/Quest_for_the_Star_Forge and the planet pages | Malak sends him: «My apprentice, Darth Bandon, shall take care of our young Jedi friend.» Killed by the player. |
| Uthar Wynn / Yuthura Ban | K1/Tomb_of_Naga_Sadow | Final academy test. The player sides with one and kills the other (Yuthura betrays the player if sided with). |
| Admiral Saul Karath + 2 dark Jedi | K1/Bridge | Killed. Dies after his last words to Carth. |
| **Malak #1 (Leviathan hangar)** | K1/Hangar | Malak deflects Carth's bolts and stasis-locks Bastila and Carth, then duels the player alone. After the player inflicts >1/3 of his Vitality, Malak stasis-locks them too, and Bastila holds him off so the others can escape. Outcome: **Malak wins / Revan escapes**. This is early, low-level Revan. |
| Bastila (Temple Summit) | K1/Temple_Summit | Bastila is reduced to 50%, then uses Force Wave and the dialog resumes. Light: she flees. Dark: she joins Revan, who then kills Jolee/Juhani. |
| Three dark Jedi + Bastila (Command Center) | K1/Command_Center | Light: Bastila is beaten and redeemed (or killed). |
| **Malak #2 (Star Forge Viewing Platform)** | K1/Viewing_Platform | Malak drains captive Jedi to fully restore his Vitality and Force (up to 8 captives). Revan defeats him once the captives are freed or killed. Outcome: **Revan kills Malak**, who concedes in his dying words. |

Malak's game stats (Viewing Platform prose, mechanics only): 327 max Vitality, 175 Force points, Defense 38 ("almost the highest in the entire game"), "his Attack may well be the highest in the entire game", Master Flurry/Power Attack, Force Immunity, Force Breach, Force Lightning, Throw Lightsaber, Kill/choke. Immune to mind-affecting powers.

## 4. Force powers and abilities shown
- Playable power list (K1/Force_powers): Light side: Cure, Force Aura/Valor, Stun, Stun Droid. Universal: Affect Mind, Burst of Speed, Energy Resistance, Force Push (Whirlwind/Wave), Force Resistance/Immunity, Force Suppression/Breach, Throw Lightsaber. Dark side: Drain Life (Death Field), Fear (Horror/Insanity), Shock (Lightning/Storm), Slow (Plague), Wound (Choke/Kill).
- Story-level abilities, which carry more lore weight than the gameplay list:
  - **Malak's captive-Jedi drain.** He feeds on Jedi «For all intents and purposes dead... I have not let them become one with the Force» to restore himself (K1/Viewing_Platform).
  - **Bastila's Battle Meditation.** It can "swing the tide of nearly any battle" (Vandar). It is used against Dodonna's fleet from the Star Forge (K1/Command_Center, K1/Star_Forge).
  - **The Force bond between Revan and Bastila.** They share dreams and visions (K1/Jedi_Enclave, K1/Bastila).
  - **Malak's stasis.** He stasis-locks three people at once (K1/Hangar).
  - **The Star Forge as a dark side amplifier.** «Its very walls are alive with dark side energies!» (K1/Command_Center).
  - **The Council's mind-reprogramming of Revan.** «the Council used the Force to reprogram your mind» (Malak, K1/Hangar). Uthar and Yuthura both sense Revan's identity on sight (K1/Hangar).


> **SUPER-DEEP CHARACTER WRITE-UPS (Oct 19, 2026):** all 24 analyses for this game were rewritten in full. Each has background, personality, a scene-by-scene arc with light/dark variants, relationships, abilities (lore, plus mechanics flagged as such), feats, statements, duels, cut content (RCM), verdict implications, gaps and complete verbatim quote banks. They are in **[kotor-1-characters/](kotor-1-characters.md)**, split out for size. The shorter analyses below are kept as summaries.

## 5. Character analyses
### Revan (player character)
- **Feats:**
  - Defeats Malak on the Star Forge while Malak keeps draining captive Jedi (K1/Viewing_Platform).
  - Survives "an army of the Star Forge's battle droids" (K1/Deck_2).
  - Beats Bastila twice and kills Bandon, Uthar or Yuthura, Calo Nord and Karath.
  - Dark path: kills Jolee and Juhani together.
  - Before the game (statements only): crushed the Mandalorians and killed Mandalore (Canderous).
- **Statements:**
  - Malak: stronger now than as Dark Lord.
  - Vandar: "the more powerful of the pair".
  - Canderous: "greatest single warrior the Republic has ever known".
  - Bastila (dark): "only a shell of your former self... still a formidable opponent".
- **Arc:** amnesiac soldier → Jedi → learns he is Revan → redeemed hero or Sith Lord again.
- **Verdict impact:** Revan > Malak (KOTOR 1 Revan), high confidence. The game's own text has Malak concede the title and the higher destiny. Caveat: the gameplay outcome scales with the player's build, and the Leviathan loss shows an underleveled Revan.

### Darth Malak
- **Feats:**
  - Wins the first duel on the Leviathan and stasis-locks three opponents.
  - Orders the orbital bombardment of Taris.
  - Broke Bastila to the dark side (K1/Star_Forge_System torture scene: «You are strong, child. But I will break you.»).
  - Drains captive Jedi to fully heal.
- **Statements:** claims to have surpassed Revan (K1/Viewing_Platform, K1/Command_Center). His own insecurity: "betraying you from afar... some who would think I acted out of fear".
- **Arc:** loyal apprentice → usurper → dies conceding that Revan deserved the title.
- **Verdict impact:** below Revan (high). Malak-on-the-Star-Forge is a nexus-amped version. Out of nexus he lacks the drain-heal loop.

### Bastila Shan
- **Feats:**
  - Battle Meditation swings fleet battles.
  - Was on the strike team that captured Revan (K1/Bastila: «due to my Battle Meditation, I was with the Jedi strike team that boarded Revan's ship»).
  - Holds Malak off long enough for the party to escape (K1/Hangar).
  - Dark Bastila fights Revan twice (summit and Command Center) and loses both times.
- **Statements:** dark Bastila claims "a greater command of the Force than all but the most powerful Jedi Masters" (self-hype while Star Forge-amped).
- **Arc:** proud Padawan → Malak's apprentice → redeemed (light side) or Revan's apprentice (dark side).
- **Verdict impact:** a support-power outlier whose Battle Meditation matters at army scale. In a duel she is a clear tier below Revan and Malak.

### Jolee Bindo
- **Feats:** veteran of the Exar Kun war. Defeated his own fallen pupil Nayama in «a long and terrible battle» (K1/Jolee_Bindo). Survived decades in the Shadowlands.
- **Statements:** calls Nomi Sunrider «one of the greatest Jedi ever». Frames the Sith as «the worst thing since Exar Kun» (K1/Carth).
- **Arc:** a grey hermit who rejoins the fight. On the dark path he is killed by Revan.
- **Verdict impact:** a skilled veteran (Knight to Master level). A useful scaling link to the Sith War era but no high-end feats.

### Juhani
- **Feats:** a fallen Cathar Jedi who stasis-locks the party, then loses one-on-one to a newly trained Revan (K1/Grove: «you bested me so easily»).
- **Statements:** Revan's troops saved her on Taris during the Mandalorian Wars (K1/Hangar).
- **Arc:** fallen → redeemed. On the dark path she is killed at the summit.
- **Verdict impact:** a low-end Jedi Knight benchmark.

### HK-47
- **Feats (from statements):** Revan's assassin droid. «I exist to serve Revan as your personal battle droid.» (K1/Hangar)
- **Arc:** reveals in KOTOR 1 that Revan built him («You are Revan... you are my master, the one who created me»). His big Revan intel comes in KOTOR 2 (see kotor-2-notes).
- **Verdict impact:** none for Force tiers. He is a Revan-strategy witness.

### Carth Onasi
- **Feats:** a Republic pilot and soldier. Learns Revan's identity from Saul Karath (K1/Hangar).
- **Statements:** «I only met Malak once, but I was impressed by him» (K1/Carth). Sums up Revan and Malak before their fall: «Revan and Malak were heroes».
- **Arc:** trust issues → loyalty (light side). He may leave on the dark path.
- **Verdict impact:** none (non-Force user). A morale and witness role.

### Canderous Ordo
- **Statements:** the main source for Revan's Mandalorian War hype: «Revan was a genius on the field», «Even Mandalore himself was taken» (K1/Canderous), «You were the only one in the galaxy who could best us» (K1/Hangar).
- **Arc:** mercenary → Revan loyalist. He will follow light or dark (K1/Temple_Summit). Becomes Mandalore in KOTOR 2.
- **Verdict impact:** strong strategic and martial hype for Revan. Note his bias: he hero-worships Revan.

### Yuthura Ban and Uthar Wynn (Korriban)
- **Statements:**
  - Yuthura: «Malak is the strongest of us, and the strongest always rules» (K1/Sith_Academy_Entrance).
  - Both see through Revan's identity: «So it is... Darth Revan, not dead as we were led to believe. And yet... you are *not* Revan» (Uthar, K1/Hangar).
  - Uthar ranks Naga Sadow «the greatest of Korriban's Sith Lords».
- **Fight:** the player kills one or both in the Tomb of Naga Sadow.
- **Verdict impact:** academy-master level. They confirm that Revan's Force signature is recognizable.

### Vandar Tokare and Vrook Lamar (Jedi Council)
- Witnesses to the Revan > Malak hierarchy (Vandar, above). Vrook places the fall at Dantooine's dark cave, before the Mandalorian Wars (K1/Jedi_Enclave).
- No combat in KOTOR 1. Vrook fights in KOTOR 2.

### Saul Karath, Darth Bandon, Calo Nord
- Mid-bosses. Malak downgrades bounty hunters: «No mere bounty hunter can stand against a Jedi.» (K1/Quest_for_the_Star_Forge). All three are killed by the party.

## 6. Gaps
- K1 NPC stat blocks use a different template from K2, so boss stats came from the prose (Malak only). Bastila's and the Uthar/Yuthura numbers were not extracted.
- Pages on the TOC but not found in allpages: `/Force`, `/Melee` (the character-build pages). `/Ranged` exists.
- The wiki has no Revan-vs-Mandalore scene. That is backstory only, via Canderous.

---

# DEEP PASS (Oct 19, 2026, second read)

Method: second pass over the same 156 saved K1 content pages. Nothing was re-fetched. The pages were parsed into an ordered digest, a narration-only plot file, and 24 per-character dossiers, then cross-checked with targeted greps of dialog/ALL.tsv and the raw .wiki files (including the NPC stat-block pages). Every «quote» below was machine-checked against the saved wiki text. Text in "double quotes" is walkthrough narration, not character dialog. Citations use the form [K1/<Page>].

## D1. Backstory and history (as told in K1)
- **The Council's hesitation.** Dorak explains that the Council weighed «many factors to consider before we allowed ourselves to be drawn into another conflict so soon after the war with Exar Kun» [K1/Jedi_Enclave]. Zhar: «The Jedi Order moved too slowly for Revan and Malak» [K1/Jedi_Enclave].
- **Revan's war.** Canderous: «It was by the actions of one person, the Jedi Revan, that you prevailed.» [K1/Canderous]. «Mandalore himself was killed at the hands of the Jedi Revan. The best of us could not defeat him!» [K1/Canderous]. Juhani was among those Revan's troops saved on Taris: «It was Revan, leading an army out to defeat the Mandalorians. It was you...» [K1/Hangar].
- **The return as Sith.** Carth: «when they returned from wherever they went, they had an entire fleet with them» [K1/Carth]. Dorak: «For two years the Sith were all but invincible.» [K1/Jedi_Enclave].
- **The ambush.** Malak: «I ordered my own ships to fire on your bridge.» [K1/Hangar]. He also tells how the Jedi strike team took Revan: «The Jedi set a trap. They lured us into battle against a small Republic fleet.» [K1/Hangar]. Bastila: «It was Malak who turned on his own master, firing upon Revan's ship while we were still on board it.» [K1/Bastila].
- **Malak's own justification.** «Once you were stronger than me, Revan. But as your apprentice I surpassed you.» [K1/Viewing_Platform].
- **Ancient history.** Ajunta Pall: «We were the first. The first to rebel, to betray...» [K1/Tomb_of_Ajunta_Pall]. «We destroyed each other.» [K1/Tomb_of_Ajunta_Pall]. Keeper Orsaa on the Rakata: «Long ago the Rakata ruled all the known galaxy» [K1/Elder_Settlement]. The Star Forge is described as a «Rakatan factory» [K1/Command_Center].
- **Telos.** Carth: «Four years ago, Saul led the Sith fleet there and demanded its surrender. The planet refused and Saul proceeded to devastate its entire surface.» [K1/Carth]. This links directly to the Telos restoration in K2.

## D2. Scene-by-scene plot (expanded)
- **Endar Spire.** Trask leads the escape and dies holding back Bandon. Carth joins and the two escape by pod.
- **Taris.** On the Leviathan, Karath and Malak watch the blockade. The party works through the Upper and Lower City, Javyar's Cantina (Calo Nord counts «One.» «Two.» «Three.» [K1/Javyar's_Cantina]), the Undercity and the Vulkar base, and wins the swoop race to free Bastila. The dueling ring includes Bendak Starkiller. On Davik's estate Calo Nord threatens to blow everyone up with a thermal detonator [K1/Davik's_Estate]. The Leviathan bombards Taris as the party escapes on the Ebon Hawk.
- **Dantooine.** The Council trains the player; the training montage is narrated. The Juhani grove is resolved by redemption or by killing her: Juhani claims she «struck down my Master, Quatra» [K1/Grove]. Other side quests are the Sandral-Matale feud and the Ruins Star Map, after which the hunt for the Star Maps begins.
- **Tatooine.** Czerka, Anchorhead and the Tusken raiders; the Dune Sea and the krayt dragon.
- **Kashyyyk.** Chuundar vs Freyyr and the life-debt politics, which include possibly turning Zaalbar against his father. Jolee lives in the Shadowlands. The Star Map's final question gives a dark-side point [narration].
- **Manaan.** The Sunry murder trial; the Genoharadan assassin quests; the Hrakert Rift firaxan sharks. Darth Bandon appears on one of the Star Map worlds: «Malak and Revan found a way down here long before the Hrakert station was built.» [K1/Quest_for_the_Star_Forge]. Calo Nord appears on another and claims «I am hard to kill, Lord Malak.» [K1/Quest_for_the_Star_Forge].
- **Korriban.** Dreshdae, then the academy: Uthar's tests and Yuthura's plot. Ajunta Pall's spirit, then the Tomb of Naga Sadow. The ending is light (Yuthura possibly redeemed) or dark (Uthar or Yuthura killed).
- **Leviathan.** The party is captured. Carth faces Karath: «The only thing you taught me was betrayal and death, Saul.» [K1/Bridge]. In the Hangar, Malak reveals Revan's identity. Bastila is captured.
- **Unknown World (Rakata Prime).** Elder and One factions; the Temple of the Ancients; at the Temple Summit, Bastila tempts the player toward the dark side.
- **Star Forge.** Malak shows force: "flanked by two choking Jedi knights behind him. As you watch, he throws his lightsaber at the one on the right then uses Force Lightning on the one on the left, killing them both". Bastila holds the Command Center with Battle Meditation, fighting the Republic fleet if she has fallen, or aiding it on the light path. The Viewing Platform duel follows: Captive Jedi "play no part until Darth Malak's Vitality or Force has been sufficiently reduced, at which point he drains one to restore both to maximum." There are eight captives in electrical prisons [K1/Viewing_Platform].
- **Endings.** On the light path Revan defeats Malak, the Star Forge is destroyed, and there is a medal ceremony. On the dark path Revan reclaims the Dark Lord title with Bastila.

## D3. Lore and power-scaling statements compilation (K1)
**Revan**
- «Revan was always the leader, the more powerful of the pair.» (Vandar) [K1/Jedi_Enclave]
- «Revan always was strong in the Force.» (Malak) [K1/Deck_2]
- «Mandalore himself was killed at the hands of the Jedi Revan. The best of us could not defeat him!» (Canderous) [K1/Canderous]
- Uthar senses the change in him: «you are *not* Revan, are you?» [K1/Hangar]

**Malak**
- His boasts: «Even my old master is no longer a match for me!» [K1/Hangar]. «I have surpassed you in every way» [K1/Command_Center]
- Stat block: per the walkthrough, «his Attack may well be the highest in the entire game». His Defense of 38 is «almost the highest in the entire game». Mind-affecting immunity. He drains the captive Jedi to fully restore both his Vitality and his Force [K1/Viewing_Platform]. These are game mechanics, but they follow the story framing.
- Shows lightsaber throw plus Force Lightning (kills two Jedi knights), Force Push, and deflecting Carth's bolts; places Bastila and Carth in stasis (narration) [K1/Hangar].

**Bastila (Battle Meditation)**
- «With this power she can swing the tide of nearly any battle» (Vandar) [K1/Jedi_Enclave]
- Fallen Bastila: «I have a greater command of the Force than all but the most powerful Jedi Masters.» [K1/Command_Center]


> **SUPER-DEEP CHARACTER WRITE-UPS (Oct 19, 2026):** all 24 analyses for this game were rewritten in full. Each has background, personality, a scene-by-scene arc with light/dark variants, relationships, abilities (lore, plus mechanics flagged as such), feats, statements, duels, cut content (RCM), verdict implications, gaps and complete verbatim quote banks. They are in **[kotor-1-characters/](kotor-1-characters.md)**, split out for size. The shorter analyses below are kept as summaries.

## D4. Character analyses (deep). 24 entries; the earlier analyses above remain valid.
1. **Revan**. Verdict: Revan > Malak, high confidence (the earlier verdict holds). Revan beats Malak in a duel despite Malak's drain-regeneration, and the statements from Vandar, Canderous and Kreia's K2 lines are unanimous. The amnesiac player Revan is not peak Revan.
2. **Darth Malak**. Feats are listed above. Arc: an apprentice who betrayed his master «from afar», which he partly regrets: «A small part of me has always regretted betraying you from afar.» [K1/Hangar]. Verdict: a strong 1v1 brute whose top-tier status depends on sustaining himself with captives.
3. **Bastila Shan**. Battle Meditation is her strategic hax. She was on the strike team that captured Revan. She falls to the dark side and is redeemed on the light path. Uses Throw Lightsaber in the Temple fight (narration). Verdict: support/hax tier, mid-level duelist.
4. **Carth Onasi**. Republic pilot whose wife died on Telos and whose son Dustil is missing. His nemesis is Karath. Verdict: non-Force, street to military level.
5. **Mission Vao**. Twi'lek street kid from Taris; looks for her brother; Zaalbar's companion. No scaling.
6. **Zaalbar**. Wookiee companion of Mission; tied to the Chuundar/Freyyr plot on Kashyyyk. Physical brute.
7. **Canderous Ordo**. Mandalorian veteran of clan Ordo: «No one before me had mastered the power of our Basilisk war droids as quickly as I had. Except Mandalore himself of course.» [K1/Canderous]. The major source of statements about Revan in the Mandalorian Wars.
8. **HK-47**. Assassin droid whose memory is restored step by step. Captured by Mandalore and reprogrammed to attack his master: «I was captured by this Mandalore during the attempt.» [K1/HK-47]. Elite non-Force combatant.
9. **T3-M4**. Utility droid (on Taris, Davik's Estate). No scaling.
10. **Jolee Bindo**. Hermit Jedi who fought in the Great Sith War era. He failed to kill his wife Nayama, who had fallen: «she went on to kill many Jedi during the war» [K1/Jolee_Bindo]. On the dark ending at the Temple Summit he fights the player: «I'm a Jedi... I'll never bow down to the Sith.» [K1/Temple_Summit]. Veteran mid-tier.
11. **Juhani**. Cathar who believes she killed Master Quatra, but Quatra is alive: «I do not believe she has died» [K1/Grove]. Redeemed or killed. Revan's troops saved her on Taris. Mid-low tier.
12. **Vandar Tokare**. Council leader and the source of statements ranking Revan above Malak. No combat feats in K1.
13. **Vrook Lamar**. Council skeptic: «For fifteen thousand years the Republic has brought peace» [K1/Jedi_Enclave]. No feats.
14. **Zhar Lestin**. Trained Revan and Malak on Coruscant: «Revan and Malak often came to me for addition» (the line continues: "additional...") [K1/Jedi_Enclave]. Teacher; no feats.
15. **Dorak**. Chronicler and source of the history. Revan's teacher per K2 Disciple. No feats.
16. **Uthar Wynn**. Korriban headmaster. Senses that the player is Revan yet changed [K1/Hangar]. Killed or survives depending on the branch. Mid-level Sith Master.
17. **Yuthura Ban**. Twi'lek Sith master, schemer and one-time Jedi apprentice. Her redemption line: «My old master said he would start exercises with me again» [K1/Tomb_of_Naga_Sadow]. Mid-low tier.
18. **Darth Bandon**. Malak's apprentice; kills Trask on the Endar Spire (per the first pass). Hunts the party on a Star Map world and dies: «You may have defeated the pathetic bounty hunter my Master sent after you» [K1/Quest_for_the_Star_Forge]. Mid tier.
19. **Calo Nord**. A top bounty hunter: «nobody gets away from Calo Nord in the end!» [K1/Quest_for_the_Star_Forge]. Escapes Davik's Estate and resurfaces later («I am hard to kill»). Non-Force.
20. **Admiral Saul Karath**. Commander of the Sith fleet, who bombarded Telos and Taris: «Admiral Saul Karath is the commander of the entire Sith fleet.» [K1/Carth]. Dies on the Leviathan bridge. No scaling value.
21. **Ajunta Pall**. Spirit of one of the first Sith Lords. A source of history, not of feats.
22. **Belaya**. Dantooine Jedi student; Juhani's friend. No scaling.
23. **Keeper Orsaa / The One (Rakata)**. Sources of Rakatan history: «Our ships combined technology and the power of the Force» [K1/Elder_Settlement].
24. **Davik Kang**. Crime lord on Taris; Calo Nord's employer (Davik's Estate). Fate not re-verified. Street tier.

## D5. Deep-pass gaps
- K1 has no Restored Content Mod page equivalent.
- Pages missing on the wiki: K1 Force and Melee.
- Boss stats are gameplay mechanics, used here only as supporting framing.
- Trask's death and Bandon's role on the Endar Spire carry over from the first-pass notes; their wording was not re-quoted in this pass.


---

<!-- 023-kotor-and-revan/kotor-1-characters.md (verbatim copy) -->

# KOTOR 1: super-deep character write-ups (Oct 19, 2026)

Method: for every character, a script pulled ALL of their own lines and every line by others that names them, from raw/kotor/dialog/ALL2.tsv (45,051 transcribed lines, including 19,180 player dialogue options). It also pulled every walkthrough-narration line naming them, from the saved page text (digest/K1-narr.txt), and the gameplay stat blocks from the raw .wiki pages. Near-duplicate he/she variants are collapsed. ALL own lines are included regardless of length. Only exact duplicates and he/she variants are merged, and each merge is noted inline. 'About' lines cover names, aliases and epithets (chargen/aliases.py) plus pronoun references resolved from context (scene-wide, every candidate hand-reviewed and flagged [context-resolved] with its anchor line). A separate bank lists lines addressed to the character. The hand-written synthesis comes first. The quote banks follow it, verbatim and grouped by scene (page). Every «quote» is checked by verify_kotor_quotes.py. Game mechanics are flagged as mechanics. (RCM) marks Restored Content Mod material.

Characters (24): Revan (player character); Darth Malak; Bastila Shan; Carth Onasi; Mission Vao; Zaalbar; Canderous Ordo; HK-47; T3-M4; Jolee Bindo; Juhani; Vandar Tokare; Vrook Lamar; Zhar Lestin; Dorak; Uthar Wynn; Yuthura Ban; Darth Bandon; Calo Nord; Admiral Saul Karath; Ajunta Pall; Belaya; Keeper Orsaa and The One (Rakata); Davik Kang

