# notes148 EGVV 1996 — quote-image QA v3, checkpoint CP1 (4 of 51) — 2026-11-09 ~19:05 CST

Scope: **only** the 4 crops below. The other 47 C/C* crops in this book are **not** re-verified here; the old "C" ratings are not trusted.
Source: `primary/essential-guides/eg-vehicles-1996/Essential-Guide-to-Vehicles-and-Vessels-1996.pdf` (RO12wBBC; 121 PDF pages, 1 embedded 200-ppi gray JPEG per page = 2-page spread).
Native image: `pdfimages -j -f N -l N` (byte-identical to old `/tmp/native/148/i-(N-1).jpg`, checked with cmp). Scan number = PDF page number.
Locator: printed folios **read directly off the footer of each spread** (138, 180, 174, 162 on the left page); all four agree with k=S−19 → printed 2k/2k+1. No correction assumed.
Method: crop from the native 200-ppi image (no resampling) with text-safe margins set between line gaps; stacked numbered PARTs (left column → right column, which continues the sentence); labels say scan/printed page/column. Each FINAL jpg was Read back visually (in halves for the tall ones) and every line start/end checked against the transcription below. Word-shape zooms (3×) used for the Sun Crusher name/wording problem and the TIE apostrophe. OCR in `wip/ocr/148` was used **only to find coordinates**; the text below comes from reading the images, not from OCR.
Backup of the old copies (before replacement): `notes/audits/quote-qa-v3-2026-11-09/backup-148-cp1-20261109-190426/` (with SHA256SUMS, checked OK).
WIP/proof zooms: `notes/audits/quote-qa-v3-2026-11-09/wip/148-cp1/` (mk.py crop boxes + zoom PNGs).

Transcription rules: line-by-line as printed. A hyphen at a line end is the printed hyphen. Italic shown as *…*. Small caps are shown as CAPS. Nothing has been normalized.

---
## 1. egvv1996-p138-scan088-shieldship-limits.jpg — SHIELDSHIP
- Locator: PDF p.88 / scan 088 / printed **p.138** (left page of the 138–139 spread; 139 is the diagram). The whole article text is on p.138, in two columns.
- Old defect (confirmed): the old crop was the wide top of the spread. It cut the left column after "Nkllon takes only one hour." It left out the column-end sentence opening "Ships without slave circuits must be escorted to Nkllon", so the right column started mid-sentence with "by utilizing sublight drives". It also included part of the p.139 diagram.
- Fix: PART 1 = full left column (subtitle → "escorted to Nkllon"). PART 2 = full right-column text ("by utilizing…" → "…yet been built."). Illustration and diagram left out.
- Old SHA256 cfddd6696da47855222fc516f15345e1eff571f62cb01acf9be939cae3743797 → **new 2adcd6b5078f07879dc4b898f8d266d31b3e1d6f4deb6aa6f8259293f794b6c0** (702x2099, 598672 B). Native boxes: L (120,425,822,1935), R (864,425,1552,920).
- Opening: "REPUBLIC ENGINEERING CORPORATION HEAT-RESISTANT" / ending: "No additional shieldships have yet been built."
- Target "limits" sentences inside: "The shieldships have proved extraordinarily difficult to pilot and need constant maintenance. The cooling gear must be replaced after every trip in-system, requiring substantial downtime for each vessel." + "Ships without slave circuits must be escorted to Nkllon by utilizing sublight drives; even a slight miscalculation on the hyperspace jump into the system would leave the visiting ship unprotected, resulting in its destruction. The sublight journey into the system takes ten hours."

PART 1/2 (left col)
```
REPUBLIC ENGINEERING CORPORATION HEAT-RESISTANT
ESCORT VEHICLE
Shieldships are unique escort vessels that protect ships
traveling to the planet Nkllon in the Athega system. These
vessels are necessary to block the searing rays of Athega's
superhot star, which can destroy ships that carry only stan-
dard shielding.
Nkllon is so hot that it is habitable only on the dark, or
"night," side. However, its mineral resources are too valu-
able to pass up, especially for someone like Lando
Calrissian, who's willing to bet on the longest odds if the
payoff is right. Lando's payoff was handsome indeed—
once Nomad City was up and running, it was pulling in
nearly 10 million credits per year.
The shieldships were built to Lando's specifications by
the Republic Engineering Corporation, which was formed
shortly after the New Republic seized power in the Galactic
Core. The shieldships have proved extraordinarily difficult to
pilot and need constant maintenance. The cooling gear
must be replaced after every trip in-system, requiring sub-
stantial downtime for each vessel. Lando purchased twelve
of the shieldships, allowing for up to three visits to Nkllon
per day once normal maintenance was taken into account.
The ships appear to be giant umbrellas; the shields are
giant cones approximately eight hundred meters across.
The face of the shieldship has thick armor plating honey-
combed with coolant chambers to keep the outer surface
from being burned off. The back has immense tubes and
fins to vent the intense heat. The shadow behind the shield
is the protected area for incoming starships. Trailing behind
the shield is a four-hundred-meter pylon with a drive tug
which provides sublight and hyperdrive thrust.
The vehicles operate from a central depot on the outer
rim of the Athega system, and use a sophisticated slaving
system to tie their navigation computers into the computers
of any ships they are escorting. Normally, the shieldship
simply takes control of the escorted vessel and jumps into
the heart of the system, bringing the other vessel along for
the ride. In this manner, the journey from the outer depot to
Nkllon takes only one hour.
Ships without slave circuits must be escorted to Nkllon
```
PART 2/2 (right col, continues)
```
by utilizing sublight drives; even a slight miscalculation on
the hyperspace jump into the system would leave the visit-
ing ship unprotected, resulting in its destruction. The sub-
light journey into the system takes ten hours.
The success of the Nkllon mining operation and its
strong New Republic affiliations made it a prime target for
Grand Admiral Thrawn's forces. Thrawn's second attack on
Nomad City destroyed its drive units and long-range com-
munications; the Star Destroyers attacking the outer depot
disabled all but one of the shieldships. Only the timely
assistance of Senator Garm Bel Iblis allowed the evacua-
tion of Nomad City before it was melted by Athega's sun.
No additional shieldships have yet been built.
```
- Remaining defects: none in the text. A small speck from the scan sits after "ten hours." (it is not a character). Quotes and apostrophes are curly in print.

---
## 2. egvv1996-p180-scan109-tie-limits-tight.jpg — TIE FIGHTER
- Locator: **PDF p.109** / scan 109 / printed **p.180** (left page of 180–181; this native image is 3372×2173, unlike the 3700×2200 spreads around it).
- Old defect (confirmed): the old crop was the whole p.180 left column plus the right-column top and illustration. It **ended at "novice pilots may"** and never showed the continuation "attempt an advanced maneuver only to send the ship careening." (That line is at the top of the right column; the old crop's right side started at "The pilot is strapped…".)
- Fix ("tight" = the limits passages only): PART 1 = left col "TIE fighters have only sublight drives." → "novice pilots may". PART 2 = right col "attempt an advanced maneuver…" → "…is very difficult." (the control-yoke difficulty paragraph is included because it is also a limitation). The companion crop `…-tie-no-shields-casualties.jpg` was **not** touched in CP1.
- Old SHA256 f78a080ac113fd84d7f520e45c22f5d239db46aef9c67b215f91ad2b716b01f7 → **new 4266c881732e2e8ccf4d0c939d4a7e8e9d49e53a42b7d87a986aaa69a4babe28** (694x1235, 362381 B). Native boxes: L (138,1236,832,1972), R (880,395,1570,800).
- Opening: "TIE fighters have only sublight drives." / ending: "control through the hand-control unit is very difficult."

PART 1/2 (left col)
```
TIE fighters have only sublight drives. This saves weight
and increases speed and maneuverability, but it makes
TIEs dependent on a home base, such as a nearby planet
or an Imperial cruiser. TIEs carry only two days' worth of
supplies under optimal conditions; in actual combat, TIEs
often must refuel after the first few hours.
The TIEs maneuverability and speed come at great prac-
tical cost to the pilot inside. TIE fighters have no shields, no
secondary weapon or drive systems, minuscule fuel sup-
plies, and no onboard life support system: pilots must wear
fully sealed flight suits with self-contained atmosphere con-
verters. By eliminating all these systems, the TIE saves
mass and makes room for large power generators,
engines, and weapons inside the compact hull.
With thousands of new TIE ships being manufactured
each year and new pilots regularly graduating from
Imperial military academies, casualties are deemed
inconsequential as long as military objectives are
achieved. Some military strategists claim that the TIE is
*too* responsive to piloting adjustments: novice pilots may
```
PART 2/2 (right col, continues)
```
attempt an advanced maneuver only to send the ship
careening.
The pilot is strapped into a simple high-gee shock
couch and is protected by crash webbing and a repulsorlift
antigravity field. The pilot's feet slip into control yokes:
pressing or pulling on the yokes controls speed and
maneuvering. The hand-control yoke affects precise
maneuvering, targeting, navigation, and fire control.
Auxiliary speed and maneuver controls are also located in
the hand-control yoke, but attempting both flight and fire
control through the hand-control unit is very difficult.
```
- Source quirk, kept: "The TIEs maneuverability" is printed **without an apostrophe** (3× zoom `wip/148-cp1/z109_tIEs.png`). Quote it as printed, adding [sic] if needed. "*too*" is italic in print.
- Remaining defects: none.

---
## 3. egvv1996-p174-scan106-tiecrawler-treads.jpg — TIE CRAWLER
- Locator: PDF p.106 / scan 106 / printed **p.174** (left page of 174–175).
- Old defect (confirmed): the old crop started at "campaign to recapture…" with the right column cut at the top. So the left column ended "The drive sys-" but the right side started "tially cheaper than comparable repulsorlift craft." The three lines "tem is simple enough … scavenged for parts." and the line "The TIE tank can navigate most terrain and is substan-" were missing. **The old helpers disagreed because both looked at the cut crop.** The page itself shows "sys-" continuing directly with "tem is simple enough" at the top of the right column.
- Fix: PART 1 = left col last paragraph "The twin Santhe SSct…" → "The drive sys-". PART 2 = right col first two paragraphs "tem is simple enough…" → "…easily damaged by enemy fire."
- Old SHA256 d7277f0664aaf1da8d79a1c52bcbf75004f58fee8a0d9b196ebab2c15f63036d → **new cc78c3a7f50dfea44498f766f3e92e355569c8ef641221250606e4482853526a** (689x694, 165512 B). Native boxes: L (133,1159,822,1314), R (872,425,1558,870).
- Opening: "The twin Santhe SSct power generators are attached to" / ending: "and tread wheels are easily damaged by enemy fire."

PART 1/2 (left col)
```
The twin Santhe SSct power generators are attached to
each side of the pod and drive the tread wheels. The TIE
tank has a top speed of only ninety kilometers per hour, but
drive components are common and cheap. The drive sys-
```
PART 2/2 (right col, continues)
```
tem is simple enough that many pilots can fix the tank
themselves if it is damaged in the field, and it is not unusu-
al to see damaged TIE tanks scavenged for parts.
The TIE tank can navigate most terrain and is substan-
tially cheaper than comparable repulsorlift craft. The
weapons are powered by a single power generator mount-
ed in the rear of the command pod, and they include two
medium blaster cannons that are forward-firing, while a
retractable light turbolaser is mounted in the bottom of the
command pod and can fire in any direction. The TIE tank
has light armor plating on all surfaces, but the drive system
and tread wheels are easily damaged by enemy fire.
```
- Remaining defects: none.

---
## 4. egvv1996-p162-scan100-suncrusher-quantum-armor.jpg — SUN CRUSHER
- Locator: PDF p.100 / scan 100 / printed **p.162** (left page of 162–163; 163 is the diagram).
- Old defect (confirmed): the old crop was the top of the spread. It cut the left column partway through the "command cabin" paragraph ("…the main gunner" / the "fired the resonance torpedoes…" line was clipped), and it included part of the p.163 diagram. (In the old crop the torpedo paragraph "The Sun Crusher carried eleven…" was complete, but the paragraph after it was cut.)
- Fix: PART 1 = full left column (subtitle → "…central piloting station."). PART 2 = full right-column text ("Han Solo was imprisoned…" → "…the Maw's black holes."). This is the whole article text, with the illustration and diagram left out.
- Old SHA256 d6d1a62f758d870e2719ccd6dca435ad060b6d1874d8f5780238b6682d8a9991 → **new c407e8262865130c4860270426a35a8c9308c00426ef1841a1573c05ce7ec362** (692x2125, 567701 B). Native boxes: L (128,420,820,1998), R (868,425,1556,878).
- Opening: "IMPERIAL SUPERWEAPON PROTOTYPE" / ending: "one of the Maw's black holes."
- **Designer spelling, read directly from enlarged letter shapes (3×, `wip/148-cp1/z100_*.png`): printed "Qui Xux" (Q-u-i) in all 4 places on this page** (left col lines 10, 12, 17; right col line 2). It is **not** "Qwi". Elsewhere in this repo, EGC 1995 and the chronologies print "Qwi Xux". Treat "Qui Xux" as this 1996 book's own spelling (likely a typo/variant). When quoting, keep "Qui" and add [sic] or a note; do not change it silently.
- **Wording, read directly (`z100_r580.png`): "stole the Sun Crusher from the Empire."** The words "stole the weapon" do **not** appear on this page. (The page does say "After they delivered the weapon to Coruscant".) Any character quote that reads "stole the weapon" is a misquote of this page and must be corrected to the printed wording.

PART 1/2 (left col)
```
IMPERIAL SUPERWEAPON PROTOTYPE
The Sun Crusher was an Imperial superweapon
designed at the Maw Installation, an Imperial military think
tank that had been secretly established by Grand Moff
Tarkin. The Maw Installation was hidden in the heart of the
Maw, a cluster of black holes near the infamous spice
world of Kessel. The original Death Star superlaser was
invented at the Maw Installation by Imperial Engineer Bevel
Lemelisk and a top design team that included an Omwati
female named Qui Xux. After Tarkin and Lemelisk departed
to build the Death Star, Tarkin left Admiral Daala in com-
mand and ordered Qui Xux to create a new Imperial super-
weapon.
When Tarkin was killed at the Battle of Yavin, the Maw
Installation was forgotten. Admiral Daala waited nearly ten
years for word from the Grand Moff, and during that time
Qui Xux and the design team made the many break-
throughs that led to the new superweapon, dubbed the Sun
Crusher.
The Sun Crusher was only slightly larger than a fighter,
yet its resonance torpedoes were powerful enough to
destroy a star. The ship was a marvel of galactic technol-
ogy that could not be bought at any price—its unique
miniature systems, layered molecular armor, and reso-
nance torpedoes each cost as much to develop as did the
original Death Star superlaser.
The ship was a slender vessel that flew in an "upright"
position: the cockpit was placed at the top of the ship,
while a dish-shaped resonance projector hung from the
bottom of the Sun Crusher. A number of rotating laser tur-
rets were used to disable attacking enemy ships, although
the shimmering quantum-crystalline armor made the Sun
Crusher virtually impervious to damage.
The Sun Crusher carried eleven "resonance torpedoes"
which were energized and launched through the resonance
projector. The torpedoes could be launched into a star to
trigger a chain reaction that would cause the star to go
supernova, incinerating every world in its system.
The command cabin had room for six. Normally, the
pilot handled navigation and control and the main gunner
fired the resonance torpedoes, while the four other gunners
handled the defensive laser cannons. All the controls could
be linked through the central piloting station.
```
PART 2/2 (right col, continues)
```
Han Solo was imprisoned in the Maw Installation, where
he met the Sun Crusher's designer, Qui Xux, and convinced
her of the evil the weapon presented. She, Solo,
Chewbacca, and an escaped slave named Kyp Durron
stole the Sun Crusher from the Empire. After they delivered
the weapon to Coruscant, the New Republic Assembly
voted to have the weapon cast down into the gas giant
Yavin. However, Kyp retrieved the Sun Crusher and went on
a rampage, destroying several Imperial worlds before sur-
rendering the vessel. The Sun Crusher was destroyed at the
Battle of the Maw, when it was caught in the gravity well of
one of the Maw's black holes.
```
- Remaining defects: none in the crop. The "Qui" spelling is the printed source's own and is kept.

---
## Handoff to parent (character files: parent edits, not this worker)
- Qui/Qwi Xux (EGVV 1996 p.162): source-specific facts as printed: Omwati female. She was on Lemelisk's top design team at the Maw Installation. Tarkin ordered her to create a new Imperial superweapon. She and the design team made the breakthroughs that produced the Sun Crusher. Han Solo convinced her "of the evil the weapon presented". She, Solo, Chewbacca and Kyp Durron "stole the Sun Crusher from the Empire." Quote the name as "Qui Xux" [sic].
- Kyp Durron (p.162): "an escaped slave named Kyp Durron". "Kyp retrieved the Sun Crusher and went on a rampage, destroying several Imperial worlds before surrendering the vessel."
- Daala / Tarkin / Bevel Lemelisk (p.162): the lines on left col 7–19 above.
- Lando Calrissian / Garm Bel Iblis / Thrawn (p.138): the shieldship lines above. Lando: "willing to bet on the longest odds if the payoff is right"; Nomad City "nearly 10 million credits per year"; twelve shieldships. Bel Iblis: "Only the timely assistance of Senator Garm Bel Iblis allowed the evacuation of Nomad City before it was melted by Athega's sun." (In print, "evacua-/tion" is hyphenated at the line break.)
- Not changed in CP1: the other 47 crops, the TIE no-shields companion crop, and characters/.
