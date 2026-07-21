# research-portfolio

Research portfolio of **Ayan Ahmed Khan** — trustworthy and efficient machine learning.

Live at <https://ayanahmedkhan.github.io/>

## What this is

A single self-contained page. No build step, no dependencies, no external
requests: the stylesheet, the scripts and the portrait are all inlined, so the
whole site is one `index.html` that works from any static host or straight off
disk.

- Six project pages, hash-routed (`#/p/ckd`, `#/p/osr`, …) so each has its own
  shareable URL and the browser back button behaves.
- Light and dark themes, following the system preference with a manual toggle
  that persists.
- The hero figure is a reliability diagram drawn on `<canvas>` — the dashed
  diagonal is perfect calibration, the curve below it is observed behaviour, and
  the shaded gap between them is the subject of the research.

## Editing

Project content lives in the `P` object inside the `<script>` block near the
bottom of `index.html`. Each entry has `title`, `domain`, `meta`, `status`,
`lede`, `body`, `stats` and `practices`; adding a key there and a matching card
in the Research section is all a new project needs.

## Contact

ayan.ahmedkhan591@gmail.com · [github.com/AyanAhmedKhan](https://github.com/AyanAhmedKhan)
