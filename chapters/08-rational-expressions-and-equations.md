---
book: prealgebra-bundle
chapter: 08-rational-expressions-and-equations
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 8 (CC-BY 4.0). Modules m82531–m82543, m82560.
status: draft
---

# Suggested titles

1. Rational Expressions: When Variables Land in the Denominator
2. The Algebra of Rates and Ratios
3. Where Polynomials Meet Division — and What Can Go Wrong

---

**TL;DR.** A *rational expression* is a polynomial divided by another polynomial — algebra's analogue of a fraction. The arithmetic mirrors fraction arithmetic from prealgebra: multiplication multiplies tops and bottoms, division flips and multiplies, addition requires a common denominator. Two new wrinkles arrive: the *domain* (values that make the denominator zero are forbidden) and *extraneous solutions* (values that satisfy the cleared equation but not the original).

---

## 1. Chapter opening

Two contractors are paving a parking lot. Each has a paving machine. The first machine, working alone, can finish the job in $6$ hours. The second, alone, in $4$ hours. The owner needs the lot done before the morning rush. *If both machines work together, how long will the job take?*

The intuition that says *the answer is $5$ hours, the average of $4$ and $6$* is wrong. So is the intuition that says *$2$ hours, half of either*. The right answer is somewhere between two and four hours, and to find it requires thinking about *rates*, not times.

Each machine paves a fraction of the lot per hour. Machine 1 paves $\frac{1}{6}$ of the lot per hour. Machine 2 paves $\frac{1}{4}$ per hour. *Rates of work add.* Together, they pave $\frac{1}{6} + \frac{1}{4}$ of the lot per hour. Find the common denominator (12), add: $\frac{2}{12} + \frac{3}{12} = \frac{5}{12}$ of the lot per hour. The two machines together pave five-twelfths of the lot in one hour.

If they pave $5/12$ of the lot per hour, they finish the whole lot in $\frac{12}{5}$ hours — that is, $2.4$ hours, or $2$ hours and $24$ minutes.

The setup that produced this answer involved variables in denominators, fraction-like operations, and a final equation of the form $\frac{1}{6} + \frac{1}{4} = \frac{1}{x}$. That is a *rational equation*. This chapter develops the algebra of expressions like these — *rational expressions*, polynomials over polynomials — and shows how to manipulate them, simplify them, and solve equations involving them.

The trickiest thing in the chapter is also the most useful: *some operations on rational expressions can introduce solutions that are not actually solutions of the original equation*. We will mark this carefully when we get there.

### Learning objectives

By the end of this chapter you should be able to:

- **Identify** a rational expression and **determine** the values for which it is undefined.
- **Simplify** a rational expression by factoring numerator and denominator and canceling common factors.
- **Multiply, divide, add, and subtract** rational expressions, using the LCD when adding or subtracting expressions with unlike denominators.
- **Solve** a rational equation by clearing denominators (multiplying both sides by the LCD), and **check** every candidate solution against the original equation to identify and reject *extraneous solutions*.
- **Set up and solve** word problems that produce rational equations — uniform motion with current, work-rate problems, and ratio/proportion problems.

### Prerequisites

Chapters 1–7. Especially: factoring (chapter 7), exponent rules including negatives and the quotient rule (chapter 6), the general strategy for solving linear equations (chapter 2). Factoring is the central skill in this chapter; if you cannot factor a quadratic in seconds, the whole chapter slows down. Practice chapter 7 before continuing.

### Why this chapter matters

Rates, ratios, and proportions show up everywhere outside algebra class — chemistry concentrations, electrical circuits, fluid flow, financial returns, machine throughput, scaling laws in biology. Almost every one of these involves dividing by a quantity that itself depends on a variable, which is exactly what rational expressions handle. The chapter's specific machinery — the LCD, the canceling, the extraneous-solution check — is what lets you do real arithmetic with these quantities without breaking the rules.

---

## 2. Concept 1 — What rational expressions are, and the domain trap

A **rational expression** is a fraction whose numerator and denominator are polynomials. Examples:

$$\frac{x + 3}{x - 2}, \qquad \frac{x^2 - 4}{x^2 + 5x + 6}, \qquad \frac{1}{x}, \qquad \frac{3x^2 - 2}{1}.$$

The last one is technically a polynomial, so every polynomial is a rational expression with denominator $1$. The chapter focuses on rational expressions with *non-constant* denominators — the cases where the denominator can equal zero for some value of the variable.

### The domain trap — when the denominator is zero

Division by zero is undefined (chapter 1). For a rational expression, the values of the variable that make the denominator equal zero are *not in the domain* — they are forbidden, full stop.

> **Example.** For what values of $x$ is $\dfrac{x + 3}{x - 2}$ undefined?
>
> The denominator is zero when $x - 2 = 0$, i.e., $x = 2$. So the expression is undefined at $x = 2$. The domain is *all real numbers except 2*.

> **Example.** For what values is $\dfrac{x^2 - 4}{x^2 + 5x + 6}$ undefined?
>
> Factor the denominator: $x^2 + 5x + 6 = (x + 2)(x + 3)$. Zero when $x = -2$ or $x = -3$. The domain is all real numbers except $-2$ and $-3$.

The first move on every rational expression: *find where the denominator is zero, and note those values as excluded*. They will matter again at the end of any equation-solving.

### Simplifying rational expressions

To simplify: factor numerator and denominator, then cancel common factors.

> **Example.** Simplify $\dfrac{x^2 - 4}{x^2 + 5x + 6}$.
>
> Factor: $\dfrac{(x + 2)(x - 2)}{(x + 2)(x + 3)}$.
>
> Cancel the $(x + 2)$: $\dfrac{x - 2}{x + 3}$.

The simplified form $\dfrac{x - 2}{x + 3}$ is *equivalent to* the original *for all values where both expressions are defined*. The original was undefined at $x = -2$ and $x = -3$. The simplified form is undefined only at $x = -3$. The values are different: simplification has *expanded* the domain by removing the cancelable factor.

For pure simplification, this is fine — the simplified form is correct. But when we *solve equations*, the difference between the original domain and the simplified domain becomes the source of *extraneous solutions* in §4.

### Cancellation only of common *factors*, never common *terms*

The most expensive error in this chapter is canceling things that look common but are not factors of the whole numerator and denominator. *You can cancel factors that multiply.* You cannot cancel pieces that add.

$$\frac{6x}{6} \to \frac{6 \cdot x}{6} = x \quad \checkmark$$

$$\frac{x + 6}{6} \not\to x + 1 \quad \times$$

The second is a non-cancellation. The $6$ in the numerator is added, not multiplied. To simplify, you would need to factor the numerator first: there is no common factor between $x$ and $6$, so $\dfrac{x + 6}{6}$ is already in simplest form.

The rule: *factor first, then cancel*. Never cancel directly across a sum.

### Multiplying and dividing rational expressions

Multiplication mirrors fraction multiplication: multiply tops, multiply bottoms, simplify.

$$\frac{a}{b} \cdot \frac{c}{d} = \frac{ac}{bd}.$$

Division: invert the second fraction, then multiply.

$$\frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \cdot \frac{d}{c} = \frac{ad}{bc}.$$

> **Example.** Multiply $\dfrac{x^2 - 4}{x + 1} \cdot \dfrac{x + 1}{x - 2}$.
>
> Factor: $\dfrac{(x+2)(x-2)}{x+1} \cdot \dfrac{x+1}{x-2}$.
>
> Cancel: $(x - 2)$ and $(x + 1)$.
>
> Result: $x + 2$.

> **Example.** Divide $\dfrac{x^2 - 9}{x + 2} \div \dfrac{x - 3}{x^2 - 4}$.
>
> Invert and multiply: $\dfrac{x^2 - 9}{x + 2} \cdot \dfrac{x^2 - 4}{x - 3}$.
>
> Factor: $\dfrac{(x+3)(x-3)}{x+2} \cdot \dfrac{(x+2)(x-2)}{x-3}$.
>
> Cancel: $(x - 3)$, $(x + 2)$.
>
> Result: $(x + 3)(x - 2)$.

### The trade-off

Rational expressions extend algebra into the territory of rates and ratios. The trade-off is the *domain*. Every operation must be checked against where the original expression is defined, and the rules for simplification (cancel only factors, never terms) are tighter than for polynomial arithmetic. The procedural cost is high; the descriptive power is higher.

### Common misconceptions

- *"$\dfrac{x + 6}{x + 3}$ simplifies to $\dfrac{6}{3} = 2$."* No — you cannot cancel the $x$'s because they are added in both numerator and denominator, not factored. The expression is already in simplest form.
- *"Once I simplify, the original domain restrictions don't matter."* They do. The original expression's domain is the binding constraint; the simplified form might be defined at points where the original was not.
- *"Multiplying rational expressions is the same as multiplying polynomials."* Almost — but you must factor before multiplying so you can cancel. Multiplying first and trying to simplify after is several times more work.

---

## 3. Concept 2 — Adding, subtracting, and the LCD

Adding and subtracting rational expressions requires *a common denominator* — the same rule you learned in elementary school for ordinary fractions. With rational expressions, the common denominator is harder to find but the principle is identical.

### Common denominator first

$$\frac{a}{c} + \frac{b}{c} = \frac{a + b}{c}, \qquad \frac{a}{c} - \frac{b}{c} = \frac{a - b}{c}.$$

When the denominators match, add or subtract the numerators and keep the denominator. Simplify the result by factoring and canceling.

> **Example.** $\dfrac{3x}{x + 2} - \dfrac{6}{x + 2} = \dfrac{3x - 6}{x + 2} = \dfrac{3(x - 2)}{x + 2}.$ (Final form depends on whether $x - 2$ shares a factor with $x + 2$; here it does not, so we stop.)

### When the denominators differ — the LCD

To add $\dfrac{2}{x} + \dfrac{3}{x + 1}$, the denominators are different. We need a *common* denominator that both can be rewritten over.

The **least common denominator** (LCD) of two rational expressions is the simplest expression divisible by both denominators. To find it:

1. Factor each denominator completely.
2. The LCD is the product of each *distinct factor* raised to the *highest power* it appears in any single denominator.

> **Example.** Find the LCD of $\dfrac{2}{x}$ and $\dfrac{3}{x + 1}$.
>
> Factors: $x$ and $x + 1$ — no shared factor.
>
> LCD: $x(x + 1)$.

> **Example.** Find the LCD of $\dfrac{1}{x^2 - 4}$ and $\dfrac{1}{x^2 - 4x + 4}$.
>
> Factor: $x^2 - 4 = (x + 2)(x - 2)$ and $x^2 - 4x + 4 = (x - 2)^2$.
>
> LCD: take each distinct factor at its highest power: $(x + 2)(x - 2)^2$.

### Adding with the LCD

Once you have the LCD: rewrite each fraction with the LCD as denominator (multiply numerator and denominator of each by whatever factors are missing), then add the numerators.

> **Example.** Add $\dfrac{2}{x} + \dfrac{3}{x + 1}$.
>
> LCD: $x(x + 1)$.
>
> Rewrite: $\dfrac{2(x+1)}{x(x+1)} + \dfrac{3x}{x(x+1)} = \dfrac{2x + 2 + 3x}{x(x+1)} = \dfrac{5x + 2}{x(x+1)}$.

> **Example.** Subtract $\dfrac{x}{x - 1} - \dfrac{2}{x + 1}$.
>
> LCD: $(x - 1)(x + 1)$.
>
> Rewrite: $\dfrac{x(x + 1)}{(x-1)(x+1)} - \dfrac{2(x - 1)}{(x-1)(x+1)} = \dfrac{x^2 + x - 2(x - 1)}{(x-1)(x+1)} = \dfrac{x^2 + x - 2x + 2}{(x-1)(x+1)} = \dfrac{x^2 - x + 2}{(x-1)(x+1)}$.

The numerator $x^2 - x + 2$ does not factor over the integers (its discriminant is $1 - 8 = -7 < 0$). So this is final form.

### A worked combined example

> **Problem.** Simplify $\dfrac{2}{x - 1} + \dfrac{3}{x + 2} - \dfrac{4x}{(x-1)(x+2)}$.
>
> *LCD:* $(x - 1)(x + 2)$.
>
> *Rewrite:*
> $$\dfrac{2(x + 2)}{(x-1)(x+2)} + \dfrac{3(x - 1)}{(x-1)(x+2)} - \dfrac{4x}{(x-1)(x+2)}$$
>
> *Combine numerators:*
> $$\dfrac{2(x+2) + 3(x-1) - 4x}{(x-1)(x+2)} = \dfrac{2x + 4 + 3x - 3 - 4x}{(x-1)(x+2)} = \dfrac{x + 1}{(x-1)(x+2)}.$$

### The trade-off

The LCD method always works for adding or subtracting any number of rational expressions. The trade-off is computational overhead: you factor every denominator, build the LCD, multiply each numerator by the missing factors, distribute, combine like terms, and simplify. For complicated examples, this is twenty steps of bookkeeping. The discipline is its own teaching: *what looks complicated reduces to a sequence of simple moves, each of which you already know.*

### Common misconceptions

- *"I can add tops and bottoms separately without a common denominator."* No. $\dfrac{a}{b} + \dfrac{c}{d} \ne \dfrac{a + c}{b + d}$. That is the most common error in fraction arithmetic from elementary school onward, and it carries forward into rational expressions.
- *"The LCD is always the *product* of the two denominators."* Sometimes — when they share no factors. But when they share factors, the LCD is *less* than the product. Find it correctly to keep the arithmetic clean.
- *"I can cancel terms in the numerator after adding."* Cancel only common *factors*, not common terms. Factor first, then cancel.

---

## 4. Concept 3 — Solving rational equations and the extraneous solution risk

A **rational equation** is an equation containing one or more rational expressions. To solve it, *clear the denominators*: multiply both sides by the LCD of every fraction in the equation. After that, the equation is polynomial, and chapter 2 (linear) or chapter 7 (quadratic by factoring) takes over.

### The procedure

1. **Identify the LCD** of all denominators.
2. **Note the values** that make any denominator zero — these are *forbidden* and must be excluded from any solution.
3. **Multiply both sides** by the LCD; distribute carefully on every side.
4. **Solve** the resulting polynomial equation.
5. **Check** every candidate solution: does it lie in the original domain? If a candidate makes any original denominator zero, it is *extraneous* and must be rejected.

> **Example.** Solve $\dfrac{1}{x - 2} = \dfrac{3}{x + 4}$.
>
> *Forbidden values:* $x = 2$ and $x = -4$.
>
> *LCD:* $(x - 2)(x + 4)$. Multiply both sides:
>
> $$(x - 2)(x + 4) \cdot \dfrac{1}{x - 2} = (x - 2)(x + 4) \cdot \dfrac{3}{x + 4}$$
>
> Cancel:
>
> $$x + 4 = 3(x - 2).$$
>
> *Solve:* $x + 4 = 3x - 6$, so $-2x = -10$, $x = 5$.
>
> *Check:* $5$ is not $2$ or $-4$, so it is in the domain. Verify in the original: $\dfrac{1}{5 - 2} = \dfrac{1}{3}$ and $\dfrac{3}{5 + 4} = \dfrac{3}{9} = \dfrac{1}{3}$. $\checkmark$
>
> **Solution:** $x = 5$.

### Why extraneous solutions can arise

When you multiply both sides of an equation by an expression containing the variable, you have done something that is *not always reversible*. If the expression you multiplied by is zero for some value of the variable, then that value cannot be tested against the original — the original is undefined there.

In the language of chapter 2: multiplying both sides by a nonzero quantity preserves equality. Multiplying by an expression that *could* be zero may not. The solving procedure may produce candidates that satisfy the *cleared* polynomial equation but make the *original* equation undefined.

> **Example.** Solve $\dfrac{2}{x - 3} + \dfrac{1}{x} = \dfrac{x + 3}{x(x - 3)}$.
>
> *Forbidden values:* $x = 0$ and $x = 3$.
>
> *LCD:* $x(x - 3)$. Multiply:
>
> $$x(x - 3) \cdot \dfrac{2}{x - 3} + x(x - 3) \cdot \dfrac{1}{x} = x(x - 3) \cdot \dfrac{x + 3}{x(x - 3)}$$
>
> Simplify each term:
>
> $$2x + (x - 3) = x + 3.$$
>
> *Solve:* $3x - 3 = x + 3$, so $2x = 6$, $x = 3$.
>
> *Check:* $x = 3$ makes the denominators of the original equation zero. It is *extraneous* and must be rejected.
>
> **Solution:** *no solution*. (The equation has no value of $x$ that satisfies it within the original domain.)

The check at the end is not optional. *Every* rational equation requires it.

### The procedure, formalized

The lesson of the extraneous-solution case is that *clearing denominators is not always a reversible step*. In chapter 2, every step of the general strategy was reversible — we noted this then. Multiplying by an expression that could be zero is the first time in the book a solving step is not.

This is why chapter 2 forbade dividing both sides of an equation by a variable. It is the same issue, viewed from the other side: dividing by zero hides solutions; multiplying by zero introduces false ones.

### A worked application — back to the paving lot

Recall the cold open: two paving machines, $6$ hours and $4$ hours alone. *How long together?*

Let $t$ = hours for both machines together. Each contributes its rate.

$$\frac{1}{6} + \frac{1}{4} = \frac{1}{t}.$$

This is a rational equation. *Forbidden:* $t = 0$.

*LCD:* $12t$. Multiply:

$$12t \cdot \dfrac{1}{6} + 12t \cdot \dfrac{1}{4} = 12t \cdot \dfrac{1}{t}$$
$$2t + 3t = 12$$
$$5t = 12$$
$$t = \dfrac{12}{5} = 2.4 \text{ hours}.$$

*Check:* $2.4$ is not $0$. Verify in original: $\dfrac{1}{6} + \dfrac{1}{4} = \dfrac{2 + 3}{12} = \dfrac{5}{12}$, and $\dfrac{1}{2.4} = \dfrac{1}{12/5} = \dfrac{5}{12}$. $\checkmark$

**Answer:** *Two hours and 24 minutes.*

### Proportions

A **proportion** is a special rational equation of the form $\dfrac{a}{b} = \dfrac{c}{d}$. Cross-multiplying — a shortcut that comes from clearing denominators — gives $ad = bc$. Useful for similar figures, scale drawings, and ratios in word problems. (Always check that the resulting equation has solutions in the original domain.)

### The trade-off

Rational equations let you solve problems involving rates, ratios, and proportions — work problems, mixture problems with concentration changes, motion in a current, electrical circuits in parallel, optical lens equations. The trade-off is the *check*. Every solution must be tested against the original domain, and an extraneous solution is not a contradiction in the math — it is a signal that an irreversible step (clearing denominators) introduced a candidate the original never permitted.

The reflexive note: this is the first chapter where solving steps are *not all reversible*. Chapters 9 (radical equations, where squaring both sides can introduce false solutions) and 10 (occasionally, when working with absolute value or higher-degree equations) will repeat the lesson. The pattern is the same: when a step might not be reversible, *check every candidate against the original*.

### Common misconceptions

- *"If my candidate solves the cleared equation, it solves the original."* Not necessarily — extraneous solutions exist. Always check.
- *"Cross-multiplying is a separate technique from clearing denominators."* It is the same technique applied to a proportion. The shortcut hides the LCD work but is mathematically identical.
- *"$x = 0$ is always a forbidden value."* Only when $x$ appears in a denominator. If the equation has no $x$ in any denominator, $x = 0$ is fine.

---

## 5. Integration / Synthesis

A boat travels at a constant speed in still water. On a river with a current of $2$ mph, the boat goes $24$ miles downstream in the same time it takes to go $16$ miles upstream. *Find the boat's speed in still water.*

This problem combines all three concepts.

### Concept 1 — set up rational expressions

Let $b$ = boat speed in still water (mph). Downstream speed: $b + 2$. Upstream speed: $b - 2$.

Time = distance / rate.

Time downstream: $\dfrac{24}{b + 2}$. Time upstream: $\dfrac{16}{b - 2}$.

The two times are equal:

$$\frac{24}{b + 2} = \frac{16}{b - 2}.$$

This is a rational equation.

### Concept 2 — clear denominators (Concept 3 of the chapter)

*Forbidden:* $b = -2$ and $b = 2$. Note for later.

LCD: $(b + 2)(b - 2)$. Multiply both sides:

$$(b + 2)(b - 2) \cdot \dfrac{24}{b + 2} = (b + 2)(b - 2) \cdot \dfrac{16}{b - 2}$$

Cancel:

$$24(b - 2) = 16(b + 2).$$

Distribute:

$$24b - 48 = 16b + 32.$$

Solve:

$$8b = 80, \quad b = 10.$$

### Concept 3 — check

$10$ is not $-2$ or $2$. Verify in original:

Downstream: $\dfrac{24}{10 + 2} = \dfrac{24}{12} = 2$ hours.
Upstream: $\dfrac{16}{10 - 2} = \dfrac{16}{8} = 2$ hours. $\checkmark$

**Answer:** *The boat's speed in still water is 10 mph.*

The same problem in chapter 3 produced a quadratic equation; in chapter 5 it became a system of linear equations. Here it is a rational equation with two-line setup. *Different formulations, same answer.* Choose the form that uses the fewest unknowns and the simplest algebra; this version was both.

### What this shows

Rational equations are a third strategy for problems that involve ratios, rates, and time-distance. The chapter 5 technique (system of linear equations) and the chapter 8 technique (single rational equation) are interchangeable on motion problems with a current; the choice between them is a matter of taste and convenience. The chapter 3 technique (one quadratic equation in one unknown), in contrast, often arises when the structure of the problem requires it — and that is one path that produces *quadratic* rather than *linear* algebra.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** For what values is $\dfrac{x + 1}{x - 5}$ undefined?

2. **(LO 1, easy)** Simplify: $\dfrac{6x^2}{12x}$.

3. **(LO 2, easy)** Simplify by factoring: $\dfrac{x^2 - 9}{x + 3}$.

### Application

4. **(LO 2, medium)** Multiply: $\dfrac{x^2 - 1}{x + 3} \cdot \dfrac{x + 3}{x + 1}$.

5. **(LO 3, medium)** Add: $\dfrac{3}{x} + \dfrac{2}{x + 1}$.

6. **(LO 3, medium)** Subtract: $\dfrac{x}{x - 2} - \dfrac{4}{x - 2}$.

7. **(LO 3, medium)** Add: $\dfrac{1}{x - 1} + \dfrac{2}{x^2 - 1}$. *(Hint: factor the second denominator.)*

### Synthesis

8. **(LO 4, harder)** Solve: $\dfrac{2}{x} + \dfrac{3}{x + 1} = \dfrac{5}{x(x + 1)}$. Check for extraneous solutions.

9. **(LO 4, harder)** Solve: $\dfrac{x}{x - 3} - \dfrac{3}{x - 3} = 2$. *(Watch the domain.)*

10. **(LO 5, harder)** A printer can complete a print run alone in $9$ hours. With a second, faster printer, the same run takes $6$ hours. How long does the faster printer alone take? *(Hint: rates add.)*

### Challenge

11. **(LO 4, hard)** Solve: $\dfrac{2}{x - 1} + \dfrac{1}{x + 1} = \dfrac{6}{x^2 - 1}$. *(Notice that $x^2 - 1 = (x-1)(x+1)$, the LCD.)* Identify any extraneous solutions.

12. **(LO 5, hard, points to chapter 9)** A car travels at a constant speed. On a $480$-mile trip, if the car had averaged $10$ mph more, the trip would have taken $1$ hour less. Find the speed. *(Setup gives a rational equation that simplifies to a quadratic. Solve using chapter 7 factoring or chapter 10 quadratic formula.)*

13. **(LO 4, hard)** Show that *every* extraneous solution to a rational equation must be a value that makes some original denominator equal to zero. Why does this guarantee that checking against the original domain is the *only* extra step required?

---

## 7. Chapter summary

You came in able to factor polynomials. You leave able to do arithmetic on *fractions whose numerators and denominators are polynomials*.

You know that a rational expression is a polynomial divided by another polynomial, that the values making the denominator zero are *forbidden*, and that the first step on every rational expression is to identify those values. You can simplify a rational expression by factoring numerator and denominator and canceling common factors, and you know that simplification can *expand* the domain — the simplified form is correct for values where both expressions are defined, but the *original* domain is the binding constraint.

You can multiply rational expressions by multiplying tops and bottoms after factoring, divide by inverting and multiplying, and add or subtract by finding the LCD, rewriting each fraction with that denominator, and combining numerators. You know that the LCD is the product of each *distinct factor* of any denominator, raised to the *highest power* it appears anywhere.

You can solve a rational equation by clearing denominators with the LCD, then solving the resulting polynomial equation. You know that this step is *not always reversible* — multiplying by an expression that could be zero may introduce solutions that satisfy the cleared equation but not the original. You always check every candidate against the original domain and reject extraneous solutions.

The single most important idea: *rational expressions extend algebra into the territory of rates, ratios, and proportions, and the price of admission is the domain check*. Every operation must respect the values where the expression is defined.

The most common mistake to watch for: canceling terms instead of factors. *Factor first, then cancel.* Never cancel directly across an addition.

What you should be able to teach someone else: why simplifying a rational expression is not the same as evaluating one (the domain may differ), why extraneous solutions can arise from clearing denominators but never from the chapter 2 strategy, and why the LCD is the product of distinct factors at their highest powers.

---

## 8. Connections forward

Chapter 9 introduces *radicals* — expressions involving square and higher roots. The radical equation $\sqrt{x + 1} = x - 5$ is solved by squaring both sides, which (like clearing denominators in this chapter) is *not always reversible*. Squaring can introduce extraneous solutions, and the lesson of chapter 8 — *check every candidate against the original* — applies word for word in chapter 9.

Chapter 10 generalizes the solving methods of chapter 7 (factoring) to *every* quadratic equation. Some of the equations you encounter in real-world rational-equation problems (e.g., the speed problem in challenge exercise 12) reduce to quadratics that do not factor over the integers; chapter 10's quadratic formula handles those cases.

The deeper point: *some algebraic moves are reversible, and some are not*. The reversible moves of chapter 2 (add, subtract, multiply by nonzero, divide by nonzero) preserve solution sets exactly. The irreversible moves you have started to meet — clearing denominators, squaring both sides — preserve solutions but can introduce false candidates. The defense, in every case, is the check.

Bring the factoring fluency with you. Chapter 8's machinery is built on chapter 7's, and so is the rest of the algebra you have not yet seen.

---

**What would change my mind:** If a careful study showed that students who are taught rational expressions *without* the formal LCD method (instead just always multiplying out the product of denominators, then simplifying) develop equally strong fluency with less procedural overhead, I'd reconsider whether the LCD method is pedagogically essential for elementary algebra or simply traditional. The LCD method generalizes more cleanly to advanced topics, but for the cases in this chapter, it is not strictly necessary.

**Still puzzling:** Why does the extraneous-solution phenomenon catch students by surprise even after they have been warned? The structural reason — clearing denominators is not always reversible — is short and clean. But year after year, students treat the check as a formality and miss the case when it actually fires. Whether this is a pedagogical failure (we under-emphasize the irreversibility) or a generic feature of how procedural fluency develops, I am not sure.

---

**Tags:** rational-expressions, rational-equations, LCD, extraneous-solutions, work-problems, motion-with-current, domain, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 8 (modules m82531–m82543, m82560), used under CC-BY 4.0. Source content (rational expression definitions, simplification rules, LCD method, equation-solving with extraneous-solution checks, work and motion applications) derives from OpenStax. Voice, scenes, and pedagogical commentary are original.*
---

## LLM Exercise — Chapter 8: Rational Expressions and Equations (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon.
**What you're building this chapter:** the rational-expression dimension — rates, densities, averages — applied to your phenomenon, plus the discipline of catching extraneous solutions.
**Tool:** **Claude Project**.

---

**The Prompt:**

```
Chapter 8 of my Modeling project. Prior sections in this Claude
Project. Chapter 8 taught: rational expressions (fractions with
polynomials); the domain trap (excluded values where the
denominator is zero — must always be named); simplification
(factor numerator and denominator; cancel common factors); LCD
operations for adding/subtracting; multiplying (multiply
numerators × multiply denominators, then simplify); dividing
(multiply by reciprocal); solving rational equations (multiply
through by LCD to clear fractions); extraneous solutions
(algebraic solutions that aren't valid because they produce
division by zero or violate the problem's constraints).

Write the brief's "Rate, Density, or Average" section in 400–600
words.

1. **The rational quantity.** What rate, density, average, or
   per-unit measure does your phenomenon have? Examples:
   - Cost per unit: total cost / quantity.
   - Average growth: total growth / time elapsed.
   - Pace: distance / time.
   - Efficiency: output / input.
   - Density: amount / area or amount / volume.
   - Saturation: current value / max value.

   Pick one. Express it as a rational expression.

2. **Identify the domain trap.** Where does the denominator equal
   zero? Those values are excluded. State them explicitly.
   "Time can't be zero in pace = distance/time." Physical
   interpretation matters as much as the algebraic exclusion.

3. **Operate on the rational expression.** Pick a question that
   requires manipulating the rational expression. Examples:
   - Combine two rates with LCD ("average pace over two intervals
     with different paces").
   - Solve for a parameter using cross-multiplication ("given
     this rate and this distance, what time?").
   - Simplify a complex fraction (fraction of fractions).

   Show every step.

4. **Solve a rational equation.** Pose and solve an equation
   involving rational expressions:
   - "When does cost-per-unit drop below $X?"
   - "When does average growth match initial growth?"
   - "At what point is the rate of change of the phenomenon equal
     to a specific target?"

   Multiply through by the LCD to clear fractions. Solve the
   resulting polynomial. Apply the Zero Product Property if
   factoring (from Ch 7).

5. **Check for extraneous solutions.** Plug each candidate
   solution back into the ORIGINAL rational equation. If it
   produces division by zero (the candidate equals an excluded
   value), discard it. If it violates the phenomenon's constraints
   (negative time, negative quantity), discard it. State which
   candidates survived and which didn't.

End with the physical interpretation of the surviving solution.
The point of all this algebra is a decision someone could make.
```

---

**What this produces:** A 400–600 word section that adds the rate/density/average dimension to your model. The extraneous-solution discipline is the chapter's hardest discipline; the section earns its keep by catching at least one false candidate.

**How to adapt this prompt:**

- *For your own project:* If your phenomenon is genuinely rate-free (one-time event, no per-unit measure), force a rate by introducing one (cost per time, value per attempt). The chapter's techniques are valuable regardless.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* Optional sidecar for symbolic simplification.
- *For a Claude Project:* Append.

**Connection to previous chapters:** Ch 7's factoring + Ch 8's rational-equation solving are paired — factoring the cleared-fraction polynomial is the standard solve path.

**Preview of next chapter:** Chapter 9 adds radicals — square roots and higher roots. Many real-world phenomena involve square roots (Pythagorean distance, period of a pendulum, geometric mean, standard deviation). The squaring trap surfaces: squaring both sides can introduce extraneous solutions.


---

## AI Wayback Machine

**Bhāskara II** was 12th-century Indian mathematician whose Līlāvatī systematized rational expressions and arithmetic.

**Run this:**

```
Who is Bhāskara II, and how does their work connect to rational expressions we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"Bhāskara II"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way Bhāskara II would have.
- Add a constraint: "Answer including criticisms or limits of Bhāskara II's methods."

What changes? What gets better? What gets worse?
