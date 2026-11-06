# Every Puzzle Project

**Finding, indexing and transcribing every crossword ever printed.**
Home: **[everypuzzleproject.org](https://everypuzzleproject.org)**

The first crossword appeared in 1913. Since then countless newspapers,
magazines and books have printed them, and most survive only on paper, or as
page scans you can look at but not search. We catalog the publications, index
every puzzle they ran, and transcribe each one into an
[xd](https://github.com/century-arcade/xdformat) file, linked to the scan it
was read from, so that it can be searched, studied and preserved. The finished
puzzles join the xd Crossword Corpus, a research archive of crosswords from
1913 to today.

This is a research archive, not a place to play old puzzles. Inspired by David
Steinberg's [Pre-Shortzian Puzzle Project](http://www.preshortzianpuzzleproject.com/).

## How a puzzle gets from a page to the corpus

1. **Find.** The [catalog](https://github.com/EveryPuzzleProject/catalog) lists
   every publication known to have printed a crossword: when it ran them, where
   copies survive, and how far we've got.
2. **Index.** One repo per publication (below) records which puzzles exist,
   which we have a copy of, and which pages are still wanted.
3. **Transcribe and check.** OCR built for this project reads each puzzle from
   its scan; volunteers and their Claude check every square and clue against the
   page on [Blitz](https://blitz.xwordapp.com/), the
   [review site](https://blitz.xwordapp.com/review/).
4. **The corpus.** Checked puzzles join the
   [xd Crossword Corpus](https://github.com/century-arcade/xdcorpus), browsed at
   [crosswordreference.com](https://crosswordreference.com).

## Publications

| Publication | Years | Status page |
|---|---|---|
| [Judge](https://github.com/EveryPuzzleProject/judge) | 1924–1939 | [everypuzzleproject.org/judge](https://everypuzzleproject.org/judge/) |
| [GAMES](https://github.com/EveryPuzzleProject/games) | 1977 on | [everypuzzleproject.org/games](https://everypuzzleproject.org/games/) |
| [The Boston Globe](https://github.com/EveryPuzzleProject/bostonglobe) | 1917 on | [everypuzzleproject.org/bostonglobe](https://everypuzzleproject.org/bostonglobe/) |
| [New York World](https://github.com/EveryPuzzleProject/newyorkworld) | 1913–1924 | [everypuzzleproject.org/newyorkworld](https://everypuzzleproject.org/newyorkworld/) |
| [Bell Syndicate](https://github.com/EveryPuzzleProject/bell) | 1924–1925 | [everypuzzleproject.org/bell](https://everypuzzleproject.org/bell/) |
| [The Daily Collegian](https://github.com/EveryPuzzleProject/collegian) | 1976–1981 | [everypuzzleproject.org/collegian](https://everypuzzleproject.org/collegian/) |

Each repo says what we have, what we still need, and how you can help. Live
counts for all of them are on the [home page](https://everypuzzleproject.org/#publications).

## How to help

- **Seen a crossword somewhere?** [Report a puzzle](https://github.com/EveryPuzzleProject/catalog/issues/new?template=report-puzzle.yml)
  or [report a publication](https://github.com/EveryPuzzleProject/catalog/issues/new?template=report-publication.yml).
  No technical skills needed.
- **Have a Claude account?** Direct your Claude to review puzzles against the
  scans: [blitz's How to help](https://github.com/EveryPuzzleProject/blitz#how-to-help)
  has the prompt to paste. Or point it at an open
  [lead](https://github.com/EveryPuzzleProject/catalog/issues?q=is%3Aopen+label%3Alead)
  in the catalog.
- **Have Newspapers.com or a library card?** Each status page lists the pages
  it still wants. Open an issue with the date and a clipping link (no page
  images, please; issues are public).
- **Rather check by hand?** The [review site](https://blitz.xwordapp.com/review/)
  shows each clue beside its scan. No account needed.
