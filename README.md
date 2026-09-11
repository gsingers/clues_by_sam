# Clues by Sam Field Manual

A reference for [Clues by Sam](https://cluesbysam.com/), the daily logic puzzle on a 4 × 5 grid
of twenty suspects. It collects the rules, techniques and note-taking notation that recur across
boards, aimed at the harder days where the difficulty is in how clues interact rather than in
reading any one of them.

**Read it here: https://gsingers.github.io/clues_by_sam/**

## What's in it

- **Basics** — the exact in-game meanings of *neighbors*, *connected*, *directly above*, *edges*,
  *in between*, *all* vs *any*, and the parity clues; board geometry and neighbor counts by position.
- **Advanced** — connectivity rules and connector cost; the three-bank tagging system, with links,
  groups, comparatives and branch-independent pairs; a set- and graph-theory notation for keeping
  a paper ledger alongside the app; and the procedure to run when a board stalls.
- **Worked example** — the daily of 9 September 2026 solved in full, twenty placements, each one
  accepted by the game on the first attempt.

Every example in the manual uses that same board, so the cast is shared throughout.

## How it's built

One self-contained `index.html`. No build step, no dependencies, no framework — open the file in a
browser and it works. Fonts load from Google Fonts; everything else, including the two small
interactive pieces, is inline. It follows the reader's light or dark theme and is readable at phone
width.

## Contributing

Corrections are the most useful thing you can send, particularly on rules. Definitions here are
quoted from the official in-game glossary, but several of the derived techniques were worked out
rather than documented, and two have already needed fixing after closer examination. If something
is wrong, or you have a board that contradicts a rule stated here, please
[open an issue](https://github.com/gsingers/clues_by_sam/issues) or send a pull request.

The manual's own Sources section lists what each claim rests on, and is explicit about where no
public record exists to check against.

## License

MIT — see [LICENSE](LICENSE).
