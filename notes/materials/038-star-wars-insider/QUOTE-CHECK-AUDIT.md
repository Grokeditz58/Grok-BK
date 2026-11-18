# Star Wars Insider — quote image-check audit

Generated 2026-11-03 (CST). Count-only audit: no quotes were re-checked.

Scope: all 160 issues in PAGEREAD.md. Quote count = records with `"t": "q"` in `issues/<key>/hand/<key>.jsonl`. Evidence = the issue's PAGEREAD.md Notes cell (and the matching `read` notes in the jsonl) plus every STATUS.md entry naming the issue.

Rules:
- **yes** — a note explicitly says the issue's quotes (Q, T/Q, or all quotes) were checked against page images or crops (e.g. "crop-verified T/Q", "T/Q verified on crops", "Q checked against page image", "all image-checked", "none left unverified"). For ins044-ins053 the per-range PAGEREAD notes were matched against each quote's page.
- **unclear** — some image/crop work is recorded, but it does not clearly cover all the quotes (e.g. only T lines/captions verified, "every page image-checked" without naming Q, quotes "with crops" but no check stated, or only some quotes fixed against images).
- **no** — no image or crop check of any kind is recorded for the issue.
- T lines are `stat` records, not `q` records, so "T verified on crops" alone does not count as a quote check.

## Totals

| Status | Issues | Issues with ≥1 Q | Quotes |
|---|---|---|---|
| yes | 53 | 52 | 1483 |
| no | 50 | 36 | 191 |
| unclear | 57 | 24 | 212 |
| **all** | 160 | 112 | 1886 |

Quotes not confirmed image-checked (no + unclear): 403 of 1886.

- **no** issues with quotes: ins036 (1), ins038 (1), ins110 (13), ins111 (7), ins112 (18), ins113 (7), ins114 (9), ins115 (11), ins116 (6), ins117 (4), ins118 (5), ins119 (8), ins120 (6), ins121 (3), ins122 (5), ins123 (4), ins125 (5), ins126 (4), ins127 (9), ins128 (2), ins129 (2), ins130 (4), ins131 (2), ins132 (9), ins133 (1), ins134 (4), ins136 (3), ins137 (4), ins138 (4), ins139 (3), ins140 (2), ins141 (3), ins142 (1), ins143 (4), ins144 (7), ins145 (10)
- **unclear** issues with quotes: ins023 (1), ins026 (1), ins027 (1), ins028 (4), ins042 (2), ins044 (3), ins054 (6), ins055 (27), ins056 (28), ins057 (44), ins058 (14), ins062 (21), ins063 (18), ins064 (2), ins065 (2), ins066 (4), ins067 (6), ins070 (5), ins071 (8), ins124 (1), ins146 (5), ins147 (6), ins148 (1), ins149 (2)

## Per issue

| Issue | Q in hand jsonl | Image-checked | Evidence |
|---|---|---|---|
| ins023 | 1 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins024 | 0 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins025 | 0 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins026 | 1 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins027 | 1 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins028 | 4 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins029 | 0 | unclear | "every page image-checked" (four-page sheets plus crops) and "verified T lines"; Q not named |
| ins030 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins031 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins032 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins033 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins034 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins035 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins036 | 1 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins037 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins038 | 1 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins039 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins040 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins041 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins042 | 2 | unclear | only Prequel Update captions crop-verified; Q not named |
| ins043 | 0 | no | no image/crop check recorded in PAGEREAD or STATUS (STATUS lists T lines only) |
| ins044 | 3 | unclear | PAGEREAD: quotes checked against page images for pp. 21-30, 38-64; p17 quote falls in pp. 1-20 ("page images for captions") - 2 of 3 explicit |
| ins045 | 14 | yes | PAGEREAD: "Q checked against page image(s)" for every page range holding a quote |
| ins046 | 6 | yes | PAGEREAD: "Q checked against page image(s)" for every page range holding a quote |
| ins047 | 10 | yes | PAGEREAD: "Q checked against page image(s)" for every page range holding a quote |
| ins048 | 12 | yes | PAGEREAD: "Q checked against page image(s)" for every page range holding a quote |
| ins049 | 18 | yes | PAGEREAD: "Q checked against page image(s)" for every page range holding a quote |
| ins050 | 19 | yes | STATUS: "N Q crop-verified"; PAGEREAD: Q checked against page image in every range |
| ins051 | 12 | yes | STATUS: "N Q crop-verified"; PAGEREAD: Q checked against page image in every range |
| ins052 | 14 | yes | STATUS: "Q, all image-checked"; PAGEREAD: Q checked against page image in every range holding a quote |
| ins053 | 23 | yes | STATUS: "Q, all image-checked"; PAGEREAD: Q checked against page image in every range holding a quote |
| ins054 | 6 | unclear | STATUS: "4 Q creator quotes with crop ok" but jsonl has 6 Q; PAGEREAD: "Q ... with crops" |
| ins055 | 27 | unclear | "Q creator/actor quotes with crops" (crops made; check not stated); only T "verified on crops" |
| ins056 | 28 | unclear | "Q creator/actor quotes with full-quote crops" (crops made; check not stated); only T "verified on crops" |
| ins057 | 44 | unclear | "Q creator/actor quotes with full-quote crops" (crops made; check not stated); only T "verified on crops" |
| ins058 | 14 | unclear | "Q creator/actor quotes with full-quote crops" (crops made; check not stated); only T "verified on crops" |
| ins059 | 31 | yes | PAGEREAD: "phase 1 redo with re-OCR, crops verified"; STATUS auto-quote fix pass: re-read against page images, "none left unverified" |
| ins060 | 80 | yes | PAGEREAD: "phase 1 redo with re-OCR, crops verified"; STATUS auto-quote fix pass: re-read against page images, "none left unverified" |
| ins061 | 33 | yes | PAGEREAD: "all 100 scan pages read from page images; verbatim quotes and boxed sidebars checked on crops" |
| ins062 | 21 | unclear | "17 auto-quotes fixed verbatim against page images"; other Q only "with full-quote crops" (21 Q in jsonl) |
| ins063 | 18 | unclear | "4 auto-quotes fixed or verified verbatim against page images"; T verified on crops; other Q not stated (18 Q) |
| ins064 | 2 | unclear | STATUS: "T for ... verified on crops"; Q listed separately with no check stated (some quotes "rewritten verbatim") |
| ins065 | 2 | unclear | STATUS: "T for ... verified on crops"; Q listed separately with no check stated (some quotes "rewritten verbatim") |
| ins066 | 4 | unclear | STATUS: "T for ... verified on crops"; Q listed separately with no check stated (some quotes "rewritten verbatim") |
| ins067 | 6 | unclear | STATUS: "T for ... verified on crops"; Q listed separately with no check stated (some quotes "rewritten verbatim") |
| ins068 | 3 | yes | STATUS: "T/Q ... verified on crops" |
| ins069 | 1 | yes | STATUS: "T/Q ... verified on crops" |
| ins070 | 5 | unclear | STATUS: "T for ... verified on crops"; Q listed separately with no check stated (some quotes "rewritten verbatim") |
| ins071 | 8 | unclear | STATUS: "T for ... verified on crops"; Q listed separately with no check stated (some quotes "rewritten verbatim"); 6 missing quote crops re-boxed and checked against page images (6 of 8) |
| ins072 | 16 | yes | STATUS: "T/Q ... verified on crops" |
| ins073 | 12 | yes | STATUS: "T/Q ... verified on crops" |
| ins074 | 32 | yes | STATUS: "T/Q ... verified on crops" |
| ins075 | 19 | yes | STATUS: "T/Q ... verified on crops" |
| ins076 | 14 | yes | STATUS: "T/Q ... verified on crops" |
| ins077 | 26 | yes | STATUS: "T/Q ... verified on crops" |
| ins078 | 22 | yes | STATUS: "T/Q ... verified on crops" |
| ins079 | 32 | yes | STATUS: "T/Q ... verified on crops" |
| ins080 | 25 | yes | STATUS: "T/Q ... verified on crops" |
| ins081 | 33 | yes | STATUS: "T/Q ... verified on crops" |
| ins082 | 29 | yes | STATUS: "T/Q ... verified on crops" |
| ins083 | 9 | yes | STATUS: "T/Q ... verified on crops" |
| ins084 | 7 | yes | STATUS: "T/Q ... verified on crops" |
| ins085 | 8 | yes | STATUS: "T/Q ... verified on crops" |
| ins086 | 3 | yes | STATUS: "T/Q ... verified on crops" |
| ins087 | 4 | yes | STATUS: "T/Q ... verified on crops" |
| ins088 | 10 | yes | STATUS: "T/Q ... verified on crops" |
| ins089 | 8 | yes | STATUS: "T/Q ... verified on crops" |
| ins090 | 15 | yes | STATUS: "crop-verified T/Q" |
| ins091 | 23 | yes | STATUS: "crop-verified T/Q" |
| ins092 | 16 | yes | STATUS: "crop-verified T/Q" |
| ins093 | 25 | yes | STATUS: "crop-verified T/Q" |
| ins094 | 150 | yes | STATUS: "crop-verified T/Q" |
| ins095 | 64 | yes | STATUS: "crop-verified T/Q" |
| ins096 | 50 | yes | STATUS: "crop-verified T/Q" |
| ins097 | 76 | yes | STATUS: "crop-verified T/Q" |
| ins098 | 121 | yes | STATUS: "crop-verified T/Q" |
| ins099 | 90 | yes | STATUS: "crop-verified T/Q" |
| ins100 | 26 | yes | STATUS: "crop-verified T/Q" |
| ins101 | 71 | yes | STATUS: "crop-verified T/Q" |
| ins102 | 81 | yes | STATUS: "crop-verified T/Q" |
| ins103 | 35 | yes | STATUS: "crop-verified T/Q" |
| ins104 | 20 | yes | STATUS: "crop-verified T/Q" |
| ins105 | 8 | yes | STATUS: "crop-verified T/Q" |
| ins106 | 12 | yes | STATUS: "crop-verified T/Q" |
| ins107 | 3 | yes | STATUS: "crop-verified T/Q" |
| ins108 | 6 | yes | STATUS: "crop-verified T/Q" |
| ins109 | 6 | yes | STATUS: "crop-verified T/Q" |
| ins110 | 13 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins111 | 7 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins112 | 18 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins113 | 7 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins114 | 9 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins115 | 11 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins116 | 6 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins117 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins118 | 5 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins119 | 8 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins120 | 6 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins121 | 3 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins122 | 5 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins123 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins124 | 1 | unclear | only "OCR-failed pages read from images" (Marshall interview); no quote check recorded |
| ins125 | 5 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins126 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins127 | 9 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins128 | 2 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins129 | 2 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins130 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins131 | 2 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins132 | 9 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins133 | 1 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins134 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins135 | 0 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins136 | 3 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins137 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins138 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins139 | 3 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins140 | 2 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins141 | 3 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins142 | 1 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins143 | 4 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins144 | 7 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins145 | 10 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| ins146 | 5 | unclear | only T lines / Rogues Gallery bios crop-verified; Q not named |
| ins147 | 6 | unclear | only T lines / Rogues Gallery bios crop-verified; Q not named |
| ins148 | 1 | unclear | only T lines / Rogues Gallery bios crop-verified; Q not named |
| ins149 | 2 | unclear | only T lines / Rogues Gallery bios crop-verified; Q not named |
| ins150 | 0 | unclear | only T lines / dates crop-verified; 0 Q |
| ins151 | 0 | unclear | only T lines / dates crop-verified; 0 Q |
| ins152 | 0 | unclear | only T lines / dates crop-verified; 0 Q |
| ins153 | 0 | no | STATUS entry is a content summary; no image/crop check recorded for quotes |
| insbestbuy2004 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| inssampler2010 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| inssampler2011 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| insspecial2010 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| insspecial2012 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| insspecial2013 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| insspecial2014 | 0 | unclear | "T lines, crop-checked against page images"; 0 Q |
| lfc001 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc002 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc003 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc004 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc005 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc006 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc007 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc008 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc009 | 0 | no | no image/crop check recorded; 0 Q |
| lfc010 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc011 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc012 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc013 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc014 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc015 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc016 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc017 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc018 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc019 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc020 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc021 | 0 | unclear | some pages/crops viewed or crop-verified; 0 Q |
| lfc022 | 0 | yes | "all T quotes were crop-verified"; 0 Q |
