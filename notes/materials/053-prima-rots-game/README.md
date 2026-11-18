# 053 · Prima Official Game Guide: *Star Wars Episode III: Revenge of the Sith* (game)

- **Status:** DONE, read in full on 2026-11-03.
- **Source:** MEGA handle dfsURbAS. The PDF has 127 pages and a text layer; PDF page = printed page + 1. The source file is not committed.
- **Bibliographic details:** Michael Knight; Prima Games / Random House, 2005; ISBN 0-7615-5164-6. The game was developed by The Collective and published by LucasArts for PS2 and Xbox.

## Files
- `rots-01.md`: front matter, Introduction, Anakin & Obi-Wan, Jedi Training, Allies & Enemies bios, and Missions 1–3. Appended to it are the notes for M3-end through M13 (pp. 32–65).
- `rots-02.md`: Missions 14–17, Bonus Missions 1–5, Multiplayer Duelists and Duel Arenas (pp. 66–97).
- `rots-03.md`: Challenge Missions, the Doe, Gillard and Lambros interviews, the Experience appendix, the Gallery (viewed as images), the Game Credits and the cover.

## Quote check
- 230 quote segments of 12+ characters were checked against the normalized text layer; 14 were flagged.
- Every flag was checked with grep:
  - Most are two-column interleaving or line-wrap artifacts in pdftotext. The words are contiguous in the printed column.
  - Three are cover or gallery labels read from page images, so they are not in the text layer.
