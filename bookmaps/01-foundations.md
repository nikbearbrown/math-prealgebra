# Source map — Chapter 01, Foundations

Source: OpenStax *Elementary Algebra 2e*, Chapter 1, modules m82451 through m82461. License: CC-BY 4.0.

## Source files

- `01-m82451.md` — Chapter introduction (61 words). Provided the framing metaphor of "firm foundation," echoed in the rewrite's chapter opener and §1.
- `02-m82452.md` — Whole numbers, place value, primes, divisibility, LCM (5,214 words). Contributed: the integer/whole/counting number progression in §2, the ellipsis convention. Most of the prime-factorization and LCM content **deferred** to a later chapter on number theory or to chapter 7 (factoring).
- `03-m82453.md` — Variables and algebraic symbols, order of operations, like terms, English-to-algebra translation (6,028 words). Contributed: the Greg-and-Alex worked variable example in §3, the PEMDAS rule (with the rewrite adding the "convention, not discovery" framing), the like-terms definition, the translation table.
- `04-m82454.md` — Negatives, opposites, absolute value, integer addition and subtraction (5,210 words). Contributed: §2 (Concept 1) — opposites, absolute value, walking-on-the-line addition, "subtraction as addition of the opposite."
- `05-m82455.md` — Integer multiplication and division (3,339 words). Contributed: brief reference to multiplication-of-negatives in the trade-off discussion in §2. **Most content deferred** — multiplication of integers in full appears in chapter 2's setup.
- `06-m82456.md` — Equivalent, simplified, multiplied, and divided fractions (3,607 words). Contributed: the $\frac{37}{4}$ arithmetic in §5 synthesis. **Most content deferred** to a future treatment.
- `07-m82457.md` — Fraction addition and subtraction with common and different denominators (2,512 words). Contributed: same as above — used for the synthesis arithmetic. **Deferred** for explicit treatment.
- `08-m82458.md` — Decimals (4,822 words). Contributed: nothing direct. **Fully deferred** — decimals are used in the rewrite (e.g., $60.92$ inches) but not taught.
- `09-m82459.md` — Square roots, integers/rationals/irrationals/reals, locating fractions and decimals on the number line (4,986 words). Contributed: brief preview in §1 chapter opening and in the chapter summary, where rationals and irrationals are named as inhabitants of the number line. **Most content deferred** to chapter 9.
- `10-m82460.md` — Commutative, associative, identity, inverse, distributive properties; properties of zero (4,764 words). Contributed: §4 (Concept 3) — the entire treatment of the five property families, including the worked simplification example.
- `11-m82461.md` — Unit conversions (US, metric, F-to-C) (8,058 words). Contributed: nothing direct. **Fully deferred** — unit conversions belong with chapter 3 (math models) or as a separate appendix.

## Concept coverage

- **Concept 1: The number line and integer arithmetic.** Primary source: m82454 (negatives, opposites, absolute value, integer add/sub). Supplementary: m82452 (whole and counting numbers, ellipsis), m82459 (preview of rationals and irrationals on the line).
- **Concept 2: Variables, expressions, and the order of operations.** Primary source: m82453 (variables, PEMDAS, like terms, translation). Supplementary: m82452 (the ellipsis notation as an example of mathematical writing).
- **Concept 3: The properties of real numbers.** Primary source: m82460 (commutative, associative, identity, inverse, distributive, properties of zero). Supplementary: m82454 (additive inverse implicit in opposite-of-a-number).

## Deferred material

Material in the source not used in the rewritten chapter, with reason for deferral:

- **Prime factorization and LCM** (from m82452) — too peripheral to a foundations chapter that focuses on the number line, naming unknowns, and properties. Better placed in chapter 7 (factoring) or as a number-theory aside.
- **Integer multiplication and division** (from m82455) — covered briefly in passing in §2's trade-off paragraph, but the full pattern (positive×negative, negative×negative) is deferred. Reason: pedagogically, the multiplication rule is more naturally introduced at the moment a student needs it (when distributing across a negative coefficient in chapter 2). Forcing it into Concept 1 of this chapter would have either broken the number-line framing or required a fourth concept.
- **Fraction operations — simplification, multiplication, division, addition, subtraction with unlike denominators** (from m82456 and m82457) — fractions appear in the rewrite as ingredients in worked problems, not as a topic of instruction. Reason: students arriving at this chapter are expected to have prealgebra-level fraction comfort. A full re-teaching of fractions would balloon the chapter past the 8,000-word ceiling and would duplicate prealgebra coverage that lives in earlier OpenStax volumes.
- **Decimals — naming, place value, rounding, all four operations, conversions among decimals/fractions/percents** (from m82458) — same reasoning as fractions. The rewrite uses decimals (in checking-account examples, in carpenter measurements) but does not teach them.
- **Square roots and the rational/irrational distinction** (from m82459) — previewed in passing but not deep-dived. Reason: square roots and irrationals are the subject of chapter 9. Pulling them forward would either leave them shallow here or duplicate chapter 9.
- **Properties of zero — multiplication by zero, division by zero** (from m82460) — touched in §4 in the inverse-property paragraph (zero has no multiplicative inverse, dividing by zero is undefined) but not given full standalone treatment. Reason: the *why* of these facts is most naturally addressed when the student first attempts to violate them in an equation, which happens in chapter 2 (clearing fractions) and chapter 8 (rational expressions).
- **Unit conversions — US, metric, US-to-metric, Fahrenheit-to-Celsius** (from m82461) — fully deferred. Reason: unit conversions are a powerful application of multiplicative-identity reasoning (multiplying by $\frac{12 \text{ in}}{1 \text{ ft}}$ is multiplication by 1 in disguise) but they belong with chapter 3 (math models) or as an appendix. They have no place in a foundations chapter that aims to teach only the most general number-line, variable, and property machinery.

## Source-level notes

- **No contradictions** between source files were observed; OpenStax content is internally consistent.
- **Authorship.** OpenStax modules carry no individual author byline; they are collectively authored under the OpenStax editorial process. The rewrite is by Nik Bear Brown, written in his voice, but the *factual content* is OpenStax. Attribution appears at the bottom of the chapter file and on the per-chapter footer in `_notes.md`.
- **Source quality.** OpenStax content is pedagogically conservative — heavy on definitions, light on motivation, scrupulous about correctness. The voice rewrite preserves the correctness while replacing the conservative definitional opening with scene-driven cold opens and trade-off framing. Every fact, equation, and example used in the rewrite traces to a specific OpenStax module above.
- **Figure handling.** OpenStax figures (referenced as `<figure id="CNX_ElemAlg_Figure_..."` in source) are not embedded in the rewrite. Two figure briefs were generated (see images/01-foundations.md). The remaining source figures are listed in that file under "figures NOT used."
- **Voice anchoring.** No `books/prealgebra-bundle/style/` per-book voice samples exist as of this draft. Anchor was the workshop-level `style/VOICE.md`. First-chapter status: voice-calibration-pass; reviewer should read with explicit attention to whether the cold opens, trade-off framings, and "convention vs. discovery" stance land for elementary algebra students.
