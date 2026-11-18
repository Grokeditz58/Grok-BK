# QUOTE QA — PATCHv3d (EGC 1995 / notes147) — final remaining 31 assets (30 old Round-2 “C” + Ackbar statblock “S”)

- Date: 2026-11-09 ~18:55 CST (America/Chicago)
- Scope: the 31 assets not covered by v3a (5), v3b (9) or v3c (18). 30 RECUT target quotes + 1 statblock kept unchanged (S). Does NOT touch any v3a/v3b/v3c asset, the sealed EOF, or earlier patch ZIPs.
- Source: native 200 dpi page images (`pdfimages`) from `primary/essential-guides/eg-characters-1995/Essential-Guide-to-Characters-1995.pdf`; PDF page N = scan N; printed folio = scan − 9, checked on each page Read.
- Method: Read the full native source page(s) this run → recut the whole named passage from the native page (numbered stacked PARTS across columns/pages/art wraps; whole lines only, neighbour lines clamped) → Read the FINAL file against the page. OCR used only for coordinates; OCR errors (fo/to, affer/after, leff/left, frapped/trapped, etc.) corrected against the image. Old Round-2 “C” claims were NOT relied on: every old crop was viewed (contact sheets) and every one of the 30 was found loose/sliced or incomplete, so all 30 were recut. No whole-page uploads.
- Cross-page passages: karrde-ysalamiri (p.88→89, scans 097→098), anakin-spirit-forgiveness-leia (p.154→155, scans 163→164).
- Confirmed old-crop text defects (beyond looseness): hethrir-force-dampen (right line ends cut), karrde-ysalamiri (ended mid-word “Force-damp-”), owen-flashy-brother-kenobi (ended mid-sentence “Lars used”), luke-byss-apprentice (began mid-sentence “clone of Emperor Palpatine”), anakin-spirit-forgiveness-leia (began mid-sentence “trying to take away her anger”), vader-throws-emperor (began mid-sentence “killing bolts”), palpatine-cities (top line was the tail of a previous sentence).

## Status summary

| # | file | status | locator | old sha256 (12) | new sha256 (12) |
|---|---|---|---|---|---|
| 1 | `egc1995-p001-palpatine-cities.jpg` | RECUT | printed p.1 / scan 010 / PDF page 10 | `a463bc624cc4` | `7202fac637c0` |
| 2 | `egc1995-p002-bwing-admiral.jpg` | RECUT | printed p.2 / scan 011 / PDF page 11 | `52c52b8a7cbe` | `fb329ce4c4b9` |
| 3 | `egc1995-p004-greatest-military.jpg` | RECUT | printed p.4 / scan 013 / PDF page 13 | `aa6549a4ed73` | `d5ebdde1f1d0` |
| 4 | `egc1995-p004-terpfen-spy.jpg` | RECUT | printed p.4 / scan 013 / PDF page 13 | `a6a68d4a347e` | `d3db33d50f46` |
| 5 | `egc1995-p005-yavin-vader-hit.jpg` | RECUT | printed p.5 / scan 014 / PDF page 14 | `c4c47a827d75` | `a7bf59422bf1` |
| 6 | `egc1995-p006-endor-reactor.jpg` | RECUT | printed p.6 / scan 015 / PDF page 15 | `90b630dbeb0b` | `2d3d5fce2756` |
| 7 | `egc1995-p006-hoth-atat.jpg` | RECUT | printed p.6 / scan 015 / PDF page 15 | `eb109fa3aa23` | `002850588c01` |
| 8 | `egc1995-p009-bodo-holocron.jpg` | RECUT | printed p.9 / scan 018 / PDF page 18 | `a5a45ad3fd51` | `f576102b4de8` |
| 9 | `egc1995-p011-kenobi-cantina.jpg` | RECUT | printed p.11 / scan 020 / PDF page 20 | `aeda464e7a6f` | `2e45085ac28a` |
| 10 | `egc1995-p029-cbaoth-death-mara.jpg` | RECUT | printed p.29 / scan 038 / PDF page 38 | `c7cf2d78ebd0` | `54a787dfc4fd` |
| 11 | `egc1995-p070-hethrir-force-dampen.jpg` | RECUT | printed p.70 / scan 079 / PDF page 79 | `4d471f55703d` | `6fc071f72a6b` |
| 12 | `egc1995-p083-mara-destiny-cbaoth.jpg` | RECUT | printed p.83 / scan 092 / PDF page 92 | `4954fc6a87d7` | `397c6a9f3f64` |
| 13 | `egc1995-p088-karrde-ysalamiri.jpg` | RECUT | printed pp.88–89 / scans 097–098 / PDF pages 97–98 | `c3f49a5051a1` | `2c6ed40c914d` |
| 14 | `egc1995-p090-ken-jedi-prince.jpg` | RECUT | printed p.90 / scan 099 / PDF page 99 | `90e022a726fa` | `b8bc57f53c7f` |
| 15 | `egc1995-p092-kenobi-millions-voices.jpg` | RECUT | printed p.92 / scan 101 / PDF page 101 | `bd83fb07fede` | `30346e97a2c4` |
| 16 | `egc1995-p102-scan111-owen-flashy-brother-kenobi.jpg` | RECUT | printed p.102 / scan 111 / PDF page 111 | `573a8102d6e8` | `7abd94b509eb` |
| 17 | `egc1995-p125-scan134-palpatine-final-death-terror.jpg` | RECUT | printed p.125 / scan 134 / PDF page 134 | `a3388c75667b` | `c61d3d8a872b` |
| 18 | `egc1995-p125-scan134-vader-throws-emperor.jpg` | RECUT | printed p.125 / scan 134 / PDF page 134 | `51ace872e7af` | `2ca61280ee8c` |
| 19 | `egc1995-p129-scan138-ulic-sith-brand-exar-quote.jpg` | RECUT | printed p.129 / scan 138 / PDF page 138 | `d5fbf28859df` | `977db8627958` |
| 20 | `egc1995-p137-scan146-luke-owen-kenobi-brother.jpg` | RECUT | printed p.137 / scan 146 / PDF page 146 | `1ca19c40ecfc` | `72bd8f32df9f` |
| 21 | `egc1995-p139-scan148-yoda-do-or-do-not-cave.jpg` | RECUT | printed p.139 / scan 148 / PDF page 148 | `7e52061118dd` | `a914641d727b` |
| 22 | `egc1995-p141-scan150-luke-byss-apprentice.jpg` | RECUT | printed p.141 / scan 150 / PDF page 150 | `9f34fc0de6a3` | `c1841de177b6` |
| 23 | `egc1995-p141-scan150-obiwan-final-goodbye-first-of-new.jpg` | RECUT | printed p.141 / scan 150 / PDF page 150 | `fb74867df95d` | `421bff607dc5` |
| 24 | `egc1995-p152-scan161-leia-owen-kenobi-brother.jpg` | RECUT | printed p.152 / scan 161 / PDF page 161 | `4ed1d7aafc41` | `cded3a4374f0` |
| 25 | `egc1995-p155-scan164-anakin-spirit-forgiveness-leia.jpg` | RECUT | printed pp.154–155 / scans 163–164 / PDF pages 163–164 | `fb6cdeb63e5f` | `d6a117a0fd35` |
| 26 | `egc1995-p170-scan179-luke-first-new-jedi-knights.jpg` | RECUT | printed p.170 / scan 179 / PDF page 179 | `a1b913dd3579` | `4002728b929e` |
| 27 | `egc1995-p177-scan186-vader-twins-owen-kenobi-brother.jpg` | RECUT | printed p.177 / scan 186 / PDF page 186 | `a97cfdd8aa23` | `0843444df6c9` |
| 28 | `egc1995-p191-scan200-yoda-force-knowledge-never-attack.jpg` | RECUT | printed p.191 / scan 200 / PDF page 200 | `12a81546740e` | `a4f51c70f2ea` |
| 29 | `egc1995-p192-scan201-yoda-another-skywalker-death.jpg` | RECUT | printed p.192 / scan 201 / PDF page 201 | `b28f6f58c1de` | `f60396381a43` |
| 30 | `egc1995-p192-scan201-yoda-do-or-do-not-size-fail.jpg` | RECUT | printed p.192 / scan 201 / PDF page 201 | `8505788d9c67` | `72a1c210badb` |
| 31 | `egc1995-p001-ackbar-statblock.jpg` | S (UNCHANGED, hash proof only) | printed p.1 / scan 010 / PDF page 10 | `51b83fad2993` | `51b83fad2993` |

## Records

## `egc1995-p001-palpatine-cities.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.1 / scan 010 / PDF page 10
- Prior defect: old crop target complete but top line was the tail of a previous sentence (“facilities orbited the planet…”); recut with clean start
- Method: 2 numbered PARTS: right col full-width lines (1094,824)-(1539,1177); art-wrapped lines (1092,1185)-(1353,1427)
- Opening words: “The first time a Mon Calamari” · Ending words: ““inferior” alien species. The plan backfired.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: edge of Ackbar photo beside PART 2 narrow lines; text complete
- sha256 old → new: `a463bc624cc4e7a9437b7107dd0e0128a67faf35033adcf3f6306a492d71bd29` → `7202fac637c06ba725f07f28a284ba5d8c182657754fc7a2f27f5814bb9e2062`

> The first time a Mon Calamari ship met an Imperial ship, the Calamari made overtures of peace and free trade, but the Imperials were more interested in slaves and Mon Calamari technology. They began an invasion, and when the peaceful people protested, Emperor Palpatine ordered the destruction of three of their floating cities. The Emperor wanted to send a clear message across the galaxy as to the fate of all those who opposed his New Order . . . especially the “inferior” alien species. The plan backfired.

## `egc1995-p002-bwing-admiral.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.2 / scan 011 / PDF page 11
- Prior defect: old crop: first line (“Made a commander in the Alliance,”) sliced at top edge, left-column slivers, trailing next paragraph; recut
- Method: single block middle col (630,448)-(1080,1229)
- Opening words: “Made a commander in the Alliance,” · Ending words: “admiral by Alliance leader Mon Mothma.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `52c52b8a7cbe837bf05cadb35acb7bf83bba059af797de6c305d56d6909c9051` → `fb329ce4c4b99d327696057c21625934771c26e766bf8e8ff1968bbae111f83e`

> Made a commander in the Alliance, Ackbar wanted to create an answer to the Empire’s deadly new Nebulon-B frigate, which maintained twenty-four laser batteries, heavy shielding, and two TIE fighter squadrons, which made it more than a match for traditionally lightly armed Rebel starfighters. Ackbar went to the Roche system to deal with a renowned species of brilliant ship designers, the insectoid Verpine. Code-named Shantipole, the project would lead to the development of an oddly shaped, two-crewed B-wing starfighter. Working with Ackbar and other Calamari, the peaceful Verpine were able to create several prototypes of the B-wing. Despite a betrayal by Salin Glek, Ackbar’s Quarren lieutenant, the Empire was unable to capture the new ships. Several days after the B-wings were delivered, Ackbar was promoted to admiral by Alliance leader Mon Mothma.

## `egc1995-p004-greatest-military.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.4 / scan 013 / PDF page 13
- Prior defect: old crop: sliced top line + large art; recut
- Method: 2 numbered PARTS: right col full-width (1141,1204)-(1584,1375); art-wrapped (1138,1386)-(1370,1594)
- Opening words: “Ackbar and the white-haired beauty would” · Ending words: “of the galaxy’s greatest military leaders.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: thin art line beside PART 2; text complete
- sha256 old → new: `aa6549a4ed73906a10302f6969c7801ccb37baa225b82883e6ad0dc40adfa87c` → `d5ebdde1f1d055170a35ce2a29b05147b0a9e510830128570a725d1b131957df`

> Ackbar and the white-haired beauty would enjoy each others’ company a lot over the coming years, both in their tasks for building the New Republic, and in private. With many more missions and successes in his future, Admiral Ackbar would go down in history as one of the galaxy’s greatest military leaders.

## `egc1995-p004-terpfen-spy.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.4 / scan 013 / PDF page 13
- Prior defect: old crop: sliced top line and preceding paragraph; recut
- Method: single block left col (150,1784)-(594,2032)
- Opening words: “Unknown to Ackbar, his chief starship” · Ending words: “reported to Caridian Imperial Ambassador Furgan.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `a6a68d4a347e0c691a3689d59b4b9de2843a01f9292425d1985c9d1031ffbd3f` → `d3db33d50f46a35bda1e8c15d255a53c640efa09d45f1993f9d48f809e0332b9`

> Unknown to Ackbar, his chief starship mechanic, a Mon Calamari named Terpfen, was secretly a spy. Terpfen had been tortured by the Imperials, and organic circuitry had been placed into his brain, forcing him to spy for them. He reported to Caridian Imperial Ambassador Furgan.

## `egc1995-p005-yavin-vader-hit.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.5 / scan 014 / PDF page 14
- Prior defect: old Round-2 crop: sliced edge line(s)/loose column (seen in old-crop contact sheet); recut clean
- Method: single block right col (1100,1684)-(1543,2000)
- Opening words: “Despite evasive maneuvers, Wedge’s ship was” · Ending words: “and the Death Star was destroyed.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `c4c47a827d7563898b8eeb0977ed1aa120cdf3b787b6219d312ca8fe79e68d4b` → `a7bf59422bf1691a529ba990e25039a8f7ca6f2a4cccf7492eb7b4b3c9069dde`

> Despite evasive maneuvers, Wedge’s ship was hit in an attack by Darth Vader and two TIE fighters, forcing him to abort and skim off into space. Then, Biggs’s X-wing was destroyed in a blast from Vader’s ship. Wedge watched from space as Luke Skywalker completed his run alone. Amazingly, his missiles did find their mark, and the Death Star was destroyed.

## `egc1995-p006-endor-reactor.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.6 / scan 015 / PDF page 15
- Prior defect: old crop: right-column paragraph only; the sentence leading into it (“Wedge went down the main reactor shaft first, followed by…”) begins in the art-wrapped middle column; recut with it
- Method: 2 numbered PARTS: middle col art-wrapped lines (642,1665)-(817,2020); right col (1136,253)-(1583,750)
- Opening words: “Once the shields were down, the” · Ending words: “them, the battle station blew up.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: tiny art fleck beside PART 1; text complete
- sha256 old → new: `90b630dbeb0be4115b05ebc541b2452fa9ab4a381d5692043ddb8ab8febd60ff` → `2d3d5fce27561387139e1e92beb56b16ab0abec8818db7132e2f887c1458a6ae`

> Once the shields were down, the Rebels were freed to make their attack runs. Wedge went down the main reactor shaft first, followed by the Millennium Falcon, several other X-wings, and a mob of enemy TIE fighters. Both Wedge and the Falcon made it to the reactor core. Wedge targeted the power regulator in the north tower, launching concussion missiles, and Lando torpedoed the main reactor. Then the two ships had to retrace their perilous flight through the Death Star superstructure, even as it collapsed and exploded around them. With milliseconds to spare, Wedge and the Falcon escaped the shaft into open space. Behind them, the battle station blew up.

## `egc1995-p006-hoth-atat.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.6 / scan 015 / PDF page 15
- Prior defect: old Round-2 crop: sliced edge line(s)/loose column (seen in old-crop contact sheet); recut clean
- Method: single block left col (151,1270)-(595,1514)
- Opening words: “During the battle, many of Rogue” · Ending words: “a walker, causing it to explode.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `eb109fa3aa239e508e7447d54370e78d00b426826fbfe679e6beda04b4974488` → `002850588c0166914ca5ee09f313390ea24715cd33e6cfa8962b901e96154951`

> During the battle, many of Rogue Squadron tried their best, but the twelve two-person snowspeeders lost many of their gunners in the battle. Wedge was backed up by his own gunner, Wes Janson. They were the first to successfully trip a walker, causing it to explode.

## `egc1995-p009-bodo-holocron.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.9 / scan 018 / PDF page 18
- Prior defect: old crop: whole-page-like region (stat box + art + two columns), cut at bottom mid-sentence (“Several Holocrons ex-/isted, each with its own interactive”); recut to the named execution / light-side-levels paragraph
- Method: single block middle col (629,1650)-(1074,1967)
- Opening words: “During the great purge of the” · Ending words: “the light side of the Force.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `a5a45ad3fd51f23b43bb3cda345f4def65e9af16aa38560585bbfd88d0b86a79` → `f576102b4de81ccac6557ec5aba0279619153c910f01c0a0dfc1f0135644371a`

> During the great purge of the Jedi, Emperor Palpatine had Bodo Baas executed, and the Holocron in the Jedi’s belongings eventually passed into his grasp. Although Palpatine was able to unlock many of the mysteries of the Holocron, deeper levels were reserved only for those Jedi Knights using the light side of the Force.

## `egc1995-p011-kenobi-cantina.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.11 / scan 020 / PDF page 20
- Prior defect: old crop: entire left column plus slivers of middle column; target complete but loose; recut to the cantina paragraphs
- Method: single block left col (126,860)-(572,1392)
- Opening words: “On one fateful day at the” · Ending words: “right arm at the elbow joint.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `aeda464e7a6fbdd48e068387343adab994d07a4a8b42b9a8d348d00fc971f8ed` → `2e45085ac28adbea7b6b56ae0d105b6839256f5e1d31bc9ec82038528312404a`

> On one fateful day at the cantina, Ponda Baba picked the wrong person to harass. Drunk, Baba shoved young Luke Skywalker. When Luke tried to smooth matters, Dr. Evazan threatened him, bragging that he had the death sentence in twelve systems. “I’ll be careful,” Luke said. “You’ll be dead,” Evazan snarled, not noticing the brown-robed old man who had appeared next to the young farm boy. The man, Obi-Wan Kenobi, attempted to calm Baba and Evazan. When the duo attacked anyway, Obi-Wan ignited his lightsaber, slicing Evazan’s chest and cutting off Baba’s right arm at the elbow joint.

## `egc1995-p029-cbaoth-death-mara.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.29 / scan 038 / PDF page 38
- Prior defect: old crop: right column with top line sliced and middle-column slivers; recut
- Method: 2 numbered PARTS: right col art-wrapped lines (1195,604)-(1567,1065); right col (1121,1073)-(1566,1501)
- Opening words: “C’Baoth lost control, his dark-Force powers” · Ending words: “C’Baoth was finally and truly dead.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: edge of illustration at left of PART 1; text complete
- sha256 old → new: `c7cf2d78ebd0620feb34220e283bac0b09fce6c24e2b74b17ca94d9293ca905a` → `54a787dfc4fd38c9d2d48d444e3b0fd4bb0427520d3297c5c4cc4ffde4ca6629`

> C’Baoth lost control, his dark-Force powers raging against the Jedi and Jedi-to-be. He attacked Luke and Mara using blue lightning and collapsed rubble from the ceiling, planning to replace the clone of Luke and grow another clone of Mara Jade. “I have foreseen that Mara Jade will kneel before me,” he said. “One Mara Jade . . . or another.” Mara freed herself first, charging C’Baoth with Leia’s lightsaber. She used it to deflect his corona of lightning, but was overcome by a blinding hail of rocks. Leia, who had accompanied them, linked her mind with Mara’s, allowing her to see where she was going. Exhausted and in pain, Luke used the Force to free the savage vornskrs that were leashed nearby. The growling creatures ran for Joruus, distracting the evil clone and his magics. Mara Jade charged and killed C’Baoth with a thrust of the lightsaber. Joruus C’Baoth was finally and truly dead.

## `egc1995-p070-hethrir-force-dampen.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.70 / scan 079 / PDF page 79
- Prior defect: CONFIRMED BAD: old crop cut off the right ends of the text lines (“Darth Vade”, “dark side c”, “disappoin”, “coul”, “hopes fo”)
- Method: single block left col (179,1712)-(625,2029)
- Opening words: “When Hethrir was young, he and” · Ending words: “hopes for turning it to evil.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `4d471f55703d2953a3f789a61bbbdfc196e02aff62e3610a768aadb1864d8fa6` → `6fc071f72a6bf806cc559105d3c75abc08ad7d326d2038001e852bf2fbd25422`

> When Hethrir was young, he and his lover, Rillao, trained with Darth Vader. Hethrir was eager to learn the dark side of the Force, but his mate was a disappointment to the Dark Lord. While Hethrir could dampen others’ Force abilities, she was a healer and light-side user. When the two conceived a child, Vader had high hopes for turning it to evil.

## `egc1995-p083-mara-destiny-cbaoth.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.83 / scan 092 / PDF page 92
- Prior defect: old crop: target complete but included the full Mara illustration, trailing paragraphs, and right-column slivers; recut skipping the art
- Method: 2 numbered PARTS: middle col above art (608,293)-(1053,610); middle col below art (606,1558)-(1050,1766)
- Opening words: “Finally, Mara would face her destiny.” · Ending words: “commanded her. She finally felt free.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `4954fc6a87d76a67822f36061ba3c362ebe2d97242797919275b12276f8d2855` → `397c6a9f3f64be95635e74e48030121b4405596fed178cc537efac2630286739`

> Finally, Mara would face her destiny. During a mission that took them to Wayland to destroy the Emperor’s Spaarti cloning cylinders, Luke trained Mara in her slowly returning Force talents. Joruus C’Baoth called both Luke and Mara to him, intending to turn them to the dark side. When it became clear he couldn’t turn Luke, he unleashed his own clone of the hero, calling it Luuke Skywalker. In the battle to follow, Mara killed the Luuke clone, and with help from Luke and Leia Organa Solo, she slew C’Baoth, as well. She had done what the Emperor’s compulsion commanded her. She finally felt free.

## `egc1995-p088-karrde-ysalamiri.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed pp.88–89 / scans 097–098 / PDF pages 97–98
- Prior defect: CONFIRMED BAD: old crop sliced top line and ended mid-word “Force-damp-” without the scan 098 continuation; recut with cross-page continuation
- Method: 3 numbered PARTS: s097 right col (1136,483)-(1578,835) Aves paragraph; s097 right col last 2 lines (1135,1965)-(1577,2029); s098 left col continuation (118,291)-(561,716)
- Opening words: “Aves coordinates Karrde’s operatives and offers” · Ending words: “pay a higher bounty for Skywalker.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `c3f49a5051a142bbe67ced97c62a6a354e6632bbb9d225f561b5a3261938b31a` → `2c6ed40c914df79fdcda4be7248854f58165ae40cd7faae0087e5d564b6a0ed5`

> Aves coordinates Karrde’s operatives and offers advice. Chin, a middle-aged Myrkr native, handles and trains Karrde’s pet vornskrs, Sturm and Drang. Chin also harvests the mysterious Force dampeners known as ysalamiri. Dankin, Fynn Torve, and Wadewarn are three of Karrde’s best freighter pilots. Ghent is a barely-above-teens slicer with tremendous knowledge of computers, droids, and access codes. ¶ When Grand Admiral Thrawn contacted Karrde to provide him with the Force-dampening ysalamiri, Karrde was more than happy to comply. On his way to deliver the creatures to Thrawn, he found Luke Skywalker in a damaged X-wing, floating in space. Knowing that Thrawn had a 30,000 credit bounty out for Skywalker, Karrde agreed to take Luke to Myrkr. The young Jedi’s Force powers were useless while near the ysalamiri, and the smugglers locked him in a storage shed. Perhaps the New Republic would pay a higher bounty for Skywalker.

## `egc1995-p090-ken-jedi-prince.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.90 / scan 099 / PDF page 99
- Prior defect: old crop: large page region with art and column slivers; recut to the two named passages (opening + “Jedi Prince” prophecy)
- Method: 2 numbered PARTS: left col opening paragraph incl. drop cap (120,1571)-(592,1743); right col Kadann paragraph (1137,810)-(1578,1124)
- Opening words: “The grandson of Emperor Palpatine, the” · Ending words: “the Alliance and train with Skywalker.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: column rule visible at left edge of PART 1; text complete
- sha256 old → new: `90e022a726fae71df8dd66ee43375d3f386633e8ddad63fe812c09f43ac52006` → `b8bc57f53c7f0dad9ad2b44ada50081ddf1da89e30211d4e896ae9fe834ef684`

> The grandson of Emperor Palpatine, the young Jedi named Ken lived sheltered deep in the bowels of the Lost City of the Jedi, until a brush with the Alliance unraveled his past and his future. ¶ Meanwhile Kadann, the Supreme Prophet of the Dark Side, had predicted that a young Jedi Prince would destroy prospective emperor Trioculus, so the ruthless Imperial leader came to Yavin Four, intent on killing Ken. With the help of Skywalker, Han Solo, and Chewbacca, Ken and the droids foiled Trioculus’s plans. Ken left the Lost City to join the Alliance and train with Skywalker.

## `egc1995-p092-kenobi-millions-voices.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.92 / scan 101 / PDF page 101
- Prior defect: old crop: sliced top line, included art; recut
- Method: single block right col (1134,636)-(1576,988)
- Opening words: “By the time the Falcon reached” · Ending words: “orbiting Death Star, and pulled inside.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: top edge of Kenobi photo beside the final two short lines (“and pulled / inside.”); text complete
- sha256 old → new: `bd83fb07fededbe4485d0d643450d836bc073a2fe9588a3d2564e538be761cad` → `30346e97a2c4844f6411fb4a1bd69db7a964be724a5f5613013f6c9a1f041d09`

> By the time the Falcon reached the Alderaan system, the Death Star satellite had already destroyed the planet. Ben felt the psychic pain from the destruction, noting that it was “as if millions of voices suddenly cried out in terror and were suddenly silenced.” Pursuing a TIE fighter, the Falcon was trapped in a tractor beam from the orbiting Death Star, and pulled inside.

## `egc1995-p102-scan111-owen-flashy-brother-kenobi.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.102 / scan 111 / PDF page 111
- Prior defect: CONFIRMED BAD: old crop included art + opening paragraph and ended mid-sentence at “Lars used”; recut with column continuation
- Method: 2 numbered PARTS: left col (135,1734)-(606,2026); middle col continuation (640,1548)-(1086,1794)
- Opening words: “Owen Lars was never as flashy” · Ending words: “with an infant daughter named Camie.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `573a8102d6e82e0870740c531b5020763e8a355eec840d1624cc304dcea6aa42` → `7abd94b509ebbdc4197b07f3cc420669e99aea7c1a3768813bceb060713e22ec`

> Owen Lars was never as flashy as his brother, Obi-Wan Kenobi, one of the strongest of the Jedi Knights, nor as daring as Kenobi’s friend, Anakin Skywalker. He was content to marry Beru and live a practical life in the arid wastes of Tatooine, moisture farming in order to irrigate his underground produce gardens. Lars used vaporators to distill water from the air, a difficult task on a planet with two suns and many seasons each year. He made some money selling excess water to those who maintained hydroponic gardens, such as the nearby family with an infant daughter named Camie.

## `egc1995-p125-scan134-palpatine-final-death-terror.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.125 / scan 134 / PDF page 134
- Prior defect: old crop: target complete but loose (art, preceding paragraphs, column slivers); recut tight
- Method: single block right col art-wrapped (1251,1720)-(1563,2034) [margins applied]
- Opening words: “Luke Skywalker knows that the Emperor” · Ending words: “the dark side of the Force.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: art edge sliver at lower-left of narrow lines; text complete
- sha256 old → new: `a3388c75667bc1db2533feabc2dcd930f12135b2255ea3a791644f38120ae6bb` → `c61d3d8a872babdfb2fd7e3e0691f804a128362126df4a4b06aaa38cad11b50c`

> Luke Skywalker knows that the Emperor has a limited supply of clones, but the capacity to create more. Palpatine himself is terrified of a “final” death, which will lead to his perpetual madness as a disembodied spirit, adrift in the dark side of the Force.

## `egc1995-p125-scan134-vader-throws-emperor.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.125 / scan 134 / PDF page 134
- Prior defect: old crop: began at “killing bolts” without the sentence start in the left column; included art and following paragraphs/column slivers; recut with sentence start
- Method: 2 numbered PARTS: left col art-wrapped paragraph (134,1686)-(433,2039); middle col continuation (624,273)-(1070,590)
- Opening words: “Palpatine knew then that the younger” · Ending words: “and the Death Star was destroyed.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `51ace872e7af5bbcc17c00fae559789c73d1f5849c2d9a0d54fee7c12e6f0334` → `2ca61280ee8c244e84bf5d9260e24b2a5f85930cb4e155c6c614c4191aa79ad6`

> Palpatine knew then that the younger Skywalker would join him, so he called on the dark side, throwing blue Force lightning into Luke. It crippled and incapacitated the young man, reducing him to writhing agony in minutes, but as Palpatine prepared to deliver the killing bolts, Vader betrayed him. ¶ The Dark Lord lifted his master into the air and threw him into the burning shaft of the power core. As Palpatine disappeared into the abyss below, Force lightning crackled around and through his body, and then the Emperor was gone. Minutes later, Darth Vader also died, Luke escaped, and the Death Star was destroyed.

## `egc1995-p129-scan138-ulic-sith-brand-exar-quote.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.129 / scan 138 / PDF page 138
- Prior defect: old crop: text present across middle and right columns but loose (large art, neighbouring column slivers, unrelated paragraphs); recut to the two-part passage
- Method: 2 numbered PARTS: middle col art-wrapped (628,1779)-(1073,2023); right col continuation (1123,872)-(1567,937)
- Opening words: “The creature in the vision bestowed” · Ending words: “we will bring down the galaxy.””
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: art edge at lower-left of PART 1 narrow lines; text complete
- sha256 old → new: `d5fbf28859df405a14ed43e778ab0721233990cbef76983344f1c4af1bc4d705` → `977db862795877181aa1d3560d47e348e0a3c4ca74a5122637ae201657e10b42`

> The creature in the vision bestowed the title of Dark Lord of the Sith on Exar Kun, and the title of Sith Apprentice on Ulic Qel-Droma. Each of them was branded with tattoos on their foreheads, dark symbols from an evil power. “The ancient Sith have spoken,” Exar Kun said. “Together we will bring down the galaxy.”

## `egc1995-p137-scan146-luke-owen-kenobi-brother.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.137 / scan 146 / PDF page 146
- Prior defect: old crop: target complete but loose (stat box, opening paragraph, next paragraph, column slivers); recut tight
- Method: single block left col (134,1743)-(576,1949) [margins applied]
- Opening words: “In the time after the Clone” · Ending words: “the dark side of the Force.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `1ca19c40ecfc62c099dcfa94611868cc9b874d2b91e000a9be4abb39fb47cd58` → `72bd8f32df9f9e46034b528e01d21bba501ffdeddc7f83b9eabfc09c6da30484`

> In the time after the Clone Wars, the Jedi Knight Obi-Wan Kenobi asked his brother and sister-in-law, Owen and Beru Lars of Tatooine, to raise Luke, the son of Kenobi’s Jedi student who had been seduced by the dark side of the Force.

## `egc1995-p139-scan148-yoda-do-or-do-not-cave.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.139 / scan 148 / PDF page 148
- Prior defect: old crop: loose page region (art, neighbouring columns, following paragraph); recut to cave + do-or-do-not passage
- Method: 2 numbered PARTS: middle col (613,1575)-(1060,2072); right col (1112,1032)-(1555,1528) two paragraphs
- Opening words: “It was then that he found” · Ending words: “do not. There is no try.””
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `7e52061118ddf22b9541fbbba6a2b8ddc2100988706f2274fb4d1683d76eba30` → `a914641d727b356b17c029684e506888f4c2f90644a8290929f19db0895482f2`

> It was then that he found out the diminutive being was Yoda. The Jedi Master discussed Luke’s future with the spirit of Kenobi, then commenced training Luke immediately. He lectured him about the Force while Luke performed rigorous physical and psychological exercises, warning him against the easy path of anger and the lure of the dark side. One of Luke’s most difficult tests was when Yoda told him to go into a tree suffused with dark-side energy. When Luke asked what was inside, the enigmatic Master said, “Only what you take with you.” ¶ Inside the tree, Luke dueled with an apparition that resembled Darth Vader—until the helmet cracked and Luke saw his own face. He too could become part of the dark side. ¶ Luke learned other valuable lessons when Yoda had him practice levitation using the Force. Luke despaired when he spotted his X-wing sinking in the bog. Yoda ordered him to use the same powers to raise his ship as he had on rocks and supplies. Luke said he’d try, but was cut off curtly by Yoda. “No! Try not. Do. Or do not. There is no try.”

## `egc1995-p141-scan150-luke-byss-apprentice.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.141 / scan 150 / PDF page 150
- Prior defect: CONFIRMED BAD: old crop began mid-sentence at “clone of Emperor Palpatine…” (scan 150 right col) without the sentence start in the middle column, and included photo/following paragraph and column slivers; recut with the middle-column start
- Method: 2 numbered PARTS: middle col art-wrapped (625,1403)-(1074,2046); right col continuation (1123,281)-(1567,707)
- Opening words: “Surviving Imperial forces drove the New” · Ending words: “and Leia helped destroy the clone.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: Luke art beside PART 1 art-wrapped lines; text complete
- sha256 old → new: `9f34fc0de6a3a75cab880452fdfe6ac59d188d06fe299889e7ba713beda50448` → `c1841de177b6b404ef3cc8803a22a60fa5e4ef5247254335272672165b7e0f51`

> Surviving Imperial forces drove the New Republic off Coruscant; its temporary headquarters were established on the Fifth Moon of Da Soocha in the Cyax system. Lando, Wedge, and Luke attacked Coruscant, but their ship crashed. Although the others escaped in the Falcon, Luke allowed himself and Artoo to be sucked up into a crackling blue Force storm. It transported him to an Imperial dungeon ship, which, in turn, took him to Byss. There, he was surprised to find the clone of Emperor Palpatine, alive and willing to teach him. ¶ Like a few others in the history of the Jedi, Luke felt he could learn about—and destroy—the dark side of the Force from within. As the training went on, Luke was sure he was staying with the light, but he was becoming corrupted. It wasn’t until Leia confronted him, her lightsaber flashing, that he realized how much he had almost lost. Working together, Luke and Leia helped destroy the clone.

## `egc1995-p141-scan150-obiwan-final-goodbye-first-of-new.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.141 / scan 150 / PDF page 150
- Prior defect: old crop: loose (art, neighbouring column slivers, following paragraphs); recut tight
- Method: single block middle col (628,390)-(1073,850)
- Opening words: “Luke saw his earlier mentor for” · Ending words: “but “the first of the new.””
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `fb74867df95d1d9bb3d8c9ee1cd6a65b9f36cadd0c81a1c9b939ebfe62666c5a` → `421bff607dc55b2ebb87677cc909dc2872fc7987110b9b3b4ccb078fc1a54060`

> Luke saw his earlier mentor for the final time in the Imperial Palace on Coruscant. Ben appeared to him as he slept, warning him that the pathways were closing for the fading Jedi. He assured Luke that he was a powerful Jedi, and a hope for the future. Obi-Wan then bid him good-bye, adding, “I loved you as a son, and as a student, and as a friend. Until we meet again, may the Force be with you.” Then, as he disappeared forever, he told Luke to think of himself not as the last of the Jedi, but “the first of the new.”

## `egc1995-p152-scan161-leia-owen-kenobi-brother.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.152 / scan 161 / PDF page 161
- Prior defect: old crop: loose (art/stat box, opening paragraph, next paragraph) and bottom line(s) sliced at crop edge; recut tight
- Method: 2 numbered PARTS: left col (145,1857)-(590,2029); middle col continuation (639,1567)-(1086,1882)
- Opening words: “In the time after the Clone” · Ending words: “raised by Kenobi’s brother, Owen Lars.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `4ed1d7aafc4146613d3ec2bc76d2d63b314b45d3c76c8a0dee7eda4db813272d` → `cded3a4374f06c188f2900f5137c609ab567a100837831ce4dab0daf94fdcc7b`

> In the time after the Clone Wars, the Jedi Knight Obi-Wan Kenobi arrived at the home of his old friend, Viceroy and First Chairman of Alderaan, Bail Organa. Kenobi’s Jedi student, a hotshot young star pilot named Anakin Skywalker, had been seduced by the dark side of the Force and had become the Dark Lord of the Sith, Darth Vader. Kenobi brought with him Skywalker’s wife and her young newborn twins, Luke and Leia. Bail sheltered the woman and her daughter in the Royal House while Obi-Wan brought the infant Luke to Tatooine to be raised by Kenobi’s brother, Owen Lars.

## `egc1995-p155-scan164-anakin-spirit-forgiveness-leia.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed pp.154–155 / scans 163–164 / PDF pages 163–164
- Prior defect: CONFIRMED BAD: old crop began mid-sentence at “trying to take away her anger” with no scan 163 (printed p.154) sentence start; also loose (art, neighbouring column slivers); recut with cross-page start
- Method: 3 numbered PARTS: s163 right col (1141,1865)-(1584,2038); s164 left col (136,737)-(578,947); s164 left col (136,956)-(578,1128)
- Opening words: “The truce wasn’t the most important” · Ending words: “ease the pain of her memories.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `fb6cdeb63e5f68812b34f8674d3ae016a36c208adce9753b5b5cb31419af13b5` → `d6a117a0fd35f30f7b183d262eac60b19559595f6311028654d783de55499ebe`

> The truce wasn’t the most important part of the trip for Leia’s mental health; Anakin Skywalker’s spirit appeared to her in her suite on Bakura. The man who had once been Darth Vader begged her forgiveness, trying to take away her anger. “Anger is the dark side,” he cautioned, adding, “I do not ask for absolution. Only your forgiveness.” But Leia refused to forgive the man who had tortured her, helped destroy her world, and frozen Han in carbonite. ¶ Eventually, in the heat of the Bakuran battle, she did come to at least forgive her father. Even if she would never forget, every world she took from the Empire would help ease the pain of her memories.

## `egc1995-p170-scan179-luke-first-new-jedi-knights.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.170 / scan 179 / PDF page 179
- Prior defect: old crop: target complete but loose (Tionne art, neighbouring column slivers, surrounding paragraphs); recut tight
- Method: single block right col (1131,1219)-(1574,1425) [margins applied]
- Opening words: “Shortly thereafter, Luke Skywalker addressed his” · Ending words: “You are champions of the Force.””
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: tip of instrument art beside left edge of lines 3–4; text complete
- sha256 old → new: `a1b913dd357999af4d248d760a1e29dbd37cc8f66e770bcb8c4b16c447a17095` → `4002728b929e38ac87b329a8eaf988639a8e69dce67dad0272c576d5502a024d`

> Shortly thereafter, Luke Skywalker addressed his students. “You are the first of the new Jedi Knights. You are the core of what will become a great order to protect the New Republic. You are champions of the Force.”

## `egc1995-p177-scan186-vader-twins-owen-kenobi-brother.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.177 / scan 186 / PDF page 186
- Prior defect: old crop: target complete but loose (top line of prior paragraph sliced, next paragraph, Vader art, middle-column slivers); recut tight
- Method: single block left col (130,947)-(570,1263) [margins applied]
- Opening words: “On the day the twins, Luke” · Ending words: “they were his aunt and uncle.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `a97cfdd8aa234776c3dc1acce747c202496c6ed61d9c2204e10f0b04c89787e7` → `0843444df6c9cdebd2fc69fad9deea67307845d2d9c77e4a0554da5d3a27c0d6`

> On the day the twins, Luke and Leia, were born, Kenobi and their mother separated them. Leia remained on Alderaan, where she was adopted by Bail Organa into the Royal House as his daughter. Obi-Wan brought the infant Luke Skywalker to his brother’s home on Tatooine. There, Owen and Beru Lars promised to raise the child as if they were his aunt and uncle.

## `egc1995-p191-scan200-yoda-force-knowledge-never-attack.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.191 / scan 200 / PDF page 200
- Prior defect: old crop: loose (whole stat box/art and full right column); recut to the named two paragraphs
- Method: single block right col two paragraphs (1120,563)-(1565,1062)
- Opening words: “Yoda taught his students that affinity” · Ending words: “to pass along to future Jedi.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `12a81546740ec8996e27793b09c5b0e76f9d20b54bc00c5fab5d170510cc9b44` → `a4f51c70f2ea0c50f8715c18f539497671da014864c4226c67e409cbacbbff6b`

> Yoda taught his students that affinity with nature enhanced an affinity with the Force. He gave them endurance tests, had them run marathons, jump wide lagoons, fight seeker balls with their lightsabers, balance in seemingly impossible ways, meditate for long periods, and levitate objects. Yoda made his students unlearn that which their upbringings, and their own eyes and ears, had taught them. ¶ “A Jedi uses the Force for knowledge. Never for attack.” Lessons such as these made training easier; they also became good advice to pass along to future Jedi.

## `egc1995-p192-scan201-yoda-another-skywalker-death.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.192 / scan 201 / PDF page 201
- Prior defect: old crop: loose (top line sliced, following paragraph, art, column slivers); recut tight
- Method: single block right col two paragraphs (1124,613)-(1567,1148)
- Opening words: “Luke was not lost to the” · Ending words: “disappeared, becoming one with the Force.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: none
- sha256 old → new: `b28f6f58c1de1d13f7ec24cc7e313daf223bcbcccec6714cfd9b121dbd2c9ce4` → `f60396381a4322d5cee3b62de259d9bc0cd6d4f5ae113d1d03b852175b82cb2f`

> Luke was not lost to the dark side, and the following year he returned to Dagobah, as he had sworn to do. But he found that Yoda was dying. Yet the diminutive Jedi Master joked that Luke would not look nearly so good at nine hundred years old. ¶ Then Yoda offered his final advice. He once again warned Luke to beware the dark side, even though a confrontation with Darth Vader would be a necessity. Reminding Luke that he was now the last of the Jedi, Yoda’s final words were to reveal that there was another Skywalker. Then Yoda breathed his last and disappeared, becoming one with the Force.

## `egc1995-p192-scan201-yoda-do-or-do-not-size-fail.jpg`

- Kind: target quote · Status: **RECUT**
- Source: EGC 1995 printed p.192 / scan 201 / PDF page 201
- Prior defect: old crop: loose (neighbouring column slivers, following paragraph narrowing into art, sliced top line); recut tight
- Method: single block middle col two paragraphs incl. art-wrapped lines (626,869)-(1073,1620)
- Opening words: “Luke learned two other valuable lessons.” · Ending words: “why you fail,” Yoda told him.”
- Source page(s) Read this run: **yes**. Final file Read against page: **yes**; every line start and end present; ¶ = paragraph break in source.
- Remaining defect: minor: edge of Yoda ear art beside final art-wrapped lines; text complete
- sha256 old → new: `8505788d9c676fb3b303fc87a75aca3131952bbdb0733d917b2700c79ae03494` → `72a1c210badb408a0a617f2c7ad4d2c53883c470baa6dbeda3bbf26a6d407dc0`

> Luke learned two other valuable lessons. Once, when Yoda had him practice levitation, Skywalker was distracted when his X-wing sank in the bog, and he gave in to despair. Yoda ordered him to use the same levitation powers to raise his ship. Luke said he’d try, but was cut off curtly by Yoda. “No! Try not. Do. Or do not. There is no try.” ¶ Lacking belief in himself or his powers, Luke was unable to raise his ship, complaining that it was too big. “Size matters not,” Yoda told him, reminding him that the Force flowed through everything . . . through Luke, through the bog, and through his ship. Then Yoda concentrated, and grandly raised the X-wing out of the marsh and onto dry land. “I don’t believe it,” his astonished student said. ¶ “That is why you fail,” Yoda told him.

## `egc1995-p001-ackbar-statblock.jpg`

- Kind: statblock/illustration (not a verbatim quote) · Status: **S (UNCHANGED, hash proof only)**
- Source: EGC 1995 printed p.1 / scan 010 / PDF page 10
- Prior defect: old Round-2 “S” classification confirmed
- Method: kept unchanged; image Read this run
- Image Read this run: **yes**. Not a quote; kept unchanged; hash proof only (no JPG in this ZIP).
- Remaining defect: illustrative only: crop stops at Homeworld (later sidebar fields not shown); not to be cited as a quote
- sha256 old → new: `51b83fad2993ea9104d5cb37e277058ec2d12f9f22d254f9cf082d473d7351a1` → `51b83fad2993ea9104d5cb37e277058ec2d12f9f22d254f9cf082d473d7351a1`

> N/A — not a quote. Image shows the ADMIRAL ACKBAR title bar, Rebel emblem, Ackbar illustration, and the book’s in-universe data box fields: Species: Mon Calamari; Sex: Male; Hair Color: None; Eye Color: Orange; Height: 1.8 meters; Homeworld: Mon Calamari. These are the book’s descriptive sidebar fields, not RPG/game statistics.

## Aggregate 63-asset accounting (EGC 1995 quotes folder)

- v3a: 5 (published earlier) · v3b: 9 · v3c: 18 · v3d: 31 (30 RECUT + 1 S unchanged) → **63** = all 63 JPGs in `quotes/`.
- 62 target quotes (5 + 9 + 18 + 30) + 1 statblock (`egc1995-p001-ackbar-statblock.jpg`, illustrative, not a quote, no RPG stats).
- Unresolved exceptions: none at text level. Cosmetic only: art/photo edges beside art-wrapped lines on palpatine-cities, greatest-military, kenobi-millions-voices, palpatine-final-death-terror, ulic-sith-brand-exar-quote, luke-byss-apprentice, luke-first-new-jedi-knights, yoda-do-or-do-not-size-fail; column rule at the left edge of ken-jedi-prince PART 1. Statblock crop stops at Homeworld (illustrative only).
