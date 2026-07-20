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
5. **`practice-quiz.html`** — Self-grading quiz covering every concept, in
   two modes. Practice mode: instant feedback, score/streak tracker, "show
   steps" reveal on every question. **Exam mode** (added unit 2): no feedback
   or steps until a final Submit — a dress rehearsal for the real test, with
   a per-concept score breakdown at the end. Also has a **Print worksheet**
   button that lays out every question (answer key on the last page) for one
   full pass on paper.

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
- **`unit-02-sets-and-triangle-angles/`** — sets and elements, subsets,
  union and intersection with Venn diagrams, sets applied to probability
  and geometry, the triangle angle-sum theorem, and the proofs of why the
  interior angles sum to 180° (rearranging onto a straight line; parallel
  lines and alternate interior angles).

- **`unit-03-systems-of-equations-inequalities/`** — solving systems of
  linear equations by graphing, substitution, and elimination (linear
  combination); one/no/infinitely-many solutions; modeling word problems
  with systems; writing and graphing systems of linear inequalities.
  This unit has a sixth piece: `cheat-sheet.html` (the printable 1-page
  format introduced by the midterm review).

- **`unit-04-nonlinear-functions-part-two/`** — solving and graphing absolute
  value equations and inequalities, verifying solutions by substitution,
  absolute value functions and their vertical/horizontal translations
  (including reading increasing/decreasing intervals off a translated
  graph), adding and subtracting rational expressions with common
  denominators, and simplifying/multiplying/dividing radical expressions
  (including rationalizing the denominator). This unit has six pieces too
  (the standard five plus `cheat-sheet.html`).

- **`unit-05-polynomial-expressions/`** — adding and subtracting polynomials;
  multiplying monomials, binomials, and trinomials, including the special
  products (difference of squares, perfect square trinomials, and sum/
  difference of cubes as multiplication patterns); and factoring — GCF,
  factoring by grouping, factoring trinomials with a leading coefficient of
  1 (both positive and negative constants), and factoring the sum/difference
  of cubes. This unit also has six pieces (the standard five plus
  `cheat-sheet.html`). The playground's factoring-trinomials station has a
  real interactive algebra-tile builder — pick a candidate number pair,
  check it against both conditions (multiply to c, add to b), and the tile
  rectangle renders itself once you find the right one.

- **`midterm-review/`** — cumulative review for the first half of the class
  (built from the 25-question Edgenuity cumulative exam review). Three pieces
  instead of five: `cheat-sheet.html` (the whole exam on 1–2 scannable,
  printable pages — 10 one-sentence big ideas plus "do this" boxes per topic),
  `practice-quiz.html` (41 questions across 7 topics, **generated from
  randomized templates** — fresh numbers on every deal via 🎲 New questions,
  every exam-mode run, and every worksheet print), and `flashcards.html`
  (40 cards). Topics: solving equations, literal equations & formulas,
  inequalities, function basics, features of graphs, lines/slopes/sequences,
  sets & Venn diagrams.

## Starting the next unit

1. Copy the topic list for the new test.
2. Make a new folder: `unit-02-<topic>/`.
3. Ask Claude to build the same five files for the new topics — point it at
   this README so it reuses the structure and design language.
