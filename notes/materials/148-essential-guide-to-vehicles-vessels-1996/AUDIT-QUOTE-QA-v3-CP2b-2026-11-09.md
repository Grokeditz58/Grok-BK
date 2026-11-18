# notes148 EGVV 1996 — quote-image QA v3, checkpoint CP2b (6 of 51; 16 of 51 with CP1+CP2a) — 2026-11-09

Scope: **only** the 6 crops below (printed pp. 36, 38, 40, 44, 46, 52 / scans 037, 038, 039, 041, 042, 045). Together with CP1's 4 already-packaged crops (p138, p180-tie-limits-tight, p174, p162) and CP2a's 6 (p008, p010, p018, p022, p030, p032), **16 of 51** EGVV quote images now have an accepted v3 QA package. **35 remain** unchecked (not recut or re-audited here). This package does not start those 35.

CP1's and CP2a's crops and packages were not touched. The six live quote JPEGs listed below were not modified in this packaging step (no text-defect recut was required). WIP `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp2b/records.md` holds the six accepted transcription records and was not edited in this packaging step. An earlier unverified writeup `AUDIT-QUOTE-QA-v3-CP2-2026-11-09.md` remains in the materials folder; **this CP2b audit is the accepted record for these six.**

Source: `primary/essential-guides/eg-vehicles-1996/Essential-Guide-to-Vehicles-and-Vessels-1996.pdf` (RO12wBBC; 121 PDF pages, one embedded gray JPEG per PDF page = a two-page spread). Scan number = PDF page number. Printed folios were read from each spread's footer (not from the k = S − 19 formula alone); all six sit on the left page of the spread. Folios agree with k = S − 19 as a cross-check.

Method: native `pdfimages` crops (200 ppi sources already present under `/tmp/cp2r/`; pdfimages was not re-run for this package), stacked in reading order (left column → right column). Where art intrudes, a staircase of native rectangles leaves the art out without redrawing text. Each crop was read back against the native source and the live final at legible resolution. OCR was used only for coordinates. Boxes are from `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp2r/boxes.json`.

Old SHA256 values were checked against `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp2r/shas.txt`, `backup-148-cp2-20261109-191248/SHA256SUMS`, and `backup-pre-v3/148.sha` (all six old hashes agree). New SHA256 values match the installed live files and the “new” column of `shas.txt`.

Transcription: running text as printed, with italics as `*…*`. A hyphen at a printed line end is noted as `foo-/bar` in the notes, not kept as a mid-word hyphen in the running verbatim. **A spaced slash ` / ` in the verbatim blocks below is a paragraph separator, not a character printed in the book.** Slashes inside tokens (B-wing/E, B-wing/E2, TIE/In, Griffyn/Y2TG) *are* printed. No per-record clock times are asserted in this audit.

Character facts below are taken **only from the six audited crops**. Adjacent text that was deliberately excluded from a crop is noted as adjacent and is not treated as a fact from the quote image. Do not infer a commander aboard a ship from adjacent text (for example, Palpatine aboard the *Eclipse*, or Ackbar as the owner of a B-wing/E2, are adjacent only).

---
## 1. egvv1996-p036-scan037-deathstar2-improvements.jpg — DEATH STAR II
- Locator: PDF p.37 / scan 037 / printed **p.36**. left page of the 36–37 spread (footer "36" / "37" verified in the native footer strip, not from the k=S−19 formula alone); left-column staircase continuing into the right column, art cut out. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): (scan 037 p.36, left col, art cut out) [140, 826, 817, 1079]; [140, 1079, 579, 1114]; [140, 1114, 527, 1188]; [140, 1188, 444, 1262]; [140, 1262, 395, 1368]; [140, 1368, 357, 1477]; [140, 1477, 336, 1658]; [140, 1658, 369, 1766]; [140, 1766, 408, 1840]; [140, 1840, 474, 1948]; [140, 1948, 589, 1986]; [878, 428, 1565, 646] (right col, continues).
- Old SHA256 `81583b7b18eb8db12e638d9e102ca0e54669aa93f35878e492f3ead5eff9673d` → **new `86425c950fbf6d5ec8f7c75ac7e4037f6837cd5faeacf60b6764865c08428596`** (687x1472, 272384 B).
- Opening: “Not only was the second Death Star larger and more deadly, but several flaws in the original design were corrected.” / ending: “construction.”
- Start = paragraph start (prev para ends "…completed the second Death Star's design."); end = paragraph end "construction." (next right-col para "Of course, the Death Star was also part of an elaborate trap set by Emperor Palpatine…" excluded). No partial lines; art cut out by the staircase. Column wrap "Lemelisk added 20,000 turbolasers" / "to repel attacks…"
- Hyphenations / spellings: "cor-/rected", "one-hundred-/story" (compound), "observa-/tion", "shield-/ed", "ter-/rifying", "super-/laser", "in-/creased", "power-/control" (compound). Em dash as printed: "chamber—perhaps". In-line compounds: "millimeter-wide", "one-hundred-story", "power-control". Spellings as printed: "160 kilometers in diameter", "20,000 turbolasers". No italics in this crop.
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
Not only was the second Death Star larger and more deadly, but several flaws in the original design were corrected. The vulnerable thermal exhaust ports were replaced with millimeter-wide heat dispersion ducts, leaving no weak spots in this battle station's armor. The finished design increased the overall size of the new Death Star to 160 kilometers in diameter. The north pole of the station featured a one-hundred-story tower topped by the Emperor's private observation chamber—perhaps the most heavily armored and shielded portion of the station. / This new Death Star's central weapon, the terrifying superlaser, featured substantially increased power, allowing it to be recharged in a matter of minutes rather than hours. The superlaser's targeting and power-control systems were refined so the weapon could be turned on capital starships. Lemelisk added 20,000 turbolasers to repel attacks from starfighters and capital ships. Once completed, this station would have carried thousands of TIE fighters, troops, and ground combat vehicles. This new Death Star would have been invincible; the only way to stop it would have been to destroy it while it was still under construction.
```

- Remaining defects: none (targeted passage complete; following trap paragraph is outside the crop by design).
- Character facts (this crop only): The Emperor — has a private observation chamber topping a one-hundred-story tower at the north pole of the second Death Star, described as perhaps the most heavily armored and shielded portion of the station. Lemelisk — added 20,000 turbolasers to the station to repel attacks from starfighters and capital ships. This crop does not name Palpatine, and does not describe the Endor trap, Bothan spies, Ewoks, the *Millennium Falcon*, Lando Calrissian, or Mon Mothma.
- Adjacent, not in crop: NOT used as facts from this quote image: preceding paragraphs on the same page name Emperor Palpatine and Bevel Lemelisk, and mention the *Tarkin* battle station; following right-column paragraphs, excluded from the crop, describe Palpatine's Endor trap, Bothan spies, the "primitive" Ewoks, the *Millennium Falcon* commanded by General Lando Calrissian, the Emperor's death, and Mon Mothma declaring the end of the Rebellion / formation of the New Republic.

---
## 2. egvv1996-p038-scan038-ds-proto-limits.jpg — DEATH STAR PROTOTYPE
- Locator: PDF p.38 / scan 038 / printed **p.38**. left page of the 38–39 spread (footer "38" / "39" verified in the native footer strip, not from the k=S−19 formula alone); left-column staircase continuing into a right-column staircase, art cut out. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): (scan 038 p.38, left col, art cut out) [140, 1522, 341, 1705]; [140, 1705, 367, 1778]; (right col, continues; art cut out) [885, 432, 1556, 1053]; [996, 1053, 1556, 1090]; [1052, 1090, 1556, 1126]; [1106, 1126, 1556, 1163]; [1144, 1163, 1556, 1199].
- Old SHA256 `6340acc2a674bd73ffaf117516f11382f0f9fbec2e0d0081ad97b9ff8524729f` → **new `12091fa4f1ed9d7392ba477626789b0ee77759c3e9705bc2cc5a322b3846fc90`** (671x1117, 255549 B).
- Opening: “The prototype superlaser had several disadvantages compared with the working model of the first Death Star.” / ending: “starships.”
- Start = paragraph start (prev left-col para ends "…and the prototype superlaser itself."); end = paragraph end "starships." (next right-col para "The prototype was activated by Tol Sivron…" excluded). No partial lines; art cut out by staircases on both columns. Column wrap "the first Death" / "Star. For example…"
- Hyphenations / spellings: "proto-/type", "superla-/ser", "mod-/el", "incredi-/bly", "destruc-/tive", "slave-/rigged", "mainte-/nance". Typographic quotes as printed around “only”. Colon as printed after "planet". In-line compound: "slave-rigged".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
The prototype superlaser had several disadvantages compared with the working model of the first Death Star. For example, the firepower was “only” sufficient to destroy the core of a planet: while the planet would inevitably be rendered uninhabitable, the weapon did not completely vaporize the victim world. The targeting system was never perfected, plus the superlaser was also incredibly wasteful of power and the weapon's storage batteries took several hours to recharge fully. While the weapon could be fired at reduced power, the superlaser's destructive ability was reduced significantly. / The prototype Death Star was never intended to be a practical weapon of war, so there was no need to install the maintenance and repair machinery, the immense computer core, or the hyperdrive engines that took up a huge amount of space in the actual Death Star space station. Instead, the prototype had only a small command cabin with slave-rigged computer systems to control the superlaser and drive units. This computer system minimized personnel requirements, but such linked computer systems are prone to failure without constant maintenance and are not practical for military starships.
```

- Remaining defects: none (targeted limits passage complete; activation/destruction paragraph is outside the crop by design).
- Character facts (this crop only): none (no named characters).
- Adjacent, not in crop: NOT used as facts from this quote image: preceding left-column text names Bevel Lemelisk, Tarkin, Tol Sivron, the Maw Installation, and Despayre; the following right-column paragraph, excluded from the crop, says the prototype was activated by Tol Sivron after the Maw Installation was attacked by a New Republic task force, and was finally destroyed when Kyp Durron, piloting the Sun Crusher, lured it into one of the Maw's black holes.

---
## 3. egvv1996-p040-scan039-desert-skiff-not-combat.jpg — DESERT SKIFF
- Locator: PDF p.39 / scan 039 / printed **p.40**. left page of the 40–41 spread (footer "40" / "41" verified in the native footer strip, not from the k=S−19 formula alone); right text column of printed p.40 (x 880–1572, left half of the spread); single box. Native source 3708x2213 gray 200ppi.
- Native boxes (`boxes.json`): [880, 658, 1572, 1282] (scan 039 p.40, right col).
- Old SHA256 `5592f16518121803287e3277503d76511af068ae14a1b0f76803560d7fe32846` → **new `15723559bf34134c37e70e53c1ea81cfeb0e58f3559cb730da7edcb5bd6148b5`** (692x662, 179939 B).
- Opening: “Skiffs do not make good combat vehicles.” / ending: “spectacularly.”
- Start = paragraph start (prev para ends "…keep passengers dry."); end = paragraph end and end of column text ("spectacularly." then art below). No partial lines/art in the crop. Two full paragraphs
- Hyphenations / spellings: "nei-/ther", "repulsor-/lift". Em dash as printed: "quickly—something". In-line compound: "armor-plated". Spellings as printed: "Ubrikkian Bantha II", "Jabba had had", "Great Pit of Carkoon", "Sarlacc's".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
Skiffs do not make good combat vehicles. They are neither maneuverable nor sturdy enough to stand up in battle. A single blast from a hand blaster can disable the repulsorlift unit or smash a steering vane. If the repulsorlift unit is damaged, the skiff can topple if weight shifts too quickly—something that a number of Jabba's henchmen learned the hard way when they tumbled down into the Sarlacc's mouth. / Jabba the Hutt used a number of Ubrikkian Bantha II cargo skiffs as patrol and escort vehicles for his sail barge. While they were armor-plated, they were still unsuited to combat, as Luke Skywalker quickly proved. Jabba had had extendable gangplanks affixed to the skiffs to increase the entertainment value of his Sarlacc feedings. After the rescue of Han Solo, Luke Skywalker and other Rebel heroes used one of Jabba's skiffs to escape from the Great Pit of Carkoon even as Jabba's sail barge exploded spectacularly.
```

- Remaining defects: none.
- Character facts (this crop only): Jabba's henchmen — a number of them learned the hard way that a damaged skiff can topple if weight shifts too quickly, when they tumbled down into the Sarlacc's mouth. Jabba the Hutt — used a number of Ubrikkian Bantha II cargo skiffs as patrol and escort vehicles for his sail barge; they were armor-plated but still unsuited to combat; he had had extendable gangplanks affixed to the skiffs to increase the entertainment value of his Sarlacc feedings; his sail barge exploded spectacularly. Luke Skywalker — quickly proved the armor-plated skiffs were still unsuited to combat; after the rescue of Han Solo, he and other Rebel heroes used one of Jabba's skiffs to escape from the Great Pit of Carkoon. Han Solo — had been rescued (the crop does not describe who rescued him or how). Other Rebel heroes — used that skiff to escape with Luke. The Sarlacc — mentioned as having a mouth (henchmen tumbled into it) and as the object of Jabba's feedings.

---
## 4. egvv1996-p044-scan041-ewing-typeb-overload.jpg — E-WING: TYPE B
- Locator: PDF p.41 / scan 041 / printed **p.44**. left page of the 44–45 spread (footer "44" / "45" verified in the native footer strip, not from the k=S−19 formula alone); right text column of printed p.44; single box. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [872, 1126, 1565, 1530] (scan 041 p.44, right col).
- Old SHA256 `3a5543193d38570c430bdddd676d3822754d57b05127dad6380f6efe216c2d8d` → **new `ae321d4082523a3e2c3f2cab02e381da18b959dbb98af5658702796c5fc0be06`** (693x442, 108331 B).
- Opening: “Initial battles showed that the laser cannons were underpowered because they used synthetically spin-coiled Tibanna gas, which broke down quickly, greatly reducing the fire range.” / ending: “E-wing: Type B.”
- Start = paragraph start (prev para ends "…on an X-wing."); end = paragraph end and end of column text ("E-wing: Type B." then art below). No partial lines/art in the crop
- Hyphenations / spellings: "under-/powered", "termi-/nal". In-line compound: "spin-coiled". Spellings as printed: "Tibanna gas", "Battle of Calamari", "E-wing: Type B" (colon as printed). "refitting" was confirmed at full letter height on the native line (no text defect).
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
Initial battles showed that the laser cannons were underpowered because they used synthetically spin-coiled Tibanna gas, which broke down quickly, greatly reducing the fire range. Because of the Battle of Calamari, New Republic technicians lacked the time to design a permanent solution, such as refitting the weapons for a more suitable blaster gas. Instead, they rigged the laser cannons to accept three times the standard power feed, increasing the weapon range to acceptable levels but also risking a terminal power overload. These modified ships have been dubbed E-wing: Type B.
```

- Remaining defects: none.
- Character facts (this crop only): no named characters. New Republic technicians — because of the Battle of Calamari, they lacked the time to design a permanent solution such as refitting the weapons for a more suitable blaster gas, and instead rigged the laser cannons to accept three times the standard power feed (the Type B overload risk). The crop does not name any individual technician, pilot, or commander.

---
## 5. egvv1996-p046-scan042-eclipse-superlaser-ram.jpg — ECLIPSE
- Locator: PDF p.42 / scan 042 / printed **p.46**. left page of the 46–47 spread (footer "46" / "47" verified in the native footer strip, not from the k=S−19 formula alone); left column continuing into the right column. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [135, 1226, 830, 1304] (scan 042 p.46, left col); [872, 428, 1565, 868] (right col, continues).
- Old SHA256 `be129607ec8bdb87d858ac72453e3bbf0efbe7950b08d18b3f5d2a0a63abd850` → **new `b784fa29862d5b8c0d3285b3b9dca7f2cf228318a2d8f13b2500d8df3981af1f`** (695x612, 145280 B).
- Opening: “In combat, the *Eclipse*'s hull and shields were so strong that it could ram enemy vessels without hesitation.” / ending: “outright.”
- Start = paragraph start (prev left-col para ends "…demoralizing enemy troops."); end = paragraph end "outright." (next right-col para "For ground assaults, the *Eclipse* carried…" excluded). Column wrap "The" / "ship was equipped…"
- Hyphenations / spellings: "pre-/vent", "power-/ful". In-line compounds: "gravity-well", "two-thirds". Em dash as printed: "Star—it". Typographic quotes as printed around “merely”. Italics as printed on *Eclipse* and *Eclipse's*. Figures as printed: "ten", "Five hundred", "550", "fifty" / "(six hundred ships)", "eight".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
In combat, the *Eclipse*'s hull and shields were so strong that it could ram enemy vessels without hesitation. The ship was equipped with ten gravity-well projectors to prevent enemy vessels from escaping to hyperspace. Five hundred heavy laser cannons and 550 turbolasers made the ship capable of engaging entire New Republic fleets. The *Eclipse* carried fifty squadrons of TIE interceptors (six hundred ships) and eight squadrons of TIE bombers. / The *Eclipse* was also intended to devastate entire worlds. Its main weapon was a superlaser weapon, although its power was only two-thirds that of the main weapon aboard the first Death Star—it was “merely” powerful enough to crack the crust of a planet rather than destroy it outright.
```

- Remaining defects: none (ground-assault / Pinnacle Moon paragraph is outside the crop by design).
- Character facts (this crop only): none (no named characters). The crop describes the ship *Eclipse* only; it does not name a commander or say anyone is aboard.
- Adjacent, not in crop: NOT used as facts from this quote image: preceding left-column text says Palpatine, renewed in a fresh clone body, directed his forces from a new command vessel, the *Eclipse*, and calls it the Emperor's new flagship and a symbol of Palpatine's thirst for power. The following right-column paragraphs, excluded from the crop, give garrison/AT-AT/crew figures and then say the *Eclipse* was stopped over the Pinnacle Moon when Luke Skywalker and Leia Organa Solo joined Force energies to engulf Emperor Palpatine in a wave of life energy, stunning Palpatine so that he lost control of Force storms he had summoned.

---
## 6. egvv1996-p052-scan045-bwing-e2-limits.jpg — B-WING/E2
- Locator: PDF p.45 / scan 045 / printed **p.52**. left page of the 52–53 spread (footer "52" / "53" verified in the native footer strip, not from the k=S−19 formula alone); right text column of printed p.52; single box. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [879, 904, 1566, 1487] (scan 045 p.52, right col).
- Old SHA256 `c8298d3d9a4f7234d207ff56072a184e225db5f3e6b35e16374c60cf3d468a49` → **new `fabab9227ca6d5726c7249b36799abd5f7a663b50c1ee73e025fb318273752a8`** (687x621, 182367 B).
- Opening: “The B-wing/E is faster and tougher but less maneuverable than the standard B-wing.” / ending: “maneuverability.”
- Start = paragraph start (prev para ends "…any evasive maneuvers the B-wing may be making."); end = paragraph end "maneuverability." (next para "Ackbar's personal B-wing/E2 was modified…" excluded). No partial lines/art in the crop
- Hyphenations / spellings: "maneuver-/able", "fire-/linked", "proton-/torpedo" (the first "proton-torpedo"; later occurrences of the compound are in-line). Printed slashes inside tokens: "B-wing/E", "B-wing/E2" (not paragraph separators). In-line compounds: "fire-linked", "proton-torpedo". Typographic quotes as printed around “neck”.
- Qualification: A stray ink speck / smudge sits above the initial "a" of "ammo" in "a removable ammo magazine". It is not a diacritic (other a-glyphs on the line are clean) and is not a crop clip. The word is still "ammo". No recut.
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
The B-wing/E is faster and tougher but less maneuverable than the standard B-wing. The modified ship is as fast as the Y-wing fighter. Increased shield generators have added to the ship's ability to withstand damage, making the vessel a true threat to Imperial ships. The standard weapon configuration for the B-wing/E consists of two fire-linked laser cannons, three ion cannons, and a proton-torpedo launcher with eight torpedoes. The B-wing/E2 added an extra proton-torpedo launcher for a faster rate of fire but kept the same standard load of eight torpedoes. Recently, New Republic technicians designed a removable ammo magazine that can be mounted on the “neck” of the fighter. This attachment carries an additional twelve proton torpedoes and feeds directly into the launchers, although it disrupts the fighter's mass balance enough to reduce maneuverability.
```

- Remaining defects: a stray ink speck / smudge sits above the initial "a" of "ammo" (visible at 6x; not a diacritic and not a crop clip). The word is still "ammo". No recut (legible; not a text-integrity defect).
- Character facts (this crop only): no named characters. New Republic technicians — recently designed a removable ammo magazine that can be mounted on the “neck” of the fighter (additional twelve proton torpedoes; it disrupts the fighter's mass balance enough to reduce maneuverability). The crop itself does not name Ackbar or any other individual.
- Adjacent, not in crop: NOT used as facts from this quote image: the following paragraphs name Ackbar — "Ackbar's personal B-wing/E2 was modified from the standard design, with the second seat placed beside the pilot," and begin "It was Ackbar's B-wing that crashed while on final…".

---
## Handoff (character facts from these 6 crops only)
- Death Star II (p.36): The Emperor has a private observation chamber topping a one-hundred-story tower at the north pole of the second Death Star (perhaps the most heavily armored and shielded portion of the station). Lemelisk added 20,000 turbolasers to repel attacks from starfighters and capital ships. Do **not** cite Palpatine by name, the Endor trap, Bothan spies, Ewoks, the *Millennium Falcon*, Lando Calrissian, or Mon Mothma from this quote image (those sit in adjacent excluded text).
- Death Star Prototype (p.38): no named characters in the crop. Do **not** cite Bevel Lemelisk, Tarkin, Tol Sivron, the Maw Installation, Despayre, Kyp Durron, or the Sun Crusher from this quote image.
- Desert skiff (p.40): Jabba the Hutt used Ubrikkian Bantha II cargo skiffs as patrol and escort vehicles for his sail barge (armor-plated but still unsuited to combat); he had had extendable gangplanks affixed for the entertainment value of his Sarlacc feedings; his sail barge exploded spectacularly. A number of Jabba's henchmen tumbled into the Sarlacc's mouth when a damaged skiff toppled. Luke Skywalker quickly proved the skiffs unsuited to combat; after the rescue of Han Solo, Luke and other Rebel heroes used one of Jabba's skiffs to escape from the Great Pit of Carkoon. The crop does not say who rescued Han Solo or how.
- E-wing: Type B (p.44): no named characters. Unnamed New Republic technicians, because of the Battle of Calamari, lacked time for a permanent blaster-gas solution and instead rigged the laser cannons to accept three times the standard power feed, risking a terminal power overload. Do not name an individual technician, pilot, or commander from this quote image.
- *Eclipse* (p.46): no named characters in the crop. The crop describes the ship only (hull and shields strong enough to ram enemy vessels; ten gravity-well projectors; five hundred heavy laser cannons and 550 turbolasers; fifty TIE interceptor squadrons / six hundred ships and eight TIE bomber squadrons; a superlaser at two-thirds the power of the first Death Star's main weapon, “merely” powerful enough to crack a planet's crust). It does **not** name a commander or say anyone is aboard. Do **not** cite Palpatine, Luke Skywalker, Leia Organa Solo, or the Pinnacle Moon from this quote image (adjacent only).
- B-wing/E2 (p.52): no named characters in the crop. Unnamed New Republic technicians recently designed a removable ammo magazine mounted on the “neck” of the fighter (twelve extra proton torpedoes; it reduces maneuverability). **Ackbar is adjacent only** and must not be cited from this quote image. A stray ink speck over the initial “a” of “ammo” is noted above; the word is still “ammo.”
- Not changed in CP2b: CP1's 4 crops and package, CP2a's 6 crops and package, the other 35 EGVV quote images, characters/, Git, or any sealed package.
