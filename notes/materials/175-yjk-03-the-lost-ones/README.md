# 175: Young Jedi Knights 3: The Lost Ones (Kevin J. Anderson & Rebecca Moesta)

Status: DONE (2026-11-20 CST). Full read of every line, in order, of the owner's library copy. Only the notes are committed here; no book text is stored.

Sources (owner's MEGA library):
- Epub: MEGA handle kTlghbZa (1,668,652 B, sha256 `ec9847944339bf9c1ff9b9404f23a002c69c64005ac1fe1a7e72965cdf8a3aba`). Path: Kileko's Files/eBooks/Young adult novel/Young Jedi Knight (not retail)/Star Wars - Young Jedi Knights 03 - The Lost Ones # Kevin J. Anderson & Rebecca Moesta.epub. It contains a title block, 22 chapters and a cover image, which is repeated at the end. Cover tagline (read from the image): "AN OLD FRIEND COULD BECOME A NEW ENEMY...".
- Mobi: MEGA handle cLsU3RaC (526,958 B, sha256 `a3ea59f13b47ed27b7fd4273d9905435aa6765f7320a32d3dac719d662cd87d8`), same folder. It has the same text as the epub and was used only for cross-checking.
- No scan of this book is in the library, so there are **no printed-page numbers**. Citations are "LO ch. N".

Method:
- The epub text was extracted and cleaned into one reading text with `## CHAPTER N` headings: READ.txt, **l.1–1265 of 1265** (232,394 B, sha256 `375c17b5db423bb8d87633d6f84e39b42c08c7d9ef7f9964a85109377d737dd4`).
- The text was read in order in 44 chunks of about 5.6 KB each. Notes were written after each chunk as anchors (line number + first and last words).
- A script (expand.py) then replaced every anchor with the exact passage pasted from READ.txt plus its chapter citation, so no quote is retyped. An anchor that did not match would stop the build; none failed.
- A second script matched all 600 quoted passages in the part files back against READ.txt: **0 mismatches**.
- E-book glitches are kept as they appear, e.g. joined words ("theFountainPalace", "theShadowAcademy"), a space before punctuation ("Imperial City .", "New Republic ,"), and a stray ‘ for “. Where a glitch was checked against the one printed excerpt we have, the note says so (see GAP / cross-check below).

GAP: chapter 1 opens mid-scene. Its first line is "Must be a sign of maturity", and the printed opening aboard the Falcon is missing from both the epub and the mobi. Every other chapter begins with its small-caps opener, so the rest looks intact.

Cross-check: the Shadow Academy printing bundles a preview of this book (notes 174, `sa-05.md`; printed p.209–225, scan p219–p237). It runs from the blurb and the tourism-deck scene in LO ch. 2 (READ l.102) through the hawkbat-nest escape. One dropped word in the epub was confirmed against it: the epub's "I’ve always wanted to one up close" (l.163) reads "see one up close" in the print preview (scan p232).

| File | Coverage |
|---|---|
| lo-01.md | Front matter (title lines), ch. 1–4 (READ l.1–292) |
| lo-02.md | ch. 5–10 (l.293–579) |
| lo-03.md | ch. 11–15 (l.580–907) |
| lo-04.md | ch. 16–22 (l.908–1265) |
| summary.md | Plot by chapter, strongest tagged findings by character, scale notes |
| COVERAGE.md | Stamp, coverage, density, checks |

Chapter starts (READ line): ch1 l.9; ch2 l.68; ch3 l.189; ch4 l.239; ch5 l.293; ch6 l.337; ch7 l.410; ch8 l.463; ch9 l.499; ch10 l.525; ch11 l.580; ch12 l.659; ch13 l.717; ch14 l.766; ch15 l.829; ch16 l.908; ch17 l.939; ch18 l.1008; ch19 l.1036; ch20 l.1104; ch21 l.1179; ch22 l.1234.


## Scope trim (2026-11-20 CST)

Under the owner's scope ruling of 2026-11-20, these notes were trimmed in place to scaling-relevant material only: feats of every kind (Force, lightsaber, strength, durability, speed, reflexes, agility, stamina, pain tolerance, marksmanship, hand-to-hand, tech and tactics, senses), statements about characters, narrative portrayal, and anti-feats and limitations. Plot bullets stay, so the story can still be followed.
- Passages with nothing scaling-relevant (scenery, jokes, filler dialogue, front matter and ads) were removed. Each run of them is marked "(Passages here were read but are not quoted: not scaling-relevant; see the Plot bullet.)" and then left as blank lines. That keeps every line number the same, so the `Our notes: path:line` pointers in the character files still resolve.
- Tagged passages that were not routed to a character file keep their first quote, cut to the first two sentences. "[…]" marks a cut, and "(+N further passage(s) read, not quoted, through …)" gives the page span.
- Passages routed to character files are kept as they were. Any context quotes in the same bullet that were not routed were dropped and marked "(+N context passage(s) read, not quoted)".
- summary.md: the findings index now gives citations only. The quotes are in the part files.
- Folder size: 173,933 B before, 102,183 B after. The character files were not changed.