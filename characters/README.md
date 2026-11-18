# characters/ — per-character power-scaling notes



## Current format (rebuilt 2026-11-17)

Every character file was rebuilt on 2026-11-17 so each quote can be read in full with its citation. The old layout described further down (pointer bullets, Part 3, Sources Index) is kept in `_bak/<name>.md.bak-20261117`. Status and per-batch file lists: `_REBUILD-STATUS.md`. Tool: `[local path]`. **Do not rerun `_build/render.py`**: it would overwrite the rebuilt files with the old layout.

Each file now has:
1. A short header: name, aliases, era, continuity, research tier, entry counts.
2. `# LEGENDS` and then `# CANON`, each grouped by source work (`## <book / comic / guide / issue>`), in reading-number order.
3. Each entry:
   ```
   > the full quotation, verbatim (paragraphs kept)  *(chapter/page tag from our notes, if any)*
   — Source: <citation as written in our notes>. POV: <narrator / speaker>.
   (Full sentence/passage taken from the source text on file: `<text copy on the box>`.)   ← only when the quote was extended
   Context / Note / Label in our notes: <plain words around the quote>
   Our notes: `<path>:<line>`; ...   ← every notes location the item came from
   ```
   A summary with no quotation is shown as `- Note (summary from our notes, not a quotation): ...`.
   `[fragment — full passage not on file]` means our notes hold only part of the passage and the source text is not on the box (or could not be matched word for word), so only the words in our notes are shown. Nothing is reconstructed.
4. `# Debate and forum claims (unverified)`: Suspect Insight / Discord debates, respect threads, forum posts and verdicts, grouped by thread, each with "Posted by" when our notes name the poster, then the verdict pointers.
5. Any `# Chat-research quotes (...)` section is kept as written, at the end.

## Layout

- `<kebab-name>.md`: one file per character. Example: `darth-sidious.md`, `hero-of-tython.md`.
- `INDEX.md`: every file, with its tier, entry count (Legends/Canon), merges, and the aliases that were matched.
- `PROGRESS.md`: build checklist, every source processed with its record count, and every skipped source with the reason.
- `_build/`: the tools that build this folder.
  - `roster.py`: the characters and their aliases.
  - `extract.py`: pulls verbatim units out of a notes file.
  - `run_all.py`: runs every source; resumable.
  - `render.py`: dedupes and writes the files.
  - `make_docs.py`: writes INDEX and PROGRESS.
  - `out/`: per-source records as jsonl.
  - `stats.json`, `sources.json`.
- PDFs, if any, are in `characters/pdf/`. The zip of the whole folder is `research/characters.zip`.

### Inside each character file

1. A header with: name, the aliases matched, era, continuity, research tier, entry count, and duplicates merged.
2. `# LEGENDS`, then `# CANON`. Each has the same sections:
   - Force feats
   - Combat & duels (outcomes included)
   - Durability
   - Speed & reflexes
   - Telepathy & mental
   - Statements & hype
   - Characterization & weaknesses
   - Debate arguments & forum opinion (not feats)
   - Other notes
3. `# VERDICTS (pointers)`: links into `verdicts.md` (heading and line) and into each SI debate that involves the character (with its Result line). Read verdicts there. They are not copied as feats.
4. `# SOURCES INDEX`: every notes file this character's entries came from, with a count for each.
5. `# PART 3: FEATS AND STATEMENTS ONLY`: the character's own feats and statements, one line each. Each line carries its images indented directly under it: the entry's own quote crops, image lines that directly follow it in the notes file, and any comic/book panel whose issue/page tag (e.g. `sw3-p16`, `009-legacy-book-1-panels/p361`) matches an issue/page cited on the line. The character's panels that match no line are listed as their own Part 3 entries. Rows with no image have no panel on file for that issue/page.

### Entry format

```
- [Continuity · version] <the line from the notes, verbatim>
  - Context (parent line in notes): <the bullet or table header it sat under, if any>
  - Speaker: <who says it>, about <character>   (or "(the character's own line)")
  - Source: <the citation as written in the notes: book/chapter/issue/mission/post/URL> — <title of the notes file>
  - Notes: `<path relative to research/>:<line>`   ← open this for full context
  - Also in: `<path>:<line>` — <its source>   ← the same item found in other notes, merged here
```

## Rules (standing, from the maintainer)

1. **Record everything relevant in two places.** When reading any material (a PDF, book, game, forum thread, blog or video) and a quote or feat for a character turns up, put it in that material's notes file **and** in the character's file here.
2. **Skip filler and irrelevant characters.** The roster (`_build/roster.py`) only lists characters that matter for scaling.
3. **Never invent anything.** That covers quotes, feats, page numbers, chapter numbers and links. Every entry is copied verbatim from a notes file on the box, and the Notes path points to that file and line. If a notes file gives no page, issue or speaker, the entry says so instead of guessing.
4. **Quotes go in full, verbatim, with their source.** A long quote is never cut down. Blockquotes and quoted passages are kept whole.
5. **Name the speaker for game quotes, and say who the line is about.** Example: `Speaker: Master Orgus Din, about the Hero of Tython - "..."`. The same applies to novel and comic dialogue when the speaker isn't obvious from the line. Narration is labelled `Narration (POV X)`. If our notes don't name the speaker of a game quote, the entry says `Speaker: [not given in our notes — see path:line]`, so it can be checked in the source.
6. **No duplicates within one file.** The same feat or quote appears once per character file. When it was found in several notes files, the extra sources are merged onto that one entry as `Also in:` lines. The longest and most complete version is kept, and a shorter copy that it fully contains is folded in.
   - Duplicates **across** files are expected and correct. The same quote should sit in the SI debate or material notes file **and** in the character's file, and in each character's file it concerns.
   - Material and debate notes files are never edited or trimmed by this process.
7. **Forum and respect-thread claims are recorded as cited.** A poster's argument, ranking or verdict is opinion, not a feat. Those go under "Debate arguments & forum opinion (not feats)", or under Verdicts as pointers.
8. **Feats are short plain lines plus their source.**
9. **Text only.** No embedded images. An image or panel is referred to by its path or URL only, e.g. `[panel: panels/...]`.
10. **Keep Legends and Canon separate.** An entry is filed as Canon when one of these applies:
    - the notes mark it Canon;
    - it comes from a Canon debate;
    - the character is Canon-only.
    Anything else goes under Legends. The version label, e.g. `[Legends · LotF (40–41 ABY)]` or `as debated: <side name>`, shows which version of a character an entry is about.
11. **Material from other agents' notes** (`external/mega-notes/` and the `notes/materials/021-023` imports) is marked `(via other Grok's notes)`. Secondhand reads never raise a character's research tier.
12. **Every quote from a secondary source gets a cropped image of the full quote from its page.** Secondary sources are sourcebooks, companions, guides and other reference books (e.g. the Tales of the Jedi Companion, the Legacy Era Campaign Guide). The crop shows the whole quote as printed, never a fragment; a quote that runs across columns is cropped per column and stacked. The image is embedded on the line directly under the quote, in the notes file and in every character file the quote lands in, as `![Quote image: <book>, p<N> — full quote as printed](<path>)`. If an existing panel already shows the full quote, that panel is reused instead of a new crop. Crops live next to the notes (`notes/materials/024-tales-of-the-jedi/quotes/`, `notes/materials/011-legacy-era-campaign-guide-panels/quotes/`). This is the one exception to rule 9. Quotes inside table rows, analysis or debate phrases, and quotes from other materials are not cropped.

## Tales of the Jedi: arcs not read yet

The 024 material covers 3 of the 7 Tales of the Jedi arcs: *The Freedon Nadd Uprising*, *Dark Lords of the Sith* and *The Sith War*, plus the WEG *Tales of the Jedi Companion*. Every feat from those three arcs now has a page or panel image. These arcs have **not** been read yet, and their feats and images will be added when their PDFs arrive:

- Knights of the Old Republic era stories (the Ulic Qel-Droma and Nomi Sunrider stories set before the Freedon Nadd Uprising)
- Ulic Qel-Droma and the Beast Wars of Onderon
- Golden Age of the Sith
- Fall of the Sith Empire
- Redemption

Until then, character files hold nothing from these arcs, so gaps there are not a finding.

## Jedi Academy trilogy (026)

All three Kevin J. Anderson novels (*Jedi Search*, *Dark Apprentice*, *Champions of the Force*) were read in full by us on 2026-10-27/28; notes are in `notes/materials/026-jedi-academy-trilogy/`. Entries are tagged `[Legends · Jedi Academy Trilogy: <book> (11 ABY)]`. Twenty roster entries were added for this cast: Admiral Daala, Gantoris, Streen, the Sun Crusher, Thrawn, Tarkin, Chewbacca, Ackbar, Anakin Solo, Dorsk 81, Furgan, Kirana Ti, Lando, Moruth Doole, Qwi Xux, Terpfen, Tionne, Tol Sivron, Vima-Da-Boda and Winter. Mentions of "baby Anakin" or "son, Anakin" are filed under Anakin Solo, not Darth Vader. MASTERY for this trilogy covers the 026 version only (see `legends-feats.md`).

## The New Essential Chronology (027)

All 249 scanned pages of *The New Essential Chronology* (Daniel Wallace, Del Rey, 2005) were read by us on 2026-10-28, including every art caption. Notes are in `notes/materials/027-new-essential-chronology/`. Entries are tagged `[Legends · The New Essential Chronology (Del Rey, 2005)]`, and each one has its quote crop. This is a **secondary source**: in-universe history narration, ranked below the novels and comics it summarises. 740 entries went into 112 existing character files. From p.160 on, a bare "Anakin" is filed under Anakin Solo, not Darth Vader. Jorus C'baoth (the Outbound Flight Master) is not filed under the clone Joruus.

## Jedi Academy Training Manual (028)

All 161 scanned pages of the Saga Edition *Jedi Academy Training Manual* (Rodney Thompson, Eric Cagle, Patrick Stutzman and Robert Wieland, Wizards of the Coast, 2009) were read by us on 2026-10-28, including every sidebar, caption and stat block. Notes are in `notes/materials/028-jedi-academy-training-manual/`. Entries are tagged `[Legends · Jedi Academy Training Manual (Saga Edition, 2009)]`, and each one has its quote crop. This is a **secondary source** (an RPG supplement summarising the novels and comics); stat-block entries are marked **RPG mechanics (weaker source)** and rank lowest. 187 entries went into 26 existing character files. "Anakin is nearly lost" (p.120) is filed under Anakin Solo, not Darth Vader, and the bare "Jax" beside Carnor Jax (p.117) is not filed under Jax Pavan.

## The Jedi Academy Sourcebook (029)

All 145 scanned pages of the West End Games d6 *The Jedi Academy Sourcebook* (1996) were read by us on 2026-10-28, including every sidebar, caption, fiction excerpt and stat block. Notes are in `notes/materials/029-jedi-academy-sourcebook/`. Entries are tagged `[Legends · The Jedi Academy Sourcebook (WEG, 1996)]`, and each one has its quote crop. This is a **secondary source** (an RPG supplement summarising the Jedi Academy Trilogy); stat-block entries are marked **RPG mechanics (weaker source)** and rank lowest. 353 entries went into 36 existing character files. Kun "posing as Anakin Skywalker" (p.49) and Furgan's plan for a "grandson or granddaughter of Darth Vader" (p.53) are not filed under Darth Vader; baby Anakin is filed under Anakin Solo. Brakiss does not appear in this book.

## The Complete Star Wars Encyclopedia, Vol. I (A–G) (030)

All 398 scanned pages of *The Complete Star Wars Encyclopedia*, Vol. I (A–G; Del Rey, 2008) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/030-complete-star-wars-encyclopedia-vol-1/`. Entries are tagged `[Legends · The Complete Star Wars Encyclopedia, Vol. I (2008)]`, and each one has its quote crop. This is a **secondary source**. 475 quotes naming 118 roster characters went into their character files. 

## The Complete Star Wars Encyclopedia, Vol. II (H–O) (031)

All 440 scanned pages of *The Complete Star Wars Encyclopedia*, Vol. II (H–O; Del Rey, 2008) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/031-complete-star-wars-encyclopedia-vol-2/`. Entries are tagged `[Legends · The Complete Star Wars Encyclopedia, Vol. II (2008)]`, and each one has its quote crop. This is a **secondary source**. 568 quotes naming 139 roster characters went into their character files. 

## The Complete Star Wars Encyclopedia, Vol. III (P–Z) (032)

All 385 scanned pages of *The Complete Star Wars Encyclopedia*, Vol. III (P–Z; Del Rey, 2008) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/032-complete-star-wars-encyclopedia-vol-3/`. Entries are tagged `[Legends · The Complete Star Wars Encyclopedia, Vol. III (2008)]`, and each one has its quote crop. This is a **secondary source**. 626 quotes naming 129 roster characters went into their character files. 

## Power of the Jedi Sourcebook (d20, 2002) (033)

All 163 scanned pages of *Power of the Jedi Sourcebook* (Wizards of the Coast, 2002) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/033-power-of-the-jedi-sourcebook/`. Entries are tagged `[Legends · Power of the Jedi Sourcebook (2002)]`, and each one has its quote crop. This is a **secondary source**. 103 quotes naming 48 roster characters went into their character files. 

## The New Essential Guide to Characters (2002) (034)

All 215 scanned pages of *Star Wars: The New Essential Guide to Characters* (Del Rey, 2002) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/034-new-essential-guide-to-characters/`. Entries are tagged `[Legends · The New Essential Guide to Characters (2002)]`, and each one has its quote crop. This is a **secondary source**. 205 quotes naming 57 roster characters went into their character files. 

## Dark Side Sourcebook (d20, 2001) (035)

All 161 scanned pages of *Star Wars Roleplaying Game: Dark Side Sourcebook* (Wizards of the Coast, 2001) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/035-dark-side-sourcebook/`. Entries are tagged `[Legends · Dark Side Sourcebook (2001)]`, and each one has its quote crop. This is a **secondary source**. 118 quotes naming 39 roster characters went into their character files. 

## Book of Sith: Secrets from the Dark Side (2012) (036)

All 162 scanned pages of *Book of Sith: Secrets from the Dark Side* (becker&mayer!/Chronicle, 2012) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/036-book-of-sith/`. Entries are tagged `[Legends · Book of Sith (2012)]`, and each one has its quote crop. This is a **secondary source**. 81 quotes naming 14 roster characters went into their character files. 

## Star Wars Insider #1–153 plus specials (with The Lucasfilm Fan Club Magazine #1–22) (038)

All 12592 scanned pages of *Star Wars Insider* (Lucasfilm Fan Club / Titan) issues 23–153 with The Lucasfilm Fan Club Magazine 1–22 and seven specials, from the Internet Archive item starwarsinsider_1_to_153_plus_specials (Image Container PDF of each issue) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/038-star-wars-insider/`. Entries are tagged `[Legends · Star Wars Insider]`, and each one has its quote crop. This is a **secondary source**. 406 quotes naming 85 roster characters went into their character files. 

## Star Wars D20 Drive folder (Core, Revised Core and Saga Edition) (037)

All 11616 scanned pages of the owner's "Star Wars D20" Drive folder (subfolders Star Wars - Roleplaying Game Core, Revised Core and Saga Edition; Wizards of the Coast, 2000–2010) were OCR'd and screened by us on 2026-10-28. Notes are in `notes/materials/037-sw-d20-folder/`. Entries are tagged `[Legends · Star Wars RPG d20 (WotC)]`, and each one has its quote crop. This is a **secondary source**. 5731 quotes naming 443 roster characters went into their character files. 

## How the files are built (so gaps are understood)

- Every source in PROGRESS.md is split into units: bullets, numbered items, table rows (with their header), blockquotes, record blocks (`[N] Type: …`) and paragraphs.
- A unit is filed under each character it names, using the roster aliases, or under the heading's character. It is capped at 6 characters, so lists that name many characters in passing aren't copied everywhere.
- Some blocks were left out on purpose: plot summaries, method and verification blocks, cast tables, image lists, game mechanics, changelogs, quote banks of non-power lines, and narration banks.
- Each entry's text is the notes line itself, copied unchanged. Section placement and the continuity tag are automatic, so an entry can land in a neighbouring section. Always open the Notes path for context.
- Aliases are case-sensitive, and ambiguous ones were dropped (e.g. "Savage", "Chosen One", "Supreme Chancellor"). Even so, a short alias can attach a stray line now and then. Report or fix these when found.
- To add new material: write its notes file as usual, add it to `run_all.py` if it lives in a new place, then run `python3 run_all.py && python3 render.py && python3 make_docs.py` in `_build/`.

## Respect threads (Suspect Insight directory)

- The directory list with every thread's status is in `suspect-insight/respect-threads/DIRECTORY.md`. Directory: https://www.suspectinsightforums.com/t4470-respect-thread-directory
- Every thread was saved raw, all pages, to `suspect-insight/respect-threads/raw/<nnn>-<name>.txt`. Each raw file's header gives the URL and the copy it was fetched from.
  - SI threads were fetched directly.
  - Comic Vine blocks the box with a 403, so its threads came from Wayback Machine snapshots. Four threads with no snapshot (Andeddu overview, Kopecz, Qordis, Skere Kaan) and Quinlan Vos page 2 came from a public reader view of the live page.
- Each thread also has a notes file, `suspect-insight/respect-threads/<character>.md`. It is the same text word for word, laid out as: claim bullet, then the quoted passage as `>` lines, then the named source.
- How thread content goes into character files:
  - Quoted passages that have a source go into the normal feat and quote sections. The entry reads `Source: <respect-thread notes file>:<line>`, and the book or comic named in the post is in the quote itself.
  - A poster's own claims that have no quoted evidence go under "Debate arguments & forum opinion (not feats)".

## Verification (`_build/verify.py`, last run 2026-10-28)

- 1578 character files, 141,763 entries (25,331 in Part 3). Every entry's text was found word-for-word in the notes file it points to (141,762 of 141,763).
- Within-file duplicates: 0. 14,780 duplicate copies were merged into `Also in:` source lines. Separator-only lines (`____`) from respect threads are dropped.
- Game entries: 3,347 have quotes. When the notes give the speaker inside the line (for example `HoT: «…»`), the entry says `Speaker: as labeled inside the line — X; about <character>`. When the notes don't name a speaker, the entry says `Speaker: [not given in our notes — see path:line]` and nothing is guessed. 42 game lines have no Speaker line because they are plot summaries whose only quote marks are scare quotes (for example an amnesiac "soldier"). They are not dialogue.
- PDFs: `pdf/` holds INDEX plus the 15 largest character files. Bundle: `characters.zip`.
