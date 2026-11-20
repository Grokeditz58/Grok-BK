# 176: Young Jedi Knights 4: Lightsabers (Kevin J. Anderson & Rebecca Moesta)

Status: DONE (2026-11-20 CST). Full read of every line, in order, of the owner's library copy. Only the notes are committed here; no book text is stored.

Sources (owner's MEGA library):
- Page scan (PDF): MEGA handle watkSL6B (35,986,112 B, sha256 `585c81902c897f7346db9770a0666cbed535251ecbfa1843c4ff0a7e7ff1cce5`). Path: Kileko's Files/To Be Sorted/YJK/Lightsabers_nodrm.pdf. It has 244 scan pages of the Boulevard paperback (March 1996); scan page = printed page + 10.
- OCR epub: MEGA handle 4Ck0DTrB (432,151 B, sha256 `1c542ae6180def68f401ab33d5dac8ef7b3bf83e178bd7787a18e6a6e03f81ce`), same folder. It is an archive.org OCR of that same scan and carries the printed page breaks. It was used for the story text.
- "Not retail" text PDF: MEGA handle kG9SHTLC (336,908 B, sha256 `57bf0ea624ab254bc1f10aebf831d36408e164eefbba79e6d63628337083f2fb`). Path: Kileko's Files/eBooks/Young adult novel/Young Jedi Knight (not retail)/…Lightsabers….pdf. Its text starts in the middle of ch. 1 and drops chapter openings, so it was **not** used.

Method:
- READ.txt (**l.1–1845 of 1845**, 287,090 B, sha256 `493853407273ae7c0ec40b41a143929d301a6167b21bc53056aea2d97f3d21c7`) was assembled as follows:
  - Front matter (scan p1–p6: cover, series ad, about the authors, title page, copyright page) and the back cover (scan p244) come from the scan's text layer.
  - The dedication (scan p7), the acknowledgments (scan p9), all 21 chapters, the Darkest Knight blurb (p.219) and the preview (p.220–232) come from the OCR epub.
  - `[p.N]` markers come from the epub's page breaks and were spot-checked against the scan; the epub's lone page-number and running-head lines were dropped.
  - `## CHAPTER N` headings were placed at each small-caps opener. The count was checked against the scan, where ch. 21 opens on scan p221 with its number.
- The text was read in order in 52 chunks of about 5.6 KB each. Notes were written after each chunk as anchors (line number + first and last words).
- A script (expand.py) then replaced every anchor with the exact passage pasted from READ.txt plus its chapter and printed-page citation, so no quote is retyped. An anchor that did not match would stop the build. One anchor had a wrong end word and was corrected before the build.
- A second script matched all 930 quoted passages in the part files back against READ.txt: **0 mismatches**. summary.md adds 57 more, also with 0 mismatches.
- OCR glitches are kept as they appear, e.g. hyphens left from line breaks ("Sky-walker", "skyhop-per"), "hirn", "Vm", "/" for an italic I, "oflen", "outsidel".

| File | Coverage |
|---|---|
| ls-01.md | Front matter, ch. 1–5 (READ l.1–518) |
| ls-02.md | ch. 6–10 (l.519–763) |
| ls-03.md | ch. 11–15 (l.764–1141) |
| ls-04.md | ch. 16–18 (l.1142–1418) |
| ls-05.md | ch. 19–21, Darkest Knight blurb and preview, back cover (l.1419–1845) |
| summary.md | Plot by chapter, strongest tagged findings by character, scale notes |
| COVERAGE.md | Stamp, coverage, density, checks |

Chapter starts (READ line): ch1 l.132; ch2 l.232; ch3 l.293; ch4 l.352; ch5 l.453; ch6 l.519; ch7 l.568; ch8 l.628; ch9 l.680; ch10 l.727; ch11 l.765; ch12 l.809; ch13 l.896; ch14 l.990; ch15 l.1056; ch16 l.1142; ch17 l.1264; ch18 l.1311; ch19 l.1419; ch20 l.1498; ch21 l.1638; back matter l.1692.
