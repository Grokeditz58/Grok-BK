# notes148 EGVV 1996 — quote-image QA v3, checkpoint CP3a (4 of 51; 20 of 51 with CP1+CP2a+CP2b) — 2026-11-09

Scope: **only** the 4 crops below (printed pp. 56, 60, 62, 64 / scans 047, 049, 050, 051). These were previously untouched pre-QA screenshot crops (not part of CP1 or the CP2 wave). Together with CP1's 4, CP2a's 6, and CP2b's 6 (CP2b is accepted and queued for publication on the same PR 2), **20 of 51** EGVV quote images now have an accepted v3 QA package. **31 remain** unchecked. This package does not start those 31.

CP1, CP2a, and CP2b crops and packages were not touched. The four live quote JPEGs listed below were recut from native 200 ppi source this run (old screenshot files were backed up first at `notes/audits/quote-qa-v3-2026-11-09/backup-148-cp3a-pre-20261109-200535/`). WIP `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp3a/records.md` holds the four accepted transcription records and was not edited in this packaging step. An earlier unverified writeup `AUDIT-QUOTE-QA-v3-CP2-2026-11-09.md` remains in the materials folder and is not an accepted record for these four.

Source: `primary/essential-guides/eg-vehicles-1996/Essential-Guide-to-Vehicles-and-Vessels-1996.pdf` (RO12wBBC; 121 PDF pages, one embedded gray JPEG per PDF page = a two-page spread). Scan number = PDF page number. Printed folios were read from each spread's footer (white numerals in the black folio boxes below the footer rule; not from the k = S − 19 formula alone); all four sit on the left page of the spread. Folios agree with k = S − 19 as a cross-check.

Method: native `pdfimages` crops (200 ppi sources extracted this run under `/tmp/cp3a/src/` for scans 047, 049, 050, and 051 only). Each targeted passage is a single native rectangle (no resampling, no masking). Art and facing-page bleed from the old screenshots were left out. Each crop was read back against the native source and the new final at legible resolution. OCR was used only as a coordinate assist, never as the verbatim source. Boxes are from `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp3a/boxes.json`. Recut composer matches CP2 (`DejaVuSans-Bold` 24 pt labels, JPEG quality 90, grayscale).

Old SHA256 values were checked against `notes/audits/quote-qa-v3-2026-11-09/backup-148-cp3a-pre-20261109-200535/SHA256SUMS` and `backup-pre-v3/148.sha` (all four old hashes agree). New SHA256 values match the installed live files.

Transcription: running text as printed, with italics as `*…*`. A hyphen at a printed line end is noted as `foo-/bar` in the notes, not kept as a mid-word hyphen in the running verbatim. **A spaced slash ` / ` in the verbatim blocks below is a paragraph separator, not a character printed in the book.** Slashes inside tokens, if any, *are* printed. No per-record clock times are asserted in this audit.

Character facts below are taken **only from the four audited crops**. Adjacent text that was deliberately excluded from a crop is noted as adjacent and is not treated as a fact from the quote image.

---
## 1. egvv1996-p056-scan047-flurry-bakura-destroyed.jpg — FLURRY (BAKURA)
- Locator: PDF p.47 / scan 047 / printed **p.56**. left page of the 56–57 spread (footer "56" / "57" verified in the native footer strip, not from the k=S−19 formula alone); right text column of printed p.56; single box. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [872, 766, 1565, 1532] (scan 047 p.56, right col).
- Old SHA256 `d6f15acac8ebcbd1e211f8709ff5cecd0dd8c722921c99998c8f5dde4e8f9742` → **new `37803240864b376d413c168dfe7c5377e24aed067c9dfaa8695ab1905612326b`** (693x804, 196312 B).
- Opening: “For the Bakura mission against the Ssi-ruuk incursion, the *Flurry* was equipped with a prototype battle analysis computer (BAC).” / ending: “sacrifice.”
- Start = paragraph start (prev right-col para ends "…an additional astromech droid to provide targeting telemetry."); end = paragraph end and end of column text ("sacrifice." then whitespace, then ship art below, excluded). No partial lines; no art in the crop. Three full paragraphs
- Hyphenations / spellings: "naviga-/tion", "pro-/vide", "X-/wings" (the first "X-wings"; later "X-wings" is in-line), "fol-/lowing", "fire-/power". Italics as printed on *Flurry* (three times) and *Dominant*. In-line compounds: "X-wings", "A-wings", "B-wings", "much-needed". Spellings as printed: "Ssi-ruuk", "battle analysis computer (BAC)", "Carrack cruiser".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
For the Bakura mission against the Ssi-ruuk incursion, the *Flurry* was equipped with a prototype battle analysis computer (BAC). The creation of famed Alliance strategist General Jan Dodonna, the BAC was linked to every navigation and combat computer in the Alliance task force to provide detailed composite images of the battle. / As a result of the emergency nature of the Bakura relief effort, the *Flurry* was assigned whatever Alliance starfighters were still operational: Captain Manchisco got twenty X-wings, three A-wings, and four B-wings. Fortunately, the X-wings included Rogue Squadron, under the command of Wedge Antilles. While Alliance command knew that the B-wings were quite likely to break down (because there hadn't been time for a thorough maintenance overhaul following the Battle of Endor), it was thought that their firepower would give the task force some much-needed punch, even if that help would be only temporary. / The *Flurry* was destroyed over Bakura when the Imperial Carrack cruiser *Dominant* suddenly opened fire on her. All hands were lost and were posthumously decorated for their heroic sacrifice.
```

- Remaining defects: none.
- Character facts (this crop only): General Jan Dodonna — famed Alliance strategist; the BAC is described as his creation, and it was linked to every navigation and combat computer in the Alliance task force to provide detailed composite images of the battle. Captain Manchisco — as a result of the emergency nature of the Bakura relief effort, got twenty X-wings, three A-wings, and four B-wings (whatever Alliance starfighters were still operational). Wedge Antilles — commanded Rogue Squadron, which was included among those X-wings. Alliance command — knew that the B-wings were quite likely to break down (no time for a thorough maintenance overhaul following the Battle of Endor) but thought their firepower would give the task force some much-needed punch, even if only temporary. The Imperial Carrack cruiser *Dominant* — suddenly opened fire on the *Flurry* over Bakura; the *Flurry* was destroyed; all hands were lost and were posthumously decorated for their heroic sacrifice. This crop does not give Manchisco a first name.
- Adjacent, not in crop: NOT used as facts from this quote image: adjacent left-column text on the same page names "Captain Tessa Manchisco"; do not attach "Tessa" to this quote image.

---
## 2. egvv1996-p060-scan049-hapan-battledragon-recharge.jpg — HAPAN BATTLE DRAGON (RECHARGE)
- Locator: PDF p.49 / scan 049 / printed **p.60**. left page of the 60–61 spread (footer "60" / "61" verified in the native footer strip, not from the k=S−19 formula alone); left text column of printed p.60; single box. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [140, 833, 830, 1232] (scan 049 p.60, left col).
- Old SHA256 `dba640f3e20fc30743c57f8531075864bfe785b32c4b45357680f5baf938797e` → **new `f23d9b37816fb669baf563c93239466e07b1719c58ea6fa529616e6d0b6c0de7`** (690x437, 110591 B).
- Opening: “Hapes lags significantly behind in turbolaser technology, with a weapon-recharge rate only one-third that of comparable Imperial weapons.” / ending: “place.”
- Start = paragraph start (prev left-col para ends "…four pulse mass generator tubes."); end = paragraph end "place." (next left-col para "The Hapans also link weapons banks…" excluded). No partial lines; no art in the crop. Two full paragraphs
- Hyphenations / spellings: "technolo-/gy", "superi-/or", "mount-/ed". Typographic quotes as printed around “weapon rotation”. Colon as printed after "saucer". In-line compounds: "weapon-recharge", "one-third".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
Hapes lags significantly behind in turbolaser technology, with a weapon-recharge rate only one-third that of comparable Imperial weapons. While the actual blasts are as damaging, the slow recharge rate is a significant liability. / The Hapans compensated for this by developing a superior “weapon rotation” system. All the weapons are mounted on a drive system that rotates around the saucer: weapons are moved to the optimal target point, fired, and immediately moved away for recharging, while new weapons are instantly moved into place.
```

- Remaining defects: none.
- Character facts (this crop only): none (no named characters). The crop describes Hapes / the Hapans and the Battle Dragon's weapon-recharge rate and “weapon rotation” system only.
- Adjacent, not in crop: NOT used as facts from this quote image: later right-column text on the same page names Prince Isolder, Leia Organa, the *Song of War*, the Battle of Dathomir, and Warlord Zsinj.

---
## 3. egvv1996-p062-scan050-hapes-nova-recycle.jpg — HAPES NOVA BATTLE CRUISER (RECYCLE)
- Locator: PDF p.50 / scan 050 / printed **p.62**. left page of the 62–63 spread (footer "62" / "63" verified in the native footer strip, not from the k=S−19 formula alone); right text column of printed p.62; single box. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [872, 510, 1565, 914] (scan 050 p.62, right col).
- Old SHA256 `80471cd85f6524589250c31f540caa74fbbce14594e1e5dd7e9517d4b09429d3` → **new `1b491abd9f4443aa0fbd3e931a2776d749ca23f44f6423306ad252cf46e6393e`** (693x442, 102203 B).
- Opening: “Because of the Hapans' limited turbolaser technology, Hapes Nova cruisers must choose their battles carefully.” / ending: “borders.”
- Start = paragraph start (prev right-col wrap ends "…for planetary invasions."); end = paragraph end "borders." (next right-col para "Taking a cue from Mon Calamari designs…" excluded). No partial lines; no art in the crop
- Hyphenations / spellings: "inop-/portune". Possessives as printed: "Hapans'".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
Because of the Hapans' limited turbolaser technology, Hapes Nova cruisers must choose their battles carefully. Since the Hapan turbolasers take nearly three times as long as Imperial turbolasers to recycle, a Hapes Nova cruiser can find itself incapable of returning fire at the most inopportune time. To counteract this weakness, the Hapans often assign Hapes Nova cruisers in groups of three or more ships. Hapan captains tend to favor swift, brutal assaults, intending to destroy all enemy ships with the first attack. This approach has added to the Hapans' reputation for vigorously defending their borders.
```

- Remaining defects: none.
- Character facts (this crop only): none (no named characters). The crop describes the Hapans / Hapan captains and Hapes Nova cruisers only.
- Adjacent, not in crop: NOT used as facts from this quote image: the following paragraphs mention Mon Calamari designs and backup shield generators; a later paragraph on the same page names Prince Isolder, Leia, Han Solo, and the distant world of Dathomir.

---
## 4. egvv1996-p064-scan051-hornet-unstable-lasers.jpg — HORNET INTERCEPTOR (UNSTABLE LASERS)
- Locator: PDF p.51 / scan 051 / printed **p.64**. left page of the 64–65 spread (footer "64" / "65" verified in the native footer strip, not from the k=S−19 formula alone); right text column of printed p.64; single box. Native source 3700x2200 gray 200ppi.
- Native boxes (`boxes.json`): [872, 653, 1565, 842] (scan 051 p.64, right col).
- Old SHA256 `5bd64cbb8f2b86a93e734cd08a86783e10ecd4aaf268d2341846d32f588ef5fb` → **new `ee66a96b3539e2f20715331be47a5433baabd9bc526cd843d676a1c009aa2d02`** (693x227, 51355 B).
- Opening: “The Hornet's weaponry is an unusual hybrid of turbocharged laser cannons.” / ending: “uses.”
- Start = paragraph start (prev right-col para ends "…the Hornet has no hyperdrives."); end = paragraph end "uses." (next right-col para "The Hornet Interceptor has been made available only to groups affiliated with the Tenloss Syndicate…" excluded). No partial lines; no art in the crop
- Hyphenations / spellings: "tur-/bocharged", "can-/nons". In-line compound: "turbocharged".
- Verbatim (running text; spaced ` / ` = paragraph break, not a printed slash):

```
The Hornet's weaponry is an unusual hybrid of turbocharged laser cannons. While not full turbolasers, these weapons have more punch than do standard laser cannons, although they also become dangerously unstable after only a few uses.
```

- Remaining defects: none.
- Character facts (this crop only): none (no named characters). The crop describes the Hornet's weaponry only.
- Adjacent, not in crop: NOT used as facts from this quote image: preceding left-column text names the Tenloss Syndicate, the Tenloss *Leukish*, and Emperor Palpatine; following right-column paragraphs mention the Tenloss Syndicate and the renewed Emperor, and a later paragraph names Han Solo, a diplomatic mission to Kessel, Moruth Doole, and the *Millennium Falcon*.

---
## Handoff (character facts from these 4 crops only)
- *Flurry* / Bakura (p.56): General Jan Dodonna is a famed Alliance strategist; the BAC is described as his creation and was linked to every navigation and combat computer in the Alliance task force. Captain Manchisco got twenty X-wings, three A-wings, and four B-wings for the Bakura relief effort; the X-wings included Rogue Squadron under the command of Wedge Antilles. Alliance command knew the B-wings were quite likely to break down (no time for a thorough maintenance overhaul following the Battle of Endor) but thought their firepower would give a much-needed, if temporary, punch. The Imperial Carrack cruiser *Dominant* suddenly opened fire on the *Flurry* over Bakura; the *Flurry* was destroyed; all hands were lost and were posthumously decorated. Quote Manchisco as **Captain Manchisco** only — "Tessa" is adjacent left-column text, not in this quote image.
- Hapan Battle Dragon recharge (p.60): no named characters. The crop covers Hapes lagging in turbolaser technology (weapon-recharge rate only one-third that of comparable Imperial weapons) and the Hapans' superior “weapon rotation” system. Do **not** cite Prince Isolder, Leia Organa, the *Song of War*, the Battle of Dathomir, or Warlord Zsinj from this quote image (adjacent only).
- Hapes Nova recycle (p.62): no named characters. Hapan turbolasers take nearly three times as long as Imperial turbolasers to recycle, so a Hapes Nova cruiser can find itself incapable of returning fire at the most inopportune time; the Hapans often assign these cruisers in groups of three or more, and Hapan captains tend to favor swift, brutal first-attack assaults. Do **not** cite Prince Isolder, Leia, Han Solo, or Dathomir from this quote image (adjacent only).
- Hornet unstable lasers (p.64): no named characters. The Hornet's weaponry is an unusual hybrid of turbocharged laser cannons: not full turbolasers, more punch than standard laser cannons, but dangerously unstable after only a few uses. Do **not** cite the Tenloss Syndicate, Emperor Palpatine, Han Solo, Moruth Doole, Kessel, or the *Millennium Falcon* from this quote image (adjacent only).
- Not changed in CP3a: CP1's 4 crops and package, CP2a's 6 crops and package, CP2b's 6 crops and package, the other 31 EGVV quote images, characters/, Git, or any sealed package.
