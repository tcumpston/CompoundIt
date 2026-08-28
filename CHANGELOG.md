# Changelog

## 1.0 — 28 August 2026

First public release for Windows. COMPOUND IT has been playable in a browser at
wombyland.com; this is the same game as a native download.

**The game**

- Six modes: Build a named compound atom by atom, Identify one on sight, predict
  what happens when two React, Explore freely to discover real molecules, revise
  by topic in Quiz, or just read the fact deck.
- Every molecule can be rotated and scaled, switched between the flat Lewis
  diagram and the real three-dimensional shape, and shown with or without lone
  pairs.
- Fifty compounds with common and IUPAC names, formulae, VSEPR geometry, bonding
  type, lone pairs and real-world uses. A hundred facts with questions and
  explanations.
- Lightning Round against the clock, streak counters, achievements, and a lab
  book that keeps the tally.
- Content lives in editable JSON and CSV copied to a writable folder on first
  run, so a teacher can add compounds or reword facts in a text editor. Files
  parse tolerantly - one bad entry is skipped and logged, never the whole file -
  and Content notes on the main menu reports anything unreadable.

**In this build**

- Opens in a window at about two thirds of the screen instead of borderless
  fullscreen. Fullscreen put the game on whichever monitor Unity considered
  primary, which was frequently the wrong one, and there was no way to move it.
  The window can simply be dragged.
- The window is always exactly 16:9, which is the aspect the molecule stage is
  framed for.

**Known limitations**

- The game is not code-signed, so Windows SmartScreen will warn on first run,
  and Smart App Control may block it outright. See the README.
- No application icon yet; the game uses the default Unity icon.
- Large molecules can overlap the title and feedback text. Rotating and scaling
  the model reveals anything obscured.
