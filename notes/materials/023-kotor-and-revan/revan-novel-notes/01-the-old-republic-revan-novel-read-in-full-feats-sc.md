# The Old Republic: Revan (novel, read in full): feats, scaling, quotes and story notes — part 1 of 3

[All parts](README.md) · [Next](02-the-appendix-q-exhaustive-per-character-quote-harv.md)

# The Old Republic: Revan (novel, read in full): feats, scaling, quotes and story notes

<!-- read up to: EPILOGUE + About the Author (L6299), END OF BOOK. Written in house style (cf. lotf-7-fury-notes.md), deeper. -->

- **Book:** *Star Wars: The Old Republic: Revan* by Drew Karpyshyn (Del Rey, 2011). The front matter misspells the author as «Karpyshin» (L5, sic). Prologue, Part One (Ch1-16), Part Two (Ch17-29), Epilogue. About 94,365 words (wc on the source).
- **Continuity:** Legends. It bridges *KOTOR* (3,956 BBY), *KOTOR II* (3,951 BBY) and *SWTOR* (~3,643 BBY). **Part One is ~3,954 BBY.** The Prologue is set «two standard years after rediscovering his true identity» (L83), and Ch3 says «Almost two years had passed since he had been proclaimed the savior of the galaxy» (L611). **Part Two is ~3,951 BBY**, after the end of KOTOR II. Revan has been in Nyriss's cells for three years (Ch19), his son is three, and Revan has been gone about four years (L3505, L3513). Meetra defeated Traya «Three years after Revan's unsuccessful attempt to locate her» (L3515). **The Epilogue is ~50 years later** («these past fifty years», L6241), so roughly 3,900 BBY. Revan and Malak's first visit to Dromund Kaas is «Five years ago» as of 3,954 (L3383), i.e. ~3,959 BBY, between the Mandalorian Wars and the Jedi Civil War.
- **Source file:** `[local path]` (6,299 lines). The file is encoding-damaged: every apostrophe, quotation mark and em dash is a U+FFFD replacement character, and accented letters became `?` («d?j? vu» L2835, «coup de gr?ce» L6093, «na?ve» L567). In this file I show the text with the punctuation restored (' " —). The verifier counts every quote or dash character, including U+FFFD, as the same character, so the restoration can't produce a false match.
- **Method:** I read every line in order, in large chunks: front matter, Prologue, Ch1-29, Epilogue, back matter. I kept a reading log while reading (`research/_revan-work/log.md`). `L####` is the line number in the source file. **Text inside «…» is copied from the source and checked by script** (`_revan-work/verify.py`; the report is at the end of the curated sections). Quotes from other files (KOTOR notes, verdicts.md) use plain "double quotes" with a file tag, so they are not counted as book quotes. My work files are all in `research/_revan-work/`. I did not use or modify the other workers' `_extract/*` files.
- **Chapter heading lines:** Front matter L1-60 (dramatis personae). Prologue L63. PART ONE L157. Ch1 L161, Ch2 L377, Ch3 L607, Ch4 L727, Ch5 L961, Ch6 L1137, Ch7 L1285, Ch8 L1523, Ch9 L1761, Ch10 L2025, Ch11 L2163, Ch12 L2499, Ch13 L2721, Ch14 L3013, Ch15 L3167, Ch16 L3337. PART TWO L3497. Ch17 L3501, Ch18 L3717, Ch19 L3889, Ch20 L4069, Ch21 L4339, Ch22 L4665, Ch23 L4891, Ch24 L5105, Ch25 L5445, Ch26 L5661, Ch27 L5789, Ch28 L5973, Ch29 L6107. Epilogue L6215. About the Author L6295.
- **Feat vs. statement:** Section 3 is what the narration *shows* (FEAT). Section 4 is what characters say or think (**STATEMENT**). Karpyshyn writes in rotating tight third person: Revan, Scourge, Meetra and Bastila each get scenes (the POV map is in §1b). So a lot of "narration" is that character's perception or estimate, and it is marked *(POV X)*. One distinction matters for scaling. POV *perception* (what someone senses) is fairly reliable. POV *self-assessment* or *prediction* («Alone, probably not», L5861; «the Emperor would have won regardless», L6129) is that character's opinion, not authorial fact. Karpyshyn does sometimes give an omniscient-style line inside a POV, e.g. «the Emperor was infinitely more powerful than Darth Nyriss had ever been» (L6001). I treat those as near-authorial because they explain an on-page result.
- **Headline:** this is the **Revan-meets-Vitiate** book. It retcons the Mandalorian Wars and the Jedi Civil War into the Sith Emperor's plan: the Emperor manipulated Mandalore, then dominated Revan and Malak. The **only Revan vs Emperor fight on page (Ch28)** goes like this. Revan, with memories restored and «balance on the knife-edge», trades knockbacks with the Emperor and lands a redirected lightning bolt. Then he loses the lightning clash outright. T3 buys him time and dies. **Meetra's Force-guided saber throw** saves him and catches the Emperor «by surprise». Then **Scourge stabs Meetra in the back** after a Force vision, and the Emperor drops the distracted Revan with one bolt. Earlier, **Revan Reborn redirects a dozen of Nyriss's bolts and burns her to ash in one exchange** (Ch24). Nyriss had just had Scourge «barely» parrying and Meetra «clearly overmatched» (L5397-5399). The book's power ladder is clear: **Emperor ≫ Revan Reborn > Nyriss ≥ Meetra ≈ Scourge > Xedrix (decrepit)**. The novel then turns Vitiate into a **Revan-fed amp** (Ch29), and gives Scourge his immortality.

---

## 1. Cast

| Character | Role in this book | Force user? | On-page combat? |
|---|---|---|---|
| Revan | Post-KOTOR Jedi, Bastila's husband. Hunts the "something" he and Malak found. Captured at Nathema (Ch15-16), freed and memories restored (Ch24), loses to the Emperor (Ch28), imprisoned in stasis and fed on (Ch29) | Yes | Yes: Basilisk fight (Ch11), tomb fight (Ch13), Nyriss (Ch24), guards (Ch27), Emperor (Ch28) |
| Meetra Surik (the Exile) | Post-KOTOR II Jedi Master. Searches for Revan via Nathema and Dromund Kaas. Killed by Scourge (Ch28); her spirit stays with Revan (Ch29) | Yes | Yes: Murtog's team (Ch21), Nyriss (Ch24), guards (Ch27), Emperor (saber throw, Ch28) |
| The Sith Emperor (Vitiate / Tenebrae) | 1,000-year-old Emperor of the Sith Empire on Dromund Kaas. Origin told in Ch15 | Yes | Yes: mind-brush (Ch23), Revan duel (Ch28), Scourge's immortality ritual (Ch29) |
| Lord Scourge | Newly made Sith Lord, a Sith pureblood with an emotion-feeding talent. Nyriss's bodyguard turned conspirator turned traitor. Made the Emperor's Wrath and immortal (Ch29) | Yes | Yes: mercs (Ch1), UDM plant (Ch4), separatists (Ch8), Xedrix (Ch10), Nyriss (Ch24), Yarri (Ch27), stab (Ch28) |
| Darth Nyriss | Dark Council sorceress for ~20 years. Leads a conspiracy against the Emperor. Killed by Revan (Ch24) | Yes | Yes (Ch24) |
| Darth Xedrix | Longest-serving Dark Councilor. Human, decrepit. Killed by Scourge (Ch10) | Yes | Yes (Ch10) |
| Bastila Shan | Revan's wife, mother of Vaner. POV in Ch17 and the Epilogue. Gives Meetra the mask | Yes | No |
| Canderous Ordo / Mandalore the Preserver | Clan Ordo. Takes the Mask on Rekkiad (Ch14) | No | Yes (Ch11, Ch13: kills Veela) |
| T3-M4 | Astromech. Recorded Scourge, repaired the Hawk, found HK, saves Meetra (Ch21), flames the Emperor (Ch28), obliterated | No (droid) | Yes |
| HK-47 | Mentioned only: left Revan's home (Ch3); T3 found his parts and Meetra rebuilt him; he went missing (Ch17) | No | No |
| Sechel | Nyriss's near-Force-null pureblood adviser/slicer. Double agent; killed by Scourge (Ch22) | Barely | No |
| Murtog | Nyriss's security chief. Killed with his team by Meetra and T3 (Ch21) | No | Yes (lost) |
| Veela | Clan Ordo chief, Canderous's wife (L2021). Turns on Revan in the tomb; killed by Canderous (Ch13) | No | Yes |
| Edric | Clan Ordo warrior on Rekkiad | No | Minor |
| Captain Yarri | Imperial Guard captain; led Revan and Malak into the trap ~3,959 BBY (L5883). Decapitated by Scourge (Ch27) | Guard (draws on the Emperor) | Yes |
| Atris | Jedi Master/Archivist (Ch5). The only named Council member who appears | Yes | No |
| Malak, Mandalore the Ultimate, Dramath I and II, Marka Ragnos, Kreia/Traya, Mission, Zaalbar, Juhani, Jolee | Memory, lore or mention only (Mandalore speaks in a memory, Ch13) | n/a | Memory only |
| Vaner, Emess, Reesa, Bress | Revan's son; daughter-in-law and grandchildren (Epilogue) | Vaner no; grandkids yes (Force skips a generation) | No |

### 1a. Version tags used in this file (a statement counts only for the version it describes)

| Tag | Era / when | What it covers in this book |
|---|---|---|
| **[MW-Revan]** | Jedi Revan, Mandalorian Wars, ~3,964-3,960 BBY | Mandalore single combat (Ch3 summary, Ch13 memory), Basilisk-war know-how, Meetra's mentor |
| **[DK1-Revan]** | Revan on his first Dromund Kaas visit, ~3,959 BBY | «overwhelmed Revan completely; it wasn't even fair to call it a battle» (L5859), dominated (L5601) |
| **[Darth Revan]** | ~3,959-3,956 BBY Dark Lord | Mask-era memories, «campaigns against the Mandalorians and the Republic» (L5349); Veela's «Revan the Butcher» (L2927) |
| **[PK-Revan]** | Post-KOTOR light-side Revan, ~3,954 BBY, memories incomplete | Prologue to Ch15 (Rekkiad, tomb, Nathema) |
| **[Captive-Revan]** | Drugged prisoner, 3,954-3,951 BBY | Ch16, Ch19, Ch24 before the mask (fear-amp on a guard, unconscious drug suppression) |
| **[Revan Reborn]** | Memories restored by the mask, "gray" knife-edge balance, ~3,951 BBY | Ch24 (Nyriss) to Ch28 (Emperor duel). **The book's peak Revan** |
| **[Stasis-Revan]** | Imprisoned, fed on, mental war; 3,951 BBY onward | Ch29 |
| **[Tenebrae/Lord Vitiate]** | Pre-Nathema, childhood to ~4,980 BBY | Ch15 lore (hearsay from Nyriss), Ch14 datacron, Ch18 archives |
| **[Nathema ritual]** | The act itself, ~1,000 years before | Ch15, Ch18, Ch25 |
| **[Emperor-base]** | Post-Nathema immortal Emperor as of 3,951 BBY, before feeding on Revan | Ch23 (mind-brush), Ch27-28 (duel) |
| **[Emperor-amp]** | The Emperor feeding on captive Revan through the stasis link, 3,951 BBY onward | Ch29 (L6189). Also the SWTOR-era Emperor |
| **[Meetra-PK2]** | Post-KOTOR II Jedi Master, ~3,951 BBY | Ch17-28 |
| **[Meetra-spirit]** | After death; did not become one with the Force | Ch29 |
| **[Scourge-mortal]** / **[Scourge-Wrath]** | Before and after the Ch29 immortality ritual | Ch1-28 / Ch29 |
| **[Nyriss-prime]** | Dark Council sorceress «in the prime of her powers» (L2607) | Ch2-24 |

**Cross-version links.** These are comparative statements from someone who knew both versions:
- **DK1-Revan → Revan Reborn:** «Revan had grown since then. He was far more powerful now» (L5859, POV Revan).
- **Emperor-base → Emperor-amp:** «Revan could feel the Emperor feeding on him, drawing on his power to sate his endless hunger» (L6189).
- **Tenebrae → Emperor:** the Nathema ritual made him «stronger than any Sith who had come before» (L3227, Nyriss's hearsay). Revan says «He's stronger now» (L5637); "now" means ~3,951, compared with the ritual-era Vitiate whose ritual needed hundreds of Sith.
- **Exile (Malachor/pre-KOTOR II) → Meetra-PK2:** «surviving the trauma of Malachor V had given her the strength to defeat Darth Traya» (L3725, POV Meetra). Revan, who knew her as his MW general: «you have become far greater than I could ever have imagined» (L5535).
- **MW/Darth Revan → PK-Revan:** «he was not the same person he was back then» (L1359). His power isn't directly compared across this gap in this book. The mask restores memories, not power per se (L5349).

### 1b. POV map (whose head the narration is in)
Prologue Revan · Ch1-2 Scourge · Ch3 Revan · Ch4 Scourge · Ch5 Revan · Ch6 Scourge · Ch7 Revan · Ch8 Scourge · Ch9 Revan · Ch10 Scourge · Ch11 Revan · Ch12 Scourge · Ch13-14 Revan · Ch15 Scourge (L3167-3301), Revan (L3309-3333) · Ch16 Scourge, Revan (L3405-3445), Scourge (L3453+) · Ch17 Bastila · Ch18 Meetra · Ch19 Scourge, Revan (L3929-3955), Scourge (L3963-4001), Revan (L4009+) · Ch20 Meetra · Ch21 Scourge, Meetra (L4465-4543), Scourge (L4551+) · Ch22 Scourge, Meetra (L4807+) · Ch23 Scourge · Ch24 Meetra, Revan (L5219-5351), Scourge (L5359+) · Ch25 Meetra, Scourge (L5557+) · Ch26 Scourge · Ch27 Revan, Scourge (L5939+) · Ch28 Revan (L5977-6019), Scourge (L6027+) · Ch29 Scourge, Meetra-spirit (L6171-6181), Revan (L6189+) · Epilogue Bastila.

---
## 2. Chapter-by-chapter plot notes

**Prologue (L63-153), Coruscant, ~3,954 BBY. POV Revan.** Revan wakes on his balcony from the third night of a storm nightmare: a stormy world, lightning, a fortress. Bastila, his wife, gently teases him. The book recaps his history. Revan and Malak tried to destroy the Republic, Malak betrayed him, and «The Council had saved his life, but they had also stripped his memories and rebuilt him as a weapon» (L111). The public story is that the Star Forge corrupted them. Revan knows better: «a threat far greater than the Mandalorians or the Star Forge» (L151).

**Ch1 (L161-373), Dromund Kaas. POV Scourge.** Scourge is a newly made Sith Lord. He was top of his Academy class and spent two years quelling rebellions on the frontier. He has been summoned to be Darth Nyriss's bodyguard. The chapter gives Imperial history: the exodus after the Great Hyperspace War and the Emperor, «the immortal and all-powerful savior who still reigned over them even after a thousand years» (L171). Sechel, a Sith pureblood with almost no Force sensitivity, meets him. Scourge chokes him into the air for answers (L301-305). Mercenaries in a speeder attack in the courtyard. Scourge senses their intent in under two seconds, Force-speeds through cannon fire, saber-throws the speeder, kills the male merc and Force-blasts the female merc into a statue (L317-347). Murtog's guards finish her.

**Ch2 (L377-603). POV Scourge.** Nyriss is a sorceress whose aged appearance is deliberate. She reveals that she hired the mercenaries herself as a test (L541), and that the Emperor «chose you» for her protection detail (L563). Assassination attempts on her are blamed on a Dark Council rival. Scourge is assigned to go with Sechel to the Hallion droid plant.

**Ch3 (L607-723), Coruscant, Dealer's Den. POV Revan.** Revan meets Canderous Ordo. The Mandalorian Wars are recapped: Mandalore the Ultimate challenged Revan to single combat and «was no match for the Jedi Order's most powerful champion» (L671). Revan hid the Mask so no one could take Mandalore's title. Revan wonders whether Mandalore's war is tied to his own disappearance. Canderous agrees to ask among the clans.

**Ch4 (L727-957), Hallion UDM plant. POV Scourge.** Scourge and Sechel run a raid. Scourge leaps the fence, saber-throws drones and holds off swarms of droids. His Force reserves run out («he could draw on it for only so long before exhaustion set in», L863). An assault droid cracks his ribs, and he kills it through its underbelly (L893-899). He is resigned to dying (L905) until Sechel cuts the power and the plant explodes.

**Ch5 (L961-1133), Jedi Temple Archives. POV Revan.** Revan is a semi-outcast. He refused retraining because he had «learned too much about the Force, both the light side and the dark» (L973). He meets Atris. The book recaps Meetra Surik: among the first to join him, his general over nearly half his troops, the one who triggered the mass-shadow generator at Malachor V. Atris says Meetra «cut herself off from the Force—permanently» (L1093). Atris is hostile: «A chalarax can't change its spots» (L1105).

**Ch6 (L1137-1281). POV Scourge.** Scourge runs Juyo drills in his heavy armor (L1147). Nyriss diagnoses his talent: he doesn't just feed on emotions, «you gorge yourself on them», and droids starve him (L1219-1223). Darth Xedrix is introduced as a suspect. The Emperor encourages Council infighting.

**Ch7 (L1285-1519), Coruscant. POV Revan.** Canderous reports that the clans are gathering on Rekkiad to hunt for Mandalore's Mask. Revan has a memory flash of a glacier with Malak. He picks a small team (himself, Canderous, T3), excludes the others and lies that Meetra is «still a Jedi» (L1407). Bastila reveals she is pregnant (L1445). He leaves «for our child» (L1483).

**Ch8 (L1523-1757), Bosthirda. POV Scourge.** Scourge leaps 10 m between rooftops, snaps four cams with TK and slaughters about 20 separatists alone (L1555-1581). Sechel produces a holo implicating Xedrix. Nyriss sends Scourge to kill Xedrix: «The greater your opponent's connection to the Force, the stronger you become» (L1741) and «Against me, you would stand no chance» (L1745).

**Ch9 (L1761-2021), Rekkiad. POV Revan.** Revan Force-pilots the Hawk through a gale after clipping a glacier (L1787) and crash-lands. Clan Ordo takes them in. Veela, the clan chief, is Canderous's wife. Revan uses the alias «Avner» (L1989).

**Ch10 (L2025-2159), Bosthirda caves. POV Scourge. ★ Scourge vs Xedrix and two acolytes.** Scourge hides in «a cloak of the dark side» (L2033). He kills both acolytes. Xedrix's lightning rips through his barrier and nearly kills him (L2093-2095). Xedrix is a drained shell, though, and his hypnosis fails (L2135). Scourge disarms him and beheads him (L2141-2151).

**Ch11 (L2163-2495), Rekkiad. POV Revan.** A memory: Revan and Malak on the plateau. The clan council: Veela says the clans tracked Revan's three-day disappearance after Malachor V (L2283). Revan "deduces" the Twin Spears location from «Republic records» (L2295). Clan Jendri attacks before dawn. Revan senses it through the Force, fires Force-guided blaster shots, then uses his saber against Basilisk war droids. He downs one and kills its rider (L2391-2439). The rest stay out of reach (L2441) until Ordo's Basilisks arrive.

**Ch12 (L2499-2717). POV Scourge.** Scourge interrogates Sechel and cuts off two of his tendrils. Nyriss reveals that she staged the assassination attempts herself (L2571). Xedrix really had been working with the separatists, but she framed the plot on him (L2647). Then her treason: «The Emperor is mad. Unchecked, he will destroy us all» (L2603). Scourge thinks he could not stand against her (L2607). She sketches the Emperor's origin (L2687-2695) and says they will go to Nathema.

**Ch13 (L2721-3011), Twin Spears tomb. POV Revan. ★ Tomb fight.** They climb the Spear. Revan Force-opens the hatch (L2819) and Force-lifts the sarcophagus lid (L2887). A **memory**: Mandalore dying at his feet says «They promised me victory... The Sith» (L2867-2877). They find the Mask and a datacron. Veela and five Ordo warriors turn on them («Revan the Butcher», L2927). Revan: «I'm no ordinary Jedi» (L2975). He deflects bolts and kills one shooter with a deflection. He hurls the lid as a grenade shield and saber-throws the last two to death (L2981-2995). Canderous kills Veela (L2993).

**Ch14 (L3013-3163). POV Revan.** The datacron holds Lord Dramath the Second's chronicle: Lord Vitiate overthrew his father and renamed Medriaas «Nathema» (L3045). Revan tells Canderous that a red-skinned Sith emissary manipulated Mandalore with the dark side (L3073-3087). Of himself and Malak: «It would take more than some persuasive words and a subtle push from the Force to turn us» (L3115). Canderous takes the Mask: «I am Mandalore the Preserver» (L3143).

**Ch15 (L3167-3333), Nathema. POV Scourge, then Revan.** On the shuttle, Nyriss tells the Tenebrae origin tale (L3193-3227, with the caveat at L3205; see §5). Nathema is a Force void. Droids are wiped (L3267), colors are leached (L3269), and Scourge is physically ill (L3283). Leaving, Nyriss detects the Hawk and ion-cannons it (L3301). Revan, flooded with memories at Nathema, finds it «difficult to draw on the Force so close to the ravaged world» (L3317).

**Ch16 (L3337-3493). POV Scourge, Revan, Scourge.** Revan is captured. Scourge's saber looks «faded» on Nathema (L3363). Nyriss: Revan and Malak found Dromund Kaas «Five years ago. The Emperor sentenced Revan to death» (L3383). She calls him «powerful and extremely dangerous» (L3391). Under drugged interrogation, «His will was strong» (L3465). Nyriss's theory: the Emperor dominates minds (the Voice, the Hand, the Guard), so Revan's broken domination could be used against him (L3479-3487). T3 escapes in the Hawk.

**Ch17 (L3501-3715), PART TWO, ~3,951 BBY. POV Bastila.** KOTOR II recap. Bastila hid with her son while Meetra defeated Traya (L3515). Meetra and T3 arrive. T3 recorded Scourge's image, spent nearly a year repairing the Hawk on Nathema, and found HK-47's parts (L3617). Meetra rebuilt HK, who later went missing (L3635). Bastila produces Revan's mask, which she took when she led the strike team, and gives it to Meetra (L3697-3711).

**Ch18 (L3717-3885), Nathema. POV Meetra.** Meetra compares Nathema with Malachor: there, «the Force was simply—gone» (L3731). The Void nearly discorporates her, and she holds on by affirming «I am Meetra Surik!» (L3803-3807). In the Imperial archives she finds Vitiate's fear-mongering speeches and the secret Dromund Kaas survey; the ritual came three days later (L3855-3871). She concludes he became «more powerful than Meetra could imagine» (L3873).

**Ch19 (L3889-4065), Nyriss's cells, three years on. POV Scourge, Revan.** Scourge marvels at Revan's strength through the drugs (L3907). Revan senses Scourge from the top of the stairs (L3929) and works on him as «a tool» (L3931). He lies about a vision to plant a dream (L4019). Then he has a real vision: Meetra is coming (L4059-4065).

**Ch20 (L4069-4337), Dromund Kaas. POV Meetra.** Meetra senses Revan on the planet (L4077) and mind-tricks a customs official (L4113). She sells gems to Larvit. Sechel takes her fee and recognizes Scourge's image.

**Ch21 (L4339-4661). ★ Meetra vs Murtog's team.** Scourge squeezes Sechel's windpipe (L4399). Sechel sets an ambush in a cave. Meetra and T3 kill Murtog and his three soldiers (L4507-4523). Scourge watches: «impressed with how easily she had dismantled Murtog and his handpicked team» (L4553). He offers an alliance: «Save your anger for the Emperor» (L4661).

**Ch22 (L4665-4889). POV Scourge, then Meetra.** Scourge tails Sechel, takes his data disks and breaks his neck (L4797). In Meetra's POV: «Revan's command of the Force was greater than that of anyone else she had ever met» (L4811). T3 decrypts the conspiracy files. Scourge proposes the plan: Nyriss «has hundreds of guards and dozens of acolytes» (L4883), so they will let the Emperor purge her.

**Ch23 (L4891-5101), the Citadel. POV Scourge.** Scourge gets an audience with the Emperor: «unfathomable power» (L4983), a «faint rippling of the air» (L5001), a voice like «a great multitude» (L5019). The Emperor promises him Nyriss's seat (L5067). A momentary mind-brush leaves Scourge «shaking like a child» (L5075). Yarri: Nyriss will be purged «Along with her entire staff» (L5091).

**Ch24 (L5105-5441). ★ Nyriss vs Scourge and Meetra, then Revan Reborn.** The Imperial Guard storms Nyriss's stronghold. Meetra, disguised as a dancer, reaches the cells. Drugged Revan has already talked a guard down with fear-amplification (L5241-5285). Scourge injects an antidote. The mask restores Revan's memories, and he collapses (L5349-5351). Nyriss arrives and nearly kills Scourge and Meetra (L5381-5415). Revan steps out of the cell, absorbs and redirects a dozen bolts and leaves «a pile of charred ash» (L5419-5425).

**Ch25 (L5445-5657), a cave hideout. POV Meetra, then Scourge.** Revan, masked, looks «a legend come to life» (L5465). He learns his son is named Vaner (L5505). Revan praises Meetra: «far greater than I could ever have imagined» (L5535). The Emperor has killed all twelve Dark Council members (L5575-5579). Revan tells the first-capture story: «he didn't even have to fight us. Instead, he broke our wills» (L5601). On the Emperor's madness: «The dark side is like a cancer inside him» (L5617). And: «I can shield my mind from being dominated» (L5651).

**Ch26 (L5661-5785). POV Scourge.** Scourge has a true vision: all three lie defeated at the Emperor's feet (L5671-5687). Revan admits the earlier vision was a lie (L5713), says «The dark side obscures my sight» (L5747), and accepts defeat as buying time: «a few decades» (L5771). On a future champion: «I may be that champion» (L5775).

**Ch27 (L5789-5971), the Citadel assault. POV Revan, then Scourge.** Meetra enters her warrior's trance (L5797). Revan balances «on the knife-edge» (L5803). Revan's self-assessment: «Alone, probably not» (L5861). Yarri leads them in; she was the traitor guard (L5883). In the fight at the throne room doors, Revan blasts the durasteel doors open, kills a guard, brings down an archway and slams the doors (L5905-5923). Scourge kills a guard and Yarri (L5963-5967). Meetra kills her two (L5969). The Emperor: «I did not expect you to return» (L5929).

**Ch28 (L5973-6103). ★★ Revan vs the Emperor; the betrayal.** Exchange by exchange in §3.7. In outline: knockbacks are traded, Revan lands a redirected bolt, Revan loses the lightning clash, T3 is obliterated, Meetra's saber-throw save, the three regroup, Scourge's vision, Scourge stabs Meetra, the Emperor bolts Revan unconscious. The Emperor TK-stops Scourge's killing blow: «Revan can still be of use to me» (L6095).

**Ch29 (L6107-6211). POV Scourge, Meetra-spirit, Revan.** Scourge, now the Emperor's Wrath (L6119), undergoes the machine-assisted immortality ritual (L6115-6167). He is left in permanent pain: «This is the price of immortality» (L6167). The Emperor steps back from invasion for «several decades» (L6145). Revan sits in a stasis cell. Meetra's spirit feeds him strength (L6175-6181). The Emperor feeds on Revan across «a dozen parsecs» (L6189). Revan uses the two-way link to amplify the Emperor's caution and fear of death (L6197-6199).

**Epilogue (L6215-6291), ~3,900 BBY. POV Bastila.** Bastila is old. Vaner Shan may run for Supreme Chancellor (L6243), and the grandchildren are Force-sensitive. Bastila still senses Revan sometimes (L6259): «I know he succeeded» (L6279).

---
## 3. Combat, Force and strategic feats, by character (FEAT = what the narration shows)

Format: **ID · Ch · L · [version]**: what happens, then the exact quote in guillemets with its line (L). *Result.* *Shows:* scaling implication.

### 3.1 Revan

**R1 · Ch3 · L671 · [MW-Revan]**: Single combat with Mandalore the Ultimate, summarized rather than shown. «Though the Mandalorian fought valiantly, in the end he was no match for the Jedi Order's most powerful champion». *Result:* Mandalore dies; Revan hides the Mask. The memory in Ch13 adds that Mandalore lay «dying at his feet» (L2867). *Shows:* narrator-level framing of MW-Revan as the Order's strongest champion. Mandalore is a non-Force-user, so this is a status feat, not a power feat.

**R2 · Ch7 · L1455 · [PK-Revan]**: Once told, he senses the unborn child. «he'd clearly sensed the life growing inside her through the Force». *Shows:* ordinary Jedi sensing. He missed it until he was told, which is a minor perception limit.

**R3 · Ch9 · L1787 · [PK-Revan]**: Force-anticipation piloting in a gale after clipping a glacier. «Using the Force, he was able to anticipate and react to the erratic flight with instantaneous precision adjustments». *Result:* the ship survives to crash-land. *Shows:* reaction precognition at piloting scale.

**R4 · Ch11 · L2341 · [PK-Revan]**: Restores stamina with the Force. «by calling on the Force to revitalize his tired limbs». *Shows:* endurance utility.

**R5 · Ch11 · L2391 · [PK-Revan]**: Danger sense wakes him before the sentries' alarm. «Subconsciously, Revan felt the danger through the Force, causing his eyes to snap open a split second before the sentries sounded the alarm». *Shows:* passive precognition.

**R6 · Ch11 · L2401 · [PK-Revan]**: Force-augmented blaster marksmanship. «drawing on the Force to augment his accuracy... took out a sniper half hidden on a ridge over twenty meters away». *Shows:* low-end, but a reminder that he fights as a gunslinger-Jedi when it suits him.

**R7 · Ch11 · L2431-2439 · [PK-Revan] ★ Basilisk.** He zigzags under a low-flying Basilisk war droid, leaps and cuts a stabilizer fin («The energy blade ricocheted off the armor plating, but not before slicing through one of the stabilizing fins», L2431). He jumps on its back and kills the pilot through the seat («he slid his lightsaber tip through the back of the seat and through the pilot's torso», L2435). He leaps clear before the crash (L2439). *Limit:* the other Basilisks hold altitude, «well out of the reach of even a Jedi's leap... it was only a matter of time until they brought Revan down» (L2441). *Shows:* the book does not make PK-Revan invulnerable to coordinated Mandalorian air assets. His blade also «ricocheted» (L2431) off the Basilisk's armor plating, a materials note, not a weakness.

**R8 · Ch13 · L2819 · [PK-Revan]**: Force-assisted strength on a frozen durasteel hatch. «calling on the Force to give him strength when he felt his muscles beginning to strain». *Shows:* minor.

**R9 · Ch13 · L2887 · [PK-Revan]**: TK lifts a heavy stone sarcophagus lid. «After a moment it began to move... as it slowly rose into the air». *Shows:* a low-end TK baseline. It is slow, which shows ease is not the point here.

**R10 · Ch13 · L2979-2997 · [PK-Revan] ★ Tomb fight (Revan + Canderous vs Veela and five Ordo warriors).**
- E1: He ignites and deflects before Veela finishes giving the order. «Revan was in motion, his lightsaber flashing to life, before the words had finished spilling from her mouth» (L2981). One deflected bolt kills a shooter (L2983).
- E2: Grenades come in. He TK-hurls the lid as a shield. «Revan reached out with the Force and hurled the heavy stone lid of the sarcophagus toward the grenades. It acted as a shield, absorbing the worst of the blast» (L2987). The blast knocks him down.
- E3: Canderous kills Veela with a heart shot (L2993).
- E4: Saber throw. «Revan used that moment to unleash a sidearm throw of his lightsaber. The blade went spinning out in a wide arcing path that ended both their lives» (L2995).
- *Result:* Revan kills three, Canderous kills three. *Shows:* standard elite-Jedi crowd control. Veela's «We killed dozens of Jedi during the war» (L2973) is hype for Mandalorians as Jedi-killers, and Revan's «I'm no ordinary Jedi» (L2975) is the counter-claim.

**R11 · Ch15 · L3301-3317 · [PK-Revan]**: Nathema suppression. Nyriss senses the Hawk first (L3285-3287) and ion-cannons it before Revan registers the threat. «It was difficult to draw on the Force so close to the ravaged world... By the time his groggy mind registered the threat they posed, it was too late» (L3317). *Shows:* a Force-void environment plus a memory flood. **Don't use this as a Nyriss > Revan sensing feat.** Revan was inside Nathema's dead zone and reeling from memories (L3309-3313), while Nyriss was outside the atmosphere where «normalcy returned» (L3285).

**R12 · Ch16 · L3465 · [Captive-Revan]**: Endures drugged torture interrogation. «His will was strong, as was his command of the Force. Even drugged to the edge of unconsciousness he was able to draw on it to help him endure the pain». *Shows:* willpower plus drug-resistant Force use (Scourge's POV assessment).

**R13 · Ch19 · L3929 · [Captive-Revan]**: Senses Scourge from the stairwell through the drugs. «in truth he had sensed his approach from the moment he began to descend the staircase... over the years he had learned a handful of tricks». *Shows:* the drugs dampen but don't null him.

**R14 · Ch19 · L3931-4051, L4059-4065 · [Captive-Revan]**: Long-term manipulation of a Sith Lord. «To Revan he was nothing more than a tool» (L3931). He plants the idea of a vision: «"The Force has shown me that my future lies beyond these walls," Revan lied» (L4019). Then a genuine vision: «Meetra was coming to rescue him» (L4065). *Result:* Scourge's eventual defection is partly Revan's doing, as Meetra suspects at L4811. *Shows:* charisma and strategy. The vision is real precognition across distance.

**R15 · Ch24 · L5241-5285, L5331 · [Captive-Revan]**: Unarmed and drugged, he uses Force fear-amplification to talk an armed guard into surrendering. «Through the veil of drugs, he strained to reach out with the Force, amplifying the other's fear and confusion» (L5241). Afterward: «he must have instinctively used the Force to keep the worst of the drug's effects at bay. But he wasn't strong enough to keep it up any longer» (L5331). *Shows:* passive drug suppression; it has a cost.

**R16 · Ch24 · L5349-5351 · [Captive → Reborn]**: The mask restores his memories. «In an instant, all his lost memories came flooding back to him... In his weakened state it was too much to take». *Shows:* a version transition, from this point Revan Reborn. **It restores memory, not new power.** But the next scene is his strongest feat.

**R17 · Ch24 · L5417-5425 · [Revan Reborn] ★★ Nyriss's lightning absorbed and returned.**
- He steps out masked and hooded (L5417). «A dozen bolts of lightning sprang from Nyriss's hand... Instead of leaping back into the cell to avoid the deadly attack, Revan stepped forward to intercept it» (L5419).
- «He drew the bolts of lightning into his waiting grasp, channeling them away from their intended targets and absorbing their power» (L5421).
- «"I am Revan reborn," he said to Nyriss. "And before me you are nothing."» (L5423).
- «Revan unleashed the power of her own attack against her. She tried to throw up another Force shield, but the bolts ripped it apart and continued on unabated. The lightning engulfed her, the intense heat consuming her instantly, leaving only a pile of charred ash» (L5425).
- *Context:* he was freshly antidoted and had just collapsed from the memory flood (L5351). This was **the killing blow Nyriss had charged for Scourge and Meetra** (L5411). Meetra: «He had easily bested Darth Nyriss» (L5471).
- *Shows:* a one-exchange stomp of a Dark Councilor «in the prime of her powers» (L2607), who had just beaten Scourge and Meetra together. This is the cleanest gap-setter in the book: Revan Reborn ≫ Nyriss ≳ Meetra/Scourge.

**R18 · Ch25 · L5651 · [Revan Reborn] (claim)**: «I can shield my mind from being dominated by his will, and I can show you how to do the same». It is partly validated in Ch28 E2 (he is ready for the domination and counters it), and in Ch29 he holds his secrets against the Emperor's probing (L6195).

**R19 · Ch27 · L5899-5923 · [Revan Reborn] ★ Imperial Guard at the throne room.**
- A side kick (L5899).
- «blasting them wide open with the power of the Force» (durasteel doors, L5905).
- A somersault over an electrostaff guard (L5909).
- Force push: «Instead of sending him flying, it only staggered him back half a step—this close to the Emperor they were sworn to protect, the guards were able to draw on his power to protect themselves» (L5911).
- Feint and throat kill (L5913-5915).
- «ripped the vaulted stone archway in the ceiling above them free from its setting» (L5919).
- «slammed the durasteel doors shut» (L5923).
- *Shows:* good mid-tier TK. The Guard's resistance comes from proximity to the Emperor, an *Emperor* amp feat (V5).

**R20 · Ch28 · [Revan Reborn] ★★ vs the Emperor.** See §3.7.

**R21 · Ch28 · L6015-6019, L6043 · [Revan Reborn]**: Force healing under duress, not fast enough. «The healing properties of the Force were powerful, but Revan's wounds were severe and he needed more time» (L6019). After Meetra's save, he stands and calls his saber to his hand (L6043). *Shows:* resilience. He fought on after the lightning clash had melted his face to the mask (L6003).

**R22 · Ch29 · L6173-6205 · [Stasis-Revan] ★ The mental war.** He is physically paralyzed in stasis («even time itself could not touch him», L6173). He resists the Emperor's probes: «mentally he was strong enough to wage war against the Emperor, guarding and protecting his secrets for however long it might take» (L6195). He turns the link around: «The connection between them went both ways... he could subvert their relationship by planting seeds in the Emperor's thoughts» (L6197). He shapes the Emperor's policy: «Revan played on the Emperor's caution and patience... He augmented his irrational fear of death» (L6199). *Limits:* he is sustained by Meetra's spirit (L6179), and «it was inevitable that one day the Emperor would win their endless battle of wills» (L6205). *Shows:* top-tier mental resistance and influence against a planet-eater, and the source of the Emperor's amp.

**R23 · Ch25 · L5601-5603 · [DK1-Revan] (feat of will, told in flashback)**: He was dominated without a fight, but «Our wills were stronger than he thought; our minds twisted and perverted his instructions until we thought we were acting of our own accord... partially freeing us from his control». *Shows:* DK1-Revan lost instantly, and still partially broke a domination the Emperor uses on his whole inner circle (L3487). Malak shared the feat.

### 3.2 The Sith Emperor (Vitiate / Tenebrae)

**V1 · Ch15 · L3193-3227 · [Tenebrae/Lord Vitiate] ★ Origin (HEARSAY: Nyriss says «I cannot guarantee the truth of this story», L3205).**
- Born with void-black eyes; «his voice carried a weight and power that should not come from a child» (L3193).
- As a child: «He snapped his father's neck with a mere thought, killing him instantly... Tenebrae made her suffer for months» (L3197).
- At ten, against his Sith Lord father: «When they met face-to-face, Tenebrae proved the stronger. Only ten years old, he stripped his father of his power and his mind» (L3211).
- At thirteen: «Marka Ragnos granted him the title of Lord Vitiate» (L3215).
- The summons: «what could one man do against a hundred Sith Lords?» (L3221); «He dominated their minds, crushed their resistance... Lord Vitiate devoured them» (L3225).
- The planet: «Every man, woman, and child on Nathema died that day... every living being touched by the Force was consumed... Lord Vitiate sacrificed millions... stronger than any Sith who had come before» (L3227).
- *Shows:* child prodigy level. He dominates a Sith Lord at ten, dominates 100+ Sith Lords at once, and drains a planet. Its reliability is boosted by V2, the physical evidence, and by Ch18's archive (the Dromund Kaas survey followed by the ritual three days later, L3871).

**V2 · Ch15, Ch16, Ch18 · [Nathema ritual], aftermath after ~1,000 years ★ Physical corroboration.**
- «He wasn't feeling the Force» (L3239).
- «You feel the chill of the Void... here it has been stripped away» (L3257).
- Droids: «even their memory cores were completely wiped out» (L3267).
- «as if the colors had been leached out» (L3269).
- Scourge sick (L3283). Meetra «felt like she had been punched in the gut» (L3741).
- Sabers dim: «the crimson blade appeared faded» (L3363); «the dim and washed-out appearance of the glowing blade» (L3769).
- Revan's Force use is hampered (L3317).
- Meetra nearly discorporates: «her physical body discorporating into trillions of subatomic particles» (L3803).
- Compared with Malachor: «Here, however, the Force was simply—gone» (L3731).
- *Shows:* a **planetary Force-annihilation event persisting for a millennium**, worse than Malachor V's wound, per the POV of Meetra, who made Malachor. This is the strongest on-page proof of [Nathema ritual]-scale power, even if the biography in V1 is hearsay.

**V3 · Ch14 · L3073-3087, Ch13 L2869-2877 · [Emperor-base] strategic ★**: Through an emissary, he manipulated Mandalore the Ultimate into the Mandalorian Wars as a test. «They used me and my people to test the Republic's strength» (L2873). «The Sith used the power of the dark side to manipulate him» (L3087). *Shows:* galaxy-scale long-game manipulation. The war that made Revan was the Emperor's probe.

**V4 · Ch25 · L5597-5603 · [Emperor-base] vs [DK1-Revan] + Malak ★ First meeting, summarized**: «We underestimated his power. When we confronted him, he didn't even have to fight us. Instead, he broke our wills. He dominated our minds, turning us into puppets» (L5601). Revan's later recollection: «In their last meeting he had overwhelmed Revan completely; it wasn't even fair to call it a battle» (L5859). *Limit:* «he underestimated us, as well. Our wills were stronger than he thought» (L5603). The partial freedom meant the Emperor «assumed we had failed» (L5607). *Shows:* a 2-on-1 mental stomp of DK1-Revan + Malak with no combat, then a long-term failure of control. DK1-Revan is pre-Star Forge, pre-Darth peak and pre-gray-balance, so don't apply this directly to Revan Reborn (see the cross-link at L5859).

**V5 · Ch16, Ch27 · L3479-3487, L5849, L5911 · [Emperor-base] passive empowerment**: He dominates «the Emperor's Voice, the Emperor's Hand, the soldiers in the Imperial Guard» (L3487). The Guard «had a connection with the Emperor, allowing them to draw strength from the dark side» (L5849), and near him Revan's push only staggers one (L5911). *Shows:* a standing mind network plus power-sharing to elite troops.

**V6 · Ch23 · L4983-5075 · [Emperor-base] ★ Audience and mind-brush.**
- «a testament to the Emperor's unfathomable power» (L4983, guards don't even disarm visitors).
- «Scourge could feel the power of the dark side emanating from him with such intensity that it caused a faint rippling of the air» (L5001).
- «eyes were as black as the Void itself» (L5009).
- The voice: «almost as if a great multitude were speaking his words in perfect symphony» (L5019).
- Scourge's spirit-prison theory (L5021, speculation).
- «a being unique in the galaxy» (L5047).
- Remote telepathy: «the Emperor was somehow communicating with someone outside the room» (L5053, impression).
- **Mind-brush:** «Scourge cried out in anguish as the Emperor's mind brushed against his, then he collapsed to the floor, shaking like a child. The touch lasted less than a second» (L5075).
- *Limit:* «he was not omniscient» (L4989). He never detected Nyriss's decade-long conspiracy (L4845) and believed Scourge's lie in Ch28 (L6121).
- *Shows:* a passive aura and a sub-second incapacitating mental contact on a Sith Lord.

**V7 · Ch25 · L5575-5579 · [Emperor-base] strategic**: «All twelve members of the Dark Council... The other nine were called together in the hours before the attack to meet with the Emperor at his citadel. None of them left alive». *Shows:* nine Dark Councilors dead at the citadel within hours. The text never says he killed them personally, so treat it as a likely but unconfirmed personal-power feat.

**V8 · Ch28 · [Emperor-base] ★★ vs Revan Reborn + T3, then + Meetra and Scourge.** See §3.7.

**V9 · Ch28 · L6093 · [Emperor-base]**: He stops Scourge's killing blow with TK. «it suddenly stopped as if an invisible and impossibly strong hand had seized his wrist». *Shows:* casual, precise TK on a Sith Lord.

**V10 · Ch29 · L6111-6167 · [Emperor-base] sorcery ★ Immortality ritual for Scourge**: Done with machinery: «Dozens of wires and IV tubes... generators... vats filled with a strange green bubbling liquid» (L6115). «Let the spark of eternal life ignite within you!» (L6133); «Feel your mortality as it is stripped away» (L6149). The side effect is permanent pain: «Everything has a cost... This is the price of immortality» (L6167). *Shows:* he can grant immortality to others. It needs technical support and is imperfect.

**V11 · Ch29 · L6173-6191 · [Emperor-amp] ★★ The feeding link.** The stasis prison is Sith sorcery: «whatever arcane Sith sorcery the Emperor had used to bind Revan in his cell» (L6177). «Revan could feel the Emperor feeding on him, drawing on his power to sate his endless hunger. Though the two were physically separated by a dozen parsecs, there was still an unbreakable mental link, fashioned by the Emperor and sustained by the infernal machines powering the cell» (L6189). «to leach off his fallen adversary's power to sustain his own twisted existence» (L6191). *Shows:* **the amp.** From 3,951 BBY onward the Emperor has Revan's power on top of his own. *Limit:* the link is two-way, and Revan uses it to steer him (L6197-6199). The book doesn't quantify the boost.

### 3.3 Lord Scourge

**S1 · Ch1 · L301-305 · [Scourge-mortal]**: A choke-lift. «his body was lifted slowly up into the air by an invisible hand».

**S2 · Ch1 · L317-321 · [Scourge-mortal]**: Senses intent, then Force speed. «All of this, from Scourge's first awareness of the speeder to confirmation of its hostile intent, took less than two seconds» (L319). «Moving with the blinding speed of the Force» (L321).

**S3 · Ch1 · L325 · [Scourge-mortal]**: A saber throw clips the speeder and returns «to Scourge's outstretched hand».

**S4 · Ch1 · L339-347 · [Scourge-mortal]**: Kills the male merc. Then he feeds on fear: «he drew upon his opponent's fear, adding it to his own passion and further amplifying the power» (L345). A Force wave: «struck the woman square in the chest. The impact lifted her off her feet and sent her flying» (L347).

**S5 · Ch4 · L765-907 · [Scourge-mortal] ★ UDM plant.**
- Clears a 3 m electrified fence (L765).
- «he could draw on it for only so long before exhaustion set in» (L863).
- TK-knocks drones into a molten vat (L885).
- Ribs cracked by an assault droid: «he knew at least one of his ribs had been cracked» (L895). Kills it through the underbelly (L899).
- «he was nearing the point of total exhaustion» (L905).
- *Shows:* finite reserves against droids (the gift doesn't work on them, L1223). This is the low end of his range.

**S6 · Ch6 · L1147 · [Scourge-mortal]**: Juyo drills. «The weapon moved so fast that it was nothing but a blur, but each strike was precise and controlled».

**S7 · Ch8 · L1555-1581 · [Scourge-mortal] ★ Separatist massacre.** A 10 m leap: «nearly ten meters» (L1555). TK snaps four cams (L1557). «Violent bursts of the Force picked his victims up and tossed them around like rag dolls, breaking bones and shattering skulls» (L1575). He senses hidden people: «Scourge didn't need to see them to hunt them down» (L1581). *Shows:* he slaughters about 20 armed civilians-turned-fighters at a fear-feeding high.

**S8 · Ch10 · L2033-2151 · [Scourge-mortal] ★ vs Darth Xedrix + two acolytes.**
- E0: Stealth. «wrapped in a cloak of the dark side that both made him invisible to the Force» (L2033).
- E1: Ambush leap. Xedrix's blade «materialized seemingly out of nowhere to intercept the blow» (L2041). In the flurry, Xedrix is «too controlled, and it felt more like fighting a droid» (L2043).
- E2: The acolytes. He dodges and parries, rolls between them (L2053), boot-stomps the female to death and kills the male with a thrown saber: «the glowing blade easily sliced through his palms and throat» (L2073).
- E3: Xedrix's lightning. «The bolts arced through the air, ripping through the shield to engulf Scourge in electric agony» (L2093). «He fell to the floor, curled into himself, his skin blistered and burned» (L2095). He gets up anyway (L2099).
- E4: Xedrix is spent. «The blast of lightning had taken everything the old man had in reserve... he lacked the strength even for that desperate gambit» (L2135).
- E5: Finish. «Scourge used his own blade to slap it aside with ease» (L2141). He beheads him (L2151).
- *Shows:* he beats a decrepit Dark Councilor, but the lightning that broke through his barrier nearly ended it. Nyriss framed Xedrix as «a hollow shell» (L1745). Low-tier Council.

**S9 · Ch12 · L2537-2555 · [Scourge-mortal]**: A torture interrogation (severing tendrils). Not a power feat.

**S10 · Ch15 · L3283 · [Scourge-mortal]**: Nathema makes him physically ill: «having it stripped away had left him physically ill».

**S11 · Ch21 · L4399, Ch22 L4797 · [Scourge-mortal]**: «casually reaching out with the Force to give Sechel's windpipe a quick squeeze» (L4399). He kills Sechel by hand: «There was a surprisingly loud pop» (L4797).

**S12 · Ch23 · L5075 · [Scourge-mortal]**: Floored by the Emperor's sub-second mind-brush (V6). This is a durability limit.

**S13 · Ch24 · L5393-5415 · [Scourge-mortal] ★ vs Nyriss, with Meetra.** See §3.6.

**S14 · Ch27 · L5939-5967 · [Scourge-mortal] ★ vs Captain Yarri + an Imperial Guard.** «Scourge was an expert swordsman; at the Academy even the instructors had been reluctant to face him» (L5939). «Captain Yarri's skill with her electrostaff was impressive, but ultimately she was no match for a Sith Lord» (L5941). Yarri's staff clips his shoulder (L5947), and he switches hands, «The move was dangerous» (L5949). «A four-move sequence overwhelmed Yarri» (L5963). The guard gets «a quick death» (L5963). He decapitates Yarri (L5967). *Shows:* elite duelist against Emperor-boosted Guards (V5).

**S15 · Ch28 · L6059-6069 · [Scourge-mortal] ★ The crux vision and the backstab**: «a million possible futures flickered through his mind simultaneously» (L6061). «he saw the Emperor lying defeated at the feet of a powerful Jedi—but that Jedi was neither Revan nor Meetra» (L6067). «he slid the blade of his lightsaber between her shoulders» (L6069). *Shows:* precognition (his second true vision; the first is Ch26, L5687). **The kill is a backstab of an ally who wasn't watching him. It is not a duel result.**

**S16 · Ch29 · L6133-6167 · [Scourge-Wrath]**: Survives the immortality ritual, then stands through constant agony: «Focusing his will, he managed to still the convulsions racking his body» (L6159). *Shows:* he is immortal (agelessness via the ritual), with permanent pain that will fade to numbness (L6163). This sets up his SWTOR version.

### 3.4 Meetra Surik (the Exile)

**M0 · Ch17-18 · L3515, L3725 · [Meetra-PK2] background (summary)**: She regained the Force and defeated Traya. «surviving the trauma of Malachor V had given her the strength to defeat Darth Traya and her followers» (L3725, POV Meetra). The book doesn't show it.

**M1 · Ch18 · L3803-3807 · [Meetra-PK2] ★ Withstands the Nathema Void**: «The affirmation of her own existence seemed to push the Void back, at least for the moment. But Meetra knew she couldn't hold out against it much longer» (L3807). *Shows:* her Force-bond nature (the wound/Void affinity from KOTOR II) works against her here, since the Void «was trying to fill itself with her energy» (L3803). It is a resistance feat with clear limits.

**M2 · Ch18 · L3851 · [Meetra-PK2]**: Force meditation replaces food and sleep for days: «drawing on the Force to replenish her fading stores of energy and mental focus».

**M3 · Ch20 · L4077 · [Meetra-PK2]**: Planetary-range sensing of Revan on landing: «she knew with a sudden and unshakable certainty that Revan was somewhere on this world».

**M4 · Ch20 · L4113 · [Meetra-PK2]**: A mind trick on a customs official: «reaching out with the Force to give the woman's psyche a gentle nudge».

**M5 · Ch21 · L4465-4523 · [Meetra-PK2] + T3 ★ vs Murtog and three armored soldiers (night-vision, ambush).**
- E0: «Meetra was wary of a trap even before she felt the warning premonitions through the Force» (L4465). She senses them in the dark (L4487).
- E1: T3's headlamp «overloaded the night-vision goggles of her adversaries, temporarily blinding them» (L4507).
- E2: «She snapped off a quick back handspring to dodge the blasterfire, then reversed her direction with a flying leap» (L4513). The blade goes through a cortosis-suit joint and kills him (L4515).
- E3: Force push kill: «The woman flew backward, lifted off her feet and hurtled across the cave by the Force until she slammed into the rock face of the far wall. She slid to the ground, dead» (L4517).
- E4: Deflects bolts (L4519). T3's flamethrower kills one (L4521).
- E5: «a vicious two-handed slash of her blade that cleaved through the plates of the woman's armor» (L4523).
- *Assessment (POV Scourge):* «impressed with how easily she had dismantled Murtog and his handpicked team» (L4553).
- *Shows:* clean elite-Jedi work against non-Force-users. It's comparable to Scourge's S7 massacre, with better efficiency and no emotion-feeding.

**M6 · Ch24 · L5393-5415 · [Meetra-PK2] ★ vs Nyriss, with Scourge.** See §3.6. Her key lines are «The Jedi was clearly overmatched; though she managed to hold her ground, she was forced down to one knee» (L5399) and the barrier-through lightning (L5407).

**M7 · Ch27 · L5795-5797, L5899-5969 · [Meetra-PK2] ★ vs two Imperial Guards**: The warrior's trance: «a perfect conduit for the Force, an incorruptible weapon of light» (L5797). She charges two door guards. «Ordinary soldiers would have been chopped down before they could even draw their weapons, but the Imperial Guard were not so easily felled» (L5901). They force her back with coordinated attacks (L5903, L5943). She finishes both: «she, too, had just finished off her opponents» (L5969). *Shows:* she is on par with Scourge's guard fight (S14). Both take a few exchanges to kill two Emperor-boosted Guards.

**M8 · Ch28 · L6033-6039 · [Meetra-PK2] ★★ The saber-throw save on the Emperor**: «she hurled her lightsaber with a wild sidearm throw, guiding it with the Force so that it spiraled end-over-end to intercept the descending blade, knocking it from the Emperor's grasp» (L6035). «Meetra's trick had caught him by surprise. Scourge realized that if she had aimed at the Emperor instead of the blade, she could have ended his life» (L6037, POV Scourge). She recalls her saber (L6039) and stands between the Emperor and Revan (L6043). *Shows:* the only on-page moment where the Emperor is **caught flat-footed**, and he then shows «hesitation and uncertainty» evaluating her (L6041). Scourge's counterfactual is an opinion. He presumes a surprise hit would have killed, and the Emperor's Force-cocoon against T3 (L6005) suggests he can react to attacks he senses.

**M9 · Ch28 · L6069-6071 · [Meetra-PK2]**: Killed instantly by Scourge's backstab, «dead before she hit the floor». **Not a combat loss**: her attention was on the Emperor, and Scourge was an ally.

**M10 · Ch29 · L6175-6181 · [Meetra-spirit] ★**: «When she had died, she had not become one with the Force» (L6175). «her power trickling through the energy barrier that surrounded him» (L6177). «As the Emperor fed off him, Meetra was allowing Revan to feed off her» (L6179). *Shows:* a Force-ghost-like persistence (without the light-side ghost technique being named). Her power penetrates the Emperor's sorcerous barrier, though she «couldn't speak with him» (L6177). This is part of how Revan holds out (R22).

### 3.5 Darth Nyriss, Xedrix, the Imperial Guard, T3, Canderous, others

- **N1 · Ch2 · L453-457 · [Nyriss-prime]**: Her aged appearance «was intentional» (L457). Her sorcery cost her «youth and vitality» (L453, Scourge's speculation).
- **N2 · Ch15 · L3285-3301 · [Nyriss-prime]**: Senses Revan off-planet the moment the Force returns (L3285-3287) and ion-cannons the Hawk (L3301). (See the caveat at R11.)
- **N3 · Ch24 · L5381 · [Nyriss-prime]**: Lightning kills two of her own guards instantly: «turned into charred and smoking husks».
- **N4 · Ch24 · §3.6**: Beats Scourge + Meetra together, then is ashed by Revan in one exchange.
- **X1 · Ch10 · L2041-2135 · Xedrix (decrepit)**: Blocks an ambush strike. His lightning rips through Scourge's barrier. Too drained to hypnotize afterward.
- **G1 · Ch27 · L5901, L5911, L5947 · Imperial Guard**: Electrostaffs parry sabers (L5901). Pushes barely move them near the Emperor (L5911). Yarri clips Scourge (L5947).
- **T1 · T3-M4**: Slices; boosts sensors (Ch9). Repairs the Hawk alone over about a year on Nathema (L3615). Records Scourge. Rebuilds HK's parts (with Meetra, L3617-3623). Blinds Murtog's team and flames a soldier (L4507, L4521). Decrypts Sechel's disks in 1.5 hours (L4843). Kills a guard (L5899). **Flames the Emperor, forcing him into a Force cocoon** (L6005). Then: «T3 never stood a chance. The little droid exploded into a million pieces» (L6011).
- **C1 · Canderous**: Rides a Basilisk in battle (Ch11). Kills Veela and two others in the tomb (L2983, L2993). Takes the Mask (L3143).
- **H1 · HK-47**: No feats; offstage (L617, L3617-3635).

### 3.6 ★ DUEL: Darth Nyriss vs Lord Scourge + Meetra Surik, then Revan Reborn (Ch24, L5381-5425)

| # | Exchange | Quote | Result |
|---|---|---|---|
| 1 | Nyriss kills two guards on the stairs with lightning | «They barely had time to scream before they were turned into charred and smoking husks» (L5381) | Lightning lethality established |
| 2 | Taunt | «Another Jedi?» (L5389); «But neither will any of you» (L5391) | — |
| 3 | A lightning burst; both dive clear | «in doing so they gave Nyriss the early advantage» (L5393) | Nyriss takes the initiative |
| 4 | Leap into the middle; saber flurry on both at once | «she moved with the all the speed and ferocity of a dark side warrior in her prime» (L5395, sic «the all the») | Both on the defensive |
| 5 | Scourge | «Scourge barely managed to parry the first wave of her assault, unable to even think about countering» (L5397) | Scourge staggered |
| 6 | Meetra | «The Jedi was clearly overmatched; though she managed to hold her ground, she was forced down to one knee» (L5399) | Meetra nearly cut down (L5401) |
| 7 | Scourge's Force blast vs Nyriss's barrier | «An ordinary foe would have been thrown clear across the room, but Nyriss instinctively threw up a Force barrier» (L5403) | Meetra escapes |
| 8 | Nyriss's wave | «It picked Scourge up and tossed him head-over-heels» (L5405) | Scourge dazed |
| 9 | Lightning on Meetra | «Like Nyriss, she threw up a barrier to save herself from the worst of it, but she was still knocked from her feet» (L5407) | Meetra down |
| 10 | Nyriss: «Did you think I would be as easy to defeat as Xedrix?» (L5409) | Charging the finisher | «Nyriss was too powerful; her command of the dark side was too strong» (L5411, POV Scourge) | Both helpless |
| 11 | Revan Reborn intercepts | «A dozen bolts of lightning» absorbed (L5419-5421) | — |
| 12 | Redirected | «the bolts ripped it apart and continued on unabated... leaving only a pile of charred ash» (L5425) | **Nyriss dead in one exchange** |

*Verdict reading:* Nyriss mid-diffs Scourge + Meetra 2v1, and Revan Reborn low-diffs Nyriss. No real caveats for Meetra or Scourge: both were armed, rested enough, and fighting together. Both get barriers up (L5403, L5407), so their basic defenses held; they just couldn't keep up with her.

### 3.7 ★★ DUEL: Revan Reborn vs the Emperor [Emperor-base] (Ch28, L5977-6103)

Setup: T3 is with Revan; Meetra and Scourge are still at the doors fighting Guards (L5943-5969). The Emperor has been surprised by Revan's return: «I did not expect you to return» (L5929).

| # | Exchange | Quote | Result / scaling |
|---|---|---|---|
| E1 | The Emperor's opener: an energy wave timed «At the last possible instant» | «unleashed a wave of energy that swept Revan off his feet and sent him flying backward» (L5979) | Revan rolls with it and gets up (L5981). The Emperor isn't even moving: «it was as if he hadn't even moved» (L5983) |
| E2 | Domination attempt | «The Emperor was trying to crush his will: to dominate and enslave his mind as he had before. This time, however, Revan was ready» (L5983) | Revan counters with raw light+dark: «letting both the light and the dark side flow through him like twin rushing rivers... he released it in its purest form» (L5985) |
| E2b | The flash | «The energy unleashed was powerful enough to send Revan staggering. The Emperor, unprepared and with much of his strength diverted to his effort to dominate Revan's mind, was sent flying backward» (L5987) | **Revan knocks the Emperor down.** Caveat in the text: the Emperor was «unprepared» and had «much of his strength diverted» |
| E3 | Emperor bolt from one knee | «his hands flew forward as he hurtled a bolt of dark side lightning» (L5989); «Revan intercepted the bolt with the blade of his lightsaber, though the impact stopped his charge dead in its tracks» (L5991) | Revan blocks, but is halted |
| E4 | Three bolts | «Revan batted the first aside with his lightsaber, ducked the second, then deflected the third back» (L5993) | — |
| E4b | The redirected hit | «It struck the Emperor in the chest, sending him sliding several meters back on the floor. For the first time the Sith's emotionless veneer cracked as he let out a primal hiss of hate» (L5995); «his robes smoking and singed» (L5997) | **The Emperor hit by his own lightning; cosmetic damage only** |
| E5 | The storm; Revan tries the Nyriss trick | «A dozen bolts of purple lightning arced from the Emperor toward him. Revan tried to draw them in and contain them, but the Emperor was infinitely more powerful than Darth Nyriss had ever been» (L6001) | **Decisive.** «the flesh of his face melting and sticking to the superheated metal of his mask as the Emperor poured more and more power into him» (L6003) |
| E6 | T3's flamethrower | «At the last instant the Emperor cocooned himself in the Force to save himself from being incinerated, breaking his focus on Revan» (L6005) | Revan collapses, «burned but still alive» (L6007) |
| E7 | T3 obliterated | «A tremor rippled through the air as the Emperor unleashed the full power of the Force against the defenseless droid» (L6009); «exploded into a million pieces» (L6011) | — |
| E8 | Revan heals, too slowly; the Emperor takes Revan's saber | «he needed more time to restore his strength. Helpless» (L6019) | The 1v1 is lost. **Revan is beaten in about 8 exchanges, with only T3's intervention keeping him alive** |
| E9 | Meetra's throw | «knocking it from the Emperor's grasp» (L6035); «Meetra's trick had caught him by surprise» (L6037) | The Emperor steps back. «hesitation and uncertainty» (L6041) |
| E10 | Regroup, 3 on 1 | Revan: «United, we are stronger than even you» (L6055). Emperor: «That remains to be seen» (L6057) and «Then he will die with you, as well» (L6053) | Unresolved standoff |
| E11 | Scourge's betrayal | «dead before she hit the floor» (L6071) | — |
| E12 | One bolt to the distracted Revan | «The distraction gave the Emperor the opportunity he needed, and he unleashed another blast of lightning into the Jedi's chest» (L6071); «Revan screamed once then collapsed to the ground, unconscious» (L6073) | **Revan defeated** (already badly injured from E5) |
| E13 | The Emperor stops Scourge's coup de grâce | «as if an invisible and impossibly strong hand had seized his wrist» (L6093); «Revan can still be of use to me» (L6095) | Revan taken alive |

**Readings.**
- (a) **Revan Reborn 1v1 loses, but it's a fight, not a stomp.** It contrasts with DK1, where «it wasn't even fair to call it a battle» (L5859). Revan scores a knockdown (under the «unprepared» caveat, L5987) and a redirected chest hit that only singes. Then the lightning clash, his signature counter against Nyriss, fails against an output «infinitely more powerful» than hers (L6001).
- (b) **The Emperor never takes real damage.** His defensive cocoon stops the flamethrower, and the redirected bolt only singes. His only "losses" are knockback, surprise and a few seconds of hesitation.
- (c) **The 3-on-1 is never fought.** Revan's POV beforehand: «With the combined strength of Meetra, Scourge, and even T3, however, he believed they stood a real chance of victory» (L5861). Afterward, Scourge thinks «the Emperor would have won regardless» (L6129), and Revan thinks «They might have lost anyway, but they also might have defeated the Emperor» (L6201). Scourge's Ch26 vision showed all three beaten (L5671-5687). That vision came **before** the betrayal decision, and it is ambiguous whether it was the future "with" the betrayal. The Ch28 million-futures vision shows Revan's «triumph and defeat in the throne room» both as possibilities (L6061). **Net:** the team-up was a live chance, the Emperor was favored, and the book deliberately leaves it open.
- (d) In-fight diff: **high diff for the Emperor vs a lone Revan is not supported**. The Emperor took no damage, so call it **mid diff** on the narration. Revan's tactics (E2, E4) forced him to engage, and T3's flames forced a defensive cocoon.

---
## 4. Statements and hype (STATEMENT): curated, per character

These are the scaling-relevant statements, with speaker, POV and version. **Every** paragraph naming each character is in Appendix Q.

### 4.1 About Revan
| # | Ch · L | Speaker / POV | Version | Quote |
|---|---|---|---|---|
| RS1 | Pro · L151 | Revan POV | PK about past | «a threat far greater than the Mandalorians or the Star Forge» |
| RS2 | Ch3 · L665 | Canderous | MW-Revan | «You and your followers turned the entire tide of the war against us. Eventually you killed Mandalore» |
| RS3 | Ch3 · L671 | narration | MW-Revan | «no match for the Jedi Order's most powerful champion» |
| RS4 | Ch5 · L973 | narration (Revan POV) | PK | «Revan had learned too much about the Force, both the light side and the dark, to take instruction like some common Padawan» |
| RS5 | Ch7 · L1359 | narration | PK vs MW | «he was not the same person he was back then. He no longer clung to the simplistic ideals of right and wrong or good and evil» |
| RS6 | Ch13 · L2927 | Veela | Darth/MW | «To throw your lot in with Revan the Butcher?» |
| RS7 | Ch13 · L2957 | Canderous | PK | «You know Revan's reputation... And mine» |
| RS8 | Ch13 · L2975 | Revan | PK | «I'm no ordinary Jedi.» |
| RS9 | Ch16 · L3391 | Nyriss | PK | «He is powerful and extremely dangerous» |
| RS10 | Ch16 · L3465 | Scourge POV | Captive | «His will was strong, as was his command of the Force» |
| RS11 | Ch19 · L3907 | Scourge POV | Captive | «The Jedi's command of and connection to the Force was unlike anything Scourge had sensed in anyone else. Even though Revan was constantly drugged, it was impossible not to sense his strength» |
| RS12 | Ch19 · L3907 | Scourge POV | Captive / the Jedi as a class | «With men and women like Revan in their ranks, it was easy to see how they had beaten back the Sith invasion a thousand years earlier» |
| RS13 | Ch22 · L4811 | Meetra POV | Captive (her overall impression) | «Revan's command of the Force was greater than that of anyone else she had ever met» |
| RS14 | Ch24 · L5423 | Revan | Reborn | «I am Revan reborn... And before me you are nothing.» |
| RS15 | Ch24 · L5437 | Scourge POV | Reborn | «If anyone had the strength to stop the Emperor, it was this man.» |
| RS16 | Ch25 · L5465 | Meetra POV | Reborn (masked) | «indomitable, invincible—a legend come to life» |
| RS17 | Ch25 · L5471 | Meetra POV | Reborn | «He had easily bested Darth Nyriss, but the Emperor was a much greater opponent» |
| RS18 | Ch27 · L5803 | Revan POV | Reborn | «He had learned to balance on the knife-edge between them, drawing on both the light and dark sides for strength» |
| RS19 | Ch27 · L5859-5861 | Revan POV | DK1 → Reborn link | «Revan had grown since then. He was far more powerful now, but was he a match for the Emperor? Alone, probably not.» |
| RS20 | Ch27 · L5875 | Revan POV | Reborn | «Revan knew he couldn't go toe-to-toe with the Emperor by himself for very long» |
| RS21 | Ch28 · L6001 | narration (Revan POV) | Reborn vs Emperor-base | «the Emperor was infinitely more powerful than Darth Nyriss had ever been» |
| RS22 | Ch29 · L6195 | narration | Stasis | «mentally he was strong enough to wage war against the Emperor» |
| RS23 | Ch29 · L6201 | Revan POV | Reborn + team | «They might have lost anyway, but they also might have defeated the Emperor» |
| RS24 | Ch29 · L6129 | Scourge POV | team | «the Emperor would have won regardless» |
| RS25 | Pro · L111 | narration | Darth Revan, after Malak's betrayal | «Revan had been captured by the Jedi Council, barely alive, his body and mind shattered» |

### 4.2 About the Emperor / Vitiate
| # | Ch · L | Speaker / POV | Version | Quote |
|---|---|---|---|---|
| VS1 | Ch1 · L171 | narration (Imperial belief) | Emperor | «the immortal and all-powerful savior who still reigned over them even after a thousand years» |
| VS2 | Ch2 · L443 | Scourge POV, rumor | Emperor | «It was rumored that the perpetual storms of Dromund Kaas were the result of the Emperor performing one of these rituals» |
| VS3 | Ch12 · L2603 | Nyriss | Emperor | «The Emperor is mad. Unchecked, he will destroy us all.» |
| VS4 | Ch12 · L2695 | Nyriss | Nathema | «he used the dark side to conquer death and make himself immortal» |
| VS5 | Ch15 · L3205 | Nyriss | Tenebrae | «I cannot guarantee the truth of this story» |
| VS6 | Ch15 · L3227 | Nyriss | post-ritual | «stronger than any Sith who had come before» |
| VS7 | Ch16 · L3483 | Nyriss | Emperor | «The Emperor is more patient and careful than any being in the galaxy. He has lived for nearly a thousand years; he might live for ten thousand more» |
| VS8 | Ch18 · L3873 | Meetra POV | post-ritual | «more powerful than Meetra could imagine» |
| VS9 | Ch23 · L4983 | Scourge POV | Emperor-base | «a testament to the Emperor's unfathomable power» |
| VS10 | Ch23 · L4989 | Scourge POV | Emperor-base | «As powerful as the Emperor might be, he was not omniscient» |
| VS11 | Ch23 · L5047 | Scourge POV | Emperor-base | «his power and immortality had transformed him into a being unique in the galaxy» |
| VS12 | Ch25 · L5601 | Revan | vs DK1 | «he didn't even have to fight us. Instead, he broke our wills» |
| VS13 | Ch25 · L5617 | Revan | Emperor-base | «The dark side is like a cancer inside him; it grows faster than he can feed it. He has consumed an entire world, but he still hungers» |
| VS14 | Ch25 · L5621 | Revan | Emperor-base | «the only way to preserve what he has accomplished is to annihilate every potential threat in the galaxy» |
| VS15 | Ch25 · L5637 | Revan | Emperor-base vs ritual era | «He's stronger now» |
| VS16 | Ch27 · L5857 | Revan POV | DK1 memory | «In all his battles, he had never faced an enemy with that kind of power. The dark side had radiated from him in palpable waves, his physical shell barely able to contain the crackling energy» |
| VS17 | Ch28 · L6067 | Scourge's vision | future | «the Emperor lying defeated at the feet of a powerful Jedi—but that Jedi was neither Revan nor Meetra» |
| VS18 | Ch29 · L6189 | Revan POV | **Emperor-amp** | «Revan could feel the Emperor feeding on him, drawing on his power to sate his endless hunger» |
| VS19 | Ch29 · L6205 | Revan POV | Emperor-amp vs Stasis | «it was inevitable that one day the Emperor would win their endless battle of wills» |

The Emperor's own key lines:
- «You already have.» (L5045)
- «I did not expect you to return» (L5929)
- «I expected better from you, Lord Scourge» (L6047)
- «Then he will die with you, as well.» (L6053)
- «That remains to be seen» (L6057)
- «Put away your blade. You have passed the test» (L6095)
- «Revan can still be of use to me» (L6095)
- «Everything has a cost... This is the price of immortality» (L6167)

### 4.3 About Meetra Surik
| # | Ch · L | Speaker / POV | Version | Quote |
|---|---|---|---|---|
| MS1 | Ch5 · L1003-1005 | Revan POV | MW general | «a powerful Jedi named Meetra Surik... a brilliant tactician and military leader» ; «giving her control over nearly half of the Republic and Jedi troops under his command» |
| MS2 | Ch5 · L1093 | Atris | Exile pre-K2 | «She cut herself off from the Force—permanently.» |
| MS3 | Ch17 · L3515 | Bastila POV | K2 | «Like Revan before her, she became the savior of the galaxy» |
| MS4 | Ch17 · L3523 | Bastila POV | PK2 | «She possessed a presence and confidence, along with an enviable natural grace. She was clad in the simple robes of a Jedi Master» |
| MS5 | Ch17 · L3525 | Bastila POV | MW link | «a special bond not unlike that of Padawan and Master» |
| MS6 | Ch18 · L3725 | Meetra POV | Malachor → PK2 | «surviving the trauma of Malachor V had given her the strength to defeat Darth Traya» |
| MS7 | Ch21 · L4553-4557 | Scourge POV | PK2 | «impressed with how easily she had dismantled Murtog» ; «kept her emotions at arm's length so the Force could flow through her unhindered» ; «He didn't know which of them would prove the stronger» |
| MS8 | Ch24 · L5399 | narration (Scourge POV) | PK2 vs Nyriss | «The Jedi was clearly overmatched» |
| MS9 | Ch25 · L5535 | Revan | MW → PK2 link | «I was told you had been cut off from the Force, but I can sense its power in you. I always knew you had great potential, but you have become far greater than I could ever have imagined.» |
| MS10 | Ch25 · L5539 | Revan | PK2 | «I can sense you have walked a path even I would not dare to tread» |
| MS11 | Ch25 · L5541 | Meetra | PK2 → Revan | «Without your teaching, I could never have become what I am today» |
| MS12 | Ch27 · L5797 | Revan POV | MW habit | «She believed she could transform herself into a perfect conduit for the Force, an incorruptible weapon of light» |
| MS13 | Ch28 · L6037 | Scourge POV | PK2 vs Emperor | «if she had aimed at the Emperor instead of the blade, she could have ended his life even as he ended Revan's» |
| MS14 | Ch29 · L6179 | narration | spirit | «As the Emperor fed off him, Meetra was allowing Revan to feed off her» |

Note on MS9-MS10. Revan's «far greater than I could ever have imagined» measures her against *his expectations of her potential*, not against himself. «a path even I would not dare to tread» refers to her path (the Force-severing, Malachor, the Kreia lessons), not her rank. Neither line says "stronger than me". RS13 (Meetra's POV) explicitly ranks Revan above everyone she has met, and she has met Traya, Sion and Nihilus.

### 4.4 About Lord Scourge
- «You have a special gift. You do not just feed on the raw emotions of your foe; you gorge yourself on them» (L1219, Nyriss).
- «The greater your opponent's connection to the Force, the stronger you become» (L1741, Nyriss). **His talent scales with the enemy's Force connection**, so in theory he is a counter to strong Force users. In practice, it didn't save him from Xedrix's lightning, Nyriss or the Emperor's mind-brush.
- «Against me, you would stand no chance» (L1745, Nyriss).
- «If he tried to strike her down, he was fairly sure he would not be able to stand against her» (L2607, POV Scourge).
- Revan on Scourge: «he had incredible potential. Fortunately for Revan, he was also arrogant, overconfident, and ambitious» (L3937).
- «Scourge was an expert swordsman; at the Academy even the instructors had been reluctant to face him» (L5939).
- Xedrix: «Has Nyriss actually convinced you that you have the strength to stand against a member of the Dark Council?» (L2081).
- Scourge on himself: «Fighting a battle I can't win isn't brave... It's stupid.» (L1725).
- To the Emperor: «I knew I was not strong enough to defeat him myself, so I lured him here to face you» (L6079). This is part of a lie, but its premise (Scourge < Revan) matches his real POV at L5437.

### 4.5 About Nyriss, Xedrix and the Guard
- «she was a Sith Council member in the prime of her powers» (L2607).
- «I am Darth Nyriss, Lord of the Sith. I am the conqueror of Drezzi, the destroyer of Melldia, and a member of the Dark Council!» (L5413).
- Meetra, before the duel: «I would have expected someone on the Dark Council to put up better resistance» (L5165). This is about the stronghold's defense, not Nyriss herself.
- Xedrix: «He is a hollow shell of what he once was» (L1745). «Yet Scourge could sense the Councilor's enormous power» (L2039).
- The Guard: «They were formidable opponents, even for a Jedi» (L5849).

### 4.6 Others (Bastila, Canderous, Atris, T3, HK)
- **Bastila:**
  - «If it weren't for you, Darth Malak would have destroyed the Republic, eliminated the Council, and all but wiped out the Jedi» (L107).
  - «You saved the Republic from the Mandalorians. You saved the Republic from Malak» (L1473).
  - «Revan wore the mask during the Mandalorian Wars, and during his time as Darth Revan» (L3703).
  - «I don't care... Not if that power helps bring him back to me.» (L3711).
  - «there are times when I think I can still sense his presence, like he's reaching out to me from somewhere far away» (L6259).
  - «He went to stop it, and I know he succeeded.» (L6279).
- **Canderous:** «Revan is not our enemy. Not now» (L2949). «I am Mandalore the Preserver, and I will restore the honor and glory of my people!» (L3143).
- **Atris:** «The Exile betrayed the Order, as did you» (L1119). «I live for the Force. You live for yourself» (L1115). «A chalarax can't change its spots» (L1105).
- **HK-47:** Revan: «HK's a little too trigger-happy to bring on this mission. Things tend to get bloody when he's around» (L1389). «HK stormed off, swearing he would track Revan down on his own» (L3629, Bastila).
- **T3:** «T3 never stood a chance» (L6011). Bastila: «The little guy does have a knack for joining up with galactic saviors» (L3551).

---
## 5. Character analyses: personality, arc, relationships, abilities and limits, what this book adds to scaling

### 5.1 Revan
- **Personality:** Wry and guilt-ridden. Heterodox: refuses retraining and enjoys riling «overly sanctimonious» Masters (L1063). A family man who still leaves his pregnant wife «for our child» (L1483). He is a manipulator when he must be: Scourge is «nothing more than a tool» (L3931), and he lies about a vision without apologizing (L5721). He keeps his word to enemies («I gave them my word», L5325). He is fatalistic about his sacrifice: «if my role is to sacrifice myself for the one who will come next—then I embrace it» (L5775).
- **Arc:** amnesiac post-KOTOR hero → seeker (Rekkiad, Nathema) → captive (three years drugged) → **Revan Reborn** via the mask, who integrates his Darth-era memories into a gray balance (L5803) → defeated → a jailer's prisoner who fights a mental war to keep the Emperor from invading (Ch29). Bastila's mask gift is the hinge: she accepts his past as part of him (L3707).
- **Relationships:**
  - Bastila: wife and the emotional anchor.
  - Meetra: protégé, former general and friend. Her devotion is not romantic (L5521).
  - Canderous: former enemy turned brother.
  - T3: loyal; dies saving him.
  - Scourge: tool turned ally turned betrayer.
  - The Emperor: his former master by domination and his nemesis.
  - Malak: ex-apprentice and partner on the first DK trip.
- **Abilities shown:** precognition/danger sense, Force-assisted piloting and marksmanship, mid-tier TK (lid, archway, durasteel doors), saber deflection and throws, **lightning absorption and redirection** (his signature), raw light+dark release that knocks the Emperor back, mind-shielding against domination, fear-amplification, Force healing, and visions. In stasis he wages a sustained mental war and subtly rewrites the Emperor's thoughts.
- **Limits:**
  - Basilisks at altitude (L2441).
  - Nathema dampening (L3317).
  - Drugs (L5223).
  - Can't absorb the Emperor's full lightning output (L6001).
  - Healing too slow mid-fight (L6019).
  - Distractible: Meetra's death costs him the fight (L6071).
- **Scaling adds:**
  - (1) **Revan Reborn > Nyriss by a wide margin**, a one-exchange kill.
  - (2) **Revan Reborn < the Emperor 1v1**, but the duel is competitive for a few exchanges, a big step up from DK1's no-fight domination.
  - (3) Gray "knife-edge" Revan is explicitly the strongest Revan: «far more powerful now» (L5859).
  - (4) **Top-tier mental fortitude:** he resists domination, then holds out for decades/centuries in Ch29 (with Meetra's help).
  - (5) The book never gives Revan a planet-scale or fleet-scale Force feat. His power is "best Jedi of his era", not cosmic.

### 5.2 The Sith Emperor (Vitiate)
- **Personality:** Patient, careful and paranoid. «terrified of death» (L5617). Emotionless veneer, with one «primal hiss of hate» (L5995). Utilitarian: «Revan can still be of use to me» (L6095). He likes tests: the mercs, Scourge «passed the test» (L6095). Cruel in reward: Scourge's immortality is permanent agony (L6163).
- **Arc in this book:** offstage legend (Part One) → the Tenebrae origin (Ch15) → onstage in Ch23 and Ch28-29. He ends stronger (the amp) but strategically checked: he steps back from invasion for «several decades, maybe longer» (L6145), partly because of Revan's whisper campaign (L6199).
- **Abilities shown or reported:**
  - Mass mind domination: 100+ Sith Lords per lore; Revan + Malak; the Voice, Hand and Guard.
  - Planetary life-drain with a millennium-long Force void.
  - Immortality and granting it to others.
  - Aura, and a mind-brush that floors a Sith Lord in under a second.
  - Remote telepathy.
  - Lightning strong enough to overwhelm Revan's absorption.
  - Kinetic waves, Force cocoon defense, droid obliteration, casual TK.
  - Stasis-prison sorcery and a long-range feeding link (a dozen parsecs).
  - Power-sharing to his Guard.
- **Limits:**
  - Not omniscient (L4989): missed a decade-long Council plot and was fooled by Scourge's lie (L6121).
  - Surprised by Revan's return (L5929) and by Meetra's throw (L6037).
  - Knocked back when his strength was diverted (L5987).
  - The two-way link lets Revan influence him (L6197).
- **Scaling adds:**
  - (1) A firm on-page **> Revan Reborn 1v1**.
  - (2) The Nathema void corroborates planet-scale sorcery.
  - (3) The **Emperor-amp** version starts in Ch29.
  - (4) He wasn't tested against a full 3v1, and the book leaves that open (L6201). The future champion vision (L6067) points to SWTOR's Jedi Knight.

### 5.3 Lord Scourge
- **Personality:** Proud, ambitious, pragmatic («Fighting a battle I can't win isn't brave... It's stupid», L1725). He has the Sith Empire's long-term interest at heart: he thinks the invasion is «tantamount to suicide» (L3907). Cold, and capable of cruelty («savoring her terror», L5967).
- **Arc:** Nyriss's bodyguard → Xedrix's killer → disillusioned co-conspirator → Revan's ally → **betrayer** after a vision → the immortal Emperor's Wrath, waiting for the champion (L6145).
- **Abilities:**
  - The emotion-feeding talent (stronger against strong Force users, but useless against droids).
  - Juyo; an expert duelist.
  - Force speed, a 10 m leap, TK, Force waves, dark-side stealth cloak.
  - Choking, sensing.
  - Two true visions (Ch26, Ch28).
  - Immortality afterward.
- **Limits:** finite reserves (L863). Nearly killed by a decrepit Xedrix's lightning (L2093-2095). «barely» kept up with Nyriss and was thrown around (L5397-5405). Floored by the mind-brush (L5075).
- **Scaling adds:** a solid **Sith Lord / low Dark Council** level. He is **below Nyriss (prime)** on page. **Well below Revan Reborn** (his own estimate, L5437; and his lie's premise, L6079). Comparable to Meetra (L4557, and their parallel Nyriss and Guard fights).

### 5.4 Meetra Surik (the Exile)
- **Personality:** Calm, warm, guilt-haunted («still looking for redemption», L3613). Devoted to Revan (L5521). Diplomatic with Bastila. Merciful, with emotions «at arm's length» (L4555). Practical: she sells gems, uses disguises, mind-tricks officials.
- **Arc:** Bastila's interlocutor → Nathema investigator → Dromund Kaas infiltrator → rescuer → co-fighter vs Nyriss and the Emperor → killed by Scourge → a spirit sustaining Revan.
- **Abilities:**
  - Premonition, planetary sensing (L4077), mind trick.
  - Acrobatics, push kills, deflection, saber throws with Force guidance.
  - Barriers against lightning.
  - The warrior's trance.
  - Days without food or sleep via meditation.
  - After death, spirit persistence and lending strength through the Emperor's barrier.
- **Limits:**
  - Nathema's Void almost dissolves her (L3803).
  - «clearly overmatched» by Nyriss (L5399).
  - Takes several exchanges with two Guards.
  - Chose to save Revan rather than strike the Emperor (L6037).
  - Unaware of Scourge's betrayal; no danger sense triggered (L6069).
- **Scaling adds:** **This book's Meetra is roughly Scourge-level and below Nyriss on page.** That is a big gap from her KOTOR II ending, where she beat Sion, Nihilus (with help) and Traya. The novel never shows her signature Force-bond tricks (Force-breaking or draining). Her praise lines (MS9-MS10) are about growth and path, not rank. The book's most flattering *feat* for her is the Ch28 surprise disarm of the Emperor. Its most flattering *counterfactual* is Scourge's «she could have ended his life» (L6037). Both are qualified: a surprise move from outside the Emperor's focus, and an opinion.

### 5.5 Darth Nyriss
A sorceress, Dark Councilor for ~20 years, physically aged by choice (L457). Conspiratorial and cautious (she «refuses to take any real action», L3973). On page she 2v1s Scourge + Meetra with lightning, waves, barriers and fast saberwork. She is ashed by Revan in one exchange. **She is the book's measuring stick:** Revan Reborn ≫ Nyriss; the Emperor «infinitely» > Nyriss (L6001).

### 5.6 Bastila Shan (*Bastila, ~3,954 BBY (Prologue) / ~3,951 BBY (Part Two) / ~3,900 BBY (Epilogue)*)
- **Personality:** devoted and protective, and at first possessive about Revan's past: «"I tried to keep Revan's past at bay, but now I understand that was wrong. I was being selfish. His past is a part of him, whether I like it or not."» (L3707).
- **Arc:** the Prologue, where she urges Revan toward the Council («"Maybe you should speak to the Jedi Council," Bastila suggested.», L103) → left behind with their son (L3843) → POV for Part Two's opening, where she gives Meetra the mask and T3 → the Epilogue, where she is old and still waiting.
- **Relationships:** Revan (wife; he hoped to reach her through the Force from his cell, and «the drugs and the vast distance of an entire galaxy must have stopped her from sensing his need», L3935); Meetra (rival claimant to Revan's trust, L3525); Vaner (son).
- **Feats:** she «led that strike team» that captured Darth Revan (L3699). Long-range bond sensing: «there are times when I think I can still sense his presence, like he's reaching out to me from somewhere far away» (L6259).
- **Limits:** no combat on-page. She would have «eagerly fought by his side» (L3513) but stays home.
- **Every quote:** see Appendix Q · Bastila Shan (108 entries), plus the pronoun lines in Q.0.
- **Scaling implications:** a weak sensing feat only. Nothing about her KOTOR-era Battle Meditation is shown.

### 5.7 Canderous Ordo / Mandalore the Preserver (*Canderous, ~3,954 BBY*)
- **Personality:** gruff, loyal, a warrior's pragmatist: «"You look like death warmed over," Canderous said by way of greeting.» (L635). He is bitter about his people's fall: «He blamed Mandalore for not being strong enough to win their battle» (L675).
- **Arc:** reports his contacts' findings (L1327) → takes Revan, disguised as "Avner", to Clan Ordo on Rekkiad (Ch9; «"His name is Avner," Canderous said, cutting Revan off.», L1989) → when Revan's identity is exposed at the Twin Spears tomb, shoots his own wife Veela to save him: «An instant later, Veela went down from a clean kill shot through her heart.» (L2993) → takes the Mask and the title: «"I am Mandalore the Preserver, and I will restore the honor and glory of my people!"» (L3143).
- **Relationships:** Revan (old enemy turned friend, L649); Veela (wife); Edric («Canderous's oldest and most loyal friend», L2777); Meetra (KOTOR II ally, by rumor L3567).
- **Abilities and limits:** not Force-sensitive. A marksman, Basilisk-capable, a clan leader.
- **Every quote:** Appendix Q · Canderous Ordo (230 entries).
- **Scaling implications:** none for Force users. The Dramath backstory he relays (L3077–3083) is key lore for Vitiate's manipulation of the Mandalorian Wars.

### 5.8 T3-M4 and HK-47 (individual profiles)

#### 5.8.1 T3-M4 (astromech)
- **Role:** co-pilot, slicer and fighter. He boosts sensors (L1827), keeps the Hawk flying (L3325), and is Meetra's companion and code-breaker: «"I've never come across a code my friend here couldn't crack," she said, and T3 beeped his agreement.» (L4831).
- **Limits:** «as a droid, T3 could not sense the Force» (L3733), which is why he cannot tell Meetra whether Revan lives.
- **Key feat:** in the Emperor duel: «The droid let loose with his flamethrower, bathing the Emperor in fire. At the last instant the Emperor cocooned himself in the Force to save himself from being incinerated, breaking his focus on Revan.» (L6005). Destroyed immediately afterward.
- **Every quote:** Appendix Q · T3-M4 (151 entries).
- **Scaling implications:** a non-Force droid's surprise attack forces Vitiate onto the defensive. That is a reactive-awareness limit on the Emperor, not a power feat for T3.

#### 5.8.2 HK-47 (assassin droid, exposition only)
- **Role:** left behind as «a little too trigger-happy» (L1389). «"HK stormed off, swearing he would track Revan down on his own," Bastila continued.» (L3629). T3 found «the disassembled pieces of HK-47, abandoned on a remote and nameless world» (L3617). Left under the new Council's supervision (L3635), then missing.
- **Every quote:** Appendix Q · HK-47 (9 entries).
- **Scaling implications:** none.

### 5.9 Jedi Council (Atris) and other named characters with real roles (individual profiles)

Every named character with a real role in the book now has a profile. Characters with an existing Appendix Q section point to it for their complete quote register, instead of duplicating it. New characters (Larvit, the Imperial Guard, Clan Jendri, Igrol/Dark Council) get an auto-harvested register inline. Named with no real role (lore or one-line mentions, so no profile; their mentions are in Q · Other named): Marka Ragnos, Naga Sadow, Ludo Kressh, Mission, Zaalbar, Juhani, Jolee, Grizzer, Davik, Tegris, Ugroth, Ressa. Original summary, kept for reference:

- **Atris** (Ch5): the hostile traditionalist archivist who prepared the Exile report. She is the source for «cut herself off from the Force—permanently» (L1093). That line is wrong by KOTOR II's end, which the book acknowledges at L3725. The rest of the Council is unnamed and appears only as an institution (retraining offer, hostility, the "new Jedi Council" in Part Two, L3635).
- **Malak:** a memory voice on Rekkiad (L2171-2183, L2897-2905). DK1 partner, dominated alongside Revan.
- **Mandalore the Ultimate:** speaks only in Revan's dying-memory flashback (L2869-2877).
- **Xedrix:** cunning, aged and drained. Taunts Scourge (L2081, L2103).
- **Sechel:** a slick double agent; tendrils cut, killed.
- **Murtog:** a bluff security chief killed in the ambush.
- **Veela:** a hard-line clan chief.
- **Edric:** a loyal Ordo friend.
- **Yarri:** the Guard captain, killed by Scourge.
- **Larvit:** a gem broker.
- **Vaner:** a politician son, «Vote Vaner Shan for Supreme Chancellor!» (L6243).
- **Dramath I and II, Marka Ragnos:** lore only.

#### 5.9.1 Atris and the Jedi Council
- **Personality:** a sanctimonious traditionalist. «Once a close friend of Meetra's, Atris had refused to join those who had gone to battle the Mandalorians.» (L1049). She tags and prepares the Exile report, and her bitterness shows: «Atris made no effort to hide the bitterness in her voice.» (L1079).
- **Key line:** her (wrong) verdict on the Exile: «She cut herself off from the Force—permanently.» (L1093). The book corrects it in Meetra's own POV (L3725).
- **The Council:** institutional only. Revan offered «to share his new understanding of the Force» and was turned down (L985).
- **Every quote:** Appendix Q · Jedi Council and Atris (110 entries).
- **Scaling implications:** none.

#### 5.9.2 Darth Malak (memory)
- **Role:** Revan's DK-era partner, heard as a memory voice on Rekkiad. «But Malak had betrayed his Master, and Revan had been captured by the Jedi Council, barely alive, his body and mind shattered.» (L111). Revan's later understanding: «Malak and I were turned to the dark side, but in doing so we found the strength to block out all memory of the Sith and the Emperor, partially freeing us from his control."» (L5603).
- **Every quote:** Appendix Q · Darth Malak (57 entries).
- **Scaling implications:** the L5603 statement says both were dominated by Vitiate and resisted him only partly.

#### 5.9.3 Mandalore the Ultimate (memory)
- **Role:** «Realizing defeat was inevitable, Mandalore the Ultimate had challenged Revan to single combat, and Revan had accepted.» (L669). Revan hid the Mask «after slaying Mandalore the Ultimate—a final act to demoralize a defeated foe» (L1343). The flashback of his death is at L2867: «Mandalore the Ultimate lay dying at his feet.»
- **Every quote:** Appendix Q · Mandalore the Ultimate (26 entries).
- **Scaling implications:** Revan (Mandalorian Wars era) beat the Mandalore in a duel. No details are given.

#### 5.9.4 Darth Xedrix (*Xedrix, ~3,954 BBY*)
- **Personality:** a cold, aged Dark Councilor who manipulates through calm: «Everything Xedrix said made perfect sense, but on some deep, primal level Scourge felt he was being twisted and manipulated.» (L2121).
- **Duel with Scourge (Ch10):** «Scourge tried and failed to draw on his foe's fear and anger—Xedrix was too controlled, and it felt more like fighting a droid.» (L2043). He stalls to charge an attack: «Xedrix raised his left hand and unleashed his power in a storm of purple lightning.» (L2093), and Scourge nearly dies of it (L2125). Then «Scourge used his own blade to slap it aside with ease» (L2141). He begs: «"Please, Lord Scourge, I'll give you anything you want. Slaves. Wealth. Power."» (L2143).
- **Every quote:** Appendix Q · Darth Xedrix (89 entries).
- **Scaling implications:** a Dark Councilor's lightning nearly kills Scourge, but Xedrix is weak in sustained saber combat. Scourge ≥ an aged Councilor.

#### 5.9.5 Sechel (*Sechel, ~3,954–3,951 BBY*)
- **Personality:** a slick, non-Force-sensitive pureblood schemer: «He had compensated for his lack of the Force by developing his mental skills; and apparently Sechel had enjoyed a very successful career with Imperial Intelligence before becoming Nyriss's chief adviser.» (L739).
- **Arc:** greets Scourge (Ch1) → plays both sides (Ch4–12) → brokers Meetra's meeting (Ch20) → Scourge chokes him in passing (L4399) and finally kills him by hand: «There was a surprisingly loud pop, and Sechel's body spasmed once before going completely limp.» (L4797).
- **Every quote:** Appendix Q · Sechel (253 entries).
- **Scaling implications:** none.

#### 5.9.6 Murtog (Nyriss's security chief)
- **Role:** a bluff human chief who resents Scourge. «That could explain why Murtog refused to let Scourge in when they'd first arrived, and why Murtog's soldiers had killed the female mercenary just when she'd been on the verge of surrendering.» (L403). Sent to the Meetra meeting (L4451), he and his team die to Meetra: «He was impressed with how easily she had dismantled Murtog and his handpicked team.» (L4553).
- **Every quote:** Appendix Q · Murtog (79 entries).
- **Scaling implications:** a fodder baseline for Meetra's Ch21 feat.

#### 5.9.7 Veela (Clan Ordo chief, Canderous's wife)
- **Personality:** a hard-liner who hates Jedi: «"We heard you were working for the Jedi," Veela said, her voice low and hateful.» (L1969); «"We killed dozens of Jedi during the war," Veela answered grimly.» (L2973).
- **Death:** she fires on Revan at the tomb, and Revan deflects the volley («the green blade transformed into a spinning, twirling blur as he used it to deflect their bolts back in the direction of the shooters», L2981). Canderous then shoots her (L2993). His cover story is that «Veela and the others died in battle» (L3029).
- **Every quote:** Appendix Q · Veela (100 entries).
- **Scaling implications:** Revan Reborn deflects multi-shooter blaster fire with ease (low feat).

#### 5.9.8 Edric (Clan Ordo sentry)
- **Role:** Canderous's old friend, who welcomes him back («"Well, Edric," Canderous replied, "I could punch you in the face until I straightened out that crooked beak of yours, but we'd probably all freeze to death before I finished."», L1921). He scouts for the expedition (L2329) and is left behind when Canderous leaves Rekkiad (L2777).
- **Every quote:** Appendix Q · Edric (18 entries).
- **Scaling implications:** none.

#### 5.9.9 Captain Yarri (Imperial Guard)
- **Role:** the Guard captain who escorts Scourge to and from the Emperor (Ch23: «"You took a great risk," Yarri said, though it was hard to tell if she thought him admirable or foolish.», L5087) and fights him at the citadel. «Captain Yarri's skill with her electrostaff was impressive, but ultimately she was no match for a Sith Lord.» (L5941). Scourge cuts her hip and crushes her hand (L5963–5965).
- **Every quote:** Appendix Q · Captain Yarri (30 entries).
- **Scaling implications:** Scourge > an elite Imperial Guard captain, with a four-move sequence: «A four-move sequence overwhelmed Yarri» (L5963).

#### 5.9.10 Vaner Shan (Revan and Bastila's son)
- **Role:** «"But I called him Vaner."» (L5505, Revan). In the Epilogue he is a politician: «Vote Vaner Shan for Supreme Chancellor!"» (L6243); «"I guess it skips a generation," Vaner said with a soft laugh.» (L6269).
- **Every quote:** Appendix Q · Vaner (20 entries).
- **Scaling implications:** none. Not Force-sensitive.

#### 5.9.11 Kreia / Darth Traya (KOTOR II recap)
- **What the book says:** «Kreia took the name Darth Traya, and her followers called themselves the Sith after the long-lost species that had invaded the Republic a millennium before.» (L3511). Meetra «had emerged on her own to oppose and eventually defeat Darth Traya» (L3515). «The Hawk limped back to Republic space; by the time it arrived, Traya and her followers had all but wiped out the Jedi.» (L3615).
- **Every quote:** Appendix Q · Kreia / Darth Traya (8 entries).
- **Scaling implications:** a recap statement that Meetra beat Traya. The book's canon for KOTOR II's ending.

#### 5.9.12 Lord Dramath I and II (lore)
- **What the book says:** «"Tenebrae's father was named Lord Dramath.» (L3209); «Had Dramath acted more swiftly, the Emperor might have been stopped.» (L3209). His son fled: «Dramath's firstborn son fled rather than face his formidable half brother» (L3213). The Sith emissary «convinced Mandalore to help him search for his enemy's tomb» (L3077).
- **Every quote:** Appendix Q · Lord Dramath (7 entries).
- **Scaling implications:** Vitiate's origin. As a child he was already feared by his father.

#### 5.9.13 Larvit (gem broker, Dromund Kaas)
- **Role:** Meetra's black-market contact (Ch20): «From the outside, Larvit's shop didn't look like the kind of place one would chose to conduct illegal business.» (L4125). He sells her out to Sechel: «"I see Larvit does not believe in discretion when it comes to discussing business matters," Meetra grumbled.» (L4241).
- **Scaling implications:** none.
- **Complete quote register (12 lines: every sentence that names Larvit, verbatim, in book order):**
  - Ch20 L4119 «"Larvit's your best bet," the other woman told her.»
  - Ch20 L4121 «Meetra decided to walk to Larvit's store, rather than hire a speeder.»
  - Ch20 L4125 «From the outside, Larvit's shop didn't look like the kind of place one would chose to conduct illegal business.»
  - Ch20 L4127 «She stepped into Larvit's store and made a quick evaluation of her surroundings.»
  - Ch20 L4139 «"I am, I am," Larvit assured her, regaining some of his composure.»
  - Ch20 L4143 «Larvit snorted derisively.»
  - Ch20 L4147 «Larvit asked.»
  - Ch20 L4151 «Larvit shook his head and made his way back over to inspect the stones still sitting atop the counter.»
  - Ch20 L4205 «Larvit must have provided a description of her, because he seemed to know who she was.»
  - Ch20 L4235 «"Larvit tells me you are looking for someone," Sechel said, jumping right to the matter at hand.»
  - Ch20 L4241 «"I see Larvit does not believe in discretion when it comes to discussing business matters," Meetra grumbled.»
  - Ch20 L4299 «Sechel proved to be a much shrewder negotiator than Larvit; he knew he had all the leverage.»

#### 5.9.14 The Imperial Guard
- **Description:** «An army of elite warriors, the Imperial Guard underwent months of brutal training to transform them into the most disciplined and deadly troops in the Empire.» (L4907). They are under the Emperor's spell (L3487).
- **Role:** they purge Nyriss's stronghold («"The Imperial Guard," Scourge gasped. "They're here!"», L5155) and guard the citadel. Yarri commands them.
- **Scaling implications:** the elite fodder baseline for Scourge and Meetra in Ch24 and Ch27.
- **Complete quote register (16 lines: every sentence that names Imperial Guard, verbatim, in book order):**
  - Ch8 L1687 «"I'd have expected him to order the Imperial Guard to arrest Xedrix."»
  - Ch16 L3487 «Remember that all those who have direct access to the Emperor—the Emperor's Voice, the Emperor's Hand, the soldiers in the Imperial Guard—are under his spell.»
  - Ch23 L4907 «At the top of the stairs he was stopped by a pair of Sith soldiers clad in red armor—two of the famed Imperial Guard.»
  - Ch23 L4907 «An army of elite warriors, the Imperial Guard underwent months of brutal training to transform them into the most disciplined and deadly troops in the Empire.»
  - Ch23 L5091 «"She will be purged by the Imperial Guard," Yarri said.»
  - Ch24 L5155 «"The Imperial Guard," Scourge gasped.»
  - Ch24 L5163 «They were coming from all sides; obviously the Imperial Guard had the entire stronghold surrounded.»
  - Ch24 L5183 «Recognizing Scourge as a friendly target, the Imperial Guards ran past without even a second glance.»
  - Ch24 L5391 «"The Imperial Guard will make sure I never leave my stronghold alive," she told them.»
  - Ch24 L5431 «"We don't want the Imperial Guard to know you were here."»
  - Ch25 L5579 «"The Imperial Guard were only unleashed on Nyriss and two others.»
  - Ch25 L5597 «We found a member of the Imperial Guard who was willing to sneak us inside the citadel."»
  - Ch27 L5849 «On his last visit to Dromund Kaas, he and Malak had learned everything they could about the Imperial Guard.»
  - Ch27 L5901 «Ordinary soldiers would have been chopped down before they could even draw their weapons, but the Imperial Guard were not so easily felled.»
  - Ch27 L5919 «At the far end of the hall, another half a dozen of the Imperial Guard rounded the corner.»
  - Ch27 L5921 «They crossed the threshold, still engaged with Captain Yarri and the three surviving Imperial Guard that had escorted them to the throne room.»

#### 5.9.15 Clan Jendri (Mandalorian rival clan)
- **Role:** they ambush Clan Ordo on Rekkiad: «Clan Jendri outnumbered Clan Ordo by almost two to one, though Revan noticed they had only four Basilisks.» (L2397). Revan's ignited lightsaber draws all four Basilisks (L2427), and the Ordo counterattack breaks them: «The carnage lasted less than five minutes before the Jendri ranks broke.» (L2447).
- **Scaling implications:** Revan survives four war-droid Basilisks targeting him at once. That is crowd-combat context for "Avner".
- **Complete quote register (13 lines: every sentence that names Clan Jendri, verbatim, in book order):**
  - Ch11 L2311 «"The Twin Spears are in Clan Jendri's territory," Veela warned.»
  - Ch11 L2365 «"We're well inside Clan Jendri's territory," Veela said, coming over to sit beside Revan and Canderous as they tore into their rations.»
  - Ch11 L2397 «All around him he saw the men and women of Clan Ordo, most clad only in underclothes and a few scraps of plated armor, battling the forces of Clan Jendri that were swarming in from all sides.»
  - Ch11 L2397 «Clan Jendri outnumbered Clan Ordo by almost two to one, though Revan noticed they had only four Basilisks.»
  - Ch11 L2399 «Immediately Revan recognized the Jendri strategy: they had concentrated their attack near the Ordo Basilisks, hoping to keep Veela and her fellow pilots from reaching the deadly machines.»
  - Ch11 L2427 «The glowing green blade instantly drew the attention of all four Jendri Basilisks, as the pilots swung their beasts around to target the hated Jedi who had suddenly appeared in their midst.»
  - Ch11 L2443 «As the Jendri pilots prepared to retaliate against Revan, six Ordo Basilisks took to the air in attack formation.»
  - Ch11 L2445 «Now outnumbered two to one, the Jendri pilots banked their war droids away from the enemy squadron and fled.»
  - Ch11 L2447 «Even with superior numbers, the Jendri troops couldn't match the awesome firepower of half a dozen Basilisks.»
  - Ch11 L2447 «The carnage lasted less than five minutes before the Jendri ranks broke.»
  - Ch11 L2451 «Such vicious savagery was typical of Mandalorian warfare, and yet Revan knew that once the battle was over, Clan Jendri would hold no grudge against the victors.»
  - Ch13 L2725 «Six members of the clan, four men and two women, had died in the battle, a quarter of the casualties they had inflicted on Clan Jendri.»
  - Ch13 L2949 «Without him, Clan Jendri would have slaughtered us.»

#### 5.9.16 Darth Igrol and the Dark Council
- **Role:** the Council Nyriss schemes against. Nyriss lectures Scourge on its members (Ch6: «"Igrol resides on Dromund Fels.», L1257). The Emperor later purges the plotters.
- **Scaling implications:** none.
- **Complete quote register (54 lines: every sentence that names Darth Igrol and the Dark Council, verbatim, in book order):**
  - Ch1 L175 «Built by slaves and devoted followers, the citadel served as both palace and fortress, an unassailable meeting place for the Emperor and the twelve handpicked Sith Lords who made up his Dark Council.»
  - Ch1 L177 «But acolytes were not permitted inside the citadel; its secrets were reserved for those in direct service to the Emperor and the Dark Council.»
  - Ch1 L185 «More important, he was here at the personal request of Darth Nyriss, one of the most senior members of the Emperor's Dark Council.»
  - Ch1 L241 «Like every member of the Dark Council, Darth Nyriss was allowed access to the Emperor's citadel.»
  - Ch1 L245 «Rivals both off and on the Dark Council would prey on her situation, leveraging her vulnerable position to their own advantage.»
  - Ch2 L393 «Nyriss was a member of the Dark Council; she was one of the twelve most important and influential individuals in the Empire.»
  - Ch2 L443 «Scourge didn't know if that was true, but he knew that Nyriss had gained her place in the Dark Council through her knowledge and understanding of things he could never hope to fully grasp.»
  - Ch2 L449 «He didn't know how old Darth Nyriss was, though he knew she had served on the Dark Council for nearly two decades; only two other members had longer tenures.»
  - Ch2 L563 «The Emperor chose you because he knew you had been removed from the politics of Dromund Kaas and the Dark Council; you were untainted by any allegiance to a secret master who might be involved in the conspiracy against me.»
  - Ch6 L1235 «He traced the payment for the custom droid sent to assassinate me back to a group of radical human separatists from Bosthirda dedicated to freeing their world from the tyranny of the Emperor and the Dark Council."»
  - Ch6 L1245 «Humans could rise to the highest ranks of the Imperial military; a number of worlds were even ruled by wealthy and powerful human families; and the Emperor had appointed many humans to serve on the Dark Council.»
  - Ch6 L1251 «"Since they cannot get to him, one of the longest-serving members of the Dark Council is the next best thing.»
  - Ch6 L1255 «"What about Darth Igrol?"»
  - Ch6 L1257 «"Igrol resides on Dromund Fels.»
  - Ch6 L1257 «Killing one of the Dark Council on Dromund Kaas—the Imperial capital—makes more of a statement."»
  - Ch6 L1257 «Ever since I joined the Dark Council there has been animosity between us.»
  - Ch6 L1259 «It was common knowledge that members of the Dark Council typically viewed one another as dangerous rivals, and there were always rumors of shadowy feuds being fought behind the scenes.»
  - Ch6 L1267 «The separatists had tried to kill a member of the Dark Council.»
  - Ch8 L1677 «Darth Xedrix was the longest-serving member of the Dark Council, having joined a full decade before Nyriss.»
  - Ch8 L1681 «He knows those of us currently on the Dark Council would oppose him in his bid for power.»
  - Ch8 L1717 «"Asking me to kill a member of the Dark Council is not as simple as you make it sound."»
  - Ch8 L1743 «"Strong enough to kill a member of the Dark Council?"»
  - Ch8 L1751 «He wanted to test himself against a member of the Dark Council; he wanted to prove to himself and to Nyriss that he was worthy of this task.»
  - Ch8 L1753 «It was unlikely he would be chosen to replace Xedrix on the Dark Council.»
  - Ch10 L2039 «Darth Xedrix was still a member of the Dark Council, and underestimating him would be a fatal mistake.»
  - Ch10 L2081 «Has Nyriss actually convinced you that you have the strength to stand against a member of the Dark Council?»
  - Ch12 L2625 «"Some of us on the Dark Council learned of his plan.»
  - Ch12 L2637 «"If the Emperor suspected the members of the Dark Council of allying against him, he would kill us all.»
  - Ch12 L2647 «Allowing Xedrix to take the blame will confirm the Emperor's suspicion that the separatists were working with someone on the Dark Council.»
  - Ch12 L2671 «"Even with all the evidence pointing in your direction, it's possible the Emperor would still believe you over a member of the Dark Council, but honestly, he would probably kill us both just to be safe.»
  - Ch19 L3977 «"She tells me we must be patient, but her energies and resources are focused on besting her rivals on the Dark Council."»
  - Ch19 L3985 «At the time he had believed her when she said it was for the good of the cause, but now he suspected it had just been an excuse to remove a rival from the Dark Council.»
  - Ch19 L3997 «"Someone powerful, but who is not caught up in the politics of the Dark Council."»
  - Ch21 L4589 «He had come to accept that neither she nor any of the other Dark Council members who had plotted with her would ever actually dare to strike.»
  - Ch22 L4759 «"The ones implicating Nyriss and the other Dark Council members.»
  - Ch22 L4843 «Several members of the Dark Council, the Emperor's circle of handpicked advisers, had joined together in a conspiracy to remove him from the throne.»
  - Ch22 L4869 «"She's on the Dark Council," Meetra said, recalling the name from the data disks.»
  - Ch23 L4899 «He'd briefly considered approaching one of the other members of the Dark Council, hoping to convince him or her to help him get rid of Nyriss the same way she had used him to eliminate Darth Xedrix.»
  - Ch23 L4915 «"Only those on the Dark Council can speak with the Emperor," the second soldier told him, her tone curt and official.»
  - Ch23 L5037 «"They show that Darth Xedrix was not the only member of the Dark Council to betray you.»
  - Ch23 L5067 «When Nyriss falls, you will be first in line for her seat on the Dark Council."»
  - Ch23 L5087 «"But if your information is good, it sounds like you'll be on the Dark Council the next time we meet."»
  - Ch24 L5165 «"I would have expected someone on the Dark Council to put up better resistance," Meetra said as they turned a corner and raced down another hall.»
  - Ch24 L5413 «I am the conqueror of Drezzi, the destroyer of Melldia, and a member of the Dark Council!"»
  - Ch25 L5573 «"The files you showed me listed five current members of the Dark Council plotting against him," Meetra said, looking to clarify.»
  - Ch25 L5575 «"All twelve members of the Dark Council—even those who weren't part of the conspiracy.»
  - Ch25 L5589 «"He wants to get everything here back under control before any other worlds hear that he slaughtered the entire Dark Council."»
  - Ch25 L5641 «"The Emperor had to keep his plans secret because he knew the Dark Council would oppose him.»
  - Ch25 L5643 «"He can claim the Dark Council was working with agents of the Republic, and that is why he destroyed them.»
  - Ch27 L5839 «No doubt every member of the Emperor's Guard was aware by now that Scourge had been the catalyst for the Emperor's sudden purging of the entire Dark Council.»
  - Ch28 L6099 «"I trust you will remember this when you select the members of the new Dark Council."»
  - Ch29 L6119 «In the wake of Revan's defeat, the Emperor hadn't made him a member of the Dark Council after all.»
  - Ch29 L6123 «He would forever serve at the Emperor's side, an honor far greater than even that of being selected for the Dark Council.»
  - Ch29 L6143 «The Dark Council would have to be rebuilt.»

---
## 6. Scaling connections and quick ladder

**On-page ladder for this book (all ~3,951 BBY unless tagged):**
1. **Emperor-amp** (Ch29+; strength not quantified) > **Emperor-base**. He beats Revan Reborn 1v1 without taking real damage (§3.7). «infinitely more powerful than Darth Nyriss» (L6001).
2. **Revan Reborn.** Ashes Nyriss in one exchange (L5425). Knocks the Emperor back once and lands one redirected bolt on him (L5987, L5995).
3. **Darth Nyriss (prime).** Beats Scourge + Meetra 2v1 (§3.6).
4. **Meetra-PK2 ≈ Scourge-mortal.** Parallel showings vs Nyriss and the Guard. Scourge: «He didn't know which of them would prove the stronger» (L4557).
5. Imperial Guard (Emperor-boosted) and Yarri. Each takes Meetra or Scourge a few exchanges, two-on-one.
6. Xedrix (decrepit). Still has lightning that tears through Scourge's barrier.

**Links to other notes:**
- *KOTOR II context:* Kreia on Revan: "Revan was power. It was like staring into the heart of the Force." (kotor-2-notes.md L225, K2/Kreia). Sion: "I have come farther than any of her apprentices since Revan" (kotor-2-notes.md L40). The novel's Revan Reborn matches the "Revan is the high bar" framing, and the novel puts Vitiate clearly above that bar.
- *KOTOR I context:* "You are stronger than I thought; stronger than you ever were" (Malak, kotor-1-notes.md L25). That is KOTOR-ending Revan. The novel's L5859 «He was far more powerful now» compares Revan Reborn with DK1-Revan, which fits a growth line: DK1 < KOTOR-end ≤ Revan Reborn.
- *verdicts.md entries touched:* Strongest Legends (L10-14, Vitiate #1; L12 already cites "infinitely more powerful than Darth Nyriss" via a CV respect thread, now **verified in the source at L6001**). Revan vs the Exile (L345-347). Kun vs Revan (L225-227). Tier list (L383+). Luke vs Vitiate and Luke vs Revan (L363 area). RotS Yoda vs SoR Revan (L840).

### 6a. Story and prose notes (for context, not scaling)
- SP1: Karpyshyn's POV estimates are often wrong or deliberately left open. Meetra assumes Vitiate is long dead (L3877). Scourge's «would have won regardless» is a rationalization (L6129). Revan's counter-thought comes right after (L6201). Read the POV estimates as characterization.
- SP2: The book makes Revan's fall a retcon: domination by the Emperor (L5601-5603). It reframes Darth Revan as partly Vitiate's puppet and partly a self-liberated Sith who used the dark side to block the Emperor's influence.
- SP3: Meetra's death and Scourge's betrayal are fate-driven (visions L5687, L6067). The book's thesis is «victory even in defeat» (L5771): buying decades for the SWTOR-era champion.
- SP4: The encoding damage means some names are likely mangled in the file. I saw none mangled in character names; only the accent and quote characters are lost.

---

## 7. Verdict implications (leans, in low/mid/high diff terms)

**V-1. Revan vs Vitiate.**
- *Revan Reborn (3,951) vs Emperor-base:* **Vitiate, mid diff** on page. Confidence **high (8/10)**: it is a direct on-page 1v1 with an explicit authorial-style comparison (L6001). Revan made him work: the light+dark release knockback (L5987) and the redirected bolt (L5995). But the Emperor took only singed robes, and Revan was helpless within about 8 exchanges (L6019).
- *vs Emperor-amp / SWTOR-era Vitiate:* **Vitiate, low-mid diff.**
- *vs DK1-Revan (+ Malak):* **Vitiate, no diff** («it wasn't even fair to call it a battle», L5859).
- *Revan + Meetra + Scourge (+T3) vs Emperor-base:* **unresolved; lean Vitiate, high diff.** Two POVs disagree (L6129 vs L6201). Scourge's Ch26 vision showed a loss, and the Ch28 vision showed both outcomes (L6061).

**V-2. Revan vs Scourge.**
- *Revan Reborn vs mortal Scourge:* **Revan, low diff.** Confidence **high (8.5/10)**. Chain: Revan ≫ Nyriss (L5425) > Scourge (L5397-5411). Scourge's own POV: «If anyone had the strength to stop the Emperor, it was this man» (L5437). Scourge also told the Emperor he was «not strong enough to defeat him» (L6079). That is part of a lie, but it fits his real assessments.
- Captive/drugged Revan, unarmed, is the exception: «unarmed he was no match for the Sith» (L5307, Revan's foggy POV).
- *vs Scourge-Wrath (immortal):* the book adds no power, only agelessness. The SWTOR-era Scourge (300 years later) is out of scope.

**V-3. Revan vs the Exile.**
- *Revan Reborn vs Meetra-PK2 (novel versions):* **Revan, low-mid diff.** Confidence **medium-high (7/10)**. Chain: Revan ≫ Nyriss > Meetra (L5399 «clearly overmatched»). Her POV: «Revan's command of the Force was greater than that of anyone else she had ever met» (L4811). The praise lines (L5535, L5539) concern her growth, not parity.
- *Revan (any KOTOR-end+) vs KOTOR II endgame Exile:* keep **Revan, mid to mid-high**. The novel's Meetra underperforms her game showing (she shows no Force-bond powers), so the book is evidence for the novel versions, not a clean nerf of K2-endgame Exile.
- **Correction:** verdicts.md L346 counts "she dies to Scourge" as evidence. Per L6069-6071 it was **a backstab by an ally mid-fight while she faced the Emperor**. It is not combat evidence and should be removed or reworded.

**V-4. The Exile vs Scourge (mortal, 3,951).**
- **Toss-up, slight Exile, high diff.** Confidence **low (5.5/10)**.
- For Meetra:
  - Her ambush clear was cleaner than his separatist massacre (L4553).
  - She disarmed the Emperor by surprise (L6035), while he was floored by a mind-brush (L5075).
  - Her K2 feats outside this book (Traya, Sion, Nihilus) are higher than anything Scourge shows.
- For Scourge:
  - His emotion-feeding talent scales against strong Force users (L1741).
  - He is an «expert swordsman» (L5939), with Juyo.
- Against both: they performed near-identically vs Nyriss and vs the Guard.
- His own POV: «He didn't know which of them would prove the stronger» (L4557).
- The backstab (L6069) is not evidence.

**V-5. Vitiate's overall ranking.**
- **No change: still #1 among Legends Force users (tier 2).**
- What this book adds:
  - On-page dominance over the era's best Jedi (V-1).
  - Corroborated Nathema-scale sorcery (the void persists after ~1,000 years, worse than Malachor per Meetra, L3731).
  - Mass mind control (V1, V4, V5).
  - Immortality-granting (V10).
  - The **Revan-fed amp** from 3,951 BBY (L6189).
- Caveats:
  - The Tenebrae biography is Nyriss's hearsay (L3205).
  - The Emperor shows ordinary-looking duel tools (lightning, waves, TK), with no on-page cosmic feat in combat.
  - He is caught off guard twice (L5987, L6037), and he is «not omniscient» (L4989).
- The book does not by itself place him above DE Sidious; that comes from his SWTOR/Ziost material. But it is fully consistent with the verdicts.md placement.

**V-6 (new). Darth Nyriss placement.**
- Nyriss beat Scourge + Meetra together, so on this book alone the novel version of Meetra is below a mid-tier Dark Councilor. That creates **tension** with the tier list, which puts the Exile at the bottom of tier 5.
- Recommendation: tag the novel's Meetra as a separate, lower showing ([Meetra-PK2 novel]), and keep the tier placement based on K2 endgame feats. Alternatively, accept that Nyriss scales to roughly low tier 5 / high tier 6. Revan ashing her keeps Revan comfortably in tier 5.

---

## 8. Proposed verdicts.md changes (not applied; verdicts.md was read only)

1. **Revan vs the Exile (L345-347).**
   - Keep the winner (Revan) and the diff for the game versions (mid-high is defensible; I'd lean **mid**).
   - Add a version split: "Revan Reborn vs novel Meetra (3,951 BBY): Revan, low-mid diff, 7/10. Chain: Revan ashes Nyriss in one exchange (revan.txt L5425), Nyriss had Meetra 'clearly overmatched' (L5399), and Meetra's POV puts Revan above anyone she's met (L4811)."
   - **Replace** "she dies to Scourge" with: "Scourge kills her with a backstab while she faces the Emperor (L6069-6071), which isn't combat evidence."
   - Add that «far greater than I could ever have imagined» (L5535) is about her potential, not parity.
2. **NEW: Revan (Reborn, 3,951) vs Vitiate (pre-amp).** "Vitiate, mid diff, 8/10. On-page Ch28: Revan knocks him back once while his strength is diverted (L5987) and singes him with a redirected bolt (L5995), then loses the lightning clash, 'infinitely more powerful than Darth Nyriss' (L6001), and is saved only by T3 and Meetra. Vs amped Vitiate (feeding on Revan, L6189): low-mid. DK1 Revan + Malak: no diff, dominated without a fight (L5601, L5859). 3v1 with Meetra and Scourge: unresolved, lean Vitiate (L6129 vs L6201)."
3. **NEW: Revan (Reborn) vs Lord Scourge (mortal).** "Revan, low diff, 8.5/10 (Nyriss chain; Scourge POV L5437)."
4. **NEW: Meetra Surik (novel, 3,951) vs Lord Scourge (mortal).** "Toss-up, slight Meetra, high diff, 5.5/10. Parallel Nyriss and Guard showings; L4557 'didn't know which of them would prove the stronger'; the backstab isn't evidence."
5. **NEW: Revan (Reborn) vs Darth Nyriss.** "Revan, low diff, 9/10 (L5419-5425)." Also **Nyriss vs Scourge + Meetra:** "Nyriss, mid diff (L5393-5411)." Add Nyriss to "Not placed yet" (around low tier 5 / high tier 6, tension noted).
6. **Strongest Legends (L12):** add "(verified in the novel, revan.txt L6001)" after the "infinitely more powerful than Darth Nyriss" cite. Optionally add "Nathema Force void corroborated on page (L3239-3283, L3731, L3803)".
7. **Tier list note:** add a version note for Vitiate, "base (3,951) < Revan-fed amp (Ch29 L6189) < SWTOR/Valkorion". Also a Revan version note: "DK1 (dominated) < KOTOR-end < Revan Reborn (knife-edge gray, L5803/L5859)". No tier moves.
8. **Kun vs Revan (L225-227):** optional, +0.5 confidence for Revan. The novel adds a one-exchange lightning-absorb kill of a Dark Councilor and a competitive opening against Vitiate. These are new Reborn-version feats beyond KOTOR.
9. **Change log line:** "2026-10-19, *Revan* (Karpyshyn) read in full (revan-novel-notes.md). New: Revan vs Vitiate, Revan vs Scourge, Meetra vs Scourge, Revan vs Nyriss. Revised wording: Revan vs the Exile (the backstab caveat, the novel version split). No tier moves."

---

## 9. Gaps and caveats
- **No on-page first Emperor confrontation (DK1).** It is only summarized (L5601, L5859).
- **HK-47 has no on-page presence**; he appears only in exposition (L617, L1389, L3617-3651).
- **Jedi Council:** Atris is the only named member who appears (Ch5). The others are institutional only. Jolee, Juhani, Mission and Zaalbar are mentioned only (L1369-1391).
- **Malak and Mandalore the Ultimate** appear only in memories. **Dramath I and II and Marka Ragnos** are lore.
- **The Tenebrae biography is hearsay** (L3205). Corroborated in outline by the Nathema evidence and the archives (Ch18), not in detail.
- **Meetra shows none of her KOTOR II signature powers** (Force-bond severing, draining, Force-breaking). Her showing is a novel-version underperformance relative to the game.
- **The 3v1 outcome is deliberately unresolved** (L6201).
- **The Emperor-amp's magnitude is unquantified.**
- **Source encoding:** U+FFFD replaces all quotes, apostrophes and dashes, and accents became `?`. Quotes here are shown restored and verified with a quote/dash-agnostic normalizer.
- **Appendix Q harvesting limits:** it is name/alias based. Pronoun references, and descriptors like "the Jedi" or "the Sith", are not caught automatically; the important ones are in §3-§4 by hand. Speaker attribution is heuristic: "Name said", an action beat, continued speech, then A/B alternation, each labeled. Spot checks found it mostly right. Multi-speaker and pronoun-only lines can be unattributed or occasionally misattributed, so check the label before relying on an OWN LINE tag.

---

## 10. Quote verification report

- **Script:** `research/_revan-work/verify.py`, with normalization from `common.py`. Every quote character, apostrophe and dash (including U+FFFD from the damaged source) is mapped to one placeholder, runs of placeholders are collapsed, whitespace is normalized, and … becomes "...". Then every guillemet-quoted passage in this file is checked as a substring of the normalized full source.
- Quotes I shortened with "..." are checked piece by piece. Each piece must be found in order, within 4,000 characters of the previous piece; these are counted as "elided".
- **Line check:** for every guillemet quote with an L-number on its line, the first piece must occur within that line range ±2 lines.
- **Result (run 2026-10-19 on the final file):** **4,149 quotes checked, 4,149 verified, 0 failures**. 4,121 are exact contiguous substrings and 28 are elided multi-piece quotes. Of these, 431 are in the curated sections 1-9 and 3,718 in Appendix Q. **Line-number check: 4,142 checked, 0 mismatches.** The other 7 have no L-number on their line.
- **Re-run after the 2026-10-19 gap fix (America/New_York):** **4,419 quotes checked, 4,419 verified, 0 failures**: 4,391 exact and 28 elided. **Line-number check: 4,412 checked, 0 mismatches.** New material:
  - §5.6–5.9 now hold 20 individual profiles (previously four short paragraphs and a bullet list): Bastila, Canderous, T3-M4, HK-47, Atris and the Council, Malak, Mandalore the Ultimate, Xedrix, Sechel, Murtog, Veela, Edric, Yarri, Vaner, Kreia/Traya, Dramath, Larvit, the Imperial Guard, Clan Jendri, and Igrol/Dark Council. 156 profile prose quotes, plus 95 inline register lines for the four characters that had no Appendix Q section. The others point to their Q section.
  - Appendix Q.0 adds 115 hand-curated pronoun-only and epithet-only lines: Scourge 36, Revan 29, Meetra 15, Emperor 12, Nyriss 8, Canderous 5, T3-M4 4, Xedrix 2, Sechel 2, Bastila 1, Yarri 1.
- **Failures during drafting, all fixed:**
  - a case slip ("the Council" → "The Council", L111);
  - a bracketed paraphrase "gorge[s]", replaced by an exact quote at L1219;
  - a mis-recalled wording "assumed they had failed" → "assumed we had failed" (L5607);
  - "for several decades" → "several decades, maybe longer" (L6145);
  - a format placeholder;
  - five L-number slips (L2295, L2927, L1741/L1745, L2431, L5987, L567, L2835).
- External quotes from the KOTOR notes and verdicts.md are in plain "double quotes" and aren't counted.

## Appendix L. Raw reading log (written while reading, chapter by chapter)

The log is reproduced from `_revan-work/log.md`. Its quotes are in plain double quotes and are working notes. The verified versions are the guillemet quotes above.

## Prologue (L63-153) Coruscant, ~3,954 BBY (two years after KOTOR: L83 "two standard years after rediscovering his true identity")
- Revan's storm nightmare, 3rd night; Bastila (wife) on balcony. Council stripped memories (L111). He & Malak "had found something" beyond Outer Rim, "a threat far greater than the Mandalorians or the Star Forge" (L151). Official story: corrupted by Star Forge (L147).
## Ch1 (L161-373) Dromund Kaas, Scourge arrives
- Empire lore: Emperor rose after Great Hyperspace War, exodus, "immortal and all-powerful savior" still reigning after 1000 yrs (L171). Storms rumored from Emperor ritual (L443).
- Scourge: top Academy student, 2 yrs quelling rebellions; newly a Sith Lord. Sechel nearly Force-null pureblood.
- Feats: choke-lift Sechel (L301-305); senses hostile intent in <2s (L317-319); Force-speed across courtyard dodging autotargeting cannon (L321); saber throw clips speeder, returns (L325); somersault leap over merc, kills male merc (L337-339); armor hit, shoulder scorched (L343); drawing opponent's fear to amplify (L345); Force wave blasts female merc into statue (L347). Murtog's guards kill her.
## Ch2 (L377-603) Nyriss
- Nyriss: Dark Council ~20 years, sorcery expert, deliberately aged appearance (L447-459). She hired the mercs as a test (L541-557). Emperor "suggested" bringing outsider (L307, L563). Mission: Hallion droid plant with Sechel.
## Ch3 (L607-723) Coruscant, Dealer's Den - Revan & Canderous
- Revan got Cross of Glory ~2 years ago (L611); T3-M4 along; HK-47 left home (L617). Canderous hasn't taken a job in 2 yrs.
- Mandalore the Ultimate history: challenged Revan to single combat; "no match for the Jedi Order's most powerful champion" (L671); Revan hid the Mask (L671-673). Revan connects Mandalore's war to his own disappearance (L695-699). Canderous: "You and your followers turned the entire tide of the war against us" (L665). Canderous agrees to dig among clans.
## Ch4 (L727-957) Hallion - Scourge & Sechel at UDM droid plant
- Scourge leaps 3 m fence (L765), saber-throws patrol drone (L777), Force-speed (L847), armor absorbs bolts (L849), TK slam drone (L859), Force reserves limited "could draw on it for only so long before exhaustion" (L863), knocks 2 drones into vat (L885), ribs cracked by assault droid kick (L893-895), kills assault droid via underbelly (L899). Nearly exhausted vs swarm + 2 more assault droids, resigned to death (L905-907). Sechel shuts power; plant explodes. Juyo not yet mentioned (Ch6). Sechel competent ex-Imperial Intelligence (L739).
## Ch5 (L961-1133) Jedi Temple Archives - Revan & Atris
- Conservative Masters resent him; refused retraining: "learned too much about the Force, both the light side and the dark" (L973); love/emotion philosophy (L975-977); Council compromise: no heresy spreading (L985-989).
- Meetra: among first to join, brilliant tactician, general of nearly half his troops (L1003-1005). Malachor V MSG recap (L1023-1035). Revan can't sense her (L1015). Atris: Meetra cut herself off from Force permanently (L1093). Atris hostile; "A chalarax can't change its spots" (L1105).
## Ch6 (L1137-1281) Nyriss lectures Scourge
- Scourge Juyo drills in heavy armor, blade "nothing but a blur" (L1147). Murtog no challenge to a Sith Lord (L1145).
- Nyriss diagnosis: Scourge "gorge[s]" on foes' emotions (L1219); droids empty -> weaker (L1221-1223). Sith Code recited (L1211). Bosthirda separatists traced. Xedrix longest-serving, human; 5 of 12 Council human (L1245). Darth Igrol on Dromund Fels (L1255-1257). Emperor encourages infighting (L1259).
## Ch7 (L1285-1519) Canderous news; Bastila pregnant
- Clans gathering at Rekkiad hunting Mandalore's Mask (L1327-1345); Revan's memory flash of glacier with Malak (L1335). Revan "no longer clung to the simplistic ideals of right and wrong" (L1359). Team: Revan, Canderous, T3 (excludes Juhani/Jolee/Mission/Zaalbar/HK) (L1369-1393). Revan lies that Meetra "still a Jedi" (L1407). Bastila pregnant (L1445); Revan senses the life once told (L1455). "doing it for our child" (L1483). Ebon Hawk leaves.
## Ch8 (L1523-1757) Bosthirda raid; Xedrix plan
- Scourge 10 m roof leap (L1555), TK-snaps 4 cams (L1557), slaughters ~20 separatists alone, Force bursts toss bodies, fear waves (L1575-1581), senses hidden people (L1581).
- Fake Xedrix holo (Sechel) (L1637). Nyriss: Scourge's talent "The greater your opponent's connection to the Force, the stronger you become" (L1741); "Against me, you would stand no chance" (L1745); Xedrix "old and infirm... hollow shell" (L1745). Scourge: "Fighting a battle I can't win isn't brave... It's stupid" (L1725).
## Ch9 (L1761-2021) Rekkiad landing, Clan Ordo
- Revan pilots Hawk through gale; Force-anticipation keeps ship aloft after clipping glacier (L1785-1787); crash-lands in snowdrift (L1857). T3 boosts sensors, finds camp (L1829-1845). Revan carries 2 blaster pistols, no saber shown (L1883-1887). Basilisk droids violate his surrender terms (L1905). Veela, clan chief, Canderous's wife (L2021). Alias "Avner" (L1989, L2013). Revan speaks Mando'a (L1959).
## Ch10 (L2025-2159) Scourge kills Darth Xedrix (Bosthirda cave)
- Scourge hides presence in "cloak of the dark side... invisible to the Force" (L2033). Xedrix blocks first strike (L2041); Xedrix too controlled to feed on, "like fighting a droid" (L2043). Kills both acolytes: Soresu -> Ataru switch, wall flip, boot-stomp kills female, saber throw kills male (L2053-2073).
- Xedrix lightning rips through Scourge's Force barrier (L2093-2095), Scourge stands back up (L2099). Xedrix mind-trick/hypnosis attempt fails (L2121-2135); Xedrix nearly drained ("faintest flicker", L2135). Scourge disarms with ease, kills, beheads (L2141-2151). Caveat: Xedrix explicitly a frail "shell". Xedrix: "Nyriss has you twisted in knots... game far beyond anything you can imagine" (L2103).
## Ch11 (L2163-2363+) Rekkiad - memory of Twin Spears; council of Clan Ordo
- Dream/memory: Revan & Malak on plateau, "searching with the Force" (L2181). Veela: Revan vanished 3 days after Malachor V (L2283); 100+ clans, thousands (L2285). Revan reveals Twin Spears location (L2305-2309) via "Republic records". Basilisks (6) (L2331). Revan uses Force to revitalize limbs (L2341).
- Clan Jendri pre-dawn attack (L2391-2495): Revan senses danger before alarm (L2391); Force-augmented blaster shots drop soldier + sniper >20 m (L2401); dodges fire; green lightsaber (L2427); cuts Basilisk stabilizer fin with leap (L2431), boards and kills pilot through seat (L2435), leaps clear (L2439). 3 Basilisks stay out of reach: "only a matter of time until they brought Revan down" (L2441) - narrative limit. Ordo Basilisks rout Jendri. Canderous rides Grizzer's Basilisk.
## Ch12 (L2499-2717) Scourge interrogates Sechel; Nyriss reveals conspiracy
- Severs two of Sechel's tendrils (L2537-2555). Nyriss staged assassinations herself (L2571); Xedrix really was with separatists but did not try to kill her (L2565, L2647).
- Nyriss: "The Emperor is mad. Unchecked, he will destroy us all." (L2603); plans war on Republic (L2609); Council alliance against him (L2625). Scourge: "she was a Sith Council member in the prime of her powers... would not be able to stand against her" (L2607).
- Emperor lore: born ~1000 yrs ago, Nathema, "used the dark side to conquer death and make himself immortal" (L2687-2695); travel to Nathema punishable by death (L2707).
## Ch13 (L2721-3011) Twin Spears tomb; Mask found; Veela standoff
- Climb; Revan opens heavy hatch with Force-strength (L2819). Faded dark-side tomb of exiled Sith Lord (L2847-2857). TK lifts heavy stone sarcophagus lid (L2887).
- MEMORY: Mandalore dying: "They promised me victory... used me and my people to test the Republic's strength." "The Sith." (L2867-2877). Datacron + Mask in crypt; Malak flashback "The Sith are not extinct" (L2897-2907).
- Veela: "Revan the Butcher" (L2927); Canderous: "Revan is not our enemy. Not now." (L2949); "You know Revan's reputation... And mine" (L2957); Revan: "I'm no ordinary Jedi." (L2975); Veela: "We killed dozens of Jedi during the war" (L2973).
- Fight (L2979-2997): Revan ignites before order finished, deflects 3 shooters' bolts, one deflected kill (L2981-2983); TK-hurls sarcophagus lid as grenade shield (L2987); knocked down by blast; saber throw kills last two (L2995). Canderous kills Veela (heart shot, L2993) + 2 others. Revan kills 3 total.
## Ch14 (L3013-3163) Dramath datacron; Canderous becomes Mandalore the Preserver
- Datacron: Dramath II; Lord Vitiate overthrew Dramath, renamed Medriaas -> Nathema (L3045). Sith emissary (red-skinned) manipulated Mandalore ~2 yrs before war, took Dramath's remains; "used the power of the dark side to manipulate him" (L3073-3087). Revan: "It would take more than some persuasive words and a subtle push from the Force to turn us to the dark side. Something else happened to us out there." (L3115). Storm world != Nathema (L3105). Canderous dons Mask: "I am Mandalore the Preserver" (L3143).
## Ch15 (L3167-3333) Nathema
- Nyriss's Tenebrae origin tale (L3193-3227): black eyes; killed father with thought age ~6; tortured mother months; age 10 "stripped his father [Dramath] of his power and his mind" (L3211); took Nathema by 13; Marka Ragnos named him Lord Vitiate (L3215); 100 yrs research; post-GHW summons Sith Lords; "what could one man do against a hundred Sith Lords?" (L3221); dominated minds, "devoured them" (L3225); "Every man, woman, and child on Nathema died that day... every living being touched by the Force was consumed" "stronger than any Sith who had come before" (L3227). Caveat: Nyriss "cannot guarantee the truth of this story" (L3205).
- Nathema: no Force, "chill of the Void" (L3257), droids' circuits overloaded (L3267), colors leached (L3269). Scourge ill (L3283). Nyriss senses another Force user on exit (L3285-3287); ion-cannons Hawk (L3301).
- Revan memory flood at Nathema (L3309-3313); "difficult to draw on the Force so close to the ravaged world" (L3317); crash; T3 reroutes power (L3325).
## Ch16 (L3337-3493) Revan captured
- Scourge's saber faded on Nathema (L3363). Revan ~40, brown robes (L3367). Nyriss: Revan & Malak "discovered Dromund Kaas by accident... captured" "Five years ago. The Emperor sentenced Revan to death" (L3379-3383); "He is powerful and extremely dangerous" (L3391).
- Drugged; interrogation 4 hrs; "His will was strong, as was his command of the Force. Even drugged to the edge of unconsciousness he was able to draw on it to help him endure" (L3465). Revan: "I killed him" (Malak) (L3435); "I'm going to make you work for it" (L3445).
- Nyriss theory: Emperor dominates minds; Voice, Hand, Imperial Guard under his spell (L3479, L3487); "more patient and careful than any being in the galaxy... might live for ten thousand more" (L3483).
## Ch17 (L3501-3715) PART TWO - Bastila, Meetra, T3 (~3,951 BBY: son 3 yrs old, Revan gone 4 yrs, L3505, L3513)
- KOTOR II recap: Kreia/Darth Traya rogue Jedi purge (L3511); Meetra emerged "Three years after Revan's unsuccessful attempt to locate her" and defeated Traya (L3515). Meetra: short brown hair, blue eyes, ~decade older than Bastila, Jedi Master robes (L3523). "special bond not unlike that of Padawan and Master" (L3525). Bastila hid with son (L3515). T3 recorded Scourge (L3589). Canderous aided Exile (L3567).
- T3 repaired Hawk nearly a year on Nathema (L3615), found disassembled HK-47 (L3617); Meetra repaired HK, memory core damaged (L3623); HK left with new Jedi Council, disappeared, likely seeking Revan (L3635). Meetra: "I will go to Nathema" (L3659). Bastila gives Revan's mask; she led strike team and took it (L3697-3707). Bastila: "I don't care... Not if that power helps bring him back to me." (L3711).
## Ch18 (L3717-3885) Meetra on Nathema
- Meetra cut off from Force after Malachor; "Many years had passed before she regained her connection to the Force, but in the end, surviving the trauma of Malachor V had given her the strength to defeat Darth Traya" (L3725). Nathema vs Malachor: Malachor a wound, Nathema "simply--gone" (L3731). Physically ill (L3741). Void pulling on her, near discorporation, resists by self-affirmation "I am Meetra Surik!" (L3803-3807). Saber dim (L3769). Flees system.
- Archive research: Vitiate fearmongering speeches (L3855); secret team found Dromund Kaas route (L3859-3865); ritual 3 days later; "he alone would have known the location" (L3871); "more powerful than Meetra could imagine" (L3873). Meetra assumes Vitiate long dead (L3877). Uses Force meditation to go days without food/sleep (L3851). "her mentor" (L3879).
## Ch19 (L3889-4065) Revan's cell, 3 years later
- Revan imprisoned 3 yrs in Nyriss's holding cells, drugged daily; formulas rotated as body becomes resistant (L3963). Torture ended after first months; Nyriss lost interest after 6 months (L3905).
- Scourge POV: "The Jedi's command of and connection to the Force was unlike anything Scourge had sensed in anyone else. Even though Revan was constantly drugged, it was impossible not to sense his strength." (L3907); Revan experienced both sides (L3909).
- Revan senses Scourge from the top of the stairs despite drugs (L3929). Revan manipulates Scourge (L3937-3953): "To Revan he was nothing more than a tool" (L3931); "incredible potential... arrogant, overconfident, and ambitious" (L3937). Revan's lie about a vision (L4019); seeds dream-manipulation (L4049-4051). Revan's Force-vision of Meetra coming (L4059-4065). Scourge: Nyriss "refuses to take any real action" (L3973).
## Ch20 (L4069-4337) Meetra on Dromund Kaas
- Senses Revan on planet (L4077). Mind trick on customs official (L4113-4115). Sells gems to Larvit; meeting with Sechel at Nexus Room.
- Sechel recognizes Scourge's image (L4263), takes fee; Meetra tries to buy slave (L4301).
## Ch21 (L4339-4661) Scourge debates; Meetra kills Murtog's team
- Scourge mulls Revan's "You will understand in time" (L4343). Force-squeezes Sechel's windpipe casually (L4399).
- Cave ambush: Meetra senses premonition + several beings in dark (L4465, L4487); T3 headlamp blinds NV goggles (L4507); she back-handsprings, leaps, kills soldier through armor joint (L4513-4515), Force-push kills 2nd into wall (L4517), deflects bolts (L4519), T3 flamethrower kills 3rd (L4521), two-handed slash through armor kills 4th (L4523). "Four soldiers... heavy armor" incl. Murtog (dead per L4727). Blue saber (L4551).
- Scourge POV on Meetra: "impressed with how easily she had dismantled Murtog and his handpicked team"; "kept her emotions at arm's length so the Force could flow through her unhindered" (L4553-4555); "He didn't know which of them would prove the stronger" (L4557). Scourge: "You're a Jedi... He saw you. He knew." (L4533). Alliance offered. Meetra: "I will hunt you down." (L4659). Scourge: "Save your anger for the Emperor... He is the real enemy." (L4661).
## Ch22 (L4665-4889) Scourge kills Sechel; conspiracy files
- Scourge tails Sechel, throat strike, takes encrypted data disks, breaks Sechel's neck (L4713-4797). "three days" window (L4747).
- Meetra POV: "Revan's command of the Force was greater than that of anyone else she had ever met" (L4811); Scourge "wholly consumed by the dark side" (L4813). Senses Scourge alone (L4819). T3 decrypts in 1.5 hrs (L4843). Conspiracy >decade, no progress (L4845).
- Scourge: Nyriss "has hundreds of guards and dozens of acolytes trained in the dark side" (L4883). Plan: "get the Emperor to help us" (L4887).
## Ch23 (L4891-5101) Scourge before the Emperor (citadel throne room)
- Imperial Guard fanatical (L4907). No weapons check: "testament to the Emperor's unfathomable power" (L4983). Scourge reasons Emperor "not omniscient" since he never sensed Nyriss (L4987-4989).
- Emperor: dark side "with such intensity that it caused a faint rippling of the air" (L5001); eyes "as black as the Void itself" (L5009); voice "as if a great multitude were speaking" (L5019); Scourge theorizes consumed Nathema spirits inside him (L5021); "no longer a member of the Sith species... a being unique in the galaxy" (L5047); seems to communicate telepathically with someone outside (L5053); "You already have." (L5045); promises Nyriss's Council seat (L5067); MIND-BRUSH: "Scourge cried out in anguish as the Emperor's mind brushed against his, then he collapsed to the floor, shaking like a child... indescribable horrors... unbearable Void" (L5075). Captain Yarri: Nyriss to be purged with entire staff (L5091).
## Ch24 (L5105-5441) Stronghold purge; Revan freed; NYRISS DUEL
- Meetra disguised as slave. Imperial Guard artillery assault; fanatic waves overrun Nyriss's troops; Nyriss's Twi'lek slave dead (L5189).
- Revan drugged; "Had his mind been able to focus, he could have purged them" (L5223); Force-amplifies guard's fear and talks him down (L5241-5285), "my word as a Jedi" (L5245); "unarmed he was no match for the Sith" (L5307, Revan POV under drugs). Unconsciously suppressed drugs then collapsed (L5331). Scourge injects antidote (L5335). Revan's mask from Bastila -> "all his lost memories came flooding back"; collapses (L5349-5351).
- DUEL: Nyriss vs Scourge + Meetra (L5381-5415): lightning kills 2 guards on stairs (L5381); lightning burst (L5393); leap, "speed and ferocity of a dark side warrior in her prime" (L5395); Scourge "barely managed to parry" (L5397); "The Jedi was clearly overmatched... forced down to one knee" (L5399); Scourge Force-blast vs Nyriss barrier (L5403); Nyriss wave tosses Scourge (L5405); lightning hits Meetra, barrier but knocked down (L5407); Scourge: "Nyriss was too powerful" (L5411). "I am Darth Nyriss... conqueror of Drezzi, the destroyer of Melldia" (L5413).
- REVAN (masked): intercepts "A dozen bolts of lightning", absorbs them (L5419-5421), "I am Revan reborn... And before me you are nothing." (L5423), redirects; rips her Force shield, reduces her to "a pile of charred ash" (L5425). Scourge: "If anyone had the strength to stop the Emperor, it was this man." (L5437).
## Ch25 (L5445-5657) The cave; memories; Emperor purges Dark Council
- Meetra POV: mask makes him "indomitable, invincible--a legend come to life" (L5465); "He had easily bested Darth Nyriss, but the Emperor was a much greater opponent" (L5471). Son named Vaner (L5505). Meetra: "Meetra loved Revan, but not in that way... her mentor... deep admiration and intense devotion" (L5521).
- Revan to Meetra: "I was told you had been cut off from the Force, but I can sense its power in you. I always knew you had great potential, but you have become far greater than I could ever have imagined." (L5535); "I can sense you have walked a path even I would not dare to tread." (L5539). Meetra: "Without your teaching, I could never have become what I am today." (L5541).
- Emperor killed all 12 Dark Council: Guard on Nyriss + 2 others; other 9 summoned to citadel, "None of them left alive" (L5575-5579). Martial law, planetary quarantine (L5587-5589).
- REVAN'S BACKSTORY (memories restored): Revan & Malak spent months on Dromund Kaas posing as mercs; bribed Guard led them into trap; "We underestimated his power. When we confronted him, he didn't even have to fight us. Instead, he broke our wills. He dominated our minds" (L5597-5601); wills twisted his instructions, dark side let them block memory, "partially freeing us" (L5603); Emperor assumed they failed (L5607).
- Revan on Emperor: "The dark side is like a cancer inside him... He has consumed an entire world, but he still hungers... He is terrified of death." (L5617); "the only way to preserve what he has accomplished is to annihilate every potential threat in the galaxy" (L5621). Scourge: "Emperor over an empty and lifeless galaxy" (L5623). Nathema ritual "took days, if not weeks" and needed hundreds of Sith (Scourge citing Nyriss, L5635); Revan: "He's stronger now" (L5637). Revan: "I can shield my mind from being dominated by his will, and I can show you how to do the same." (L5651).
## Ch26 (L5661-5785) Scourge's vision
- Scourge's first Force vision: Emperor defeats all three; Revan motionless, Meetra and Scourge "twisted and broken" (L5671-5677); Scourge recognizes it as a true vision (L5685-5687). Revan admits vision-lie bluff (L5713) but did have Meetra vision (L5721). "The dark side obscures my sight" (L5747). Revan: "there can be victory even in defeat... buy time... a few decades" (L5771); "a champion of the light will one day rise... I may be that champion" (L5775). Scourge: "as mad as the Emperor" (L5777).
## Ch27 (L5789-5971) Assault on the citadel
- Meetra warrior's trance (L5795-5797). Revan "learned to balance on the knife-edge between them, drawing on both the light and dark sides for strength" (L5803). Imperial Guard "formidable opponents, even for a Jedi", draw on Emperor's power (L5849).
- Revan on first meeting: "he had never faced an enemy with that kind of power... In their last meeting he had overwhelmed Revan completely; it wasn't even fair to call it a battle. Revan had grown since then. He was far more powerful now, but was he a match for the Emperor? Alone, probably not." (L5857-5861); "knew he couldn't go toe-to-toe with the Emperor by himself for very long" (L5875).
- Captain Yarri was the Guard who led Revan & Malak into the trap (L5883). Fight: Revan side kick; T3 blaster kills guard; Meetra vs two guards (electrostaff parries saber, L5901); Revan Force-blasts durasteel doors open (L5905); somersault over guard (L5909); Force push only staggers guard - Guards draw on Emperor's power near him (L5911); feint, throat cut kill (L5913-5915); TK rips vaulted archway down on reinforcements (L5919); TK slams doors (L5923); T3 seals with foam (L5951).
- Scourge: "expert swordsman; at the Academy even the instructors had been reluctant to face him" (L5939); clipped by Yarri, switches hands (L5947-5949); kills guard + Yarri (hip cut, crushes hand, decapitates) (L5963-5967). Meetra kills her two (L5969).
- Emperor: "I did not expect you to return" (L5929).
## Ch28 (L5973-6103) DUEL: Revan vs the Emperor; Scourge's betrayal
- E1: Emperor energy wave sweeps Revan off feet, flying (L5979); Revan rolls, re-advances (L5981).
- E2: Emperor attempts domination ("trying to crush his will", L5983); Revan ready: lets light & dark "flow through him like twin rushing rivers... released it in its purest form" (L5985); brilliant flash; Revan staggered, Emperor "unprepared and with much of his strength diverted to his effort to dominate Revan's mind, was sent flying backward" (L5987).
- E3: Emperor lightning bolt from knee; Revan intercepts with saber, charge "stopped... dead" (L5989-5991). Three more bolts: bats first, ducks second, deflects third into Emperor's chest, slides him meters back; Emperor's "primal hiss of hate" (L5993-5995); robes smoking/singed (L5997).
- E4: Emperor's storm, "A dozen bolts of purple lightning"; Revan tries to absorb as with Nyriss but "the Emperor was infinitely more powerful than Darth Nyriss had ever been" (L6001); face melts to mask (L6003).
- E5: T3 flamethrower; Emperor "cocooned himself in the Force" to avoid incineration, breaking focus (L6005). Revan collapses (L6007). Emperor obliterates T3 with "full power of the Force" (L6009-6011). Revan Force-heals but needs time (L6015, L6019). Emperor picks up Revan's saber to kill (L6017).
- E6: Meetra Force-guided saber throw knocks blade from Emperor's hand (L6035); "Meetra's trick had caught him by surprise"; Scourge: had she aimed at the Emperor "she could have ended his life" (L6037). Emperor "hesitation and uncertainty... evaluate the strength and weaknesses of his new foe" (L6041). Revan stands, Force-pulls saber (L6043).
- Dialogue: Revan "You can't defeat all three of us... United, we are stronger than even you." Emperor: "That remains to be seen." (L6055-6057).
- Scourge's crux vision: million futures; "the Emperor lying defeated at the feet of a powerful Jedi--but that Jedi was neither Revan nor Meetra" (L6061-6067). Stabs Meetra between shoulders; "dead before she hit the floor" (L6069-6071). Emperor uses distraction: lightning to Revan's chest, unconscious (L6071-6073). Scourge lies. Emperor TK-stops Scourge's killing blow "as if an invisible and impossibly strong hand had seized his wrist" (L6093); "Revan can still be of use to me" (L6095).
## Ch29 (L6107-6211) Emperor's Wrath; Revan in stasis
- Scourge made Emperor's Wrath (L6119); immortality ritual with machinery, generators, IVs (L6115); permanent agony -> numbness: "This is the price of immortality" (L6163-6167). Scourge: "the Emperor would have won regardless" (Scourge POV, L6129). Waits for champion (L6145).
- Revan in stasis cage; Meetra's spirit stays, feeds him strength through barrier (L6175-6181). "Revan could feel the Emperor feeding on him, drawing on his power to sate his endless hunger... a dozen parsecs... unbreakable mental link" (L6189). Emperor probes mind; Revan resists ("mentally he was strong enough to wage war against the Emperor", L6195); link two-way; Revan nudges Emperor's caution, fear of death, anti-invasion thoughts (L6197-6199). Revan: "inevitable that one day the Emperor would win their endless battle of wills" (L6205). "It was impossible to know what would have happened if Scourge had not betrayed them... They might have lost anyway, but they also might have defeated the Emperor" (Revan POV, L6201).
## Epilogue (L6215-6291) ~50 years later
- Bastila old; son Vaner Shan, possible Chancellor; Force skips to grandkids Reesa, Bress. Bastila senses Revan sometimes (L6259). "He went to stop it, and I know he succeeded." (L6279).

---

