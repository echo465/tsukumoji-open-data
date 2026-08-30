# ATTRIBUTION — data/edrdg-bysa/
**Version: v0.3.0 · Path: /home/claude/work/mojimori/data/edrdg-bysa/ · Filename: ATTRIBUTION.md**

## Source

The files in this directory are **adaptations (extracts)** of dictionary
files that are the property of the **Electronic Dictionary Research and
Development Group** (EDRDG), used in conformance with the Group's licence:

- Licence statement: https://www.edrdg.org/edrdg/licence.html — CC BY-SA 4.0
  (verbatim page text in `EDRDG-LICENCE.txt`, fetched by
  `tools/content/fetch-edrdg.py`)
- `kanjidic2-n5.json` — derived from **KANJIDIC2**: the 103 N5-level kanji's
  English meanings, on/kun readings, stroke counts, grade/JLPT/frequency
  fields.
- `jmdict-n5.json` — derived from **JMdict** (JMdict_e): the carrier words'
  verbatim English glosses, keyed by JMdict sequence number.

As adaptations of CC BY-SA 4.0 works, both JSON files are themselves
**CC BY-SA 4.0** and are destined for the studio's public BY-SA assets
repository alongside `data/kanjivg-bysa/`.

## Isolation rule

Everything in this directory is CC BY-SA 4.0. **Nothing outside this
directory may embed or copy its contents.** The game content DB
(`data/content/kanji-db.json`, `words.json`) references entries here only by
opaque `kd_<hex>` / `word_<seq>` ids; word glosses in `words.json` are
house-authored plain-English definitions written fresh, not copied JMdict
text.

## Shipped credit line (game About screen)

> This app uses the JMdict/EDICT and KANJIDIC dictionary files. These files
> are the property of the Electronic Dictionary Research and Development
> Group, and are used in conformance with the Group's licence
> (edrdg.org/edrdg/licence.html). Our N5 extracts are available under
> CC BY-SA 4.0 at https://github.com/echo465/tsukumoji-open-data.

---
*Kanagame content pipeline — ATTRIBUTION.md — v0.3.0 — end of file*
