---
book: prealgebra-bundle
chapter: 07-factoring
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 7 (CC-BY 4.0). Modules m82561, m82564, m82566, m82527–m82530.
status: draft
---

# Suggested titles


## TL;DR

- book: prealgebra-bundle chapter: 07-factoring voice: Attenborough × Feynman v1.
- You will practice Find the greatest common factor (GCF) of a set of monomials and factor it out of a polynomial; Factor a four-term polynomial by grouping; Factor trinomials of the form $x^2 + bx + c$ by finding two numbers whose sum is $b$ and product is $c$.
- The chapter moves through Chapter opening, Learning objectives, Prerequisites, Why this chapter matters, and related ideas.

1. Factoring: Multiplication in Reverse, with a Purpose
2. Pulling Polynomials Apart
3. The Zero Product Property and Why Factoring Pays

---

**TL;DR.** *Factoring* is multiplication run backward. Where chapter 6 multiplied $(x + 2)(x + 3)$ to get $x^2 + 5x + 6$, this chapter starts with $x^2 + 5x + 6$ and recovers the factors. The payoff is the *Zero Product Property*: if a product equals zero, at least one factor equals zero. That single fact turns factoring into the master technique for solving polynomial equations.

---

## 1. Chapter opening

A baseball is hit straight up at $64$ feet per second. Its height in feet, $t$ seconds after the bat, is approximately $h(t) = -16t^2 + 64t$. *When does it hit the ground?*

Set the height to zero: $-16t^2 + 64t = 0$. Factor: $-16t(t - 4) = 0$. By a single property — the *Zero Product Property* — this equation is true exactly when $-16t = 0$ or $t - 4 = 0$. Either $t = 0$ (the moment of the swing) or $t = 4$ (the moment the ball lands).

Two answers. Two factors. One property.

A polynomial expression like $-16t^2 + 64t$, considered alone, gives you a value at every time $t$ — a height in the air. Set it equal to zero, and you have a *polynomial equation*. To solve a polynomial equation, the most reliable technique is to factor it and then read off the values that make each factor zero. The factoring is the work; the Zero Product Property is the payoff.

This chapter develops the factoring vocabulary. You will learn to pull out a common factor, group four-term polynomials, factor trinomials of two standard forms, recognize the special patterns that cancel cleanly, and then use all of that to solve quadratic equations. Chapter 10 continues the story when factoring fails — when a quadratic does not factor over the integers and you need the quadratic formula. For most quadratics that come from word problems, factoring works, and the work of chapter 10 is to give you the backup.

### Learning objectives

By the end of this chapter you should be able to:

- **Find** the greatest common factor (GCF) of a set of monomials and **factor** it out of a polynomial.
- **Factor** a four-term polynomial by grouping.
- **Factor** trinomials of the form $x^2 + bx + c$ by finding two numbers whose sum is $b$ and product is $c$.
- **Factor** trinomials of the form $ax^2 + bx + c$ (with $a \ne 1$), using the AC method or trial and error.
- **Recognize** and factor special patterns: perfect square trinomials and the difference of squares.
- **Use** the Zero Product Property to solve quadratic and higher-degree polynomial equations.
- **Set up and solve** word problems that produce factorable quadratic equations.

### Prerequisites

Chapter 6, especially the distributive property in both directions, the FOIL pattern, and the special products. Factoring is FOIL run backward; pattern recognition for the special products will accelerate you. You should also be comfortable with the chapter 2 strategy for solving linear equations.

### Why this chapter matters

Factoring is the algebraic move that does the most work for the smallest investment. Almost every polynomial equation in elementary, intermediate, and college algebra is solved by factoring when factoring is possible. The Zero Product Property — *if $AB = 0$, then $A = 0$ or $B = 0$* — is one of the few facts about the real numbers that turns multiplication into a *case analysis*. Combined with factoring, it lets you take a single complicated equation and reduce it to a small number of simple equations, each of which you already know how to solve.

---

## 2. Concept 1 — Greatest common factor and factoring by grouping

Every factoring problem starts with the same first move: *look for a common factor*. If every term shares a factor, pull it out. This is the algebraic equivalent of *pulling out what is shared* before doing the harder work.

### The greatest common factor

The **greatest common factor** of a set of monomials is the largest monomial that divides every term in the set. To find it:

1. Find the GCF of the *coefficients* (using prime factorization or just inspection for small numbers).
2. For each variable that appears in *every* term, take the *lowest* power of that variable that appears.
3. Multiply the coefficient GCF by the variable parts.

> **Example.** Find the GCF of $12x^3y^2$ and $18x^2y^4$.
>
> Coefficients: GCF of $12$ and $18$ is $6$.
> $x$ appears with exponents $3$ and $2$; lowest is $2$ — take $x^2$.
> $y$ appears with exponents $2$ and $4$; lowest is $2$ — take $y^2$.
>
> GCF: $6x^2y^2$.

### Factoring out the GCF

To factor a polynomial: find the GCF of all its terms, write the polynomial as the GCF times what remains.

> **Example.** Factor $12x^3y^2 - 18x^2y^4$.
>
> GCF: $6x^2y^2$. Divide each term by the GCF:
> $\dfrac{12x^3y^2}{6x^2y^2} = 2x$, $\dfrac{18x^2y^4}{6x^2y^2} = 3y^2$.
>
> Factored form: $6x^2y^2(2x - 3y^2)$.
>
> *Verification:* distribute back. $6x^2y^2 \cdot 2x = 12x^3y^2$ and $6x^2y^2 \cdot 3y^2 = 18x^2y^4$. $\checkmark$

The verification step — distribute back — is the only way to be sure your factoring is correct. Always do it.

### Factoring by grouping

When a polynomial has *four terms*, no GCF among all four, but a GCF among pairs, **grouping** is the technique.

> **Example.** Factor $x^3 + 2x^2 + 5x + 10$.
>
> Group: $(x^3 + 2x^2) + (5x + 10)$.
>
> First pair has GCF $x^2$: $x^2(x + 2)$.
> Second pair has GCF $5$: $5(x + 2)$.
>
> Now both terms share the factor $(x + 2)$:
>
> $x^3 + 2x^2 + 5x + 10 = x^2(x + 2) + 5(x + 2) = (x + 2)(x^2 + 5)$.
>
> *Verification:* $(x + 2)(x^2 + 5) = x^3 + 5x + 2x^2 + 10 = x^3 + 2x^2 + 5x + 10$. $\checkmark$

For grouping to work, the two pairs must produce the *same* binomial in parentheses. If they do not, try regrouping (swap the order of the four terms) or try a different first move.

### The trade-off

Pulling out the GCF is the cheapest factoring move and almost always the right first step. The trade-off is that it does not always finish the job. After GCF, you may still need to factor a trinomial, recognize a special product, or apply grouping. *GCF first* is the rule; what comes after depends on what is left.

### Common misconceptions

- *"$6$ is the GCF of $12x$ and $18y$."* No. The variables share no factor (different letters); the GCF is just $6$. The factored form $6(2x - 3y)$ is correct, but writing $6xy$ as a "common factor" is an error.
- *"Grouping always works on four-term polynomials."* No. Grouping works when the polynomial *factors*; some four-term polynomials are irreducible over the integers. If grouping does not produce a common binomial after both pairs are factored, the polynomial may not factor by this technique.
- *"Once I factor out the GCF, I'm done."* Not always. After GCF, check whether what remains can be factored further (trinomial? special product?). Factor *completely* — keep going until no further factoring is possible.

---

## 3. Concept 2 — Factoring trinomials and special patterns

Most factoring problems in this chapter and in chapter 10 are *trinomials* — polynomials of three terms. Two cases: the leading coefficient is one ($x^2 + bx + c$) or it is not ($ax^2 + bx + c$). The first case is straightforward; the second requires more work.

### Trinomials of the form $x^2 + bx + c$

Factoring $x^2 + bx + c$ as $(x + p)(x + q)$ requires finding two numbers $p$ and $q$ such that:

- $p \cdot q = c$ (their product is the constant term)
- $p + q = b$ (their sum is the coefficient of $x$)

This works because expanding $(x + p)(x + q)$ gives $x^2 + (p+q)x + pq$ — that is, the coefficient of $x$ is $p+q$ and the constant is $pq$.

> **Example.** Factor $x^2 + 7x + 12$.
>
> Need two numbers whose product is $12$ and sum is $7$. List factor pairs of $12$:
>
> $1 \times 12 \to 1 + 12 = 13$
> $2 \times 6 \to 2 + 6 = 8$
> $3 \times 4 \to 3 + 4 = 7$ ✓
>
> Factored form: $(x + 3)(x + 4)$.
>
> *Verification by FOIL:* $(x + 3)(x + 4) = x^2 + 4x + 3x + 12 = x^2 + 7x + 12$. $\checkmark$

For *negative* constants or *negative* coefficients, the signs of $p$ and $q$ adjust:

- If $c > 0$ and $b > 0$: both $p$ and $q$ positive.
- If $c > 0$ and $b < 0$: both $p$ and $q$ negative.
- If $c < 0$: $p$ and $q$ have opposite signs.

> **Example.** Factor $x^2 - x - 12$.
>
> Need $pq = -12$ and $p + q = -1$. Opposite signs.
>
> $(-4)(3) = -12$ and $-4 + 3 = -1$. ✓
>
> Factored form: $(x - 4)(x + 3)$.

### Trinomials of the form $ax^2 + bx + c$ — the AC method

When the leading coefficient is not $1$, the same logic applies but with an extra step. The **AC method**:

1. Compute $a \cdot c$ (the product of leading and constant coefficients).
2. Find two numbers $p$ and $q$ whose product is $ac$ and whose sum is $b$.
3. Rewrite the middle term as $px + qx$.
4. Factor by grouping.

> **Example.** Factor $2x^2 + 7x + 3$.
>
> $a \cdot c = 2 \cdot 3 = 6$. Need two numbers with product $6$ and sum $7$: $6$ and $1$. ✓
>
> Rewrite: $2x^2 + 6x + 1x + 3$.
>
> Group: $(2x^2 + 6x) + (x + 3) = 2x(x + 3) + 1(x + 3) = (x + 3)(2x + 1)$.
>
> *Verification:* $(x + 3)(2x + 1) = 2x^2 + x + 6x + 3 = 2x^2 + 7x + 3$. $\checkmark$

The AC method always works; it is more reliable than trial and error. The trade-off is computational: you must factor pairs of a potentially large product $ac$.

### Special patterns — pattern recognition pays

Two patterns from chapter 6 reverse cleanly. Recognize them and skip the trinomial-factoring procedure.

**Difference of squares.** $a^2 - b^2 = (a + b)(a - b)$.

> **Example.** Factor $9x^2 - 25 = (3x)^2 - 5^2 = (3x + 5)(3x - 5)$.

There is no analogous pattern for the *sum* of squares: $a^2 + b^2$ does not factor over the real numbers. (It does factor over the complex numbers, which you will meet in a later course.)

**Perfect square trinomials.** $a^2 + 2ab + b^2 = (a + b)^2$ and $a^2 - 2ab + b^2 = (a - b)^2$.

To recognize a perfect square trinomial: the first and last terms are perfect squares (say $a^2$ and $b^2$), and the middle term is $\pm 2ab$.

> **Example.** Factor $x^2 + 10x + 25$.
>
> First term: $x^2$, so $a = x$. Last term: $25 = 5^2$, so $b = 5$. Middle term: $10x = 2 \cdot x \cdot 5 = 2ab$. ✓
>
> Factored form: $(x + 5)^2$.

> **Example.** Factor $4x^2 - 12x + 9$.
>
> $a = 2x$, $b = 3$. $2ab = 2 \cdot 2x \cdot 3 = 12x$. ✓ (Sign is negative.)
>
> Factored form: $(2x - 3)^2$.

### A complete factoring strategy

The general strategy:

1. **GCF first.** Factor out any common factor among all terms.
2. **Count the terms** of what remains.
3. **Two terms:** check for difference of squares.
4. **Three terms:** is it a perfect square trinomial? If not, factor as $x^2 + bx + c$ or $ax^2 + bx + c$.
5. **Four terms:** try grouping.
6. **Always check:** can the result be factored further?

Factor *completely*. Keep going until every factor is irreducible.

> **Example.** Factor $2x^3 - 8x$ completely.
>
> *GCF first.* GCF is $2x$. $2x(x^2 - 4)$.
>
> *Count terms in remainder:* two. *Check difference of squares:* $x^2 - 4 = x^2 - 2^2 = (x + 2)(x - 2)$.
>
> *Final:* $2x(x + 2)(x - 2)$.

### The trade-off

Factoring is *pattern recognition* applied with discipline. The strategy is short; the difficulty is in spotting which case applies and not stopping too early. The trade-off, compared to a more mechanical procedure, is that students who do not develop the pattern-recognition fluency often grind through the AC method on every problem — including ones where pulling out a GCF first would have made the trinomial trivial. The strategy gives you the order; the patterns give you the speed.

### Common misconceptions

- *"$x^2 + 4$ factors as $(x + 2)(x + 2)$."* No — $(x + 2)^2 = x^2 + 4x + 4$, not $x^2 + 4$. The sum of squares $x^2 + 4$ does not factor over the reals.
- *"$(x - 3)^2 = x^2 - 9$."* No. The square of a binomial includes the cross term: $(x - 3)^2 = x^2 - 6x + 9$. The expression $x^2 - 9$ is the *difference* of squares: $x^2 - 9 = (x + 3)(x - 3)$.
- *"$ax^2 + bx + c$ always factors."* No. Many trinomials are irreducible over the integers. If the AC method's two-numbers search fails (no integer pair has the right sum and product), the polynomial does not factor over the integers, and you will need the quadratic formula (chapter 10).

---

## 4. Concept 3 — The Zero Product Property and solving by factoring

The single fact that justifies the entire chapter:

**Zero Product Property.** If $A \cdot B = 0$, then $A = 0$ or $B = 0$ (or both).

This is a property of the real numbers, not of every algebraic system. It says: the only way for a product to be zero is for at least one factor to be zero. The contrapositive is even more useful: if no factor is zero, the product is not zero.

The Zero Product Property does *not* hold in every algebraic structure. In modular arithmetic with composite moduli, two nonzero numbers can multiply to zero (in arithmetic mod 6, $2 \times 3 = 6 \equiv 0$). In matrix algebra, two nonzero matrices can multiply to the zero matrix. The Zero Product Property is a feature of the real numbers (and any *integral domain*) — and elementary algebra is built on top of it.

### Solving a quadratic equation by factoring

Procedure:

1. **Move everything to one side**, leaving zero on the other.
2. **Factor** the polynomial.
3. **Set each factor equal to zero** by the Zero Product Property.
4. **Solve** each linear equation.
5. **Verify** each solution in the original.

> **Example.** Solve $x^2 + 5x + 6 = 0$.
>
> Already in standard form. Factor: $(x + 2)(x + 3) = 0$.
>
> Set each factor to zero: $x + 2 = 0$ ⇒ $x = -2$, or $x + 3 = 0$ ⇒ $x = -3$.
>
> *Verify.* $(-2)^2 + 5(-2) + 6 = 4 - 10 + 6 = 0$ ✓. $(-3)^2 + 5(-3) + 6 = 9 - 15 + 6 = 0$ ✓.
>
> **Solutions:** $x = -2$ or $x = -3$.

> **Example.** Solve $2x^2 = 5x + 12$.
>
> *Move to one side:* $2x^2 - 5x - 12 = 0$.
>
> *Factor.* $a \cdot c = 2 \cdot (-12) = -24$. Need two numbers whose product is $-24$ and sum is $-5$. Try: $-8$ and $3$: product $-24$, sum $-5$. ✓
>
> Rewrite: $2x^2 - 8x + 3x - 12 = 0$. Group: $2x(x - 4) + 3(x - 4) = 0$. Factor: $(x - 4)(2x + 3) = 0$.
>
> *Solve.* $x = 4$ or $x = -3/2$.

### A worked application — the falling baseball, completed

Recall the chapter opener: $h(t) = -16t^2 + 64t$. *When does the ball hit the ground?*

Set $h = 0$: $-16t^2 + 64t = 0$.

GCF: $-16t$. Factor: $-16t(t - 4) = 0$.

Zero Product Property: $-16t = 0$ ⇒ $t = 0$, or $t - 4 = 0$ ⇒ $t = 4$.

The ball is at height zero at $t = 0$ (when it was hit) and at $t = 4$ (when it lands). The flight time is $4$ seconds.

### A geometric application

> **Problem.** The area of a rectangle is $48$ square inches. The length is $2$ inches more than the width. Find the dimensions.

> Let $w$ = width. Then length = $w + 2$. Area: $w(w + 2) = 48$.
>
> Expand: $w^2 + 2w = 48$.
>
> Move to one side: $w^2 + 2w - 48 = 0$.
>
> Factor: need product $-48$, sum $2$. Try $8$ and $-6$: $8 \cdot -6 = -48$, $8 + (-6) = 2$. ✓
>
> $(w + 8)(w - 6) = 0$.
>
> $w = -8$ or $w = 6$. *Width cannot be negative*, so $w = 6$ inches and length = $8$ inches.
>
> *Verify.* $6 \times 8 = 48$. $\checkmark$
>
> **Answer:** *The rectangle is 6 inches by 8 inches.*

The negative solution was rejected on physical grounds. This is normal in word problems: factoring may produce solutions that solve the equation but not the problem. Always check against context.

### The trade-off

The Zero Product Property turns one quadratic equation into two linear equations. The trade-off is that it requires *factored form*, which is not always available. When a quadratic does not factor over the integers, you cannot use this method directly — you need the quadratic formula (chapter 10) or completing the square. Factoring is the fastest method when it works; chapter 10 is the universal backup.

The reflexive note: the Zero Product Property holds because the real numbers form what mathematicians call an *integral domain* — a structure with no zero divisors. The integers, the rationals, and the reals are all integral domains; matrices and modular-arithmetic-with-composite-moduli are not. This chapter's machinery is grounded in that property, and its scope is therefore exactly the situations where the property applies.

### Common misconceptions

- *"If $A \cdot B = 12$, then $A = 12$ or $B = 12$."* No. The Zero Product Property applies only when the product is *zero*. There is no analogous "12 product property."
- *"I can use this method on $x^2 + 5x + 6 = 1$."* Not directly. First subtract 1 from both sides to get $x^2 + 5x + 5 = 0$, then attempt to factor. (This particular polynomial happens not to factor over the integers; see chapter 10.)
- *"Both solutions are always valid."* In pure algebra, yes — both factors give legitimate solutions of the equation. In word problems, one or both may be rejected on physical grounds (negative lengths, negative times, fractional people). Always check.

---

## 5. Integration / Synthesis

A small business owner notices that profit, in dollars, depends on the number of items produced according to:

$$P(x) = -2x^2 + 80x - 600,$$

where $x$ is the number of items produced and $P$ is the profit in dollars. *At what production levels does the business break even — that is, when does $P(x) = 0$?*

This problem uses every concept of the chapter.

### Concept 1 — GCF first

Set $P(x) = 0$: $-2x^2 + 80x - 600 = 0$.

GCF: $-2$. Factor: $-2(x^2 - 40x + 300) = 0$.

Divide both sides by $-2$ (keeps the equation equal to zero):

$$x^2 - 40x + 300 = 0.$$

### Concept 2 — factor the trinomial

Need two numbers whose product is $300$ and sum is $-40$. Both negative (since product is positive and sum is negative). Try factor pairs of $300$ with negative signs:

- $-1$ and $-300$: sum $-301$
- $-2$ and $-150$: sum $-152$
- $-10$ and $-30$: sum $-40$ ✓

Factor: $(x - 10)(x - 30) = 0$.

### Concept 3 — Zero Product Property

$x = 10$ or $x = 30$.

The business breaks even at production levels of $10$ items or $30$ items.

### What does that mean — and what is between them?

Between 10 and 30 items, the parabola $P(x) = -2x^2 + 80x - 600$ is *positive* — the business is making a profit. Outside that range (fewer than 10 or more than 30), the parabola is negative — the business is losing money.

Why? Because the leading coefficient is *negative* ($-2$), the parabola opens *downward*, peaking somewhere in the middle and crossing zero at the two break-even points. The peak — the *maximum profit* — is at $x = 20$, midway between the two break-even points (a property of parabolas you will prove in chapter 10). Maximum profit: $P(20) = -2(400) + 80(20) - 600 = -800 + 1600 - 600 = 200$ dollars.

### What this shows

Three lessons.

*First*, factoring solved a real business question. The two break-even points and the entire profitable range came from one quadratic and one factoring.

*Second*, the same factored form $(x - 10)(x - 30)$ that gave the *roots* will give, in chapter 10, the *vertex* and the *axis of symmetry* of the parabola — the geometric structure of the entire graph. Factoring is not just for solving; it is for *understanding the shape*.

*Third*, this is the limit of factoring's reach. The polynomial $x^2 - 40x + 300$ factored cleanly because $300$ has nice integer factors that sum to $-40$. Most quadratics that arise from real problems do not factor over the integers. Chapter 10's quadratic formula handles the rest.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** Find the GCF of $24a^3b$ and $36a b^2$.

2. **(LO 1, easy)** Factor: $15x^2 - 25x$.

3. **(LO 3, easy)** Factor: $x^2 + 8x + 12$.

4. **(LO 5, easy)** Factor as a difference of squares: $x^2 - 49$.

### Application

5. **(LO 2, medium)** Factor by grouping: $x^3 + 3x^2 + 4x + 12$.

6. **(LO 4, medium)** Factor: $2x^2 + 11x + 12$.

7. **(LO 5, medium)** Factor: $9x^2 - 24x + 16$. *(Hint: this is a perfect square trinomial.)*

8. **(LO 6, medium)** Solve: $x^2 - 7x + 10 = 0$.

### Synthesis

9. **(LO 1 + 5, harder)** Factor *completely*: $3x^3 - 12x$.

10. **(LO 4 + 5, harder)** Factor *completely*: $4x^2 - 32x + 64$.

11. **(LO 6, harder)** Solve: $x^2 + x = 12$. *(Hint: first move everything to one side.)*

12. **(LO 7, harder)** A rectangular garden has area $135$ square feet. The length is $6$ feet more than the width. Find the dimensions.

### Challenge

13. **(LO 5, hard)** Factor $x^4 - 16$ completely. *(Hint: this is a difference of squares; what you get factors further.)*

14. **(LO 6, hard, points to chapter 10)** Try to factor $x^2 + x - 1 = 0$ over the integers. What goes wrong? What does this tell you about the limits of factoring as a solving technique? *Chapter 10 will introduce the quadratic formula, which solves this equation in one step.*

---

## 7. Chapter summary

You came in able to multiply polynomials. You leave able to *unmultiply* them — and to use that to solve equations.

You know that factoring always begins with the GCF: pull out the largest monomial that divides every term, leaving a simpler polynomial inside the parentheses. You know to factor by grouping when a polynomial has four terms and no overall GCF — group, factor each pair, and look for a common binomial.

You can factor trinomials of the form $x^2 + bx + c$ by finding two numbers with product $c$ and sum $b$. You can factor trinomials of the form $ax^2 + bx + c$ using the AC method: find two numbers with product $ac$ and sum $b$, split the middle term, and group. You can recognize the special patterns: difference of squares $a^2 - b^2 = (a + b)(a - b)$, and perfect square trinomials $(a \pm b)^2 = a^2 \pm 2ab + b^2$.

You can use the Zero Product Property — *if a product is zero, at least one factor is zero* — to solve quadratic equations by factoring. You set the equation to zero, factor, set each factor to zero, and solve the resulting linear equations. In word problems, you check each solution against the context and reject those that do not fit physically.

The single most important idea: *factoring multiplies in reverse, and the Zero Product Property turns a quadratic into two linear equations*. That single move — quadratic to two linears — is one of the cleanest reductions in algebra, and it is why factoring is taught before the quadratic formula.

The most common mistake to watch for: not factoring out the GCF first. A trinomial that looks complicated often becomes trivial after the GCF is pulled. Always start with GCF.

What you should be able to teach someone else: how to recognize which factoring technique applies (GCF first, then count terms, then look for patterns), why the Zero Product Property requires the right side of the equation to be zero, and why some quadratics simply do not factor over the integers.

---

## 8. Connections forward

Chapter 8 introduces *rational expressions* — quotients of polynomials. Factoring is the central skill in chapter 8: every operation on rational expressions (simplifying, multiplying, dividing, adding, subtracting, equation-solving) requires factoring the numerator and denominator first. The factoring fluency you build here is exactly what chapter 8 cashes in.

Chapter 9 returns to the relationship between exponents and factoring at the level of square roots and radicals. The difference of squares pattern $a^2 - b^2 = (a + b)(a - b)$ generalizes to $a - b = (\sqrt{a})^2 - (\sqrt{b})^2 = (\sqrt{a} + \sqrt{b})(\sqrt{a} - \sqrt{b})$, and this is the trick used to *rationalize* denominators with square roots in them.

Chapter 10 generalizes the solving-by-factoring method of this chapter to *every* quadratic equation, even those that do not factor over the integers. The quadratic formula is a closed-form expression for the roots that always works, and it is derived by completing the square — which is itself an application of the perfect-square-trinomial pattern from this chapter.

Bring the GCF habit with you. *Pull out what is shared, then look at what remains.* That is good practice in factoring, and it is also good practice in writing, in design, and in life.

---

**What would change my mind:** If a study showed that students who skip the AC method and use trial-and-error exclusively for factoring $ax^2 + bx + c$ developed better long-term flexibility with quadratics, I'd reconsider whether the AC method is pedagogically primary. The AC method is reliable; the question is whether reliability comes at the cost of intuition.

**Still puzzling:** Why does the difference of squares pattern feel so much "cleaner" than other factoring patterns, even to students who have proven it? The middle term cancels, leaving a binomial product — and that cancellation is the entire reason rationalization works in chapter 9, the entire reason completing the square works in chapter 10, and the entire reason matrices have characteristic polynomials in linear algebra. Whether the cleanness is a deep fact about quadratic forms or a notational coincidence, I am not sure.

---

**Tags:** factoring, GCF, zero-product-property, factoring-trinomials, perfect-square-trinomials, difference-of-squares, AC-method, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 7 (modules m82561, m82564, m82566, m82527–m82530), used under CC-BY 4.0. Source content (GCF and grouping, trinomial factoring techniques, special product patterns, Zero Product Property, application examples) derives from OpenStax. Voice, scenes, and pedagogical commentary are original.*
---

## LLM Exercise — Chapter 7: Factoring (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon.
**What you're building this chapter:** factor your polynomial model and use the Zero Product Property to find specific moments when the phenomenon hits a target value (break-even, time-to-zero, equilibrium).
**Tool:** **Claude Project** + **Claude Code** for finding roots numerically as a check.

---

**The Prompt:**

```
Chapter 7 of my Modeling project. Prior sections in this Claude
Project. Chapter 7 taught: factoring techniques — GCF (factor out
greatest common factor first, always); grouping (for four terms);
factoring trinomials ax² + bx + c (when a = 1: find two numbers
that multiply to c and add to b; when a ≠ 1: AC method or trial);
special patterns (difference of squares: a² - b² = (a+b)(a-b);
perfect-square trinomial: a² + 2ab + b² = (a+b)²); the Zero
Product Property — if a × b = 0, then a = 0 OR b = 0 — which
turns factored equations into solvable equations.

Write the brief's "Factoring and Roots" section in 400–600 words.

1. **Set up a real question that requires roots.** Pick a question
   in your phenomenon whose answer is "when does this equal X?"
   Examples:
   - "When does my projectile hit the ground (height = 0)?"
   - "When does my investment account double the starting value
     (P × 2 condition)?"
   - "When does my cumulative cost equal my budget?"
   - "When does my fitness gain plateau (rate of change = 0)?"

   Rewrite the question as a polynomial equation set equal to 0.

2. **Factor the polynomial.** Take the polynomial from Chapter 6
   (or a slight modification for the specific question). Factor
   it using the techniques from this chapter:
   - First: GCF (always check).
   - Then: trinomial factoring, grouping, or special-pattern
     recognition.
   - State which technique you used and why.

3. **Apply the Zero Product Property.** Once factored, set each
   factor equal to zero and solve. State each root in physical
   terms.
   - Root x = 5 might mean "5 years from now."
   - Root x = -3 might be mathematically valid but physically
     meaningless (negative time).
   Discard roots that don't fit your phenomenon's constraints
   (the number-line restrictions you named in Ch 1).

4. **Verify the roots.** Plug each root back into the original
   polynomial. Confirm it equals 0. (This catches algebra
   mistakes — and yes, you will catch some.)

5. **What if it doesn't factor over integers?** The chapter
   noted that some trinomials are "prime" (don't factor over
   integers). If yours doesn't, state that and note that Chapter
   10's quadratic formula will solve it anyway. The factoring
   failure is itself informative.

End with one decision the roots enable. The root at x = 8 might
mean "if I'm patient until year 8, the situation changes" — and
that's a decision a real person could make.
```

---

**What this produces:** A 400–600 word section that takes the Ch 6 polynomial model and finds the moments when the phenomenon hits a specific value. Roots translate to real-world events.

**How to adapt this prompt:**

- *For your own project:* If your phenomenon's polynomial is genuinely complex (high degree, non-integer roots), use Claude Code with SymPy to find roots numerically. The pedagogical work of factoring is still valuable.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* Useful as a verifier. `from sympy import factor, solve; factor(...)` confirms your hand work.
- *For a Claude Project:* Append.

**Connection to previous chapters:** Ch 6 built the polynomial; Ch 7 finds its roots. Chs 6 + 7 + 10 together are the polynomial-to-quadratic backbone.

**Preview of next chapter:** Chapter 8 introduces rational expressions — fractions with polynomials. Your phenomenon may have a rate-of-change dimension (cost per unit, growth rate, density). Rational expressions handle that. Plus the extraneous-solution check: not every algebraic solution is physically valid.


---

##  AI Wayback Machine
**Diophantus of Alexandria** was wrote Arithmetica around 250 CE — the first systematic treatment of equations and factoring.

**Run this:**

```
Who is Diophantus of Alexandria, and how does their work connect to factoring we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"Diophantus of Alexandria"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way Diophantus of Alexandria would have.
- Add a constraint: "Answer including criticisms or limits of Diophantus of Alexandria's methods."

What changes? What gets better? What gets worse?
