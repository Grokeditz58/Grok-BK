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


> **SUPER-DEEP CHARACTER WRITE-UPS (Oct 19, 2026):** all 24 analyses for this game were rewritten in full. Each has background, personality, a scene-by-scene arc with light/dark variants, relationships, abilities (lore, plus mechanics flagged as such), feats, statements, duels, cut content (RCM), verdict implications, gaps and complete verbatim quote banks. They are in **[kotor-1-characters/](kotor-1-characters/README.md)**, split out for size. The shorter analyses below are kept as summaries.

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


> **SUPER-DEEP CHARACTER WRITE-UPS (Oct 19, 2026):** all 24 analyses for this game were rewritten in full. Each has background, personality, a scene-by-scene arc with light/dark variants, relationships, abilities (lore, plus mechanics flagged as such), feats, statements, duels, cut content (RCM), verdict implications, gaps and complete verbatim quote banks. They are in **[kotor-1-characters/](kotor-1-characters/README.md)**, split out for size. The shorter analyses below are kept as summaries.

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
