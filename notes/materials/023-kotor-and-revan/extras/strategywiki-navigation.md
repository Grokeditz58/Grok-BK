# StrategyWiki navigation guide: KOTOR 1 and KOTOR 2 (written Oct 19, 2026)

## Access
- Main pages: `https://strategywiki.org/wiki/Star_Wars:_Knights_of_the_Old_Republic` (K1) and `https://strategywiki.org/wiki/Star_Wars_Knights_of_the_Old_Republic_II:_The_Sith_Lords` (K2). Note that the K1 title has a colon after "Star Wars" and the K2 title does not.
- `index.php?...&action=raw` and the normal `/wiki/` pages are behind a Cloudflare "Just a moment..." challenge for curl. Don't use them.
- `https://strategywiki.org/w/api.php` works with any browser-like User-Agent:
  - List every subpage: `action=query&list=allpages&apprefix=<Main title>&aplimit=500&format=json`. This returned 308 titles, including 4 redirects.
  - Bulk wikitext: `action=query&prop=revisions&rvprop=content&rvslots=main&titles=A|B|...&formatversion=2&format=json`. Up to 40 titles per request worked.
- Subpages are `<Main title>/<Page>`, e.g. `Star Wars: Knights of the Old Republic/Viewing Platform`.

## Structure
- `/Table of Contents` drives the sidebar. It has three parts:
  - Gameplay: Controls, Character generation (Classes, Attributes, Skills, Feats), Items (weapon, armor and upgrade subpages), Experience, Party, Combat, Difficulty Classes, Saves, Alignment, Force powers. K2 adds Influence, Forms, Prestige classes, Autobalance, Achievements and Restored Content Mod.
  - Characters: one page per party member. K1: Bastila, Canderous, Carth, HK-47, Jolee Bindo, Juhani, Mission, T3-M4, Zaalbar. K2: Atton, Bao-Dur, Disciple, G0-T0, Handmaiden, Hanharr, HK-47, Kreia, Mandalore, Mira, T3-M4, Visas.
  - Walkthrough: grouped by planet. The planet hub page (e.g. `/Taris`, `/Korriban`, `/Malachor V`) links to area subpages (e.g. `/Tomb of Naga Sadow`, `/Trayus Core`).
- K1 walkthrough order: Endar Spire (Command Module, Starboard Section) → Taris (19 areas) → Dantooine (Enclave, Grove, Ruins) → Quest for the Star Forge: Tatooine, Kashyyyk, Manaan, Leviathan, Korriban, then Star Forge System (Rakatan beaches, Temple), Star Forge (Deck 1, Deck 2, Command Center, Viewing Platform). Yavin Station is optional.
- K2 walkthrough order: Prologue → Peragus II → Telos: Citadel Station (incl. Restoration Zone, Polar Plateau/Atris) → Nar Shaddaa / Dantooine / Dxun-Onderon / Korriban (any order) → Telos return → Ravager → Malachor V (Depths, Surface, Trayus Academy, Trayus Core). Character arcs live in the companion pages (e.g. `/Kreia`, `/Visas`) and in special pages like `/Lost Jedi`, `/Secret Tomb` and `/Rebuilt Jedi Enclave`.

## Wikitext conventions (important for quote extraction)
- Dialog: `{{KotOR/Dialog|<Speaker>||<text>}}` (party members) or `{{KotOR/Dialog||<Speaker>:|<text>}}` (NPCs). K2 uses `{{KotORII/Dialog|...}}`. Player choices are `{{...Dialog||1.|...}}`. Flags: `B=female/male` (gender variants), `C=n` (branch), `W=%` (influence).
- Boss stats: `{{KotORII/NPC|Name=...|Level=...|Vitality=...|Force=...|Defense=...}}` blocks with `{{KotORII/Power|...}}` lists. K1 stat blocks follow a different template; Malak's numbers are in the prose.
- Prose between the dialog tables describes cutscene actions, e.g. "Kreia drains them, and they collapse". These are the action feats.
- Gender-swapped duplicates exist for many lines (Revan or Exile "he/she"). Quote one and note the variant.

## Local copies
- `[local path]` holds the raw wikitext (308 files), and `raw/kotor/txt/` holds stripped text.
- `raw/kotor/dialog/ALL.tsv` holds every extracted dialog line as `page<TAB>speaker<TAB>text`: 25,840 lines. Its page tags K1/ and K2/ are the citations used in the notes.
- `raw/kotor/titles.txt` is the full page list.
