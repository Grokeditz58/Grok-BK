# 179: Young Jedi Knights 7: Shards of Alderaan (Kevin J. Anderson & Rebecca Moesta)

Status: DONE (2026-11-20 CST). Every line of the owner's library copy was read in order. Only the notes are committed here; no book text is stored.

Scope: under the owner's rulings of 2026-11-20, the notes keep only scaling-relevant material: feats of every kind (Force and lightsaber, plus strength, durability, speed, reflexes, agility, stamina, pain tolerance, marksmanship, hand-to-hand, tech and tactics, senses), skills, statements about characters, narrative portrayal, and anti-feats, limitations and caveats. Ordinary non-Force piloting is not noted (Lowie's and Jaina's asteroid-field flying, Zekk's and Fett's dogfight maneuvers); Force-assisted piloting is (Lowie in ch. 14). Each chapter has a short Plot bullet so the story is followed.

Sources (owner's MEGA library):
- Page scan (PDF) with a clean text layer: MEGA handle VbkG3BhS (22,468,152 B, sha256 `60c71377150a9de767112083638509f113607dc3a4374037b30871ef7cb3d73f`). Path: Kileko's Files/To Be Sorted/YJK/Shards of Alderaan_nodrm.pdf. It has 244 scan pages of the Boulevard paperback (January 1997); scan page = printed page + 12. **This is the reading text.**
- "Not retail" epub: MEGA handle sD8CzByD (92,809 B, sha256 `9011daa8772b08f5e05ee69dfe53303728907fd7ab9983b6a24bb030d5eb9c41`), Kileko's Files/eBooks/Young adult novel/Young Jedi Knight (not retail)/. It was not used for the text, because its paragraphs are broken.

Method:
- READ.txt (**l.1–1360**) was built from the PDF text layer by script. Paragraphs start at indented lines; running heads and page numbers were dropped, with `[p.N]` printed-page markers kept. `## CHAPTER N` markers sit at the 21 chapter-opening pages. Line-break hyphens were rejoined only where the unhyphenated word occurs elsewhere in the book; the rest were fixed by hand (e.g. "construe-tion").
- OCR misreadings were fixed in READ.txt: "Slave TV"/"Slave 7V" → Slave IV, "Boman" → Bornan, "Fm"/"IVe" → I'm/I've, "Mends" → friends, "‘" → an opening double quote, and one running head caught inside a paragraph.
- Front matter (scan p1–12: cover, copyright, dedication) was read and holds nothing scaling-relevant.
- The text was read in order in chunks of about 50–70 lines. Notes were written as anchors, and expand.py pasted each passage with its chapter and page citation, so no quote was retyped.
- A second script matched all 168 quoted passages back against READ.txt: **0 mismatches**. No quote repeats within a file. summary.md is in our own words.

Files: soa-01 (ch. 1–10), soa-02 (ch. 11–21 and back matter), summary.md, COVERAGE.md.
