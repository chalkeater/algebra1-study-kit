# Miriam's Algebra 1 — Unit Study Kit

A repeatable structure for building a full study kit ahead of each unit test.
Every unit gets its own folder: `unit-NN-topic-name/`, containing the same
five self-contained HTML files.

## The five pieces, per unit

1. **`study-guide.html`** — Open-notes reference. Dense, scannable, one
   worked example per question type, print-friendly (there's a "Print for
   test day" button). This is the only one meant to be used *during* the test.
2. **`concept-explainers.html`** — The ELI5 deep-dive. Longer, friendlier,
   one accordion section per concept: an analogy, the "why it works," a
   harder worked example, common mistakes, and a "say it back" recall prompt.
   Read this *before* the test, not during.
3. **`playground.html`** — Interactive practice: one hands-on "station" per
   concept (drive an equation solver yourself, build a number-line graph,
   click-test points on a coordinate plane, drag sliders on a real-world
   model). No lecturing — just tools to manipulate until it clicks.
4. **`flashcards.html`** — Tap-to-flip flashcards, a handful per concept.
   Filter by concept, mark each card "know it" or "still learning" (it
   remembers), shuffle, and swipe through on a phone — built for quick
   drilling on the go, not sitting at a desk.
5. **`practice-quiz.html`** — Self-grading quiz covering every concept, with
   instant feedback, a score/streak tracker, and a "show steps" reveal on
   every question.

All five are plain HTML/CSS/JS with no external dependencies (fonts are
embedded as base64 so they work fully offline) — just open any file in a
browser. Every page has a mobile viewport tag and touch-friendly (44px+)
tap targets, so they hold up as well on a phone as on a laptop. They also
work well as Claude Artifacts if you want a shareable link.

## Current units

- **`unit-01-linear-equations-inequalities/`** — solving linear equations,
  variable on one side, variables on both sides, the distributive property,
  literal equations, compound inequalities, graphing two-variable
  inequalities, modeling with two-variable inequalities.

## Starting the next unit

1. Copy the topic list for the new test.
2. Make a new folder: `unit-02-<topic>/`.
3. Ask Claude to build the same five files for the new topics — point it at
   this README so it reuses the structure and design language.
