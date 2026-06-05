---
book: prealgebra-bundle
chapter: 10-quadratic-equations
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 10 (CC-BY 4.0). Modules m82554–m82559.
status: draft
---

# Suggested titles


## TL;DR

- book: prealgebra-bundle chapter: 10-quadratic-equations voice: Attenborough × Feynman v1.
- You will practice Solve a quadratic equation of the form $ax^2 = k$ using the Square Root Property; Complete the square of a binomial expression and use it to convert any quadratic to the form $(x - h)^2 = k$; Apply the quadratic formula $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ to solve any quadratic.
- The chapter moves through Chapter opening, Learning objectives, Prerequisites, Why this chapter matters, and related ideas.

1. Quadratic Equations: When Factoring Isn't Enough
2. The Quadratic Formula, the Discriminant, and the Parabola
3. Three Ways to Solve, One Picture to See

---

**TL;DR.** A *quadratic* equation is one of the form $ax^2 + bx + c = 0$. Three solution methods cover every case: factoring (chapter 7, when it works), completing the square (universal but tedious), and the quadratic formula (universal and fast). The *discriminant* $b^2 - 4ac$ tells you, from a single calculation, whether the equation has two real solutions, one repeated real solution, or two complex (non-real) solutions. The graph of $y = ax^2 + bx + c$ is a *parabola*; its vertex, axis of symmetry, and intercepts are the geometric counterparts of the algebraic structure.

---

## 1. Chapter opening

A child shoots a basketball from a free-throw line. The ball leaves her hands at six feet above the floor with an upward velocity of twenty-four feet per second. The hoop is ten feet above the floor, fifteen feet horizontal distance away. *Will the ball go in?*

The ball's height as a function of horizontal distance traces a parabola — in approximate form, $h(x) = -0.04x^2 + 0.5x + 6$ for the geometry just sketched. *(Coefficients are physical estimates; we will use them as given.)* To know whether the ball reaches the hoop, you set the height equal to ten feet at the hoop position $x = 15$:

$$h(15) = -0.04(225) + 0.5(15) + 6 = -9 + 7.5 + 6 = 4.5 \text{ feet}.$$

Less than ten feet. The ball is below the rim. Air ball.

To find the maximum height of the ball, set $h(x) = 10$ and ask what range of horizontal distances would have the ball at rim level — but we already saw the ball does not reach ten feet at the relevant range. The path of a ball, the arc of a fireworks burst, the cross-section of a satellite dish — every one of these is a parabola, the graph of a quadratic equation. This chapter teaches you the algebra of those equations: how to solve them, what the *discriminant* tells you about the kind of solutions, and how to read the graph.

The chapter ends a story that has been building all book. Chapter 7 taught factoring, which solves quadratics that factor over the integers. Chapter 9 taught radicals, which appear in the quadratic formula. This chapter is where those tools converge: the *quadratic formula* — built from completing the square — solves *every* quadratic equation in one step.

### Learning objectives

By the end of this chapter you should be able to:

- **Solve** a quadratic equation of the form $ax^2 = k$ using the **Square Root Property**.
- **Complete the square** of a binomial expression and use it to convert any quadratic to the form $(x - h)^2 = k$.
- **Apply** the **quadratic formula** $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ to solve any quadratic.
- **Use** the **discriminant** $b^2 - 4ac$ to predict the number and type of solutions before solving.
- **Choose** the most efficient solving method (factoring, square root property, formula) for a given equation.
- **Graph** a parabola by identifying the vertex, axis of symmetry, and intercepts; **read** the equation off a sketched parabola.
- **Apply** quadratic equations to projectile motion, area, and revenue problems.

### Prerequisites

Chapters 1–9. Especially: factoring (chapter 7), the special-products patterns (chapter 6), and radical simplification (chapter 9). Completing the square in particular requires fluency with the binomial-square pattern $(x + a)^2 = x^2 + 2ax + a^2$. The quadratic formula's square-root piece relies on chapter 9.

### Why this chapter matters

Quadratic equations describe everything that *opens up or closes down* — the path of a thrown object, the profit curve of a business, the cross-section of a parabolic mirror. Wherever a relationship has a *single peak* or a *single trough* — a maximum or a minimum — there is almost always a quadratic involved. The chapter's machinery (formula, discriminant, parabola) is the toolkit for handling all of them, and it consolidates everything you have built since the foundations chapter.

---

## 2. Concept 1 — The square root property and completing the square

Two methods for solving quadratic equations existed before the quadratic formula was developed (or rediscovered, depending on whose history you read). Both still earn their place because they reveal what the formula is *doing*. The first is the simplest possible case; the second is the engine that produces the formula.

### The Square Root Property

When a quadratic equation has the form $x^2 = k$ (or, more generally, $(x - h)^2 = k$) — no linear $x$ term — taking the square root of both sides solves it directly.

**Square Root Property.** If $x^2 = k$ where $k \ge 0$, then $x = \pm\sqrt{k}$.

The $\pm$ is the entire content. *Two* roots: the positive square root and its opposite. We saw in chapter 9 that the radical symbol denotes only the principal (nonneg) root; the $\pm$ recovers both.

> **Example.** Solve $x^2 = 49$.
>
> $x = \pm\sqrt{49} = \pm 7$. Two solutions: $x = 7$ or $x = -7$.

> **Example.** Solve $(x - 3)^2 = 16$.
>
> $x - 3 = \pm 4$. So $x = 3 + 4 = 7$ or $x = 3 - 4 = -1$.

If $k < 0$, the equation has *no real solutions* — the principal square root of a negative number is not a real number. (Complex solutions exist; college algebra introduces them.)

### Completing the square

Most quadratics have a linear term and do not arrive in the convenient form $(x - h)^2 = k$. **Completing the square** is the algebraic move that converts *any* quadratic into that form.

The motivation is the binomial-square pattern (chapter 6):

$$(x + a)^2 = x^2 + 2ax + a^2.$$

If we are given $x^2 + bx$ — a quadratic with linear coefficient $b$ — and want to *write it as* a perfect square plus or minus something, we need to add the right constant. Comparing $x^2 + bx$ with $x^2 + 2ax + a^2$, we see that $b = 2a$, so $a = b/2$, and the constant we need to add is $a^2 = (b/2)^2$.

> **The recipe.** To complete the square on $x^2 + bx$: add $(b/2)^2$. The result is $(x + b/2)^2$.

The "complete" in *completing the square* names this exactly: we *complete* the perfect-square trinomial by supplying the missing constant.

> **Example.** Complete the square on $x^2 + 6x$.
>
> $b = 6$, $b/2 = 3$, $(b/2)^2 = 9$. Add 9: $x^2 + 6x + 9 = (x + 3)^2$.

### Using completing the square to solve

To solve $x^2 + bx + c = 0$ by completing the square:

1. **Move** the constant to the right side: $x^2 + bx = -c$.
2. **Complete** the square on the left by adding $(b/2)^2$ — and add the same to the right side to keep the equation balanced.
3. **Factor** the left as a perfect square: $(x + b/2)^2 = -c + (b/2)^2$.
4. **Apply** the Square Root Property and solve.

> **Example.** Solve $x^2 + 6x - 7 = 0$ by completing the square.
>
> *Step 1.* $x^2 + 6x = 7$.
>
> *Step 2.* $(b/2)^2 = (3)^2 = 9$. Add to both sides: $x^2 + 6x + 9 = 7 + 9 = 16$.
>
> *Step 3.* Factor: $(x + 3)^2 = 16$.
>
> *Step 4.* Square Root Property: $x + 3 = \pm 4$, so $x = -3 \pm 4$. Two solutions: $x = 1$ or $x = -7$.
>
> *Verify.* $1^2 + 6(1) - 7 = 1 + 6 - 7 = 0$ $\checkmark$. $(-7)^2 + 6(-7) - 7 = 49 - 42 - 7 = 0$ $\checkmark$.

### When the leading coefficient is not 1

If $a \ne 1$, divide both sides by $a$ first to normalize:

$$ax^2 + bx + c = 0 \quad \Longrightarrow \quad x^2 + \frac{b}{a}x + \frac{c}{a} = 0.$$

Then complete the square as above. The work gets messier with fractions, which is one reason the quadratic formula (Concept 2) often beats completing the square in practice.

### The trade-off

Completing the square is the slow, explicit method that *shows* what the quadratic formula compresses into one line. The trade-off is computational: even simple quadratics take five or six lines. The method earns its place because it *derives* the quadratic formula (we will do this in the next concept) and because it generalizes — the same move appears in calculus (finding extrema), in conic sections (writing equations of circles, ellipses, hyperbolas in standard form), and in statistics (the algebra of variance).

### Common misconceptions

- *"$x^2 = 49 \Rightarrow x = 7$."* Missing the negative root. $x = \pm 7$. Always.
- *"Adding $(b/2)^2$ to both sides changes the equation."* Adding the same number to both sides preserves equality (chapter 2). Completing the square is just a clever rewriting that uses this fact.
- *"Completing the square works only for $x^2$ coefficient 1."* It works for any leading coefficient — divide by the coefficient first to normalize.

---

## 3. Concept 2 — The quadratic formula and the discriminant

Apply completing the square to the *general* quadratic $ax^2 + bx + c = 0$. The result is the **quadratic formula** — the closed-form expression for the roots of any quadratic.

### Derivation (sketch)

Start with $ax^2 + bx + c = 0$. Divide by $a$: $x^2 + \dfrac{b}{a}x + \dfrac{c}{a} = 0$. Move the constant: $x^2 + \dfrac{b}{a}x = -\dfrac{c}{a}$.

Complete the square: $\left(\dfrac{b/a}{2}\right)^2 = \dfrac{b^2}{4a^2}$. Add to both sides:

$$x^2 + \dfrac{b}{a}x + \dfrac{b^2}{4a^2} = -\dfrac{c}{a} + \dfrac{b^2}{4a^2}.$$

Factor the left side as a perfect square; combine the right side over a common denominator $4a^2$:

$$\left(x + \dfrac{b}{2a}\right)^2 = \dfrac{b^2 - 4ac}{4a^2}.$$

Apply the Square Root Property:

$$x + \dfrac{b}{2a} = \pm \dfrac{\sqrt{b^2 - 4ac}}{2a}.$$

Solve for $x$:

$$\boxed{x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}.}$$

That is the **quadratic formula**. It solves any quadratic $ax^2 + bx + c = 0$ ($a \ne 0$) in one substitution.

### A worked example

> **Problem.** Solve $2x^2 - 4x - 6 = 0$ using the quadratic formula.
>
> $a = 2$, $b = -4$, $c = -6$.
>
> $$x = \dfrac{-(-4) \pm \sqrt{(-4)^2 - 4(2)(-6)}}{2(2)} = \dfrac{4 \pm \sqrt{16 + 48}}{4} = \dfrac{4 \pm \sqrt{64}}{4} = \dfrac{4 \pm 8}{4}.$$
>
> Two solutions: $x = \dfrac{4 + 8}{4} = 3$, or $x = \dfrac{4 - 8}{4} = -1$.
>
> *Verify.* $2(3)^2 - 4(3) - 6 = 18 - 12 - 6 = 0$ $\checkmark$. $2(-1)^2 - 4(-1) - 6 = 2 + 4 - 6 = 0$ $\checkmark$.

### The discriminant

The expression under the radical, $b^2 - 4ac$, is called the **discriminant** — written $\Delta$ — because it *discriminates* among the three possible cases for the equation's solutions.

| Discriminant | Number of real solutions |
|---|---|
| $\Delta > 0$ | two distinct real solutions |
| $\Delta = 0$ | one repeated real solution |
| $\Delta < 0$ | no real solutions (two complex solutions) |

The reasoning: $\sqrt{\Delta}$ is the radical in the formula. If $\Delta > 0$, the radical is a positive real, and the $\pm$ produces two distinct outputs. If $\Delta = 0$, the radical is zero, the $\pm$ disappears, and only one solution remains: $x = -b/(2a)$. If $\Delta < 0$, the radical is the square root of a negative number — not a real number.

You can predict the *kind* of solution without solving by computing $\Delta$ first.

> **Example.** How many real solutions does $x^2 - 4x + 5 = 0$ have?
>
> $a = 1, b = -4, c = 5$. $\Delta = 16 - 20 = -4 < 0$. *No real solutions.*

> **Example.** How many real solutions does $4x^2 - 12x + 9 = 0$ have?
>
> $\Delta = 144 - 144 = 0$. *Exactly one repeated real solution.* (This polynomial happens to factor as $(2x - 3)^2$, confirming the repeated root $x = 3/2$.)

### Choosing the method

Three methods solve quadratics. For a given equation, one is usually fastest:

- **Factoring** (chapter 7). Fastest *when it works*. Try first if the polynomial factors over integers.
- **Square Root Property.** Fastest when there is no $x$ term, e.g., $x^2 = 25$, $(x - 3)^2 = 49$.
- **Quadratic formula.** Universal. Use when factoring fails or when the coefficients are messy.
- **Completing the square.** Rarely the fastest in practice; useful for *deriving* results (the formula itself, conic-section standard forms, vertex form for parabolas).

The discriminant gives you a quick check before committing: $\Delta = $ a positive integer that is a perfect square ⇒ the polynomial often factors over integers. $\Delta$ negative or not a perfect square ⇒ go straight to the formula.

### The trade-off

The quadratic formula is *universal*: it solves every quadratic, no exceptions. The trade-off is that it does not *show* what is happening — you substitute, simplify, and read off the answer. Factoring shows the structure ("this polynomial decomposes into these factors"); completing the square shows the geometry ("this quadratic is shifted from a standard form by these amounts"). The formula buys reliability at the cost of insight.

The reflexive note: the quadratic formula is the simplest closed-form solution for a polynomial equation. There is also a (much longer) cubic formula, and a (much, much longer) quartic formula. For polynomials of degree five or higher, *no general closed-form solution exists* — the Abel-Ruffini theorem proved this in the early 19th century. So the quadratic formula sits at the top of a small ladder; ascending past degree 4 means giving up closed-form and using numerical methods instead.

### Common misconceptions

- *"The quadratic formula has two answers, but I should pick one."* Both are solutions — unless the context excludes one (e.g., a negative time or a negative length in a word problem). Report both algebraically, then select on physical grounds if applicable.
- *"$\sqrt{b^2 - 4ac}$ is always positive, so $\pm$ doesn't matter."* It does — the $\pm$ generates two distinct values when added or subtracted from $-b$. The radical's nonnegativity is *part* of the formula's structure, not a redundancy.
- *"If the discriminant is negative, I made a mistake."* No — sometimes the equation simply has no real solutions. (Complex solutions exist in college algebra.)

---

## 4. Concept 3 — Graphing parabolas

Every quadratic equation in two variables, $y = ax^2 + bx + c$, has a graph called a **parabola**. The geometry of the parabola encodes the algebra of the equation. Reading one off the other — graph to equation, equation to graph — is the work of this concept.

### Opening direction

The sign of the leading coefficient $a$ controls whether the parabola opens *upward* or *downward*.

- $a > 0$: parabola opens upward (a "smile"). The bottom of the parabola is its lowest point.
- $a < 0$: parabola opens downward (a "frown"). The top is the highest point.

The size of $|a|$ controls how *narrow* or *wide* the parabola is. Larger $|a|$ ⇒ steeper sides ⇒ narrower parabola.

### Vertex

The **vertex** of a parabola is its highest point (if the parabola opens downward) or lowest point (if it opens upward). The vertex is the *turning point* — the only place where the parabola changes direction.

For $y = ax^2 + bx + c$, the x-coordinate of the vertex is:

$$x_{\text{vertex}} = -\frac{b}{2a}.$$

This is the average of the two roots from the quadratic formula. Geometrically: the parabola is symmetric about the vertical line through its vertex, so the vertex sits *exactly between* the two x-intercepts.

To find the y-coordinate, substitute $x_{\text{vertex}}$ into the equation: $y_{\text{vertex}} = f(x_{\text{vertex}})$.

### Axis of symmetry

The vertical line $x = -b/(2a)$ — the line through the vertex — is the **axis of symmetry**. The parabola is mirror-symmetric across it: every point on the parabola has a partner on the other side at the same height.

### Intercepts

The **y-intercept** is where the parabola crosses the y-axis; it is found by setting $x = 0$. For $y = ax^2 + bx + c$, the y-intercept is just $c$.

The **x-intercepts** (also called the *zeros* of the function) are where the parabola crosses the x-axis; they are found by setting $y = 0$ and solving the resulting quadratic. The number of x-intercepts equals the number of real solutions of $ax^2 + bx + c = 0$:

- $\Delta > 0$: two x-intercepts (parabola crosses the x-axis at two points).
- $\Delta = 0$: one x-intercept (parabola is *tangent* to the x-axis at the vertex).
- $\Delta < 0$: no x-intercepts (parabola does not cross the x-axis).

The discriminant ↔ number of x-intercepts is the same correspondence as discriminant ↔ number of real solutions of the equation. Algebra and geometry say the same thing.

### A worked example

> **Problem.** Graph $y = x^2 - 4x + 3$.

> *Opening direction:* $a = 1 > 0$, opens upward.
>
> *Vertex:* $x = -b/(2a) = -(-4)/2 = 2$. $y = 2^2 - 4(2) + 3 = 4 - 8 + 3 = -1$. Vertex $(2, -1)$.
>
> *Axis of symmetry:* $x = 2$.
>
> *Y-intercept:* $c = 3$. Point $(0, 3)$.
>
> *X-intercepts:* solve $x^2 - 4x + 3 = 0$. Factor: $(x - 1)(x - 3) = 0$. $x = 1$ or $x = 3$. Points $(1, 0)$ and $(3, 0)$.
>
> *Plot:* vertex at $(2, -1)$, points $(1, 0), (3, 0), (0, 3)$, and use symmetry to plot $(4, 3)$ — same height as the y-intercept across the axis of symmetry.
>
> *Sketch* a smooth U-shape passing through these points.

![A parabola $y = x^2 - 4x + 3$ plotted on a coordinate plane, with axis of symmetry $x = 2$ shown as a dashed vertical line, vertex...](images/10-quadratic-equations-fig-01.png)
*Figure 10.1 — parabola $y = x^2*

### Applications — maximum and minimum problems

Because the vertex is the turning point, it is the *maximum* (downward parabola) or *minimum* (upward parabola) of the function. Many word problems ask for an extremum.

> **Problem.** A toy rocket is launched from the ground at $80$ feet per second. Its height after $t$ seconds is $h(t) = -16t^2 + 80t$. *What is the maximum height, and when does it occur?*

> Vertex is at $t = -b/(2a) = -80/(2 \cdot -16) = 80/32 = 2.5$ seconds.
>
> $h(2.5) = -16(2.5)^2 + 80(2.5) = -16(6.25) + 200 = -100 + 200 = 100$ feet.
>
> **Answer:** *Maximum height is 100 feet, reached at 2.5 seconds.*

The chapter 7 break-even problem (synthesis) and the chapter 6 baseball trajectory connect directly: the *vertex* is the maximum profit, the maximum height, the maximum revenue. Quadratic models naturally answer extremum questions.

### The trade-off

Graphing a parabola requires four numerical computations (vertex x, vertex y, intercepts) and a sketch. The trade-off, compared to plotting many points, is that you read the *structural* features — opening direction, location of vertex, symmetry — directly, which makes the sketch fast and the interpretation easy. Plotting fifty points is more accurate but loses the structure.

### Common misconceptions

- *"The vertex is at $x = b/(2a)$."* No — the formula is $x = -b/(2a)$. The negative is essential.
- *"The y-intercept is at $b$."* No — it is at $c$ (substitute $x = 0$ into $ax^2 + bx + c$ and only $c$ remains).
- *"A parabola always crosses the x-axis."* No — only when the discriminant is nonneg. A parabola with negative discriminant sits entirely above (if $a > 0$) or entirely below (if $a < 0$) the x-axis.

---

## 5. Integration / Synthesis

A small business sells widgets at a price $p$ dollars each. Demand decreases as price rises: at price $p$, the company sells $200 - 5p$ widgets per week. The cost to produce each widget is $\$8$. *What price maximizes weekly profit, and what is that maximum profit?*

This problem combines all three concepts.

### Concept 1 — set up a quadratic profit function

Number sold: $200 - 5p$.
Revenue (price × quantity): $p(200 - 5p) = 200p - 5p^2$.
Cost (cost-per-widget × quantity sold): $8(200 - 5p) = 1600 - 40p$.

Profit:

$$P(p) = \text{Revenue} - \text{Cost} = (200p - 5p^2) - (1600 - 40p)$$
$$P(p) = -5p^2 + 240p - 1600.$$

A quadratic in $p$, opening downward (leading coefficient $-5 < 0$), so the parabola has a *maximum*.

### Concept 2 — find the vertex

Vertex at $p = -b/(2a) = -240/(2 \cdot -5) = -240/(-10) = 24$.

Maximum profit at price $p = \$24$:

$$P(24) = -5(576) + 240(24) - 1600 = -2880 + 5760 - 1600 = 1280 \text{ dollars per week}.$$

### Concept 3 — graph and interpret

The parabola $P(p) = -5p^2 + 240p - 1600$ opens downward, has vertex $(24, 1280)$, and the company breaks even where $P(p) = 0$.

Find break-even points using the quadratic formula:

$$p = \dfrac{-240 \pm \sqrt{240^2 - 4(-5)(-1600)}}{2(-5)} = \dfrac{-240 \pm \sqrt{57600 - 32000}}{-10} = \dfrac{-240 \pm \sqrt{25600}}{-10} = \dfrac{-240 \pm 160}{-10}.$$

Two break-even prices: $p = (-240 + 160)/(-10) = 8$, or $p = (-240 - 160)/(-10) = 40$. The business breaks even at \$8 and \$40 per widget.

The full picture:

- Below \$8: not enough profit per widget to cover costs.
- At \$8: break-even (profit = 0).
- Between \$8 and \$40: profit is positive.
- At \$24: profit is maximum, \$1{,}280 per week.
- At \$40: break-even again (high price, low quantity).
- Above \$40: not enough customers; profit goes negative.

The vertex sits exactly at the average of the two break-even points: $(8 + 40)/2 = 24$. Geometric symmetry of the parabola, in business terms.

### What this shows

Three lessons.

*First*, the same parabola structure that handled the falling baseball (chapter 6) and the broken business budget (chapter 7) handles a revenue-cost-profit problem. *Quadratics are the algebra of optimization* — the algebra of finding the price that maximizes profit, the angle that maximizes range, the dimensions that minimize cost.

*Second*, three different methods could have solved this. Factoring would have worked: $P(p) = -5(p - 8)(p - 40)$, recovering the break-even prices directly. The quadratic formula gave the same break-evens. The vertex formula gave the maximum. Each method illuminates a different aspect; the choice depends on what you want to *see*.

*Third*, the chapter has consolidated everything since chapter 1. Functions in two variables (ch 4). Word-problem setup (ch 3). Polynomial evaluation (ch 6). Factoring (ch 7). Radicals in the formula (ch 9). Solving methods (this chapter). The whole machinery now exists for handling not just one optimization problem but the entire family.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** Solve using the Square Root Property: $x^2 = 81$.

2. **(LO 1, easy)** Solve: $(x - 2)^2 = 25$.

3. **(LO 3, easy)** Solve using the quadratic formula: $x^2 - 5x + 6 = 0$. *(Verify by factoring.)*

4. **(LO 4, easy)** Compute the discriminant of $x^2 + 2x + 5 = 0$ and state the number and type of real solutions.

### Application

5. **(LO 2, medium)** Complete the square to solve: $x^2 + 8x + 7 = 0$.

6. **(LO 3, medium)** Solve using the quadratic formula: $3x^2 - 5x - 2 = 0$.

7. **(LO 6, medium)** Find the vertex and axis of symmetry of $y = x^2 - 6x + 5$.

8. **(LO 6, medium)** Sketch $y = -x^2 + 4x$. Identify the vertex, axis of symmetry, and intercepts.

### Synthesis

9. **(LO 4 + 5, harder)** For each of the following equations, compute the discriminant, state the number and type of solutions, and choose the most efficient solving method. Then solve.
   (a) $x^2 - 6x + 9 = 0$
   (b) $2x^2 + 3x - 5 = 0$
   (c) $x^2 + 2x + 4 = 0$

10. **(LO 7, harder)** A toy rocket is fired straight up from a height of $5$ feet with initial velocity $96$ ft/s. Its height after $t$ seconds is $h(t) = -16t^2 + 96t + 5$. (a) When does it reach maximum height? (b) What is the maximum height? (c) When does it hit the ground? (d) Sketch a graph of height vs. time.

11. **(LO 7, harder)** A rectangular field is to be enclosed with $200$ feet of fencing. Express the area $A$ as a function of width $w$. What dimensions maximize the area, and what is that maximum?

### Challenge

12. **(LO 6, hard)** A parabola passes through $(0, 3)$, $(1, 0)$, and $(4, 3)$. Find its equation in the form $y = ax^2 + bx + c$. *(Hint: substitute each point into the form to get three equations in $a, b, c$ — a system from chapter 5.)*

13. **(LO 4, hard)** For the equation $x^2 + bx + 4 = 0$, find the values of $b$ for which the equation has (a) two distinct real solutions, (b) exactly one real solution, (c) no real solutions. *Express each answer as an inequality on $b$, and graph the three regions on a number line.*

14. **(LO 3, hard, points to college algebra)** Solve $x^2 + 2x + 5 = 0$. Since the discriminant is negative, the equation has no real solutions — but it does have two *complex* solutions. Use the formula and treat $\sqrt{-1} = i$ (the imaginary unit) to write the two complex solutions in the form $a + bi$. *College algebra develops the algebra of complex numbers.*

---

## 7. Chapter summary

You came in able to factor and to handle radicals. You leave able to solve every quadratic equation that exists.

You know the four structural ideas. *First*, the Square Root Property: if $x^2 = k$ ($k \ge 0$), then $x = \pm\sqrt{k}$. *Second*, completing the square: any quadratic can be rewritten as $(x - h)^2 = k$ by adding the right constant. *Third*, the quadratic formula: $x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$, derived by completing the square on the general quadratic, solves any quadratic in one substitution. *Fourth*, the discriminant $b^2 - 4ac$ predicts the number of real solutions: positive ⇒ two distinct, zero ⇒ one repeated, negative ⇒ none.

You can choose the most efficient solving method: factoring when the polynomial factors over integers, the Square Root Property when there is no linear term, and the quadratic formula otherwise. You can graph a parabola by finding its vertex (at $x = -b/(2a)$), axis of symmetry (the vertical line through the vertex), y-intercept (at $c$), and x-intercepts (at the solutions of $ax^2 + bx + c = 0$).

You know that quadratic models — a parabola opening up or down — describe a vast family of real-world problems: projectile motion, area maximization, profit optimization, parabolic mirrors and dishes. The vertex is always the extremum (max or min); the discriminant is always the predictor of whether the parabola crosses the x-axis.

The single most important idea: *every quadratic equation has at most two real solutions, and the quadratic formula finds them all*. The discriminant tells you, before you solve, what kind of answer to expect. The graph of the corresponding parabola makes the algebra geometric: roots become x-intercepts, the discriminant becomes the relationship between the parabola and the x-axis.

The most common mistake to watch for: forgetting the $\pm$ when applying the Square Root Property. *Two roots, always.* The other classic error: signing $-b$ wrong in the quadratic formula. The numerator is $-b$, not $b$; substitute carefully.

What you should be able to teach someone else: why the discriminant predicts the number of solutions, why the vertex sits at $x = -b/(2a)$, and why a parabola with $a > 0$ opens upward and has a minimum at its vertex.

---

## 8. Connections forward

Chapter 10 closes elementary algebra. The work of college algebra builds outward in three directions.

*First*, beyond quadratics. Cubic, quartic, and higher-degree polynomial equations, with their own (more complex) solving methods. Eventually the realization that no general closed-form solution exists for degree-5-and-up — and the corresponding development of numerical methods.

*Second*, beyond the real numbers. Complex numbers, where every polynomial of degree $n$ has exactly $n$ roots (counted with multiplicity). Quadratics with negative discriminant have *two* complex solutions, just like every other quadratic — the apparent "no solutions" of the real case becomes "two complex solutions" in the complex case.

*Third*, beyond polynomials. Exponential and logarithmic functions, trigonometric functions, the algebra of inverses. Each is a different family of relationships, with its own equation-solving discipline. The common thread — *some moves are reversible, some are not, and the irreversible ones require checks* — applies in all of them.

Bring the parabola with you. It is the simplest non-linear graph, and its features (vertex, symmetry, intercepts, opening direction) are the template for understanding every more complex curve you will meet.

---

**What would change my mind:** If a careful study showed that students who skip the formal derivation of the quadratic formula (treating it as a memorized recipe) developed equally strong ability to *use* the formula in applications, I'd reconsider whether the derivation in §3 is pedagogically essential. Currently, my prior is that seeing where the formula comes from helps with the discriminant-as-predictor framing in §3 and §4. The empirical question is whether that connection survives without the derivation.

**Still puzzling:** Why does the vertex formula $x = -b/(2a)$ feel less natural than the quadratic formula $x = (-b \pm \sqrt{b^2 - 4ac})/(2a)$, despite being a direct consequence of it (the average of the two roots from the formula)? Students often memorize one and re-derive the other from scratch, even after I have shown the connection. Whether this is a notational accident or a deeper feature of how mathematical fluency develops, I am not sure.

---

**Tags:** quadratic-equations, quadratic-formula, discriminant, completing-the-square, square-root-property, parabola, vertex, axis-of-symmetry, optimization, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 10 (modules m82554–m82559), used under CC-BY 4.0. Source content (Square Root Property, completing the square, quadratic formula derivation, discriminant, parabola graphing methods, projectile-motion and revenue applications) derives from OpenStax. Voice, scenes, and pedagogical commentary are original.*
---

## LLM Exercise — Chapter 10: Quadratic Equations (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon — final probe and integration.
**What you're building this chapter:** the quadratic model — your phenomenon's most sophisticated form yet — plus the parabola graphed, the discriminant interpreted, and the final compiled "Modeling [Phenomenon]" document.
**Tool:** **Claude Project** + **Claude Code** for the parabola graph. **Cowork** for the final compilation.

---

**The Prompt:**

```
Chapter 10 — the closing chapter — of my Modeling project. The
prior 9 sections are in this Claude Project. Chapter 10 taught:
the Square Root Property (if x² = c, then x = ±√c); completing
the square (rewrite ax² + bx + c into a(x + h)² + k form);
the quadratic formula (x = (-b ± √(b² - 4ac)) / 2a — solves
ANY quadratic, even ones that don't factor); the discriminant
(b² - 4ac — predicts the number and type of solutions: > 0 →
two real solutions, = 0 → one real solution, < 0 → two complex
solutions); parabolas (the graph of y = ax² + bx + c is a
parabola; a > 0 opens up, a < 0 opens down; vertex at x = -b/2a;
axis of symmetry x = -b/2a).

Two parts.

PART A — The quadratic model.

1. **Write the full quadratic.** Express your phenomenon as
   ax² + bx + c = 0 or y = ax² + bx + c. Use the variables from
   your Foundation Document. State the physical meaning of each
   coefficient.

2. **Solve by three methods.** Solve the quadratic equation by:
   - Factoring (if it factors — from Ch 7).
   - The Square Root Property (if it's in the form (x + h)² = k).
   - The quadratic formula (always works).
   All three should give the same answer for ones that factor.

3. **The discriminant interpretation.** Compute the discriminant.
   What does it tell you about your phenomenon?
   - Discriminant > 0: two real roots — the phenomenon hits the
     target value twice (e.g., on the way up AND on the way down).
   - Discriminant = 0: one real root — the phenomenon just barely
     touches the target value (a perfect throw that grazes the
     basket; a perfectly tuned investment that just hits target).
   - Discriminant < 0: no real roots — the phenomenon never hits
     the target value within the model's assumptions.

4. **Graph the parabola.** Use Claude Code (or a spreadsheet) to
   produce a real chart with:
   - The parabola plotted over the natural range of x.
   - The vertex marked (with coordinates labeled).
   - The axis of symmetry as a vertical line.
   - The roots marked on the x-axis (if real).
   - The y-intercept marked.
   Save as PNG.

5. **The maximum/minimum question.** Most quadratic models have a
   real-world maximum or minimum at the vertex:
   - "What's the maximum height the projectile reaches?" → vertex
     y-value.
   - "What's the optimal price for maximum revenue?" → vertex
     x-value (price), y-value (revenue).
   - "What's the minimum cost?" → vertex.
   Answer your phenomenon's max/min question explicitly.

PART B — The integration: compile the modeling document.

Have Claude assemble the final "Modeling [Phenomenon]" document:

1. List all 10 sections with their core findings, briefly.
2. Build the model hierarchy table:
   - Ch 2: Linear approximation — accurate for [range], breaks
     at [boundary].
   - Ch 5: Two-constraint system — explains [phenomenon
     interaction].
   - Ch 6–7: Polynomial / factored — captures [nonlinearity].
   - Ch 8: Rational — adds rate / density / average dimension.
   - Ch 9: Radical — captures [square-root behavior].
   - Ch 10: Quadratic — full model with vertex and roots.
3. The model's predictions vs. reality. Where does the quadratic
   model match observed data? Where does it still diverge? Name
   the divergences — they're where college-level math (logs,
   exponentials, calculus) would go.
4. The central question (from Ch 1) — now answered with the full
   model. Give the specific numerical answer and the reasoning
   path that led to it.

End with a 200-word coda titled "What I'd refine if I had more
math" — name one specific way the model is wrong that you now
know how to fix (or that you know you'd need more math to fix).
The coda is the project's intellectual honesty close.

Output the compiled document as one master markdown file (3,000–
5,000 words) plus the supporting charts. This is the deliverable.
```

---

**What this produces:** The full quadratic model + the compiled "Modeling [Phenomenon]" document — 3,000–5,000 words with all 10 chapters' models on one phenomenon. A real piece of mathematical analysis the student keeps.

**How to adapt this prompt:**

- *For your own project:* The "what I'd refine" coda is the project's most reflective piece. Most students at this stage know more about what they don't know than they did at the start; the coda names that.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* For the parabola graph specifically, Claude Code is the right tool. 20 lines of matplotlib produce a real annotated parabola.
- *For a Claude Project / Cowork:* The compilation step assembles 10 sections into the final document. Cowork can read all 10 sections and produce the integrated document.

**Connection to previous chapters:** Every prior chapter feeds this. The compilation tests whether the 10 models cohere on one phenomenon or fragment into 10 disconnected exercises.

**Preview of next chapter:** There is no next chapter — this is the close. What's next is the model itself: a multi-form mathematical description of one real phenomenon you understand more deeply now than when you started. Read it back six months from now and notice what stuck.


---

##  AI Wayback Machine
**Brahmagupta** was 7th-century Indian mathematician who gave the first explicit general solution of the quadratic equation.

**Run this:**

```
Who is Brahmagupta, and how does their work connect to quadratic equations we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"Brahmagupta"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way Brahmagupta would have.
- Add a constraint: "Answer including criticisms or limits of Brahmagupta's methods."

What changes? What gets better? What gets worse?

## Prompts

Use these prompts with Claude to generate interactive D3 v7 versions of the
figures in this chapter. Each produces a standalone HTML file you can open
in a browser and modify freely.

**Prerequisites:** Load `brutalist/CLAUDE.md` and `brutalist/DESIGN.md` into
your Claude project context before using these prompts. They define the stack,
naming conventions, color system, and typography the figures use.

---

### Figure 10.1 — parabola $y = x^2

Create a standalone D3 v7 HTML figure for "parabola $y = x^2". Use a 2x2 matrix with four quadrants plus axis labels. Marks: bars or rectangular panels, direct labels, and concise value labels. Channels: position for sequence or category, length for quantitative emphasis when bars are used, color for the primary highlighted item only, and direct text labels for accessibility. Use a zero baseline for quantitative bars. Include title, desc, role="img", aria-labelledby, ResizeObserver redraw, dark mode CSS variables, and reduced-motion safeguards. Deliver as one HTML file with inline CSS and the D3 7.9.0 CDN.

> Reference implementation: `d3/10-quadratic-equations-fig-01.html`
