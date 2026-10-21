# Books Cited in the Bible but Not Included

A small, verse-referenced dataset of the **26 writings that the Hebrew Bible and the New Testament cite or mention but do not contain**. Examples are the Book of Jasher, the Book of the Wars of the LORD, the royal chronicles of Israel and Judah, the prophetic records named in Chronicles, the letter "from Laodicea" and the prophecy of Enoch quoted in Jude.

It is the data behind the article
**[Books Mentioned in the Bible but Not Included](https://ancientbiotech.com/books-mentioned-in-the-bible-but-not-included/)** on Ancient Biotechnology.

Maintained by **Ancient Biotechnology** (https://ancientbiotech.com · ancientbiotech@gmail.com).

## File

`lost-books.csv`: UTF-8, comma-separated, one header row, 26 data rows (23 Hebrew Bible, 3 New Testament).

| Column | Meaning |
|---|---|
| `id` | Short stable identifier |
| `title_english` | KJV or common English name |
| `title_hebrew_or_greek` | The phrase as it appears in the Hebrew (Masoretic) or Greek (SBLGNT) text |
| `citing_references` | Verse(s) that cite the work, semicolon-separated |
| `testament` | `Hebrew Bible` or `New Testament` |
| `what_the_text_says_it_contains` | What the citing verse says is in the work. Nothing beyond the verse is assumed |
| `surviving_status` | `lost`, `possibly identified` (with a surviving or canonical text) or `extant work with the same name but probably different` |
| `note` | Scholarly caveats and clarifications |

## Sources and verification

Every reference was fetched and read (October 2026) against at least two digital texts:

* **Hebrew Bible:** [Sefaria](https://www.sefaria.org/Joshua.10.13): *Miqra according to the Masorah* (Hebrew) and the JPS English translation, plus the **King James Version** (public domain, via bible-api.com) for the English titles.
* **New Testament:** the **SBL Greek New Testament** (MorphGNT edition on GitHub) and the **KJV**.

The Hebrew and Greek title phrases were copied from those texts. Dates and editions mentioned in the notes (later "Jasher" books, the Latin Laodiceans, 1 Enoch manuscripts) were checked against the relevant Wikipedia articles; they are context, not part of the core data.

## Scope and caveats

* **Only explicit citations of a written source are included.** Mentions of a source as a written record ("it is written in...") are counted. Verses that only allude to traditions are not.
* **Royal annals are listed once.** The *Chronicles of the Kings of Israel* and *of Judah* are cited many times in 1-2 Kings. Only the first occurrence of each is listed.
* **Some "books" may be the same source.** Scholars debate whether several of the titles in Chronicles are separate works. These include the books of Nathan, Gad, Iddo, Shemaiah and Jehu, and the "book of the kings". They may be sections of one larger history, or of the canonical books of Samuel and Kings. In particular, the *Book of the Kings of Judah and Israel* cited by Chronicles may simply be the canonical Kings.
* **Same name, different book.** The midrash Sefer haYashar (earliest surviving printing Venice 1625; English 1840), Jacob Ilive's 1751 "Book of Jasher", the Latin "Epistle to the Laodiceans" and the "Prayer of Manasseh" are generally regarded as later works and are not generally accepted as the sources the Bible cites.
* **Excluded:** the "book of the covenant" (Exodus 24:7) is usually identified with Exodus 20-23, so it is not a missing book.
* The dataset records what the texts say. It takes no position on inspiration or canon.

## Licence

The dataset (CSV and this README) is released under **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)**. The biblical verses themselves are public domain or are quoted as short references. The licence covers this compilation, its structure and its notes.

**Suggested citation:**
> Ancient Biotechnology (2026). *Books Cited in the Bible but Not Included* [Data set], version 1.0. https://ancientbiotech.com/books-mentioned-in-the-bible-but-not-included/

(Replace the URL with the Zenodo DOI once one has been minted.)

## Changelog

* **1.0 (Oct 2026):** First public version, with 26 entries.
