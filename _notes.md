# Revision Notes

Track what you've added, removed, or rewritten here.

## Source attribution

This book's source content is OpenStax *Elementary Algebra 2e*, Chapter modules m82451 through m82559, used under CC-BY 4.0. The voice rewrites in `chapters/NN-[slug].md` are by Nik Bear Brown in the Attenborough × Feynman v1.1 register; factual content (operations, definitions, worked examples, sequencing) traces to OpenStax. Each rewritten chapter carries an attribution footer.

---

## 2026-05-07 — Attenborough × Feynman conversion run

Converted **all 10 chapters** from source subfolders to rewritten markdown files.

**Style:** Attenborough × Feynman v1.1 (root `style/VOICE.md`). No per-book voice samples exist at `books/prealgebra-bundle/style/`; chapters are voice-anchored at workshop level only — flag for reviewer calibration on chapter 01 in particular, as the calibration pass for register and trade-off framing.

**Chapters processed:**
- `01-foundations` — 7,192 words — **OK** — 3 concepts (number line / variables + PEMDAS / properties of real numbers); 8 deferred topics in bookmap
- `02-solving-linear-equations-and-inequalities` — 5,380 words — **OK** — 3 concepts (balance principle / general strategy + classification / inequalities + flip rule)
- `03-math-models` — 5,004 words — **OK** — 3 concepts (5-step strategy / templates: percent + mixture + motion / geometry + inequality applications)
- `04-graphs` — 5,061 words — **OK** — 3 concepts (coordinate plane / slope-intercept / writing equations + parallel/perpendicular)
- `05-systems-of-linear-equations` — 4,662 words — **OK** — 3 concepts (system + 3 outcomes / substitution + elimination / applications)
- `06-polynomials` — 4,977 words — **OK** — 3 concepts (polynomial taxonomy + add/sub / exponent rules + multiplication / division + integer exponents + scientific notation)
- `07-factoring` — 4,703 words — **OK** — 3 concepts (GCF + grouping / trinomials + special patterns / Zero Product Property + solving)
- `08-rational-expressions-and-equations` — 4,517 words — **OK** — 3 concepts (rationals + domain trap / LCD operations / rational equations + extraneous-solution check)
- `09-roots-and-radicals` — 4,249 words — **OK** — 3 concepts (square roots + simplification / operations + rationalizing / radical equations + squaring trap)
- `10-quadratic-equations` — 5,118 words — **OK** — 3 concepts (Square Root Property + completing the square / quadratic formula + discriminant / parabolas)

**Companion files generated for every chapter:**
- `pantry/NN-[slug].md` — reusable scenes, analogies, etymologies, trade-offs, scale shifts, worked examples, structural moves
- `images/NN-[slug].md` — figure briefs (where `[FIGURE: ...]` placeholders exist) plus candidates for designer reinstatement
- `bookmaps/NN-[slug].md` — source-file-by-source-file map of which source content contributed where, plus deferred-material catalog

**Source subfolders removed:** all 10 (verification passed for every chapter).

**Source subfolders preserved:** none (no flagged chapters this run).

**Combined Test status:** all 14 points pass for every chapter. Forbidden-phrase scans clean. One post-draft fix applied to chapter 07 (replaced "obviously" with "shared").

**Total output:**
- Chapter prose: ~50,863 words
- Companion files: ~28,000 words across 30 files
- Aggregate: roughly 79,000 words of new content

**Voice notes for reviewer:**
- Chapter 01 is the calibration pass; the cold-open register (Vermont thermometer; carpenter at the steel tape; recipe card) sets the tone for the rest of the book. If that register is off, all 10 chapters need a re-pass.
- Trade-off framings appear in every concept section across all chapters. Where the trade-off is genuinely contestable (e.g., teaching PEMDAS as convention vs. as rule in chapter 1), the rewrite leans on "convention, not discovery" — this is a deliberate stance, not source-derived.
- Reflexive notes (where a "rule" turns out to be system-specific — Euclidean geometry in chapter 3, integral domains in chapter 7, real-numbers-only constraint in chapter 9) are inserted to keep the chapter from claiming universality where the math is actually conditional. These are original to the rewrite, not in source.
- Chapter cross-references are heavy: each chapter explicitly names where chapter 1's properties of real numbers are doing work, and the irreversibility lesson (chapter 8 → chapter 9 → forward to college algebra logarithms) is a recurring motif.

**Deferred material aggregated across chapters:**
- Higher-order roots (cube, n-th) — chapter 9 source has full treatment
- Rational exponents — chapter 9 source has full treatment
- Sum/difference of cubes — chapter 7 source
- Direct/inverse variation — chapter 8 source
- Complex rationals as a standalone topic — chapter 8 source
- Linear programming as a standalone topic — chapter 5 source
- Linear inequalities in two variables (full treatment, beyond preview) — chapter 4 source
- Distance-rate-time as a standalone formula chapter — chapter 2 source
- Detailed unit-conversion treatment — chapter 1 source
- Decimals, fractions, primes, LCM as foundational topics — chapter 1 source (assumed prerequisite)

These deferred items are catalogued chapter-by-chapter in the bookmaps. A future "intermediate algebra" or "college algebra" book in this workshop could pick them up cleanly.

**Source-level issues discovered:** none. OpenStax content is internally consistent; all factual claims, formulas, and worked examples in the source are mathematically correct and consistent across modules.

**Voice-anchor status:** chapter 1 was drafted voice-unanchored at the per-book level (no `books/prealgebra-bundle/style/` samples); subsequent chapters inherit chapter 1's calibration. For future books in this workshop, chapter 1 of each new book should be the calibration pass — and the resulting drafts can be added to `books/[slug]/style/` to anchor chapter 2 onward.

**Next steps for reviewer:**
1. Read chapter 01 and verify the cold-open register is correct.
2. Spot-check 2–3 other chapters (suggested: chapter 04 for graphs, chapter 07 for factoring, chapter 10 for the closing arc).
3. If revisions are needed to the voice register, all 10 chapters can be re-passed in a focused revision run.
4. If approved, the chapter drafts move to the human review gate; nothing publishes from this rewrite without explicit Nik approval.

## 2026-05-12 — Running Project added: "Modeling One Phenomenon"

Generated 10 end-of-chapter LLM Exercise blocks via the Running Project Exercise Generator. Project selected: **Mathematical Modeling of One Phenomenon** — student picks a real phenomenon in Chapter 1 (compound interest / mortgage / projectile motion / fitness progression / recipe scaling / cell-phone bill / photography / gaming / sports analytics) and builds increasingly sophisticated mathematical models of it across all 10 chapters. Final deliverable: 3,000–5,000 word "Modeling [Phenomenon]" document with linear → systems → polynomial → factored → rational → radical → quadratic models all applied to the same situation.

The architecture mirrors the book's content arc precisely:
- Ch 1: Foundation Document (variables, units, relationships in English, central question)
- Ch 2: Linear model + inequality constraint
- Ch 3: 5-step strategy applied to a word problem in the student's domain
- Ch 4: Graphing the linear model (Claude Code produces real PNG charts)
- Ch 5: Two-constraint system + intersection interpretation
- Ch 6: Nonlinear upgrade (polynomial model where linear breaks)
- Ch 7: Factor and find roots (Zero Product Property → real-world events)
- Ch 8: Rational-expression dimension (rate, density, average) + extraneous-solution check
- Ch 9: Radical dimension (Pythagorean, geometric mean, period) + squaring-trap check
- Ch 10: Full quadratic + parabola + discriminant + final compiled document

**Important: book scope flag.** The slug `prealgebra-bundle-with-llms` is misleading. The content (per _notes.md and chapter scan) is OpenStax *Elementary Algebra 2e* — first-course algebra (linear through quadratic), not prealgebra-level content (whole numbers, fractions, decimals, percent, integers). The exercises are calibrated to the elementary-algebra content actually present. If the slug should point at true prealgebra content, the chapters need to be re-sourced, not just have exercises added.

Methodological commitments baked in: every chapter requires the student to (a) tie that chapter's algebra to a real measurement in their phenomenon, (b) verify the work — extraneous-solution checks in Chs 7, 8, 9; the eyeball test in Ch 4; the discriminant interpretation in Ch 10; (c) name where the model is wrong, not just where it works. The Ch 10 closer requires a "What I'd refine if I had more math" coda — the project's intellectual-honesty close.

Tool recommendations: Claude Project as the home for the building document; Claude Code for chart generation (Chs 4, 5, 6, 10), root-finding verification (Ch 7), and symbolic manipulation cross-checks (Chs 8–9). Cowork for Ch 10 final compilation across 10 sections.

Each block appended to the bottom of its chapter file. Total addition: ~9,000 words of new content across 10 chapters.

**Known follow-up for review:** the project assumes the student has Claude Code access. For students without (or in courses where the chart-generation step is impractical), a "Cowork or spreadsheet alternative" line is included in every chart-relevant chapter (4, 5, 6, 10). If the workshop wants tighter accessibility, the chart-generation requirement could be made fully optional rather than encouraged.

**Cross-book note:** this is the first running-project pass on a math book in this workshop. The pattern that worked for psychology/management/marketing/economics/accounting (one cumulative artifact built chapter-by-chapter) carries to math IF the chapter arc happens to align with one phenomenon's modeling complexity. For elementary algebra, the alignment is unusually clean — the chapter arc IS the modeling arc. For more abstract math books (set theory, formal logic, real analysis), the same approach may not transfer.
