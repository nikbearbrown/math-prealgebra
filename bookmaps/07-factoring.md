# Source map — Chapter 07, Factoring

Source: OpenStax *Elementary Algebra 2e*, Chapter 7, modules m82561, m82564, m82566, m82527–m82530. License: CC-BY 4.0.

## Source files

- `01-m82561.md` — Chapter intro on quadratic models (68 words). Contributed: framing, baseball-trajectory cold open seed.
- `02-m82564.md` — GCF, factoring out GCF, factor by grouping (2,524 words). Contributed: §2 (Concept 1).
- `03-m82566.md` — Trinomials of form $x^2 + bx + c$ (2,727 words). Contributed: §3 first part.
- `04-m82527.md` — Trinomials of form $ax^2 + bx + c$, AC method, trial-and-error (3,554 words). Contributed: §3 AC method.
- `05-m82528.md` — Special factoring patterns: perfect squares, difference of squares, sum/difference of cubes (3,319 words). Contributed: §3 perfect squares and difference of squares.
- `06-m82529.md` — General factoring strategy (1,728 words). Contributed: §3 strategy summary.
- `07-m82530.md` — Solving quadratic equations by factoring + Zero Product Property (4,482 words). Contributed: §4 (Concept 3).

## Concept coverage

- **Concept 1: GCF + factoring by grouping.** Primary source: m82564.
- **Concept 2: Factoring trinomials + special patterns.** Primary sources: m82566 ($a = 1$), m82527 ($a \ne 1$, AC method), m82528 (special patterns), m82529 (strategy).
- **Concept 3: Zero Product Property + solving by factoring.** Primary source: m82530.

## Deferred material

- **Sum and difference of cubes** ($a^3 + b^3 = (a+b)(a^2 - ab + b^2)$ and $a^3 - b^3 = (a-b)(a^2 + ab + b^2)$) — present in m82528 but deferred from the rewrite. Reason: the patterns are useful in college algebra but rarely arise in elementary-algebra word problems, and including them would dilute the chapter's focus on quadratic factoring. A future revision can add them to §3 or as an appendix.
- **Trial-and-error method for $ax^2 + bx + c$** — present in m82527 alongside AC method. The rewrite teaches AC method exclusively. Reason: AC is more reliable, especially for students who struggle with intuitive number sense; trial-and-error can be picked up later as a faster shortcut.
- **Multiple worked-example sequences for each technique** (m82566, m82527, m82530 each contain 5–10 worked examples) — compressed in the rewrite to one or two examples per technique. The remaining practice happens in exercises.
- **Cross-multiplication / "FOIL backwards" framing** for $ax^2 + bx + c$ — alternative to AC method, briefly mentioned in m82527. Not used in the rewrite. Reason: same as trial-and-error.

## Source-level notes

- **No contradictions** between source files.
- **Zero Product Property statement.** Source states the property without naming integral domains. Rewrite adds the reflexive note about modular arithmetic and matrix algebra to ground the property in its mathematical context.
- **Baseball synthesis (§1, §4).** The polynomial $-16t^2 + 64t$ matches standard physics-textbook trajectories. The cold-open setup is original; the math is universal.
- **Profit parabola synthesis (§5).** Original construction. Coefficients ($-2, 80, -600$) chosen to factor cleanly over the integers (roots at 10 and 30, vertex at 20 with profit 200) so that the entire chapter's machinery applies in one example.
- **Area-model figures.** OpenStax includes several geometric area-model figures for trinomial factoring (m82566). The rewrite does not embed them; the images companion file lists them as candidates if a designer reinstates figures.
