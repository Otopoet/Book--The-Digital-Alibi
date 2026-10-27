# The Digital Alibi

*Why Boards Are Legally Exposed by Every AI Decision They Cannot Reconstruct*
Dr Ivan Roche FRSS FRSA MInstP, Otopoetic Limited

LaTeX source for the manuscript, converted on 27 October 2026 from `Full_Manuscript_Repaired_V2` (build of 1 September 2026; wording identical to the project's `Full Manuscript Repaired.md`).

## Build (TeXstudio)

1. Open `main.tex`.
2. The first line sets the engine (`% !TeX program = xelatex`). Use Build and View (F5), or Tools > Commands > XeLaTeX.
3. Run twice (three times after structural edits) so the contents page and running heads settle.

Fonts: EB Garamond and DM Mono are used if installed; otherwise Latin Modern is used automatically. Nothing else needs changing.

## Layout

| Path | Contents |
|---|---|
| `main.tex` | Document skeleton and `\input` order |
| `preamble.tex` | Page size (6 x 9 in), brand colours, headings, tables, running heads |
| `frontmatter/` | Title page (placeholder), Foreword (placeholder, author to supply) |
| `chapters/ch01.tex` to `ch21.tex` | One file per chapter; `\part` commands sit at the head of chapters 1, 5, 11 and 16 |
| `backmatter/` | Epilogue and Appendices A to E |

Each chapter file starts with `% !TeX root = ../main.tex`, so it can be compiled from inside TeXstudio when edited.

## What was removed in conversion

The confidential book plan (commercial architecture, publisher targets, financial considerations), draft stamps, the 21 editorial-note panels dated April 2026, and one stray HTML tag. None of this is in the repository. Section headings are listed in the contents (Part, Chapter, Section).

See `OPEN_ITEMS.md` before submission.
