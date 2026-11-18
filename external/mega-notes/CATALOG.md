# CATALOG — MEGA shared folder "research" (external reference library)


## Source and download
- Shared root `KmgQhArJ` is a folder named **"Grok Notes"** (node `vighQRZT`). The link's subfolder `j2pVybKa` is named **`research`**, and that is what was fetched (not the root). Outside `research/` the root holds 33 more files (2 loose, the rest inside 1 folder), and none of them have keys (undecryptable).
- Remote size of `research/`: **9,663 files, 2.28 GB** (2,446,836,162 bytes). The quoted 9,696 files / 2.28 GB in 116 subfolders describes the whole root share: 9,696 files plus 117 folders, including the root itself.
- Downloaded 2026-10-21 about 3:07–3:14 PM CT with a small Python client for MEGA's public folder API (`[local path]`). megatools `megadl` was tried first. It found the folder but never wrote any data (its storage requests over plain HTTP hung), and it has no file-type filter, so I stopped it.
- No transfer-quota (509) errors. All 2,158 selected files came through intact, and each local size matches the MEGA size.

| Bucket | Files | Size |
|---|---|---|
| Downloaded (text/docs/data) | 2,158 | 380.6 MB |
| Skipped: images/media/pyc (paths in `SKIPPED-MEDIA.tsv`) | 2,509 | 1.8 GB |
| Undecryptable: no key in the share (see `UNDECRYPTABLE.tsv`) | 4,996 | 71.9 MB (941 are 0-byte) |

Files added next to the download: `CATALOG.md` (this file), `SKIPPED-MEDIA.tsv` (MEGA handle, size and original path of every skipped file, enough to re-fetch any of them), and `UNDECRYPTABLE.tsv`.

## Folder tree (counts and sizes are recursive; remote totals split by what happened to each file)
```
research/ | total 9663 files, 2.3 GB | text kept 2158 (380.6 MB) | images/media skipped 2509 (1.8 GB) | undecryptable 4996 (71.9 MB)
  _books-merge/ | total 5 files, 56.6 KB | text kept 5 (56.6 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  _extract/ | total 102 files, 2.6 MB | text kept 99 (2.5 MB) | images/media skipped 3 (48.6 KB) | undecryptable 0 (0 B)
    __pycache__/ | total 3 files, 48.6 KB | text kept 0 (0 B) | images/media skipped 3 (48.6 KB) | undecryptable 0 (0 B)
    duels/ | total 10 files, 262.2 KB | text kept 10 (262.2 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    read/ | total 14 files, 247.0 KB | text kept 14 (247.0 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    revan/ | total 31 files, 574.0 KB | text kept 31 (574.0 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    rots/ | total 24 files, 675.2 KB | text kept 24 (675.2 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    rots-parts/ | total 9 files, 178.4 KB | text kept 9 (178.4 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  _gapfix/ | total 46 files, 3.8 MB | text kept 43 (3.8 MB) | images/media skipped 3 (13.6 KB) | undecryptable 0 (0 B)
    __pycache__/ | total 3 files, 13.6 KB | text kept 0 (0 B) | images/media skipped 3 (13.6 KB) | undecryptable 0 (0 B)
    bak/ | total 6 files, 2.6 MB | text kept 6 (2.6 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    prof/ | total 4 files, 77.6 KB | text kept 4 (77.6 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  _revan-work/ | total 20 files, 5.5 MB | text kept 19 (5.5 MB) | images/media skipped 1 (3.5 KB) | undecryptable 0 (0 B)
    __pycache__/ | total 1 files, 3.5 KB | text kept 0 (0 B) | images/media skipped 1 (3.5 KB) | undecryptable 0 (0 B)
    parts/ | total 7 files, 98.6 KB | text kept 7 (98.6 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  batch2/ | total 7 files, 241.1 KB | text kept 7 (241.1 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  bdo-raw/ | total 69 files, 8.7 MB | text kept 69 (8.7 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  chargen/ | total 30 files, 211.0 KB | text kept 20 (132.0 KB) | images/media skipped 10 (79.1 KB) | undecryptable 0 (0 B)
    __pycache__/ | total 10 files, 79.1 KB | text kept 0 (0 B) | images/media skipped 10 (79.1 KB) | undecryptable 0 (0 B)
  extract/ | total 37 files, 1.5 MB | text kept 37 (1.5 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  forum-raw/ | total 339 files, 27.2 MB | text kept 339 (27.2 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    dooku/ | total 29 files, 2.5 MB | text kept 29 (2.5 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    exar-sion/ | total 51 files, 3.3 MB | text kept 51 (3.3 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    sw1019/ | total 136 files, 10.9 MB | text kept 136 (10.9 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  panels/ | total 6557 files, 1.9 GB | text kept 84 (19.3 MB) | images/media skipped 2175 (1.8 GB) | undecryptable 4298 (39.8 MB)
    _mp4/ | total 31 files, 6.5 MB | text kept 1 (4.1 KB) | images/media skipped 30 (6.5 MB) | undecryptable 0 (0 B)
    _raw/ | total 30 files, 7.6 MB | text kept 30 (7.6 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    _work/ | total 4296 files, 11.1 MB | text kept 51 (10.6 MB) | images/media skipped 1 (10.3 KB) | undecryptable 4244 (494.1 KB)
      <undecryptable:P2oxTDDD>/ | total 4244 files, 494.1 KB | text kept 0 (0 B) | images/media skipped 0 (0 B) | undecryptable 4244 (494.1 KB)
      __pycache__/ | total 1 files, 10.3 KB | text kept 0 (0 B) | images/media skipped 1 (10.3 KB) | undecryptable 0 (0 B)
      rd/ | total 14 files, 784 B | text kept 14 (784 B) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    abeloth/ | total 13 files, 1.2 MB | text kept 0 (0 B) | images/media skipped 13 (1.2 MB) | undecryptable 0 (0 B)
    dooku/ | total 135 files, 209.5 MB | text kept 0 (0 B) | images/media skipped 135 (209.5 MB) | undecryptable 0 (0 B)
    exar-kun/ | total 129 files, 91.0 MB | text kept 0 (0 B) | images/media skipped 129 (91.0 MB) | undecryptable 0 (0 B)
    karness-muur/ | total 3 files, 1.4 MB | text kept 0 (0 B) | images/media skipped 3 (1.4 MB) | undecryptable 0 (0 B)
    krayt/ | total 129 files, 50.0 MB | text kept 0 (0 B) | images/media skipped 129 (50.0 MB) | undecryptable 0 (0 B)
    kreia/ | total 55 files, 42.8 MB | text kept 0 (0 B) | images/media skipped 55 (42.8 MB) | undecryptable 0 (0 B)
    luke/ | total 2 files, 876.6 KB | text kept 0 (0 B) | images/media skipped 2 (876.6 KB) | undecryptable 0 (0 B)
    mace/ | total 95 files, 67.0 MB | text kept 0 (0 B) | images/media skipped 95 (67.0 MB) | undecryptable 0 (0 B)
    malgus/ | total 9 files, 6.3 MB | text kept 0 (0 B) | images/media skipped 9 (6.3 MB) | undecryptable 0 (0 B)
    maul/ | total 62 files, 29.1 MB | text kept 0 (0 B) | images/media skipped 62 (29.1 MB) | undecryptable 0 (0 B)
    meetra/ | total 18 files, 18.6 MB | text kept 0 (0 B) | images/media skipped 18 (18.6 MB) | undecryptable 0 (0 B)
    obi-wan/ | total 1 files, 19.7 KB | text kept 0 (0 B) | images/media skipped 1 (19.7 KB) | undecryptable 0 (0 B)
    plagueis/ | total 4 files, 350.0 KB | text kept 0 (0 B) | images/media skipped 4 (350.0 KB) | undecryptable 0 (0 B)
    revan/ | total 53 files, 8.5 MB | text kept 0 (0 B) | images/media skipped 53 (8.5 MB) | undecryptable 0 (0 B)
    sidious/ | total 220 files, 327.3 MB | text kept 0 (0 B) | images/media skipped 166 (288.0 MB) | undecryptable 54 (39.3 MB)
    sion/ | total 25 files, 27.1 MB | text kept 0 (0 B) | images/media skipped 25 (27.1 MB) | undecryptable 0 (0 B)
    vader/ | total 180 files, 133.7 MB | text kept 0 (0 B) | images/media skipped 180 (133.7 MB) | undecryptable 0 (0 B)
    vitiate/ | total 162 files, 549.8 MB | text kept 0 (0 B) | images/media skipped 162 (549.8 MB) | undecryptable 0 (0 B)
    yoda/ | total 35 files, 50.7 MB | text kept 0 (0 B) | images/media skipped 35 (50.7 MB) | undecryptable 0 (0 B)
  raw/ | total 1136 files, 69.3 MB | text kept 439 (37.4 MB) | images/media skipped 0 (0 B) | undecryptable 697 (31.9 MB)
    <undecryptable:P3gXTBhT>/ | total 697 files, 31.9 MB | text kept 0 (0 B) | images/media skipped 0 (0 B) | undecryptable 697 (31.9 MB)
      ci/ | total 144 files, 741.3 KB | text kept 144 (741.3 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
      hk/ | total 117 files, 103.8 KB | text kept 117 (103.8 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
      ic/ | total 103 files, 531.6 KB | text kept 103 (531.6 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    rt/ | total 6 files, 16.9 KB | text kept 6 (16.9 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  shift-drafts/ | total 2 files, 3.5 KB | text kept 2 (3.5 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    field/ | total 193 files, 75.9 MB | text kept 193 (75.9 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    mvr/ | total 17 files, 511.2 KB | text kept 17 (511.2 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    sm19/ | total 126 files, 90.9 MB | text kept 126 (90.9 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    understat/ | total 68 files, 24.0 MB | text kept 68 (24.0 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
      2026-10-18/ | total 15 files, 4.2 MB | text kept 15 (4.2 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
      2026-10-19/ | total 35 files, 12.8 MB | text kept 35 (12.8 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  sports-raw/ | total 13 files, 7.6 MB | text kept 13 (7.6 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    2026-10-19/ | total 13 files, 7.6 MB | text kept 13 (7.6 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  src/ | total 372 files, 31.5 MB | text kept 55 (1.8 MB) | images/media skipped 317 (29.7 MB) | undecryptable 0 (0 B)
    ca/ | total 333 files, 30.6 MB | text kept 16 (859.7 KB) | images/media skipped 317 (29.7 MB) | undecryptable 0 (0 B)
      img/ | total 317 files, 29.7 MB | text kept 0 (0 B) | images/media skipped 317 (29.7 MB) | undecryptable 0 (0 B)
        secret-wars-1/ | total 32 files, 2.6 MB | text kept 0 (0 B) | images/media skipped 32 (2.6 MB) | undecryptable 0 (0 B)
        secret-wars-10/ | total 34 files, 3.5 MB | text kept 0 (0 B) | images/media skipped 34 (3.5 MB) | undecryptable 0 (0 B)
        secret-wars-11/ | total 39 files, 3.5 MB | text kept 0 (0 B) | images/media skipped 39 (3.5 MB) | undecryptable 0 (0 B)
        secret-wars-12/ | total 68 files, 6.7 MB | text kept 0 (0 B) | images/media skipped 68 (6.7 MB) | undecryptable 0 (0 B)
        secret-wars-2-3/ | total 29 files, 2.9 MB | text kept 0 (0 B) | images/media skipped 29 (2.9 MB) | undecryptable 0 (0 B)
        secret-wars-4-5/ | total 45 files, 4.2 MB | text kept 0 (0 B) | images/media skipped 45 (4.2 MB) | undecryptable 0 (0 B)
        secret-wars-6-7-8/ | total 39 files, 3.8 MB | text kept 0 (0 B) | images/media skipped 39 (3.8 MB) | undecryptable 0 (0 B)
        secret-wars-9/ | total 31 files, 2.6 MB | text kept 0 (0 B) | images/media skipped 31 (2.6 MB) | undecryptable 0 (0 B)
  tm/ | total 113 files, 1.7 MB | text kept 113 (1.7 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  tmp_story/ | total 14 files, 1.2 MB | text kept 14 (1.2 MB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  work-labyrinth/ | total 13 files, 554.7 KB | text kept 13 (554.7 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
    parts/ | total 10 files, 518.1 KB | text kept 10 (518.1 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
  work-plag-lab/ | total 22 files, 658.7 KB | text kept 22 (658.7 KB) | images/media skipped 0 (0 B) | undecryptable 0 (0 B)
```
6 folders inside `panels/_work/` and `raw/` have no key in the share, so their names and contents can't be read. `panels/_work/<P2oxTDDD>` holds 4,244 tiny files (494 KB, probably OCR or thumbnail output) and `raw/<P3gXTBhT>` holds 697 files (31.9 MB). Another 54 files in `panels/sidious/` (39.3 MB) also have no key.

## File types (downloaded)
| Type | Files | Size | Notes |
|---|---|---|---|
| .txt | 586 | 20.4 MB | quote extractions, forum thread text, chapter splits, Transfermarkt text |
| .wiki / .wikitext / .wt | 399 | 5.7 MB | MediaWiki source (Invincible issue synopses, Wookieepedia) |
| .md | 153 | 18.7 MB | the actual research notes |
| .bak* / .pre-* | 78 | 10.5 MB | older versions of the notes |
| .py / .sh | 92 | 0.3 MB | scraper and build scripts (not run) |
| .err / .log / .tsv | 65 | 0.7 MB | 53 `.err` files are empty |

Skipped types: jpg 1,519 (294.9 MB), png 629 (387.2 MB), gif 313 (1.2 GB), mp4 30 (6.5 MB), pyc 18 (155 KB).

## What the content is
This is another research agent's full working directory, not a curated set of notes. It is mostly Star Wars Legends power-scaling, plus a lot of unrelated material.

**Star Wars (the core), all top level unless a path is given:**
- **Novels read in full, with line-cited feats and quotes:** *Darth Plagueis* (`darth-plagueis-notes.md`, 475 KB), *Dark Lord: The Rise of Darth Vader* (`dark-lord-novel-feats.md`), *The Old Republic: Deceived* (`deceived-novel-feats.md`), *The Old Republic: Revan* (`revan-novel-notes.md`, 1.1 MB), *Labyrinth of Evil* (`labyrinth-of-evil-notes.md`, 708 KB), the Stover *Revenge of the Sith* novelization (`rots-novel-notes.md`, 952 KB), *Legacy of the Force* 1–9 (`lotf-1-betrayal` … `lotf-9-invincible-notes.md`), *The Force Unleashed* I and II (`tfu-1/2-notes.md`).
- **Games:** *KOTOR* I and II plot, feat and character notes (`kotor-1/2-notes.md`, `kotor-1/2-characters.md`) built from StrategyWiki transcripts. `chargen/` holds the scripts that built them.
- **Per-character Wookieepedia quote/feat extracts** (`*-legends-quotes.txt`, `*-quotes.txt`): Abeloth, Agen Kolar, Ahsoka, Andeddu, Angral, Bane, Cade, Caedus, Dooku, Exar Kun, Freedon Nadd, Galen Marek, Grievous, Jaina, Kit Fisto, Krayt, Kyle Katarn, Ludo Kressh, Luke, Mace, Malgus, Mara Jade, Marka Ragnos, Maul, Meetra Surik, Naga Sadow, Nihilus, Obi-Wan, Plagueis, Qui-Gon, Saesee Tiin, Shaak Ti, Sidious, Sion, the Father, the Son, the Daughter (Mortis), Tulak Hord, Ulic Qel-Droma, Vader, Ventress, Vitiate, Wyyrlok, Yoda, Zannah.
- **Comic Vine respect-thread extracts** (`*-comicvine-respect*.txt`, `kreia-respect-quotes.txt`, `malgus-respect-1557966.txt`): Dooku, Exar Kun, Krayt, Kreia/Traya, Luke, Mace, Malak, Malgus, Maul, Meetra, Nihilus, Plagueis, Revan, Sidious, Sion, Vader (parts 1–3), Vitiate (parts 1–2), Yoda.
- **Forum-debate digests** (`debates-*.md`, about 25 files): Suspect Insight and Comic Vine threads. Examples are Sidious vs Vitiate/Tenebrae/Valkorion (SI t20, 10 pages), Revan vs Krayt, Revan vs Malgus, Vader vs Malgus, Vader vs Revan, Yoda/Mace vs Sidious, Traya vs Sidious, Muur vs Bane, Malak vs Exile, Abeloth vs Sidious/Tenebrae, and "SI vs debating 2022". The raw thread scrapes are in `forum-raw/`.
- **Synthesis files:** this agent's own `legends-feats.md`. It is a different file from ours (84 KB vs our 237 KB), and it also contains instructions written for that agent. Also `verdicts.md` (194 KB of head-to-heads and tiers, with confidence levels), `verdicts-draft-*.md` and `verdict-changes-*.txt`.
- **`panels/panels-index.md`:** an index of 2,461 saved panels and GIFs by character, with captions and sources. The images themselves were not downloaded. Star Wars characters: Sidious 220, Vader 180, Vitiate 162, Dooku 135, Exar Kun 129, Krayt 129, Mace 95, Maul 62, Kreia 55, Revan 53, Yoda 35, Sion 25, Meetra 18, Abeloth 13, Malgus 9, Plagueis 4, Karness Muur 3, Luke 2, Obi-Wan 1.

**Not Star Wars (about 70% of the downloaded bytes):**

## Coverage gaps this fills (compared with our notes/INDEX.md and research/legends-feats.md)
- **Primary-source novels.** Our files cite these only second-hand, through debaters' quotes. Here they are read in full: *Darth Plagueis*, *Dark Lord*, *Deceived*, *Revan*, *Labyrinth of Evil*, the *ROTS* novelization, all nine *LotF* books, *TFU* I and II. *Labyrinth of Evil* and the Stover name don't appear in our files at all.
- **Games:** KOTOR I and II walkthrough-based notes. Our notes have no game notes.
- **Comic Vine respect threads:** 18 characters. Our feats file never cites Comic Vine.
- **Characters with no section in our legends-feats.md who appear in our debates (INDEX):** Darth Sion, Grievous, Ahsoka Tano, Kit Fisto, Saesee Tiin, Freedon Nadd, Tulak Hord.
- **Characters in neither of our files, or only mentioned in passing:** Abeloth, Darth Nihilus, Kreia (we have Darth Traya only), Andeddu, Ludo Kressh, Agen Kolar, and the Mortis gods (Father, Son, Daughter).
- **Thin in ours, deep here:** Sidious, Vitiate/Tenebrae, Dooku, Mace Windu, Exar Kun, Meetra Surik, Malak, Maul, Vader (novel and respect-thread depth). Panel indexes for Star Wars characters beyond the Legacy comics in our materials 009–013.
- **Forum threads our 128 debates don't cover:** SI t20 (Sidious vs Vitiate), plus the Sion, Exar Kun and Dooku thread sets.

## Notes that reference the skipped images (matched by filename)
2,491 of the 2,509 skipped files are named in at least one downloaded file. To re-fetch any of them, use the handle in `SKIPPED-MEDIA.tsv`. Count = number of distinct skipped images each file names:

- `panels/_work/rows.json`: 2461
- `panels/_work/rows_linked.json`: 2461
- `panels/panels-index.md`: 2461
- `invincible-notes.md`: 472
- `secret-wars-1984-notes.md`: 396
- `panels/_work/ocr_ca.txt`: 317
- `panels/_work/ocr_list.txt`: 317
- `panels/_work/recs.json`: 317
- `sidious-comicvine-respect.txt`: 151
- `dooku-comicvine-respect.txt`: 135
- `vader-comicvine-respect-part3.txt`: 123
- `exar-kun-comicvine-respect.txt`: 117
- `krayt-comicvine-respect.txt`: 113
- `mace-comicvine-respect.txt`: 95
- `vitiate-comicvine-respect-part2.txt`: 93
- `debates-revan-vs-krayt-ss.md`: 72
- `src/ca/secret-wars-12.html`: 68
- `src/ca/secret-wars-12.txt`: 68
- `maul-comicvine-respect.txt`: 60
- `panels/_mp4/index.txt`: 60
- `kreia-respect-quotes.txt`: 52
- `vitiate-comicvine-respect-part1.txt`: 48
- `src/ca/secret-wars-4-5.html`: 47
- `src/ca/secret-wars-4-5.txt`: 47
- `vader-comicvine-respect-part2.txt`: 47
- `src/ca/secret-wars-10.html`: 41
- `src/ca/secret-wars-10.txt`: 41
- `src/ca/secret-wars-6-7-8.html`: 40
- `src/ca/secret-wars-6-7-8.txt`: 40
- `src/ca/secret-wars-1.html`: 39
- `src/ca/secret-wars-1.txt`: 39
- `src/ca/secret-wars-11.html`: 39
- `src/ca/secret-wars-11.txt`: 39
- `src/ca11.html`: 39
- `src/ca/secret-wars-9.html`: 32
- `src/ca/secret-wars-9.txt`: 32
- `src/ca/secret-wars-2-3.html`: 29
- `src/ca/secret-wars-2-3.txt`: 29
- `yoda-comicvine-respect.txt`: 28
- `sion-comicvine-respect.txt`: 23
- `meetra-comicvine-respect.txt`: 18
- `debates-exar-kun.md`: 16
- `revan-comicvine-respect.txt`: 13
- `debates-sidious-vs-vitiate.md`: 12
- `debates-yoda-mace-sidious.md`: 11
- `debates-vader-vs-malgus.md`: 10
- `debates-traya-vs-sidious.md`: 8
- `malgus-respect-1557966.txt`: 7
- `debates-muur-vs-bane.md`: 5
- `debates-revan-vs-malgus.md`: 4
- `debates-sion.md`: 4
- `plagueis-comicvine-respect.txt`: 3
- `debates-sidious-plagueis-tenebrous-vs-krayt-caedus-valkorion.md`: 2
- `debates-vader-vs-revan.md`: 2
- `luke-comicvine-respect.txt`: 2
- `debates-de-sidious-vitiate-nihilus-vs-amped-team.md`: 1
- `debates-maul.md`: 1

Matching is by file name, so a few generic names could be false matches. `.bak*` copies are not listed separately.

## Problems
- 4,996 of 9,663 files (941 of them empty) and 6 folders have no decryption key in the public share (`UNDECRYPTABLE.tsv`). They can't be fetched through this link. The owner would need to re-share them, or share from the account that uploaded them.
- megatools `megadl` didn't work here (its storage downloads over plain HTTP hung, and it has no type filter). I used a direct client over HTTPS instead.
- Notes cite source texts that weren't shared.
