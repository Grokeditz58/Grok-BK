# notes148 EGVV 1996 — quote-image QA v3, checkpoint CP2a (6 of 51; 10 of 51 with CP1) — 2026-11-09

Scope: **only** the 6 crops below (printed pp. 8, 10, 18, 22, 30, 32 / scans 023, 024, 028, 030, 034, 035). Together with CP1's 4 already-packaged crops (p138, p180-tie-limits-tight, p174, p162), **10 of 51** EGVV quote images now have an accepted v3 QA package. **41 remain:** 6 were already recut in the earlier CP2 wave (p036, p038, p040, p044, p046, p052) but have **no accepted audit in this package**; **35** have not been recut or re-audited here. This package does not start that next six.

CP1's 4 crops and package were not touched. The six live quote JPEGs listed below were not modified in this packaging step. WIP `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp2a/records.md` was not edited (records 1–3 left as accepted). An earlier unverified writeup `AUDIT-QUOTE-QA-v3-CP2-2026-11-09.md` remains in the materials folder; **this CP2a audit is the accepted record for these six.**

Source: `primary/essential-guides/eg-vehicles-1996/Essential-Guide-to-Vehicles-and-Vessels-1996.pdf` (RO12wBBC; 121 PDF pages, one embedded gray JPEG per PDF page = a two-page spread). Scan number = PDF page number. Printed folios were read from each spread's footer; all six sit on the left page of the spread. Folios agree with k = S − 19.

Method: native `pdfimages` crops, stacked in reading order (left column → right column). Where art intrudes, a staircase of native rectangles leaves the art out without redrawing text. Each crop was read back against the native source. OCR was used only for coordinates. Boxes are from `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp2a/boxes-cp2a.json`.

Old SHA256 values were checked against `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp2r/shas.txt`, `backup-148-cp2-20261109-191248/SHA256SUMS`, and `backup-pre-v3/148.sha` (all six old hashes agree). For p022, `shas.txt` lists an intermediate rebuild (`79fe39d1…`, 697×1467, 397584 B) as “new”; the **installed live file** is a later cleanup (`253b15f1…`, 697×1464, 387446 B), which is the file in this package.

Transcription: running text as printed, with italics as `*…*`. A hyphen at a printed line end is noted as `foo-/bar` in the notes, not kept as a mid-word hyphen in the running verbatim. **A spaced slash ` / ` in the verbatim blocks below is a paragraph separator, not a character printed in the book.** Slashes inside tokens (TIE/In, Griffyn/Y2TG) *are* printed. No per-record clock times are asserted in this audit (a placeholder “19:4x CST” in the WIP records file is ignored).

Character facts below are taken **only from the six audited crops**. Adjacent text that was deliberately excluded from a crop is noted as adjacent and is not treated as a fact from the quote image. On p.32 the surname Rendar appears only in adjacent left-column source; it may identify the speaker, but the quoted passage prints “Dash.”

---
## 1. egvv1996-p008-scan023-a9-combat-disappointing.jpg — A-9 VIGILANCE
- Locator: PDF p.23 / scan 023 / printed **p.8**. right column of left page (printed p.8); three-part staircase around canopy art. Native source 3708x2213 gray 200ppi.
- Native boxes (`boxes-cp2a.json`): [900, 987, 1586, 1313] (scan 023 p.8, right col); [926, 1313, 1586, 1386] (right col cont.); [992, 1386, 1586, 1428] (right col cont.).
- Old SHA256 `177156370fcdef66a9af0e518d40d046ed7f4f68797980c978d2e7e3ef131bf0` → **new `310df625740c9a4130994b20eeef34fd383afaa60c0a788622305e7b86bd9eb7`** (686x591, 153396 B).
- Opening: “While Kuat Drive Yards promised the Empire a superior fighter, combat results have been consistently disappointing.” / ending: “future New Republic fighters.”
- Start = paragraph start (prev para ends "missions against ground targets."); end = paragraph end "future New Republic fighters." followed by art. No partial lines, no art in crop.
- Hyphenations / spellings: "disappoint-/ing", "exam-/ined" (complete in crop)
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
While Kuat Drive Yards promised the Empire a superior fighter, combat results have been consistently disappointing. While the ship is indeed faster than the TIE interceptor, it has been shown to be no more maneuverable, and its hull is actually significantly weaker. The Empire purchased a fighter that is as limited in its utility as is the New Republic's A-wing fighter. It is believed that Kuat designers are developing an *improved* A-9, which should be far tougher. New Republic technicians have thoroughly examined the A-9, and while not amazed by what they see, they intend to use some of its design elements in future New Republic fighters.
```

- Remaining defects: none.
- Character facts (this crop only): none (no named characters).

---
## 2. egvv1996-p010-scan024-awing-fragile-one-hit.jpg — A-WING FIGHTER
- Locator: PDF p.24 / scan 024 / printed **p.10**. left column of left page (printed p.10); single box. Native source 3708x2213 gray 200ppi.
- Native boxes (`boxes-cp2a.json`): [188, 750, 884, 1294] (scan 024 p.10, left col).
- Old SHA256 `32d04765711e9cbaef18cf1a4b3369cbd68c6a5811c0f5523eb21e272ec19ca2` → **new `8f39639d48bcc0f75b595247e04f19a1ceb2c5367d9b15ed1088846c84ba09fa`** (696x582, 150468 B).
- Opening: “The small, wedge-shaped ship continues to be the Alliance's main interceptor fighter.” / ending: “combat.”
- Start = paragraph start (prev para ends "causing the ship to crash into the Death Star."); end = paragraph end "combat." (next para "The A-wing has two wing-mounted pivoting blaster can-" excluded). Two full paragraphs; no partial lines/art.
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
The small, wedge-shaped ship continues to be the Alliance's main interceptor fighter. It is an exceptionally difficult ship to fly because it is constantly pushing the limits of performance. The A-wing is constantly subjected to incredible stresses, and its engines, hull, and weapons systems require constant maintenance. Since it is only 9.6 meters long, each ship component is wedged into the cramped hull, and even the lightest hit can cause critical system failures. The pilot is almost totally exposed to enemy fire. / While fast, the A-wing is fragile and is easily damaged by enemy fire. One hit is often enough to destroy the vessel. A-wing pilots must rely on the ship's blistering speed and their own willingness to take foolish chances to survive in combat.
```

- Remaining defects: none.
- Character facts (this crop only): none (no named characters in the crop).
- Adjacent, not in crop: NOT used as a fact from this quote image: the preceding paragraph on the same page (outside the crop) mentions Arvel Crynyd ramming the Executor's bridge with an A-wing.

---
## 3. egvv1996-p018-scan028-chariot-thrawn-hyllyard.jpg — CHARIOT LAV
- Locator: PDF p.28 / scan 028 / printed **p.18**. right text column of left page (printed p.18); x 880–1576, left half of the spread. Native source 3628x2181 gray 200ppi.
- Native boxes (`boxes-cp2a.json`): [880, 1034, 1576, 1368] (scan 028 p.18, right col).
- Old SHA256 `d2e761b22f0cd59da134e00efac8533911a851bb9a0de5906ca93a006f83bc9b` → **new `684c77251a7becc5be72a3a3c4fa1924981bec110306baf2d5152a722de6cd76`** (696x372, 106841 B).
- Opening: “As Grand Admiral Thrawn prepared for his campaign against the New Republic, he conducted a systematic upgrade of the Chariot and other aging repulsorcraft.” / ending: “Luke Skywalker toppled a ten-meter-tall stone arch on top of it.”
- Start = paragraph start (prev para ends "...to central military command."); end = paragraph end and end of column text (whitespace then art below). No partial lines/art.
- Hyphenations / spellings: "coordi-/nate". Spellings as printed: "Myrkr", "Hyllyard City", "ten-meter-tall".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
As Grand Admiral Thrawn prepared for his campaign against the New Republic, he conducted a systematic upgrade of the Chariot and other aging repulsorcraft. The Chariot's laser cannon was replaced with a more powerful swivel gun. Thrawn used a command speeder to coordinate his search for Luke Skywalker and Mara Jade in the dense forests of Myrkr, at least until that command speeder was crushed in the town square of Hyllyard City when Luke Skywalker toppled a ten-meter-tall stone arch on top of it.
```

- Remaining defects: none.
- Character facts (this crop only): Grand Admiral Thrawn — before his campaign against the New Republic, systematically upgraded the Chariot and other aging repulsorcraft (Chariot laser cannon replaced with a more powerful swivel gun); used a command speeder to coordinate his search for Luke Skywalker and Mara Jade in the dense forests of Myrkr. Luke Skywalker — toppled a ten-meter-tall stone arch onto that command speeder in the town square of Hyllyard City, crushing it. Mara Jade — was searched for (with Luke) by Thrawn in Myrkr's forests. The source does NOT state that Thrawn was aboard the speeder, nor any injuries.

---
## 4. egvv1996-p022-scan030-cloakshape-combat-mods.jpg — CLOAKSHAPE FIGHTER
- Locator: PDF p.30 / scan 030 / printed **p.22**. left page of the 22–23 spread (footer "22" / "23"); left column continuing into the right column, staircase around art. Native source 3700x2200 gray.
- Native boxes (`boxes-cp2a.json`): [145, 958, 842, 1396] (scan 030 p.22, left col); [884, 446, 1576, 1284] (right col, continues); [1050, 1284, 1576, 1322] (right col cont.).
- Old SHA256 `639ceda5951aff21594c8f0e27bdd3c4ebb7e52c1f3b6b9d33db7ef8dbf0f75f` → intermediate rebuild `79fe39d1324f8da1e72e95517af6b4962a27298388cf52acc920706f7292eeaf` (697x1467, 397584 B) → **installed cleanup `253b15f117563e399cf788bc162310e1ff75ece757d4174de911936490d26c16`** (697x1464, 387446 B).
- Opening: “CloakShape fighters are designed for atmospheric and short-range space combat; their power plants aren't strong enough for prolonged missions in space.” / ending: “proved him wrong.”
- Start = paragraph start (prev para ends "assault starships."); end = paragraph end "proved him wrong." followed by art (end of column text). No partial lines, no art in crop. Column wrap "stock specifications. The" / "designers…".
- Hyphenations / spellings: "gener-/ator", "rein-/forced". In-line compounds as printed: "short-range", "after-market", "strap-on", "self-contained", "rear-mounted", "add-on", "hands-on", "Y-wing", "fire-linked", "concussion-missile". No italics in this crop.
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
CloakShape fighters are designed for atmospheric and short-range space combat; their power plants aren't strong enough for prolonged missions in space. In stock form, they lack a hyperdrive and are often paired with carrier ships. / Like many older fighters, the CloakShape trades speed for durability: in an era when starfighter designers are favoring firepower over a sturdy hull, the CloakShape promises to take a beating and bring the pilot home. / CloakShapes have been around so long that few of these vessels still meet the manufacturer's stock specifications. The designers built the ship to be easily modified, and it's not uncommon to find that only the original hull remains in a given ship. The hull has enough room for heavier thrusters, added weapons, or a larger fuel supply; with some work, a mechanic can even add shield generators. / There are also several after-market modification kits designed specifically for the CloakShape. One kit has a strap-on hyperdrive sled with a self-contained power generator, while another has a rear-mounted maneuvering fin that dramatically improves the CloakShape's handling. The maneuvering fin add-on is so common that most people think it is part of the ship's original design. Anyone with the time for hands-on work could probably produce a modified CloakShape that could compete with an Alliance Y-wing fighter, and have enough money left over to buy a used freighter. / The CloakShape destroyed on Nar Shaddaa included mounted fire-linked double laser cannons and a pair of concussion-missile launchers. Adding the launchers' large ammo bays meant stripping out the shield generators in order to make room. The bounty hunter thought his reinforced hull would be enough to get him through a battle; Shug Ninx's automated laser cannons proved him wrong.
```

- Remaining defects: none (passage complete).
- Character facts (this crop only): An unnamed bounty hunter — thought his reinforced hull would be enough to get him through a battle; the CloakShape destroyed on Nar Shaddaa included mounted fire-linked double laser cannons and a pair of concussion-missile launchers; adding the launchers' large ammo bays meant stripping out the shield generators to make room. Shug Ninx — his automated laser cannons proved that bounty hunter wrong. This crop does not name the bounty hunter, and does not mention Han Solo or the *Millennium Falcon*.
- Adjacent, not in crop: NOT used as facts from this quote image: the preceding left-column paragraphs (outside the crop) say a CloakShape pursued the *Millennium Falcon* on the smugglers' moon of Nar Shaddaa; the ship, owned by bounty hunters out to claim the Hutt bounty on Han Solo's head, was destroyed by the automated laser cannons in Shug Ninx's access tunnel.

---
## 5. egvv1996-p030-scan034-vader-tie-x1-limitations.jpg — TIE ADVANCED x1 / DARTH VADER'S TIE FIGHTER
- Locator: PDF p.34 / scan 034 / printed **p.30**. left page of the 30–31 spread (footer "30" / "31"); left and right text columns of printed p.30. Native source 3700x2200 gray.
- Native boxes (`boxes-cp2a.json`): [160, 833, 856, 1418] (scan 034 p.30, left col); [900, 428, 1586, 1416] (right col, continues).
- Old SHA256 `c1ad323323803492f524195331a63978ecedcd426086abba886f1dc52d6be2ce` → **new `371c02b29e776a8fbea5a0b529f0200d6adf4a53351373322b113de59429d606`** (696x1667, 443081 B).
- Opening: “The TIE Advanced x1 featured a custom-designed spaceframe and a reinforced durasteel-alloy hull, with an elongated rear deck and matching bent wings covered with solar panels.” / ending: “the end of production for the TIE Advanced x1.”
- Start = paragraph start (prev para ends '...the TIE Advanced (TIE/Ad) ship dubbed the "TIE Avenger."'); end = paragraph end "the TIE Advanced x1." followed by art (end of column text). No partial lines, no art in crop. Column wrap "a modest hyperdrive" / "(although the navigation computer…coordinates)."
- Hyphenations / spellings: "can-/nons", "excep-/tion", "ves-/sels", "maneuver-/able". In-line compounds as printed: "custom-designed", "durasteel-alloy", "front-mounted", "life-support". Spellings as printed: "I-S3a" (capital I with visible serifs), "P-s5.6" (lowercase s), "x1", "TIE interceptor" (lowercase i, three times), "ten sets".
- Qualification: TIE/ln vs I/l: both occurrences of the standard/line-fighter designation are written in the verbatim as TIE/In. In this face, capital I and lowercase l are both unhooked verticals at cap/ascender height and cannot be certified from the native 3700-wide scan. The letter after the slash matches the I in the adjacent "TIE" more closely than a distinctive tailed l, and both occurrences are consistent with each other; it is still possible the intended designation is TIE/ln. Flagged, not silently resolved from later entries or canon.
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
The TIE Advanced x1 featured a custom-designed spaceframe and a reinforced durasteel-alloy hull, with an elongated rear deck and matching bent wings covered with solar panels. The vessel mounted a Sienar Fleet Systems (SFS) I-S3a solar ionization reactor and paired SFS P-s5.6 twin ion engines for a far more powerful drive system than that of the standard TIE/In. Speed was only slightly improved over earlier models, due to the added mass and to the fact that a good deal of the extra power was bled off to the shield generators. The TIE Advanced x1 was less maneuverable than standard TIE fighters, but it could take far more punishment than could the fragile TIE/In ships. / The TIE Advanced x1 sported twin heavy blaster cannons in a fixed, front-mounted position. In a major exception to standard Imperial military policy, the TIE Advanced x1 featured shield generators and a modest hyperdrive (although the navigation computer could store only ten sets of jump coordinates). / The TIE Advanced x1 lacked a life-support system, and the pilot had to wear a fully contained flight suit with an internal oxygen supply. Pilots were strapped into an adjustable shock couch with foot yokes and a hand control panel. / The TIE Advanced x1 was initially produced in only very modest numbers. Lord Darth Vader received one of the vessels for his personal missions; most of the other ships were deployed to elite Imperial squadrons for field testing. By the time of the Battle of Hoth, TIE Advanced x1 fighters had been deployed to a number of Navy fleets, including Lord Vader's Star Destroyer squadron. / The Empire decided not to order the TIE Advanced x1 in large quantities, citing the excessive cost. Privately, some Imperial Navy strategists admitted that the Navy was afraid to purchase a fighter with a hyperdrive, fearing that it would provide an excuse to slash orders for new capital starships. / The Empire instead opted for the TIE interceptor, which featured the TIE Advanced x1's drive system, but in a more compact ship. While the TIE interceptor lacked hyperdrives and shields, it was blindingly fast, incredibly maneuverable, and significantly cheaper than the TIE Advanced x1. By the Battle of Endor, the large increase in TIE interceptor production meant the end of production for the TIE Advanced x1.
```

- Remaining defects: none (passage complete).
- Character facts (this crop only): Lord Darth Vader — received one of the TIE Advanced x1 vessels for his personal missions. By the time of the Battle of Hoth, TIE Advanced x1 fighters had been deployed to a number of Navy fleets, including Lord Vader's Star Destroyer squadron. This crop does not say Vader used the ship at the Battle of Yavin, and does not describe any combat outcome.
- Adjacent, not in crop: NOT used as facts from this quote image: the opening paragraph on the same page (outside the crop) states that the TIE Advanced x1 Prototype was the fighter used by Lord Darth Vader at the Battle of Yavin, and mentions refinements later incorporated into the TIE interceptor and the TIE Advanced (TIE/Ad) ship dubbed the "TIE Avenger."

---
## 6. egvv1996-p032-scan035-outrider-mods-quote.jpg — OUTRIDER (YT-2400)
- Locator: PDF p.35 / scan 035 / printed **p.32**. left page of the 32–33 spread (footer "32" / "33"); right text column of printed p.32, art cut out by a six-rectangle staircase. Native source 3700x2200 gray.
- Native boxes (`boxes-cp2a.json`): (scan 035 p.32, right col, art cut out) [934, 750, 1608, 1365]; [1055, 1365, 1608, 1439]; [1183, 1439, 1608, 1547]; [1279, 1547, 1608, 1618]; [1316, 1618, 1608, 1837]; [1386, 1837, 1608, 1912].
- Old SHA256 `aca0e5c9a9ff0fe96dda098e8fddcb8d28702ce3174692b3f40625173535089f` → **new `f83c57fc8fc68f276850e966c4ccdd867fb2f597ab3c66ef6866e377737ce37e`** (674x1200, 257158 B).
- Opening: “Dash, being a typical smuggler, decided to take advantage of the YT-2400's adaptability.” / ending: “scattered me across space.”
- Start = paragraph start (prev para in the same right column ends "…directly opposite the bracing arms."); end = end of the quoted sentence and of column text ("across space." then whitespace to the footer rule). No partial lines; art is cut out by the staircase.
- Hyphenations / spellings: "advan-/tage", "mil-/itary", "nor-/mally", "signifi-/cantly", "emotional-/ly", "say-/ing"; "ventral-mounted" is broken at its compound hyphen ("ventral-" / "mounted"). Italics as printed: *Outrider* (four times, including in the spoken quote), *Millennium Falcon's*, *highly*. Em dash as printed in "rating—slower". Spaced ellipsis as printed: "the best . . . she's". Curly quotes around Dash's line. Spellings as printed: "KonGar KGDefender", "SoroSuub", "Griffyn/Y2TG", "Class 0.75", "Class 0.50", "Class One or Class Two", "Dymek", "Corellian 1D".
- Qualification: "uncommon": native source (and the crop) show a defective initial letter on "uncommon" in "It's not uncommon for smugglers…". The left side of that letter is a weak, quote-shaped mark rather than a clearly inked u-stem. This is not a crop clip: the staircase left edge (x=1183) sits to the left of the mark, in whitespace, with the ship art still farther left. The reading "uncommon" is from word context; a clean "u" is not claimed as a clearly printed glyph.
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
Dash, being a typical smuggler, decided to take advantage of the YT-2400's adaptability. His first step was to replace the engines with three stolen KonGar KGDefender military-grade ion engines. A modified SoroSuub Griffyn/Y2TG hyperdrive gives the *Outrider* a Class 0.75 hyperspace speed rating—slower than the *Millennium Falcon's* Class 0.50 hyperdrive but far faster than most military vessels, which are either Class One or Class Two. Powerful shield generators and a *highly* illegal sensor stealth system make the *Outrider* a perfect smuggling ship. / A pair of heavy Dymek double laser cannons, personally modified by Dash for greater range, are dorsal- and ventral-mounted on standard Corellian 1D servo turrets. They normally are manned but can be controlled via the targeting computer in the cockpit, although accuracy is then significantly reduced. Two forward-firing concussion-missile launchers are mounted on the cockpit tube and have a magazine of three missiles each. / Dash has relied on this ship to save his life countless times. It's not uncommon for smugglers and other spacers to get emotionally attached to their vessels, and Dash is no exception. He has been heard saying, “I owe the *Outrider* the best . . . she's brought me home when any other ship would have scattered me across space.”
```

- Remaining defects: none (passage complete).
- Character facts (this crop only): Dash — described as a typical smuggler; took advantage of the YT-2400's adaptability by replacing the engines with three stolen KonGar KGDefender military-grade ion engines; the *Outrider* has a modified SoroSuub Griffyn/Y2TG hyperdrive (Class 0.75, slower than the *Millennium Falcon's* Class 0.50 but faster than most military Class One or Class Two vessels), powerful shield generators, and a *highly* illegal sensor stealth system; he personally modified a pair of heavy Dymek double laser cannons (dorsal- and ventral-mounted on standard Corellian 1D servo turrets) for greater range; two forward-firing concussion-missile launchers on the cockpit tube have a magazine of three missiles each; he has relied on this ship to save his life countless times, and has been heard saying, “I owe the *Outrider* the best . . . she's brought me home when any other ship would have scattered me across space.” The crop never uses the surname Rendar. Quote this image as “Dash,” as printed.
- Adjacent, not in crop: The left column of the same page (outside the crop) identifies him as Dash Rendar and may be used only to identify the speaker of this quote; it is not part of the quoted passage. That adjacent text is not repeated here as a fact drawn from the quote image.

---
## Handoff (character facts from these 6 crops only)
- A-9 (p.8) and A-wing (p.10): no named characters in the crops. Do not attach Arvel Crynyd / Executor to the p.10 quote image.
- Chariot (p.18): Grand Admiral Thrawn upgraded the Chariot (laser cannon → more powerful swivel gun) before his campaign against the New Republic, and used a command speeder to coordinate his search for Luke Skywalker and Mara Jade in the forests of Myrkr, until Luke toppled a ten-meter-tall stone arch onto that speeder in the town square of Hyllyard City, crushing it. The source does **not** say Thrawn was aboard, and does not mention injuries.
- CloakShape (p.22): an unnamed bounty hunter thought his reinforced hull would get him through a battle; that CloakShape, destroyed on Nar Shaddaa, had fire-linked double laser cannons and a pair of concussion-missile launchers, with shield generators stripped to make room for the launchers' ammo bays. Shug Ninx's automated laser cannons proved him wrong. Do not cite Han Solo or the *Millennium Falcon* from this quote image.
- TIE Advanced x1 (p.30): Lord Darth Vader received one of the vessels for his personal missions. By the Battle of Hoth, TIE Advanced x1 fighters had been deployed to a number of Navy fleets, including Lord Vader's Star Destroyer squadron. Do not cite Yavin use from this quote image. The TIE/In (or TIE/ln) glyph is qualified above.
- Outrider (p.32): quote **Dash** as printed. The passage describes his typical-smuggler modifications to the *Outrider* (stolen KonGar KGDefender engines; modified SoroSuub Griffyn/Y2TG Class 0.75 hyperdrive, slower than the *Millennium Falcon's* Class 0.50; *highly* illegal sensor stealth; Dymek cannons he modified for greater range; two forward-firing concussion-missile launchers with three missiles each) and the spoken line, “I owe the *Outrider* the best . . . she's brought me home when any other ship would have scattered me across space.” The surname Rendar is adjacent only and may identify the speaker; it is not in the quote image.
- Not changed in CP2a: CP1's 4 crops, the other 41 EGVV quote images, characters/, Git, or any sealed package.
