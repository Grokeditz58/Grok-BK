# 174: Young Jedi Knights 2: Shadow Academy (Kevin J. Anderson & Rebecca Moesta)

Status: DONE (2026-11-20 CST). Full read of every line, in order, of the owner's library copies. Only the notes are committed here; no book text is stored.

Sources (owner's MEGA library):
- Epub: MEGA handle lHkykZ5L (462,213 B, sha256 `1290bcfe6c8b67a8e0124811e6c64e50353ccbbb6d84c31cb4d85208cc6dcb23`). Path: eBooks/Young adult novel/Young Jedi Knight (not retail)/Star Wars - Young Jedi Knights 02 - Shadow Academy # Kevin J. Anderson & Rebecca Moesta.epub. Clean text of all 22 chapters, with no front or back matter and a few join glitches ("theGreatTemple", doubled spaces such as "Shadow    Academy", stray ‘ for “).
- PDF scan: MEGA handle ET9QjJrQ (37,218,519 B, sha256 `d1f8c0a26d01392f5037fa90c6146fc8c4533374f1e5e1c58f9f45c1488e9ff1`). Path: Kileko's Files/To Be Sorted/YJK/Shadow academy_nodrm.pdf. 244 scan pages of the Boulevard printing: ISBN 1-57297-025-1, "Boulevard edition / September 1995", © 1995 Lucasfilm Ltd. Printed page = scan page − 12.

Method:
- The epub text was aligned to the scan text (pdftotext, per page) to place printed-page markers, and the scan's front matter (scan p1–p11) and back matter (scan p219–p244) were merged in. The result is one reading text, READ.txt: **l.1–2588 of 2588** (sha256 `85e060552cea9407e34769705e2fdf29c62ab58635a66fa0fa20269b86c54b8d`). It carries printed-page markers for all 207 story pages (scan p13–p219) and chapter headings.
- The text was read in order in 56 chunks of about 5.6 KB each. Notes were written after each chunk as anchors (line number + first and last words).
- A script (expand.py) then replaced every anchor with the exact passage pasted from READ.txt plus its chapter/page citation, so no quote is retyped. An anchor that did not match would stop the build; none failed.
- A second script matched all 747 quoted passages in the part files back against READ.txt: **0 mismatches**.
- OCR convention: text-layer damage is left as printed. A reading in ⟨⟩ marks an OCR repair only, e.g. "Dave W⟨o⟩lverton". The front-matter teaser and the Lost Ones preview come from the scan's text layer, whose columns are sometimes out of order. Those quotes keep the layer's word order and say so.

| File | Coverage |
|---|---|
| sa-01.md | Front matter (cover, character teaser page, title, copyright, dedications, acknowledgments), ch. 1–5 (READ l.1–605) |
| sa-02.md | ch. 6–11 (l.606–1047) |
| sa-03.md | ch. 12–17 (l.1048–1408) |
| sa-04.md | ch. 18–22 (l.1409–1840) |
| sa-05.md | The Lost Ones blurb, The Lost Ones ch. 1 preview (printed p.209–225), About the Authors, series ads and order form, back cover (l.1842–2588) |
| summary.md | Plot by chapter, strongest tagged findings by character, scale notes |
| COVERAGE.md | Stamp, coverage, density, checks |

Chapter starts (scan p / printed p / READ line): ch1 p13/1/l.177; ch2 p24/12/l.264; ch3 p33/21/l.333; ch4 p43/31/l.419; ch5 p54/42/l.517; ch6 p64/52/l.606; ch7 p74/62/l.687; ch8 p88/76/l.806; ch9 p95/83/l.867; ch10 p101/89/l.913; ch11 p112/100/l.996; ch12 p118/106/l.1048; ch13 p123/111/l.1088; ch14 p132/120/l.1146; ch15 p142/130/l.1223; ch16 p149/137/l.1278; ch17 p156/144/l.1337; ch18 p166/154/l.1409; ch19 p178/166/l.1510; ch20 p188/176/l.1590; ch21 p198/186/l.1666; ch22 p212/200/l.1776. The novel ends on printed p.207 (l.1841).

Characters (quick reference):
- **Jacen Solo**: Force search finds a Corusca gem; senses hostile intent. His first real lightsaber fight comes under Brakiss, and he duels a disguised Jaina to a stalemate. Blindfolded deflections; cuts his door with the gem and traces its wiring by the Force; calms a hawk-bat (preview). He hands Luke's lightsaber back: "not ready".
- **Jaina Solo**: throws off Brakiss's mental pressure but is hit by his Force lightning. Duels the disguised Jacen. Wires Em Teedee into the station computer, seals Brakiss off with the Shadow Chaser's lasers, and admits she did not open the space door.
- **Tenel Ka**: Force premonitions; the Hapan heir hiding her rank. Commands her way into the Great Canyon camp and out-lifts Vonnda Ra. Breaks Garowyn's hold, deflects Tamith Kai's Force blow, and breaks her knee with a kick: "I never use the Force unless I have to". Her first joke.
- **Lowbacca**: endures hours of Tamith Kai's torture, then breaks in rage and destroys the sonic generator. Throws a bench to bowl over guards. Runs four remotes, crashes the training room, slices into the station core and drops the cloak.
- **Em Teedee**: reprogrammed as an Imperial loyalist, used for the passwords, then purged.
- **Luke Skywalker**: hurls Vonnda Ra's rancor-head chair through the roof by TK, and lifts and holds Garowyn helpless. Holds back on purpose during tests. Faces Brakiss but does not want to fight him. "No one is completely evil. Or completely good."
- **Brakiss**: persuasive voice; Force lightning on Jaina; premonition. Never actually fights, and is locked out of his own office.
- **Tamith Kai**: Force leash on three trainees and the torture regime. Blasts open her sealed door and tears out a plate; downed by one kick.
- **Garowyn, Vonnda Ra, Vilas** (new Nightsisters), **Qorl** (droid arm, doubts, secretly opens the space doors), **Lando and Lobot** (GemDiver Station), **Augwynne Djo**, **Teneniel Djo** (recounted), **Ambassador Yfra** and the **Hapan Matriarch**, **Han and Leia**. In the preview: **Zekk**.
