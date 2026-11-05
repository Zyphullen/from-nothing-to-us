# From Nothing to Us

An interactive dark-mode tree of how everything emerges, from the quantum field to humans.

Current version: **v10** (5 Nov 2026)

Live site: https://zyphullen.github.io/from-nothing-to-us/

## What it is

An interactive map of how everything emerges, from the quantum base layer to us, inspired by Alex Wissner-Gross's Chain Theory plus confirmed science, with green for known, orange for 'we think' and red for unknown.

## How it's made

A single static HTML file, plain JavaScript and WebGL, no libraries, no tracking, no accounts, built with AI assistance. The same facts are also in `facts.json`, with `llms.txt` pointing AIs to that file.

## Credits

Piano: Salamander Grand Piano by Alexander Holm (CC BY 3.0), via FreePats

Made by Zyphullen

## What's new in v10

- AI-readable facts: `facts.json` holds every node, card, colour and source, built from the same data as the page. `llms.txt` points AIs to that file.
- Human Body, drawn to scale: ribs, limbs, kidneys and palms face forward. No skin layer. Five layers are on by default.
- Heart: four chambers, the septum and the valves, about 70 beats a minute.
- Smooth zoom, and a tap only hits what is visible.
- Body → cell bridge: an organ card's "See its cells" opens the Virtual Cell, with ← Body to go back.
- Review and science fixes (element origins, cell cards, Euclid 2027, holography wording and others). Chain Theory stays orange.
- Layout: cards sit above the toolbar, the top of Tree and Circle is no longer clipped, and the phone ruler is fixed in Tree.

## What's new in v9

- Human Body: a front view with real proportions and five layers you can turn on and off (muscles, skeleton, organs, blood vessels and nerves). Zoom from cm down to mm, and tap a part for its card and sources.
- Virtual Cell: a typical human cell, drawn to scale and moving at real measured speeds, with time control (pause, slow down or speed up) and a DNA zoom from the nucleus to chromatin, "beads on a string", and the double helix.
- Explore menu: entries for the cell and the body.
- Fixes: fact-checked card text (simplifications labelled "simplified"), the phone note no longer covers the head, hidden parts can't be tapped through, and tidier labels. Version labels say v9.

## What's new in v8

- Explore menu: a side menu with All the elements and a living Virtual Cell.
- Virtual Cell: zoom from the whole cell to organelles, molecules, atoms, and inside an atom. Tap a part for a short card; a breadcrumb and scale bar show where you are, down to picometres.
- Tree of everything: the Tree view is an organic tree, with roots, a glowing trunk, tapering branches and leaves, and "Us" in the crown.
- Keyboard: Tab to any node, Enter to open.
- Phones: a compact top bar, the Circle opens at a readable size, and the Key chip sits above the pop-up.
- Circle: a wider, rounder loop, placed so the loop card no longer covers the map.
- Text: bigger small text and brighter greys, so the writing is easier to read.
- Science wording: Bennu ribose (Dec 2025), LUCA figures marked as estimates, the oldest bacterial fossils marked debated, the first photosynthesis made no oxygen, and brain synapse numbers made consistent.
- Link preview: a new image (`og-preview-2026.png`) for shared links.

## What's new in v7

- Circle view: a third option next to Map and Tree (Map / Tree / Circle). The whole journey sits on one ring in stage order, with Chain Theory on an inner ring and "Is it all one loop?" in the centre.
- The loop: a red, dashed, glowing line joins "Us" back to "Before the Big Bang?". Both ends are unknown. Its pop-up explains related ideas (the block universe, Wheeler's participatory universe, Penrose's cycles) and is clear that no experiment has tested this yet.
- Share links: they work in the Circle view (`#tv=circle`, and `#tv=circle&loop=1` for the loop).
- How to use: the first-visit card now mentions all three views.

## What's new in v6

- Chain Theory note: the Chain Theory nodes now show a small "New idea (Oct 2026) · still being tested" badge, and Read more explains that only one number match (~1/137.036) is confirmed so far; the wider claims are still conjecture.
- How to use: a small first-visit card (zoom/drag, click a node, what the colours mean, Map ⇄ Tree). Reopen it any time from the "i" panel.
- Share a node: every pop-up has "🔗 Copy link". Links like `#n=<node>` (and `&tv=tree`) open straight to that node in the right view.
- Suggest a fix: each Read more ends with a link that opens a pre-filled GitHub issue for that node; there is also a general link in the "i" panel.
- Bounty dates: open bounties show "Last checked: 26 Oct 2026", and solved bounties can now show who solved them, when, and a source.

v2: fact-checked (151 facts), 89 steps, all 118 elements, labelled recipes, layered Read more pop-ups.
v3: left-to-right layout, wheel zooms, drag to move.
