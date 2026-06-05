---
book: prealgebra-bundle
chapter: 06-polynomials
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 6 (CC-BY 4.0). Modules m82500–m82514.
status: draft
---

# Suggested titles


## TL;DR

- book: prealgebra-bundle chapter: 06-polynomials voice: Attenborough × Feynman v1.
- You will practice Identify polynomials, classify them as monomials, binomials, or trinomials, and determine their degree; Add and subtract polynomials by combining like terms; Apply the exponent rules — product, power, power-of-product, quotient — to simplify expressions.
- The chapter moves through Chapter opening, Learning objectives, Prerequisites, Why this chapter matters, and related ideas.

1. Polynomials: The Language of Non-Linear Scaling
2. Beyond the Line: Many-Term Expressions and How They Behave
3. Exponents, Polynomials, and the Multiplication of Sums

---

**TL;DR.** A polynomial is a sum of terms — each term a constant multiplied by a power of a variable. Polynomials capture relationships that *do not* scale linearly: areas, volumes, projectile heights, growth curves. This chapter teaches you to identify them, classify them, and perform the four arithmetic operations on them, with the exponent rules doing most of the heavy lifting.

---

## 1. Chapter opening

A pizza shop posts two prices on the menu. A 10-inch pizza is \$12. A 14-inch pizza is \$22. The 14-inch is forty percent wider than the 10-inch, but it costs eighty-three percent more. *Why?*

Because pizza is sold by *area*, not by diameter. The area of a circle is $\pi r^2$ — proportional to the square of the radius, not the radius itself. A 14-inch pizza has area $\pi \cdot 7^2 = 49\pi$ square inches; a 10-inch has $\pi \cdot 5^2 = 25\pi$. The bigger pizza has $49 / 25 = 1.96$ times the area, almost double the food. Eighty-three percent more cost for ninety-six percent more pizza is a slightly better deal than the small.

The shop owner's price difference is not arbitrary. It is the geometry of a square. Area scales with the *square* of length, not length itself. Volume scales with the *cube*. Projectile motion involves the square of time. The surface area of an animal scales with weight to the *two-thirds* power. Almost no useful relationship in the world is exactly linear; almost all of them are *polynomial* — combinations of variables raised to whole-number powers.

This chapter is about that family of expressions. *Polynomials.* You will learn to identify them, classify them by their structure, and perform arithmetic with them — addition, subtraction, multiplication, division — using the exponent rules that make multiplication of powers work.

### Learning objectives

By the end of this chapter you should be able to:

- **Identify** polynomials, **classify** them as monomials, binomials, or trinomials, and **determine** their degree.
- **Add and subtract** polynomials by combining like terms.
- **Apply** the exponent rules — product, power, power-of-product, quotient — to simplify expressions.
- **Multiply** monomials, multiply a polynomial by a monomial, and multiply two polynomials (including using the FOIL pattern for two binomials).
- **Recognize** and use the **special product patterns** for binomial squares and the product of conjugates.
- **Divide** a polynomial by a monomial, and divide a polynomial by a binomial using polynomial long division.
- **Work** with zero exponents, negative exponents, and **scientific notation**.

### Prerequisites

Chapters 1–5. In particular, the distributive property from chapter 1 and the order of operations. The combining-like-terms move recurs constantly. You should be comfortable with negative numbers, fractions, and the manipulation of variable expressions.

### Why this chapter matters

Three reasons. First, polynomials describe everything that does not scale linearly — area, volume, kinetic energy, falling objects, compound growth, signal processing. The set of relationships you can describe with linear equations alone is small; with polynomials, vast. Second, the exponent rules are the multiplication tables of algebra. They show up in every later chapter and most of the rest of mathematics — calculus, statistics, computer algebra, number theory. Third, polynomial *factoring* (the next chapter) and polynomial *equations* (chapter 10) cannot exist without the polynomial machinery this chapter builds.

---

## 2. Concept 1 — What polynomials are

Three words. *Polynomial*, *monomial*, *binomial*. Each comes from Greek and Latin roots that point at the structure: *poly-* (many), *mono-* (one), *bi-* (two), and *-nomial* (from Latin *nōmen*, name) — *names*, in the sense of named pieces. A polynomial is a *many-named* expression. A monomial is a *one-named* expression. A binomial is a *two-named* expression.

### Definition

A **monomial** is a single term that is either a constant, a variable, or a product of constants and variables raised to whole-number powers. *No negative exponents, no fractional exponents, no variables in denominators.*

Examples of monomials: $5$, $x$, $-3x^2$, $7xy^3$, $\dfrac{x^2}{4}$ (the $4$ is a constant; the variable is not in a denominator).

Not monomials: $x^{-2}$, $\sqrt{x}$, $\dfrac{2}{x}$, $x^{1/2}$.

A **polynomial** is a finite sum of monomials. *Polynomials with one term are called monomials; with two terms, binomials; with three terms, trinomials.* Polynomials with more terms are simply called polynomials.

### Degree

The **degree** of a monomial is the sum of the exponents of its variables. The degree of $7xy^3$ is $1 + 3 = 4$. The degree of $-3x^2$ is $2$. The degree of a constant like $5$ is $0$ (you can think of it as $5x^0$).

The **degree of a polynomial** is the largest degree among its terms. The polynomial $4x^3 + 2x^2 - 7x + 1$ has degree $3$ — the term $4x^3$ contributes degree 3, and that is the highest.

The degree-$1$ polynomials are *linear* (chapter 4). Degree-$2$ polynomials are *quadratic* (chapter 10). Degree-$3$ are *cubic*. Degree-$4$, *quartic*. The degree of a polynomial determines, among other things, the maximum number of times its graph can cross the x-axis — a fact you will use heavily in chapter 10 and in any later course that graphs polynomials.

### A worked classification

| Expression | Type | Degree |
| --- | --- | --- |
| $5x^2 - 3x + 7$ | trinomial | 2 |
| $4x^3$ | monomial | 3 |
| $x + 1$ | binomial | 1 |
| $-3$ | monomial (constant) | 0 |
| $a + b - c + 2d$ | polynomial (4 terms) | 1 |
| $5x^{-2}$ | not a polynomial | — |

### Adding and subtracting polynomials

Polynomial addition and subtraction is *combining like terms*. Two terms are *like* (chapter 1) if they have the same variable part — same letters, same exponents. Coefficients add or subtract; variable parts stay the same.

> **Example.** Add $(3x^2 - 2x + 5) + (x^2 + 4x - 7)$.
>
> Group like terms: $(3x^2 + x^2) + (-2x + 4x) + (5 - 7)$.
>
> Combine: $4x^2 + 2x - 2$.

> **Example.** Subtract $(5x^2 + 3x - 1) - (2x^2 - 7x + 4)$.
>
> Distribute the negative: $5x^2 + 3x - 1 - 2x^2 + 7x - 4$.
>
> Combine: $3x^2 + 10x - 5$.

The *distribute the negative* step is where most subtraction errors live. Every term inside the second parentheses gets its sign flipped, not just the first one. Mark the flip term-by-term until it becomes automatic.

### Evaluating a polynomial

To evaluate a polynomial at a specific value of the variable, substitute and simplify (chapter 1's order of operations).

> **Example.** Evaluate $2x^2 - 3x + 4$ at $x = -2$.
>
> $2(-2)^2 - 3(-2) + 4 = 2(4) - (-6) + 4 = 8 + 6 + 4 = 18.$

The trap: $(-2)^2$ is $+4$, not $-4$. Square *after* the negative sign is included; the parentheses force this. Without them, $-2^2$ would mean $-(2^2) = -4$. Notation matters.

### The trade-off

Polynomial expressions extend the language of algebra beyond linear relationships, at the cost of more complex arithmetic. Adding two linear expressions takes a moment; adding two cubic polynomials of three terms each takes nine pairings, each of which requires checking whether the terms are like. The trade-off is worth taking — most non-trivial physical and economic models are at least quadratic — but it forces a kind of bookkeeping discipline that the linear chapters did not require.

### Common misconceptions

- *"$3x^2$ and $3x$ are like terms because they share an $x$."* No. Different exponents, different terms. They cannot be combined.
- *"The degree of a polynomial is the *number* of terms."* No. The degree is the highest exponent on the variable (or sum of exponents in multi-variable terms). A polynomial with one term can have any degree.
- *"$x^2 + x^3$ simplifies to $x^5$."* No. Adding does not multiply exponents, and these are not even like terms. The expression is already in simplest form.

---

## 3. Concept 2 — The exponent rules and multiplying polynomials

Multiplication of polynomials is built on the multiplication of *powers*. The exponent rules are five short statements that govern every later chapter's manipulation. Memorize them once; use them forever.

### The five rules

For any nonzero base $a$ and any whole numbers $m$ and $n$:

**Product Rule.** $a^m \cdot a^n = a^{m+n}$. *Multiplying powers of the same base adds the exponents.*

Why: $a^m$ is $a$ multiplied by itself $m$ times; $a^n$ is $a$ multiplied by itself $n$ times. Multiply them: $a$ multiplied by itself $m + n$ times. So $a^m \cdot a^n = a^{m+n}$.

**Power Rule.** $(a^m)^n = a^{mn}$. *A power of a power multiplies the exponents.*

Why: $(a^m)^n$ is $a^m$ multiplied by itself $n$ times, which is $a$ multiplied by itself $m \cdot n$ times.

**Product-to-Power Rule.** $(ab)^n = a^n b^n$. *A power of a product is the product of the powers.*

Why: $(ab)^n$ is $ab$ multiplied by itself $n$ times. Each factor of $a$ stays with each factor of $a$; each factor of $b$ stays with each factor of $b$. Rearrange (commutative property, chapter 1) and you get $a^n b^n$.

**Quotient Rule.** $\dfrac{a^m}{a^n} = a^{m-n}$ (for $m > n$, with $a \ne 0$). *Dividing powers of the same base subtracts the exponents.*

Why: every factor in the numerator that matches a factor in the denominator cancels. After all cancellations, $m - n$ factors of $a$ remain in the numerator.

**Zero-Exponent Rule.** $a^0 = 1$ (for $a \ne 0$). *Anything (nonzero) to the zero power is one.*

Why: by the quotient rule, $\dfrac{a^m}{a^m} = a^{m-m} = a^0$. But $\dfrac{a^m}{a^m} = 1$ (any nonzero number divided by itself). So $a^0 = 1$. Notice $0^0$ is *undefined* — the argument requires a nonzero base.

### Negative exponents (preview)

The rules above were stated for whole-number exponents, but they generalize: $a^{-n} = \dfrac{1}{a^n}$. Negative exponents are reciprocals.

Why: by the quotient rule, $\dfrac{a^m}{a^n} = a^{m-n}$. If $n > m$, then $m - n$ is negative, but the left side is $\dfrac{1}{a^{n-m}}$ by canceling. So $a^{-(n-m)} = \dfrac{1}{a^{n-m}}$, which is $a^{-k} = \dfrac{1}{a^k}$ for any positive $k$.

We will use this in §4 for scientific notation.

### Multiplying monomials

To multiply two monomials: multiply the coefficients, then apply the product rule to like-base variables.

> **Example.** $(3x^2)(5x^4) = 15 x^{2+4} = 15x^6.$

> **Example.** $(-2a^3 b^2)(4a b^5) = -8 \cdot a^{3+1} \cdot b^{2+5} = -8 a^4 b^7.$

### Multiplying a polynomial by a monomial

Use the distributive property (chapter 1). Multiply the monomial by every term of the polynomial.

> **Example.** $3x(2x^2 - 5x + 4) = 6x^3 - 15x^2 + 12x.$

### Multiplying two binomials — the FOIL pattern

To multiply $(a + b)(c + d)$, distribute every term in the first factor with every term in the second:

$$(a + b)(c + d) = ac + ad + bc + bd.$$

The mnemonic *FOIL* — First, Outer, Inner, Last — names the four products in the order the distribution generates them:

- **F**irst: $a \cdot c$
- **O**uter: $a \cdot d$
- **I**nner: $b \cdot c$
- **L**ast: $b \cdot d$

> **Example.** $(x + 3)(x - 5)$ = First $x^2$ + Outer $-5x$ + Inner $3x$ + Last $-15$ = $x^2 - 2x - 15$.

FOIL is a convenience, not a separate rule. It is the distributive property applied twice. Once you can multiply a polynomial by a polynomial in general (by distributing every term in one against every term in the other), FOIL becomes redundant. But for binomials, FOIL is the fastest path.

### Special products — patterns worth memorizing

Two products appear so often that recognizing them saves real time.

**Binomial Square Pattern.**

$$(a + b)^2 = a^2 + 2ab + b^2$$
$$(a - b)^2 = a^2 - 2ab + b^2.$$

The square of a binomial is the *square of the first*, plus or minus *twice the product*, plus the *square of the second*. The middle term is doubled — this is the trap. $(a + b)^2$ is *not* $a^2 + b^2$; the cross term $2ab$ matters.

> **Example.** $(x + 4)^2 = x^2 + 2 \cdot x \cdot 4 + 16 = x^2 + 8x + 16.$

**Product of Conjugates Pattern.**

$$(a + b)(a - b) = a^2 - b^2.$$

The two binomials $a + b$ and $a - b$ are called *conjugates*. Their product is the *difference of squares* — the cross terms cancel. This is the cleanest cancellation in algebra and the engine of an entire factoring technique you will meet in chapter 7.

> **Example.** $(x + 5)(x - 5) = x^2 - 25.$

### A worked example combining several rules

> **Problem.** Simplify $(2x^3)^2 (3x)^2 - (4x^4)^2$.
>
> *Step 1.* Apply the product-to-power rule term by term: $(2x^3)^2 = 4x^6$, $(3x)^2 = 9x^2$, $(4x^4)^2 = 16x^8$.
>
> *Step 2.* Substitute: $4x^6 \cdot 9x^2 - 16x^8$.
>
> *Step 3.* Multiply the first product (product rule on the $x$): $36 x^{6+2} - 16x^8 = 36x^8 - 16x^8$.
>
> *Step 4.* Combine like terms: $20x^8.$

### The trade-off

The exponent rules turn polynomial multiplication from a hand-counted bookkeeping problem into a one-line application of three or four rules. The trade-off is that the rules look like arbitrary symbol-shuffling unless you have internalized why they hold. A student who memorizes "multiplying powers adds exponents" without picturing why ends up applying the rule when it does not apply (e.g., trying to use it on $2^x \cdot 3^x$, where the bases are different) or failing to apply it when it does. Memorize the rules; understand why each one holds; you will rarely misapply.

### Common misconceptions

- *"$x^2 + x^2 = x^4$."* No. Like terms add their *coefficients*, not their exponents: $x^2 + x^2 = 2x^2$. The product rule applies only to *multiplication*.
- *"$(a + b)^2 = a^2 + b^2$."* No. The cross term $2ab$ matters. Always.
- *"$(a^m)^n = a^{m+n}$."* No. The power rule *multiplies* the exponents, not adds. The product rule adds. Confusing the two is one of the top three errors in this chapter.

---

## 4. Concept 3 — Division of polynomials, integer exponents, and scientific notation

Polynomial division comes in two flavors. Dividing by a monomial is straightforward — distribute the division across each term. Dividing by a binomial requires *polynomial long division*, an algorithm that mirrors the long division you learned for integers in elementary school.

### Dividing a polynomial by a monomial

To divide each term of the polynomial by the monomial: split the fraction term by term and apply the quotient rule.

$$\frac{a + b + c}{d} = \frac{a}{d} + \frac{b}{d} + \frac{c}{d}.$$

> **Example.** $\dfrac{12x^4 - 8x^2 + 6x}{2x} = \dfrac{12x^4}{2x} - \dfrac{8x^2}{2x} + \dfrac{6x}{2x} = 6x^3 - 4x + 3.$

### Polynomial long division

To divide $P(x)$ by $D(x)$ where $D$ is a polynomial of degree $\ge 1$: arrange both in descending order of degree (filling in any missing terms with zero coefficients), then proceed as in arithmetic long division.

> **Example.** Divide $x^2 + 5x + 6$ by $x + 2$.

Set up:
$$\begin{array}{r}
\phantom{x + 2 \,\big| \;} x + 3 \\
x + 2 \,\big| \, \overline{x^2 + 5x + 6} \\
\end{array}$$

*Step 1.* Divide the leading term $x^2$ by the leading divisor $x$: $x$. Write $x$ above.
*Step 2.* Multiply $x$ by the divisor $x + 2$: $x^2 + 2x$. Subtract from $x^2 + 5x$: $3x$. Bring down the $+6$: $3x + 6$.
*Step 3.* Divide $3x$ by $x$: $3$. Write $+3$ above.
*Step 4.* Multiply $3$ by $x + 2$: $3x + 6$. Subtract: $0$.

Quotient: $x + 3$. Remainder: $0$. So $x^2 + 5x + 6 = (x + 2)(x + 3)$ — a result you will see again in chapter 7 as the factoring of $x^2 + 5x + 6$.

When the remainder is nonzero, the result is written as

$$\frac{P(x)}{D(x)} = Q(x) + \frac{R(x)}{D(x)},$$

where $Q$ is the quotient and $R$ is the remainder.

### Integer exponents — the full table

We previewed negative exponents in §3. Now collect the rules for *all* integer exponents:

| Rule | Statement |
| --- | --- |
| Product | $a^m \cdot a^n = a^{m+n}$ |
| Quotient | $\dfrac{a^m}{a^n} = a^{m-n}$ |
| Power | $(a^m)^n = a^{mn}$ |
| Product to Power | $(ab)^n = a^n b^n$ |
| Quotient to Power | $\left(\dfrac{a}{b}\right)^n = \dfrac{a^n}{b^n}$ |
| Zero Exponent | $a^0 = 1$ |
| Negative Exponent | $a^{-n} = \dfrac{1}{a^n}$ |

These hold for any nonzero $a, b$ and any integers $m, n$.

> **Example.** Simplify $\dfrac{6x^3 y^{-2}}{2x^{-1} y^4}$.
>
> Coefficients: $6/2 = 3$. $x$ exponents: $3 - (-1) = 4$. $y$ exponents: $-2 - 4 = -6$.
>
> Result: $3 x^4 y^{-6} = \dfrac{3x^4}{y^6}$.

### Scientific notation — exponents earning their keep

A number is in **scientific notation** when written as $a \times 10^n$, where $1 \le |a| < 10$ and $n$ is an integer.

Scientific notation makes very large and very small numbers manageable. The mass of the Earth is approximately $5.972 \times 10^{24}$ kilograms — twenty-five digits of decimal awkwardness compressed into four significant figures and an exponent. The mass of an electron is $9.109 \times 10^{-31}$ kilograms — thirty zeros after the decimal point, captured in four significant figures and a negative exponent.

To convert between decimal and scientific notation: count the digits the decimal point must move to land between the first two significant digits.

- $456{,}000 = 4.56 \times 10^5$ (decimal moved 5 places left; positive exponent).
- $0.00038 = 3.8 \times 10^{-4}$ (decimal moved 4 places right; negative exponent).

Multiplication and division in scientific notation use the exponent rules:

- $(3 \times 10^4)(2 \times 10^7) = 6 \times 10^{11}$.
- $\dfrac{8 \times 10^{12}}{4 \times 10^3} = 2 \times 10^9$.

If the coefficient leaves the range $[1, 10)$ after the operation, normalize:

- $(5 \times 10^4)(6 \times 10^3) = 30 \times 10^7 = 3 \times 10^8$. (Move the decimal one place; bump the exponent.)

### The trade-off

Scientific notation is the *practical* payoff of the exponent rules. Without it, every astronomer's calculation would involve dozens of placeholder zeros, every chemist's molar mass would require careful counting of decimals, every computer scientist's storage estimates would lose precision in transcription. With it, all of those become arithmetic of small numbers and exponents.

The trade-off is one layer of abstraction. *Five point nine seven two times ten to the twenty-fourth* is a phrase, not a number you can imagine. The convenience of the notation slightly distances the user from the *size* of the quantity. Most working scientists accept the trade gladly.

The reflexive note: scientific notation is base-10 because our numerals are. In computer science, the same idea uses base-2 (the *floating-point* representation that powers virtually every modern computation). The exponent rules of this chapter apply to any base.

### Common misconceptions

- *"$3.5 \times 10^4 \times 2 \times 10^3 = 5.5 \times 10^7$."* No. Multiplication does not add the coefficients — it multiplies them. The correct answer is $7 \times 10^7$.
- *"Negative exponents make the number negative."* No. They make the number a *reciprocal*, which is positive when the base is positive. $10^{-3} = \dfrac{1}{1000} = 0.001$, a small positive number.
- *"Polynomial long division is just for symbols — there's no remainder concept."* There is. When the remainder is nonzero, you write it as a fraction over the divisor, just as in integer division.

---

## 5. Integration / Synthesis

A baseball is hit straight up from a height of $4$ feet with an initial velocity of $80$ feet per second. Its height above the ground, in feet, after $t$ seconds is approximately:

$$h(t) = -16t^2 + 80t + 4.$$

This is a polynomial — degree 2, a *quadratic*, our first major non-linear function. The coefficients each have physical meaning:

- $-16$ is half of the gravitational acceleration in feet per second squared (gravity is about $32$ ft/s²; the formula uses $\frac{1}{2}gt^2$ with the conventional sign).
- $80$ is the initial vertical velocity.
- $4$ is the initial height.

This synthesis problem uses every concept of the chapter.

### Concept 1 — identify and evaluate

The expression $-16t^2 + 80t + 4$ is a polynomial of degree $2$ — a trinomial in the variable $t$.

Evaluate at $t = 2$ seconds:

$$h(2) = -16(2)^2 + 80(2) + 4 = -16(4) + 160 + 4 = -64 + 160 + 4 = 100 \text{ ft}.$$

The ball is 100 feet up at $t = 2$.

### Concept 2 — multiply and combine polynomials

Suppose a *second* baseball is hit one second later from height $5$ feet at $90$ ft/s. Its height after time $s$ from *its* launch is:

$$h_2(s) = -16s^2 + 90s + 5.$$

If we want both heights as functions of the same time $t$ (measured from the first launch), set $s = t - 1$:

$$h_2(t) = -16(t-1)^2 + 90(t-1) + 5.$$

Expand $(t-1)^2$ using the binomial square pattern: $t^2 - 2t + 1$.

$$h_2(t) = -16(t^2 - 2t + 1) + 90t - 90 + 5$$
$$= -16t^2 + 32t - 16 + 90t - 85$$
$$= -16t^2 + 122t - 101.$$

Now the *difference* in height between the two balls at the same time is:

$$\Delta h(t) = h(t) - h_2(t) = (-16t^2 + 80t + 4) - (-16t^2 + 122t - 101).$$

Distribute the subtraction:

$$\Delta h(t) = -16t^2 + 80t + 4 + 16t^2 - 122t + 101 = -42t + 105.$$

The quadratic terms canceled — both balls fall at the same rate, so their *difference* is linear. This is a real-physics fact wearing algebraic clothes.

### Concept 3 — exponent rules and scientific notation

How long does it take light to travel from the sun to Earth? The Earth-Sun distance is about $1.496 \times 10^{11}$ meters; the speed of light is about $3.00 \times 10^8$ meters per second. Time:

$$t = \frac{d}{v} = \frac{1.496 \times 10^{11}}{3.00 \times 10^8} = \frac{1.496}{3.00} \times 10^{11-8} \approx 0.499 \times 10^3 \text{ seconds}.$$

Normalize: $0.499 \times 10^3 = 4.99 \times 10^2$ seconds, which is about $499$ seconds, or roughly $8$ minutes $19$ seconds.

The exponent rules made the division clean. Without them, we would be computing $149{,}600{,}000{,}000 \div 300{,}000{,}000$ by hand.

### What this shows

Polynomials are the shape of physical motion in the small (a baseball, a falling apple, a thrown wrench). The exponent rules are the algebra of *scale*, in both abstract and astronomical senses. Together, they describe nearly every relationship that is not exactly linear, from pizza prices to planetary orbits to the dose response of a drug. The chapter has built a vocabulary big enough for the rest of algebra.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** Classify each as monomial, binomial, trinomial, or other polynomial; state the degree:
   (a) $4x^3$ (b) $x^2 - 7$ (c) $5a + 2b - c + 1$ (d) $2y^4 - 3y^2 + y - 5$

2. **(LO 2, easy)** Simplify: $(3x^2 - 5x + 1) + (2x^2 + 4x - 7)$.

3. **(LO 3, easy)** Apply exponent rules:
   (a) $x^3 \cdot x^5$ (b) $(y^2)^4$ (c) $(2a^3)^2$ (d) $\dfrac{x^7}{x^4}$

### Application

4. **(LO 2, medium)** Subtract: $(4x^3 - 2x + 5) - (x^3 + 3x^2 - x + 2)$.

5. **(LO 4, medium)** Multiply: $3x(2x^2 - 5x + 1)$.

6. **(LO 4, medium)** Multiply (FOIL): $(2x + 3)(x - 4)$.

7. **(LO 5, medium)** Apply special products:
   (a) $(x + 7)^2$ (b) $(3y - 2)^2$ (c) $(a + 5)(a - 5)$ (d) $(2x + 3)(2x - 3)$

8. **(LO 6, medium)** Divide: $\dfrac{15x^3 - 10x^2 + 5x}{5x}$.

### Synthesis

9. **(LO 4, harder)** Multiply: $(x + 2)(x^2 - 3x + 4)$. Check by computing the result at $x = 1$ in two ways: (a) substitute into the unfactored product, (b) substitute into your expanded answer.

10. **(LO 6, harder)** Use polynomial long division to compute $\dfrac{x^3 - 4x^2 + 6x - 3}{x - 1}$. State the quotient and remainder.

11. **(LO 7, harder)** Convert to scientific notation:
    (a) $0.000045$ (b) $7{,}200{,}000$ (c) $\dfrac{1}{4 \times 10^6}$
    Then compute $(2.5 \times 10^4)(3.0 \times 10^{-7})$ and write the answer in scientific notation.

### Challenge

12. **(LO 4 + 5, hard)** Expand $(a + b + c)^2$ in terms of the squares and cross-products of $a, b, c$. *Hint: write it as $((a + b) + c)^2$ and apply the binomial-square pattern with $a + b$ as one term and $c$ as the other.* What pattern do you see for $(a_1 + a_2 + \cdots + a_n)^2$ in general?

13. **(LO 7, hard, points to chapter 9)** What does $a^{1/2}$ mean? Try this: if the product rule $a^m \cdot a^n = a^{m+n}$ is to extend from integer exponents to fractional ones, what must $a^{1/2}$ equal so that $a^{1/2} \cdot a^{1/2} = a^1 = a$? *This is exactly the definition of a square root.* Chapter 9 develops this fully.

---

## 7. Chapter summary

You came in able to handle linear expressions. You leave with a polynomial vocabulary big enough for the rest of algebra.

You know what a polynomial is — a sum of terms with whole-number-power variable parts — and you can classify a polynomial as monomial, binomial, trinomial, or higher, identify its degree, and add or subtract polynomials by combining like terms. You know to distribute the negative sign across every term of a subtracted polynomial, not just the first.

You know the seven exponent rules — product, quotient, power, product-to-power, quotient-to-power, zero-exponent, negative-exponent — and *why* each holds. You can multiply monomials by combining coefficients and applying the product rule to like-base variables. You can multiply a polynomial by a monomial using the distributive property. You can multiply two binomials using FOIL, and recognize the special products: the binomial square pattern $(a \pm b)^2 = a^2 \pm 2ab + b^2$ and the product of conjugates $(a + b)(a - b) = a^2 - b^2$.

You can divide a polynomial by a monomial by distributing the division, and divide a polynomial by a binomial using polynomial long division. You can convert between decimal and scientific notation, and multiply or divide numbers in scientific notation using the exponent rules.

The single most important idea: *polynomials are the algebra of non-linear scaling*. Everything that depends on the square of a length, the cube of a radius, or any other whole-number power of a variable is a polynomial relationship. The exponent rules are the multiplication tables of that algebra.

The most common mistake to watch for: confusing the product rule (add exponents) with the power rule (multiply exponents). And forgetting the cross term $2ab$ in $(a + b)^2$. These two errors account for most chapter-6 partial-credit losses.

What you should be able to teach someone else: why $a^0 = 1$ for any nonzero $a$, why $(a + b)^2 = a^2 + 2ab + b^2$ rather than $a^2 + b^2$, and how scientific notation makes very large and very small numbers manageable.

---

## 8. Connections forward

Chapter 7 reverses the multiplication of this chapter. Where you multiplied $(x + 2)(x + 3)$ to get $x^2 + 5x + 6$, you will now go the other direction: given $x^2 + 5x + 6$, find that it factors as $(x + 2)(x + 3)$. Factoring is multiplication in reverse — and it is the foundation of solving polynomial equations in chapter 10 (the *zero-product property* requires factored form to do its work).

Chapter 8 generalizes division: where you divided polynomials, you will now allow polynomials in *both* numerator and denominator and study the resulting *rational expressions*. The exponent rules of this chapter — especially negative exponents and the quotient rule — will work harder in chapter 8 than they did here.

Chapter 9 takes the negative-exponent insight one step further. If $a^{-n} = 1/a^n$, what about $a^{1/2}$? The exponent-rule logic suggests $a^{1/2}$ should mean $\sqrt{a}$ — and chapter 9 develops the entire arithmetic of fractional exponents and radicals.

Chapter 10 then asks: when does a quadratic polynomial equal zero? The answer uses factoring (chapter 7) and a new tool — the quadratic formula — that comes from completing the square, which is itself an application of the binomial square pattern from this chapter.

Bring the exponent rules with you. They appear in every chapter ahead.

---

**What would change my mind:** If careful empirical work showed that students who memorize the seven exponent rules without understanding *why* each holds perform as well on transfer tasks as students who derive each rule from the definition of exponentiation, I'd reconsider whether the *why* explanations in this chapter are pedagogically essential or pedagogically optional. Current evidence supports including the why; if that evidence shifted, my position would too.

**Still puzzling:** Why does the binomial square pattern $(a + b)^2 = a^2 + 2ab + b^2$ catch students again and again, even after they have proven it by FOIL? The proof is short; the result is symmetric and easy to remember. Yet when the pattern arrives in a new context — completing the square in chapter 10, expanding a regression term in statistics — students freeze and re-derive. Whether this is a generic feature of mathematical learning, or a specific failure of how the pattern is initially taught, I am not sure.

---

**Tags:** polynomials, monomial-binomial-trinomial, exponent-rules, FOIL, special-products, scientific-notation, polynomial-division, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 6 (modules m82500–m82514), used under CC-BY 4.0. Source content (definitions, exponent rules, FOIL and special products, polynomial long division, scientific notation) derives from OpenStax. Voice, scenes, and pedagogical commentary are original.*
---

## LLM Exercise — Chapter 6: Polynomials (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon.
**What you're building this chapter:** the first nonlinear model — a polynomial (quadratic or cubic) that captures behavior the linear model can't. Plus exponent-rule manipulation and scientific-notation expression for large/small phenomenon values.
**Tool:** **Claude Project** + **Claude Code** for graphing the polynomial fit.

---

**The Prompt:**

```
Chapter 6 of my Modeling project. Prior sections in this Claude
Project. Chapter 6 taught: polynomials (monomials, binomials,
trinomials; degree = highest exponent); arithmetic operations
(addition + subtraction line up like terms; multiplication uses
FOIL or distribution); exponent rules (product rule:
x^a · x^b = x^(a+b); power rule: (x^a)^b = x^(ab); quotient rule;
zero exponent: x^0 = 1; negative exponent: x^-a = 1/x^a);
scientific notation for very large or very small values.

Write the brief's "Polynomial Model" section in 500–700 words.

1. **Why nonlinear.** Where does your linear model from Ch 2 break?
   Where does the actual phenomenon's behavior genuinely curve?
   Examples:
   - Compound interest: actual growth is exponential, but
     locally approximated by a quadratic (A ≈ P + Prt + 0.5Pr²t²
     for small t).
   - Projectile motion: position is genuinely quadratic in time
     (gravity).
   - Fitness progression: gains follow diminishing-returns curve,
     poorly approximated by linear past 6 months.
   - Cell-phone bill: piecewise linear with kink at the data cap;
     near the kink, quadratic is better.

   Name the specific place your linear model is wrong.

2. **Write the polynomial model.** Express the phenomenon as a
   polynomial of degree 2 or 3. Use the variables from your
   Foundation Document. Be specific about each coefficient's
   physical meaning.
   - Linear coefficient: same as before.
   - Quadratic coefficient: what does it capture? Acceleration?
     Compounding? Saturation?

3. **Verify the math with FOIL or distribution.** If your model
   has a (x + c)² term or any binomial product, expand it using
   FOIL. Verify the expanded form by plugging in a specific value
   of x and confirming both forms give the same answer.

4. **Apply exponent rules to a scaling question.** Pick a specific
   scaling question your phenomenon raises:
   - "What if I double the input — does the output also double?
     Quadruple? Less than double?"
   The polynomial model's leading term tells you. State the
   answer and show the algebra.

5. **Scientific-notation moment.** If your phenomenon involves
   very large or very small numbers (annual returns of 4.5% =
   4.5 × 10⁻², GDP in trillions = 10¹³, ball travel in feet =
   10² of feet, microseconds = 10⁻⁶ of seconds), express ONE
   relevant quantity in scientific notation. Note what doing so
   reveals about scale.

End with a graph comparing the linear model (Ch 2) and the
polynomial model (Ch 6) over your phenomenon's natural range.
Use Claude Code. Save as PNG. The two curves' divergence is the
visualization of what nonlinearity is doing.
```

---

**What this produces:** A 500–700 word section + a comparison chart with linear and polynomial models overlaid. The divergence at the edges of the range is the strongest visual case for the polynomial upgrade.

**How to adapt this prompt:**

- *For your own project:* The "where does the linear model break" question is the project's pivot. If your phenomenon is genuinely linear throughout (rare), the polynomial model adds little; the chapter still trains polynomial-operation fluency.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* Graphing the two models on the same axes is a 20-line script.
- *For a Claude Project:* Append.

**Connection to previous chapters:** Ch 2's linear coefficient becomes Ch 6's degree-1 term; the new degree-2 (or 3) term is what's new.

**Preview of next chapter:** Chapter 7 factors your polynomial. Factoring reveals roots — and roots are the moments when something interesting happens (break-even, time-to-zero, equilibrium). The Zero Product Property turns factoring into a solving tool.


---

##  AI Wayback Machine
**Hypatia of Alexandria** was taught the algebra of Diophantus in 4th-century Alexandria — and was murdered for her public intellectual role.

**Run this:**

```
Who is Hypatia of Alexandria, and how does their work connect to polynomials we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"Hypatia of Alexandria"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way Hypatia of Alexandria would have.
- Add a constraint: "Answer including criticisms or limits of Hypatia of Alexandria's methods."

What changes? What gets better? What gets worse?
