# Warsh mushaf (riwayat Warsh 'an Nafi')

Files the Seventy-Times app downloads once when the reader picks Warsh.

| File | What it is |
|---|---|
| `index.json` | version, size and SHA-256 of every file |
| `warsh_pages.json.gz` | pages, lines and words; verse markers counted the Warsh way (6214 verses) |
| `warsh_fonts_1.zip` … `_7` | one font per page (`warsh2NNN.ttf`, 604 pages), 100 pages per zip |

Source: «المصحف الشريف برواية ورش للنشر الحاسوبي», King Fahd Glorious Quran Printing
Complex (KFGQPC). The page fonts are included exactly as published, unmodified, and are
distributed under KFGQPC's terms (free use, copying and distribution; no modification, no sale).

The file's own verse markers follow the Hafs count, so the app draws its own markers at the
Warsh verse ends instead, from a word-by-word alignment of the two riwayat
(`DailySeventy/tools/warsh/warsh_file.py`).
