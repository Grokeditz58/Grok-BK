# 180: Young Jedi Knights 8: Diversity Alliance (Kevin J. Anderson & Rebecca Moesta)

Status: DONE (2026-11-20 CST), **with a source gap** (see below). Every line of the owner's English library copy was read in order. Only the notes are committed here; no book text is stored.

Scope: under the owner's rulings of 2026-11-20, the notes keep only scaling-relevant material: feats of every kind (Force and lightsaber, plus strength, durability, speed, reflexes, agility, stamina, pain tolerance, marksmanship, hand-to-hand, tech and tactics, senses), skills, statements about characters, narrative portrayal, and anti-feats and limitations. Ordinary non-Force piloting is not noted (e.g. Raaba's flying in ch. 14); Force-assisted gunnery and piloting are (Jaina and Lowie in the quad-laser wells, ch. 7). Each chapter has a short Plot bullet so the story is followed.

Sources (owner's MEGA library):
- "Not retail" epub: MEGA handle pW1kxT6C (88,488 B, sha256 `10bcc73f8d457419a152782ba61577886cdea6302f90a8842488ee2aab51d5f1`). Path: Kileko's Files/eBooks/Young adult novel/Young Jedi Knight (not retail)/. It is a calibre conversion of the 1997 Boulevard Books paperback. **This is the reading text.**
- Mobi of the same release: MEGA handle df922TYQ (150,104 B, sha256 `bf47427d99bf7c52b7ef6f86c667bdf91cefebe40fe4369e01618a743504d17e`). It was checked and has the same text, including the same truncation.
- German translation, *Allianz der Vergessenen* (trans. Michael Kubiak): MEGA handle IDtChLha (282,667 B, sha256 `b144a4966b215ced98247e59c92b63bb47a443d4b677515546842cb64ce313c6`), Kileko's Files/Foreign/German/. It was used **only** to follow the plot of the missing ending.

**Source gap:** both English files break off mid-sentence early in ch. 19 ("I suggest we discuss the merits of our escape plans aft…", READ l.1527) and jump to the back-cover blurb. The rest of ch. 19 (about two-thirds of it) and all of ch. 20 are missing. No other English copy (scan or retail) is in the library listing. The ending was read in the German edition and is given in da-02 as an English paraphrase, clearly labeled. Nothing from it is quoted or routed to character files. If an English copy turns up, those feats (Lowie's Force leap, Jaina's muzzle cut, IG-88's grenade kills, Tyko's capture) should be quoted and routed.

Method:
- READ.txt (**l.1–1624**) was built from the epub's XHTML by script. Paragraphs come from the conversion's paragraph tags, and some paragraphs broken across lines were left as they were. `## CHAPTER N` markers came from the chapter heads. `[p.N]` markers number the epub's own page-break (softbreak) marks in order. **They approximate the paperback pages and were not checked against a scan.**
- Conversion and OCR misreadings were fixed in READ.txt before pasting: Raynat → Raynar, Boman/Bomaryn → Bornan/Bornaryn, Twflek → Twi'lek, daws → claws, dues → clues, Rock Dragoh → Rock Dragon, Em Tedee → Em Teedee, How rak → Hovrak, Grammalin/Gain malin → Gammalin, stray ‘ ’ marks, and run-together words.
- The text was read in order in chunks of about 60–90 lines. Notes were written as anchors, and expand.py pasted each passage with its chapter and page citation, so no quote was retyped.
- A second script matched all 145 quoted passages back against READ.txt: **0 mismatches**. No quote repeats within a file. summary.md and the German-section paraphrase are in our own words.

Files: da-01 (front matter, ch. 1–10), da-02 (ch. 11–20 and back matter), summary.md, COVERAGE.md.
