---
book: prealgebra-bundle
chapter: 02-solving-linear-equations-and-inequalities
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 2 (CC-BY 4.0). Modules m82462–m82470.
status: draft
---

# Suggested titles


## TL;DR

- book: prealgebra-bundle chapter: 02-solving-linear-equations-and-inequalities voice: Attenborough × Feynman v1.
- You will practice Solve any linear equation in one variable using the addition, subtraction, multiplication, and division properties of equality; Apply a general strategy: simplify each side, gather variables on one side and constants on the other, isolate; Classify a linear equation as conditional (one solution), contradiction (no solution), or identity (every real number is a solution).
- The chapter moves through Chapter opening, Learning objectives, Prerequisites, Why this chapter matters, and related ideas.

1. What "Solve for x" Actually Means
2. The Balance and the Goal
3. Equations: Working Backward Until the Unknown Is Alone

---

**TL;DR.** An equation is a claim that two expressions name the same number. To *solve* an equation is to transform that claim, one legal move at a time, until the unknown stands alone on one side. Every legal move is one of the properties of real numbers you met in chapter 1, applied with a goal.

---

## 1. Chapter opening

Two friends at a coffee shop, settling up. Total bill: forty-two dollars. They had identical coffees — five between them, two for one and three for the other — plus a fourteen-dollar pastry split evenly. The waiter has gone to swipe the card. One friend says, "Wait. What does a coffee cost?"

The other friend pulls a napkin from the holder, writes the number five with a small letter $c$ next to it, then writes $+ 14 = 42$. Five coffees plus a fourteen-dollar split equals the forty-two-dollar bill. She subtracts fourteen from each side: $5c = 28$. She divides both sides by five: $c = 5.60$.

The waiter returns. The friends agree on the math.

What just happened on the napkin? Not arithmetic. Arithmetic would have been the waiter computing the total: take the price of a coffee, multiply by five, add fourteen, get forty-two. That is forward computation. The friend on the napkin did the opposite. She started with the answer, worked backward through the operations, and recovered the unknown. *That* is algebra. The arithmetic of the unknown.

This chapter is about that move — the systematic, step-by-step backward unwinding of an equation until the variable is alone. By the end, you will be able to solve any *linear* equation in one variable, recognize when no value of the variable can make the equation true, recognize when every value of the variable makes it true, and extend all of this from equations to inequalities. The inequality case has one twist that catches everyone the first time. We will mark it carefully when we get there.

### Learning objectives

By the end of this chapter you should be able to:

- **Solve** any linear equation in one variable using the addition, subtraction, multiplication, and division properties of equality.
- **Apply** a general strategy: simplify each side, gather variables on one side and constants on the other, isolate.
- **Classify** a linear equation as *conditional* (one solution), *contradiction* (no solution), or *identity* (every real number is a solution).
- **Solve** linear equations with fraction or decimal coefficients by clearing denominators or shifting decimals.
- **Solve** linear inequalities, including the rule that multiplying or dividing both sides by a negative number reverses the inequality.
- **Graph** the solution set of an inequality on a number line and write it in interval notation.

### Prerequisites

Chapter 1. In particular, the five families of properties of real numbers, the order of operations, and the language of variables and expressions. If "additive inverse" or "distributive property" do not yet make sense without flipping back, spend a day with chapter 1 before continuing. The work in this chapter consists almost entirely of applying those properties with a specific goal in mind.

### Why this chapter matters

Solving a linear equation is the simplest case of a thing you will do for the rest of your mathematical life. Solve a quadratic equation; solve a system of equations; solve a differential equation; solve a system of constraints. The structure is always the same: you have a true statement involving an unknown, you apply legal moves that preserve truth, you end with the unknown alone. Get the *one-variable linear* case fluent and the rest of algebra is tractable. Get it shaky and every later chapter inherits the shake.

---

## 2. Concept 1 — The balance principle

A pan balance — the kind a chemist uses, two trays hung from a beam, calibrated weights in a wooden box. Put a hundred-gram weight on the left, a hundred-gram weight on the right, and the beam levels. Add a fifty-gram weight to the left and the beam tips left; the balance is *broken*.

To restore the balance, you can do exactly two things. You can add the same weight to the right pan. Or you can remove the same weight from the left pan. Either way, the operation you perform must be the same on both sides, or the equality fails.

That is what an equation is. The two sides of the equals sign are the two pans of a balance. The variable lives somewhere among the weights. Solving the equation means moving weights from pan to pan — using only operations that preserve balance — until you can read the weight of the variable directly off one pan.

### What an equation is, precisely

An **equation** is a sentence claiming that two expressions name the same number. The equation $3x + 5 = 17$ claims that the expression $3x + 5$ and the number $17$ are equal *for some specific value of $x$*. A **solution** is any value of the variable that makes the equation true. Solving the equation is the process of finding that value.

To **verify** a candidate solution, substitute it and simplify. Is $4$ a solution to $3x + 5 = 17$? Substitute: $3(4) + 5 = 12 + 5 = 17$. Yes. Is $5$ a solution? Substitute: $3(5) + 5 = 15 + 5 = 20$, which is not $17$. So $5$ is not a solution.

This *check by substitution* is the safest move in algebra. After every solve, plug the answer back in. If it works, you are done. If not, retrace your steps and find the error. The check costs a minute and saves an exam.

### The four legal moves

There are exactly four operations you can perform on an equation that preserve truth. Each is one of the properties of real numbers from chapter 1, applied to *both sides* of the equation.

**Addition Property of Equality.** If $a = b$, then $a + c = b + c$ for any number $c$. *You can add the same number to both sides.*

**Subtraction Property of Equality.** If $a = b$, then $a - c = b - c$. *You can subtract the same number from both sides.*

**Multiplication Property of Equality.** If $a = b$, then $ac = bc$. *You can multiply both sides by the same number.*

**Division Property of Equality.** If $a = b$ and $c \ne 0$, then $a/c = b/c$. *You can divide both sides by the same nonzero number.*

The exclusion in the last one — *nonzero* — is the same exclusion you saw in chapter 1. Zero has no multiplicative inverse, so dividing by zero is undefined. If you "divide both sides by zero," what you have actually done is replace a real equation with the meaningless symbols $\frac{a}{0} = \frac{b}{0}$.

Strictly, only two moves are needed — addition and multiplication — because subtraction is addition of the opposite (chapter 1) and division is multiplication by the reciprocal. We name all four because, in practice, you will use all four.

### Why these are the only legal moves

A legal move on an equation is one that produces an *equivalent* equation — an equation with the same solution set. The four properties of equality produce equivalent equations because each operation is *reversible*: if you added five to both sides, you can subtract five from both sides and recover the original. Reversibility is what guarantees that you have not lost or gained any solutions in the process.

By contrast, *squaring both sides* or *multiplying both sides by a variable expression* are not always legal. Squaring can introduce false solutions; multiplying by an expression that could be zero can introduce false solutions or hide real ones. We will meet both of those traps in chapter 8 (rational equations) and chapter 9 (radical equations). For now, the four moves above are the entire toolkit.

### A worked example, with every step

> **Problem.** Solve $3x + 5 = 17$.

> *Step 1.* Subtract $5$ from both sides (Subtraction Property):
>
> $$3x + 5 - 5 = 17 - 5$$
> $$3x = 12.$$
>
> *Step 2.* Divide both sides by $3$ (Division Property):
>
> $$\frac{3x}{3} = \frac{12}{3}$$
> $$x = 4.$$
>
> *Step 3 — verification.* Substitute $x = 4$ back into the original:
>
> $$3(4) + 5 = 17 \quad \checkmark.$$
>
> **Answer:** $x = 4$.
>
> *General lesson:* undo the operations in *reverse order*. The original expression added $5$ after multiplying by $3$. To unwind, first undo the addition (subtract $5$), then undo the multiplication (divide by $3$). The unwind order is the reverse of the build order. This is the same rule you use to take off a sweater: the last layer on is the first layer off.

### The trade-off

The balance metaphor is one of the great pedagogical tools in mathematics. It makes the abstract concrete: an equation is a balance, and the four properties are the moves that keep it balanced. Students who internalize the balance picture stop making the most common error in beginning algebra — *operating on only one side*.

The trade-off is that the balance metaphor only carries you so far. Once equations involve negative numbers, fractions, decimals, and absolute values, the picture of a physical pan starts to strain. By the time you reach inequalities and the flip rule (Concept 3), the picture actively misleads — you cannot see, on a real-world pan balance, why multiplying both sides by a negative number reverses the direction of the imbalance. The balance is the *training wheels*. Eventually you ride without it.

### Common misconceptions

- *"I can't subtract a bigger number from a smaller one."* You can. The result is negative. $5 - 17 = -12$. The number line in chapter 1 holds the answer.
- *"Dividing both sides by $x$ should be fine."* It is not, in general. If $x$ could equal zero, you have either committed division by zero or thrown away a solution. Until you reach chapter 8, do not divide both sides of an equation by a variable expression.
- *"I added something to one side; the other side is still equal."* No. The two sides are only equal if the *same* operation is performed on both. Operating on one side is the most common — and most expensive — error in beginner algebra.

---

## 3. Concept 2 — A general strategy, and the three kinds of linear equation

The equations in Concept 1 came pre-tidied: variable on one side, constant on the other, no parentheses, no fractions. Real equations are messier. Variables appear on both sides; parentheses gather terms; coefficients arrive as fractions or decimals. To solve any of these, you need a *strategy* — a fixed sequence of moves that transforms a messy equation into a tidy one before you isolate the variable.

A motorcyclist learning to ride does not ad-hoc the steering on every curve. He learns a procedure: look through the curve, lean, throttle, lift. The procedure becomes invisible with practice. The same is true for solving linear equations. There is a procedure. It works every time. It becomes invisible.

### The strategy, written out

To solve a linear equation in one variable:

1. **Simplify each side separately.** Distribute through any parentheses. Combine like terms. After this step, each side is a single sum of terms, each term either a constant or a constant times the variable.
2. **Move all variable terms to one side.** Use the Addition or Subtraction Property to put every term containing the variable on, say, the left side. The right side now contains only constants.
3. **Move all constants to the other side.** Use the Addition or Subtraction Property again to put every constant term on the right.
4. **Isolate the variable.** Divide both sides by the coefficient of the variable. (Or, equivalently, multiply by its reciprocal.)
5. **Check.** Substitute back into the original.

The strategy never changes. The same five steps solve $5(x - 2) = 3x + 4$ and they solve $\frac{2}{3}x + \frac{1}{4} = \frac{5}{6}$ and they solve $0.05x + 0.20(100 - x) = 0.10(100)$. Practice makes the steps disappear.

### A worked example

> **Problem.** Solve $5(x - 2) = 3x + 4$.

> *Step 1 — simplify each side.* Distribute on the left:
>
> $$5x - 10 = 3x + 4.$$
>
> *Step 2 — variables to one side.* Subtract $3x$ from both sides:
>
> $$5x - 3x - 10 = 4$$
> $$2x - 10 = 4.$$
>
> *Step 3 — constants to the other side.* Add $10$ to both sides:
>
> $$2x = 14.$$
>
> *Step 4 — isolate.* Divide both sides by $2$:
>
> $$x = 7.$$
>
> *Step 5 — check.* Substitute $x = 7$ into the original:
>
> $$5(7 - 2) = 5(5) = 25, \qquad 3(7) + 4 = 21 + 4 = 25. \quad \checkmark$$
>
> **Answer:** $x = 7$.

### Clearing fractions and decimals

When fractions or decimals appear in the coefficients, the arithmetic at every step gets messier than it has to be. The fix is to clear them at the start.

For *fractions*, multiply both sides of the equation by the **least common denominator** of all fractions present. Every denominator divides cleanly into the LCD, so every fraction becomes a whole number.

> **Problem.** Solve $\frac{2}{3}x + \frac{1}{4} = \frac{5}{6}$.

> The denominators are $3$, $4$, $6$. Their LCD is $12$. Multiply both sides by $12$:
>
> $$12 \cdot \frac{2}{3}x + 12 \cdot \frac{1}{4} = 12 \cdot \frac{5}{6}$$
> $$8x + 3 = 10.$$
>
> Now the equation is integer-coefficient. Subtract $3$ and divide by $8$:
>
> $$8x = 7 \quad\Longrightarrow\quad x = \frac{7}{8}.$$

For *decimals*, multiply both sides by a power of ten large enough to clear every decimal point. If the longest decimal has two places, multiply by $100$.

> **Problem.** Solve $0.05x + 0.20(100 - x) = 0.10(100)$.

> Distribute first:
>
> $$0.05x + 20 - 0.20x = 10.$$
>
> Combine like terms:
>
> $$-0.15x + 20 = 10.$$
>
> Multiply both sides by $100$ to clear the decimal:
>
> $$-15x + 2000 = 1000.$$
>
> Subtract $2000$ and divide by $-15$:
>
> $$-15x = -1000 \quad\Longrightarrow\quad x = \frac{-1000}{-15} = \frac{200}{3} \approx 66.67.$$

This problem is, by the way, a *mixture problem* — concentrations of two solutions blending to a target concentration. We will meet a family of these in chapter 3.

### The three kinds of linear equation

Most linear equations have exactly one solution, like the examples above. But two pathological cases exist, and you have to recognize them or you will solve in circles.

**Conditional equation — exactly one solution.** The equation is true for one specific value of the variable. *Examples:* $3x + 5 = 17$, $5(x-2) = 3x + 4$. The strategy above produces the unique solution.

**Identity — every real number is a solution.** When you apply the strategy, the variables cancel out and you are left with a true statement, like $7 = 7$ or $0 = 0$. *Example:*

$$2(x + 3) = 2x + 6.$$

Distribute on the left: $2x + 6 = 2x + 6$. Subtract $2x$: $6 = 6$. The equation is *always* true; every real number is a solution. The two sides of the original are not really two different expressions — they are the same expression in different clothes. The distributive property guaranteed it.

**Contradiction — no solution.** When you apply the strategy, the variables cancel out and you are left with a *false* statement, like $5 = 7$ or $0 = 3$. *Example:*

$$3x + 4 = 3x + 7.$$

Subtract $3x$: $4 = 7$. There is no value of $x$ that makes the original true; the equation is a contradiction.

The recognition rule: when the strategy makes the variable disappear, look at the constant statement that remains. If it is true, every real number is a solution. If it is false, no number is.

### The trade-off

The general strategy is universal: it solves every linear equation in one variable in finitely many steps. The trade-off is that it is *procedural*. Following the strategy without thinking turns a student into a calculator. The strategy is most useful when paired with the *insight* — the ability to look at $2(x + 3) = 2x + 6$ and recognize, before any work, that the two sides are the same expression and the equation is an identity. Pattern recognition saves time. The strategy is the safety net when pattern recognition fails.

### Common misconceptions

- *"$5(x - 2)$ is the same as $5x - 2$."* No — the negative sign distributes too. $5(x - 2) = 5x - 10$. Forgetting to distribute through the negative is among the top three sources of sign errors in algebra.
- *"If the variable cancels, I made a mistake."* Sometimes. But sometimes it is an identity or contradiction. Read the resulting constant statement. If it is true, the original equation is an identity; if false, a contradiction.
- *"I cleared the fractions, so the answer is whatever the integer-coefficient equation gives."* Yes — but check against the *original* equation, not the cleared version. A computational error in the clearing step will produce an answer that satisfies the cleared equation but not the original.

---

## 4. Concept 3 — Inequalities and the flip rule

Two friends are running a foot race. After the gun, the friend on the left is ahead. To say so in the language of mathematics: $L > R$, where $L$ and $R$ are their positions on the course measured from the start.

Now turn the camera around and measure their positions from the *finish line*. The friend who was ahead — closer to the finish — now has the *smaller* number, because she has less distance to go. From this new vantage, $L < R$. The fact has not changed; only the direction of measurement.

That swap is what the flip rule is about.

An **inequality** is a sentence claiming that one expression is *less than*, *less than or equal to*, *greater than*, or *greater than or equal to* another. The symbols are $<$, $\le$, $>$, $\ge$. A **solution** is any value of the variable that makes the inequality true. Most inequalities have *infinitely many* solutions — usually a half-line on the number line — and the work is to describe that solution set, not to find a single number.

### The first three legal moves are the same as for equations

If you add the same number to both sides of an inequality, the inequality is preserved. If you subtract, ditto. If you multiply or divide both sides by a *positive* number, ditto. *Example:*

$$3x + 5 < 17.$$

Subtract $5$ from both sides:

$$3x < 12.$$

Divide both sides by $3$ (positive):

$$x < 4.$$

So the solution set is *every real number less than $4$*. On the number line: an open circle at $4$, with shading extending to the left.

In **interval notation**, this set is written $(-\infty, 4)$. The parenthesis means "not including"; the bracket would mean "including." Infinity always gets a parenthesis, because you cannot reach infinity to include it.

### The flip rule

The fourth move — multiply or divide both sides by a *negative* number — has a twist. Doing so *reverses* the direction of the inequality.

Why? Picture the number line. The inequality $3 < 5$ is true: $3$ sits to the left of $5$. Now multiply both sides by $-1$. We get $-3$ on the left and $-5$ on the right. But on the number line, $-3$ sits to the *right* of $-5$ — they have switched places. So $-3 > -5$, not $-3 < -5$. The relation has flipped.

This is not a special algebra rule glued onto inequalities. It is a direct consequence of how negation acts on the number line: multiplying by a negative reflects every number across zero, and reflection reverses left-and-right order.

The rule, written:

> If $c < 0$ and $a < b$, then $ac > bc$. *Flip the inequality when you multiply or divide by a negative.*

A worked example:

> **Problem.** Solve $-2x + 7 \ge 1$.

> Subtract $7$ from both sides (no flip):
>
> $$-2x \ge -6.$$
>
> Divide both sides by $-2$ (flip!):
>
> $$x \le 3.$$
>
> Solution set: $(-\infty, 3]$. The bracket on $3$ is correct because the original inequality was $\ge$, and after the flip it became $\le$, which includes $3$.

The most common error in inequality problems is forgetting to flip. Every student does it once. Mark the flip explicitly when it happens — write the new inequality direction immediately after the divide step, before continuing — and you will catch yourself.

### Compound inequalities, briefly

Two inequalities joined by *and* describe an intersection of solution sets; *or* describes a union. The compound inequality $-3 < x < 7$ — read *negative three is less than $x$ and $x$ is less than seven* — describes every real number strictly between $-3$ and $7$. In interval notation: $(-3, 7)$. Compound inequalities will recur in later chapters; the formal treatment of unions and intersections deferred to a later course.

### Trade-offs

An inequality and an equation differ in one structural way: an equation usually has finitely many solutions; an inequality almost always has infinitely many. That changes how you describe the answer. *Number-line diagrams* and *interval notation* exist because writing out every solution is impossible.

The trade-off is that students often arrive expecting an inequality to behave like an equation that returns a single number. They solve $-2x + 7 \ge 1$, get $x \le 3$, and write the answer as "$3$." That is wrong — it confuses a *boundary value* with the *solution set*. Three is the boundary; the solution set is *everything to the left of and including three*. Inequalities are about *regions*, not points.

### Common misconceptions

- *"I always flip the inequality when I divide."* No — only when you divide (or multiply) by a *negative* number. Dividing both sides by a positive does not flip.
- *"$-x < 5$ means $x > -5$."* Yes — multiply both sides by $-1$ and flip. The result is $x > -5$. (This is one place students often correctly recall the flip but apply it wrong; double-check by substituting a value.)
- *"The boundary value is the solution."* No — for strict inequalities ($<$, $>$), the boundary is *excluded*. For non-strict ($\le$, $\ge$), it is included. Open circles vs. closed circles on the number line; parentheses vs. brackets in interval notation.

![Two number lines stacked vertically. Top line: open circle at 4 with shading extending to the left, labeled "$x < 4$" and "$(-\infty,...](images/02-solving-linear-equations-and-inequalities-fig-01.png)
*Figure 2.1 — Two number lines stacked vertically*$". Pedagogical purpose: contrast strict vs. non-strict inequalities visually.]

---

## 5. Integration / Synthesis

A salesperson is paid \$1{,}500 per month plus a commission of \$60 per unit sold. Her monthly income goal is \$3{,}900. *How many units must she sell to reach the goal — and how many to exceed it?*

This problem uses every concept in the chapter.

### Setting up

Let $u$ be the number of units sold. Her monthly income, in dollars, is $1500 + 60u$ — a constant base plus a variable component. The goal is for that income to be at least $3900$:

$$1500 + 60u \ge 3900.$$

Two questions:

1. *What is the smallest $u$ that makes the inequality true?* (Reach the goal.)
2. *What is the solution set?* (Reach or exceed.)

### Solving (Concept 1 + Concept 2)

Subtract $1500$ from both sides — Subtraction Property of Inequality:

$$60u \ge 2400.$$

Divide both sides by $60$ — positive, so no flip:

$$u \ge 40.$$

Solution set: $[40, \infty)$.

So the answer to question 1 is *forty units* — sell forty and the income exactly hits the goal. The answer to question 2 is *forty or more*.

### Checking (Concept 1)

Verify $u = 40$ in the original boundary case:

$$1500 + 60(40) = 1500 + 2400 = 3900. \quad \checkmark$$

The boundary is included because the original inequality used $\ge$, not $>$.

### What this shows

The concepts of the chapter are not independent. The *balance principle* (Concept 1) gave us the legal moves. The *general strategy* (Concept 2) told us the order to apply them. The *flip rule* of inequalities (Concept 3) was not invoked — because we divided by a positive — but if her commission had been *negative* (a fee deducted per unit?), the same problem would have flipped the inequality at the divide step.

The unifying idea: to solve any linear equation or inequality, identify what operations have been done to the variable, then undo them in reverse order — applying the same operation to both sides at every step, flipping if you cross a negative. The structure is always the same.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** Solve $x + 9 = 23$.

2. **(LO 1, easy)** Solve $\dfrac{x}{4} = -3$.

3. **(LO 1, easy)** Solve $-7y = 35$.

4. **(LO 5, easy)** Solve and graph on a number line: $x - 3 < 5$.

### Application

5. **(LO 1, 2, medium)** Solve $4(2x - 3) = 5x + 6$.

6. **(LO 4, medium)** Solve by clearing fractions: $\dfrac{1}{2}x - \dfrac{1}{3} = \dfrac{1}{6}x + 1$.

7. **(LO 3, medium)** Classify each as conditional, contradiction, or identity, then solve where possible:
   (a) $5(x + 2) = 5x + 10$
   (b) $7x - 4 = 7x + 9$
   (c) $3x + 1 = 10$

8. **(LO 5, medium)** Solve and write in interval notation: $-3x + 8 \le 17$.

### Synthesis

9. **(LO 1, 2, 4, harder)** Solve by clearing decimals: $0.06x + 0.04(20 - x) = 0.05(20)$. Then check whether your answer makes sense given that the equation is a mixture problem (acid concentrations, total volume 20 mL).

10. **(LO 1, 2, 5, harder)** A taxi service charges \$3.50 plus \$2.20 per mile. A rider has \$30. Write an inequality describing the maximum distance she can travel without exceeding her budget, solve it, and describe the solution set in words and in interval notation.

11. **(LO 5, harder)** Solve and graph on a number line: $-2 < 3x - 5 \le 7$. (This is a compound inequality; the solution is the set of $x$ values that make *both* inequalities true.)

### Challenge

12. **(LO 5, hard)** Construct a linear inequality that requires the flip rule and whose solution set is $(-\infty, -2]$. Then construct a different linear inequality with the same solution set that does *not* require the flip rule. What does this exercise show about the relationship between an inequality's surface form and its solution set?

13. **(LO 3, hard, points to chapter 5)** Find a value of $k$ for which the equation $3(x - 2) = kx - 6$ is an identity. Find a value of $k$ for which it is a contradiction. Find a value of $k$ for which it is a conditional equation, and solve it for that $k$. Explain in one sentence what role $k$ plays.

---

## 7. Chapter summary

You came in able to simplify expressions. You leave able to *solve* equations and inequalities.

You know what an equation is — a claim that two expressions name the same number — and you know that solving means transforming the claim, one legal move at a time, into a simpler claim that names the value of the variable. You know the four legal moves: add, subtract, multiply, or divide by the same number on both sides (with division forbidden when the divisor is zero). You know that each move corresponds to a property of real numbers from chapter 1, applied with the goal of isolating the variable.

You can apply the general strategy: simplify each side, gather variables on one side and constants on the other, isolate. You know how to clear fractions by multiplying by the LCD and clear decimals by multiplying by a power of ten. You can recognize the three kinds of linear equation — conditional, identity, contradiction — by what happens when the variables cancel: a true constant statement means an identity; a false one means a contradiction.

You can solve linear inequalities using the same moves, with one twist: multiplying or dividing both sides by a negative number reverses the inequality, because multiplication by a negative reflects every number across zero on the number line. You can write solutions in interval notation and graph them on a number line.

The single most important idea: *every step in solving is reversible, and that reversibility is what guarantees the solution.* When a step is irreversible — squaring both sides, multiplying by a variable that could be zero — solutions can appear or disappear. Watch for those cases in chapter 8 and chapter 9.

The most common mistake to watch for: forgetting to flip the inequality when dividing or multiplying by a negative. Mark the flip explicitly. Every student misses it the first time; few miss it the second.

What you should be able to teach someone else: why dividing both sides by zero is forbidden, why $5(x - 2)$ equals $5x - 10$ and not $5x - 2$, why an identity means *every* real number is a solution while a contradiction means *no* real number is, and why the inequality flips when you multiply by a negative.

---

## 8. Connections forward

Chapter 3 turns the work of this chapter into a tool for problem-solving in the world. Word problems — about ages, money, mixtures, distances, geometric shapes — translate into equations of exactly the type you can now solve. The translation step is the new skill. Once the equation is on the page, the solving is what you just learned.

Chapter 4 introduces the *graph* of a linear equation in two variables. The single-variable equations in this chapter have one solution (or none, or all reals). Two-variable equations have *infinitely many* solutions, and the graph — a line in the coordinate plane — is the picture of the solution set. The graph turns out to be a more revealing object than the algebra; the slope and the intercepts will tell you, at a glance, what the equation is doing.

Bring the balance principle with you. Whatever the equation looks like — one variable, two, three; a polynomial; a rational expression; a system — *whatever you do to one side, you must do to the other*. That rule never changes.

---

**What would change my mind:** If a careful empirical study of how students solve linear equations showed that the "general strategy" of step 1–step 5 leads to more rote application and worse transfer than a more flexible, insight-first pedagogy, I'd reconsider whether to teach the strategy as the spine of the chapter. The strategy is a safety net; the question is whether nets become crutches.

**Still puzzling:** Why is the flip rule so universally surprising to students who otherwise comfortably handle negative numbers on the number line? The geometric reason is clean — multiplication by a negative is a reflection across zero, and reflection reverses order — but the algebraic statement still feels arbitrary on first encounter. Whether better imagery (a literal mirror placed at zero?) would close that gap, I am not sure.

---

**Tags:** linear-equations, inequalities, properties-of-equality, balance-principle, flip-rule, conditional-identity-contradiction, interval-notation, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 2 (modules m82462–m82470), used under CC-BY 4.0. Source content (definitions, the four properties of equality, the inequality flip rule, worked-example structure, mixture-problem framing) derives from OpenStax. Voice, scenes, framings, and pedagogical commentary are original to this rewrite.*
---

## LLM Exercise — Chapter 2: Solving Linear Equations and Inequalities (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon.
**What you're building this chapter:** the first linear model — a single linear equation that describes one relationship in your phenomenon, plus a linear inequality that names a constraint.
**Tool:** **Claude Project** "Modeling [Your Phenomenon]" — appends a section.

---

**The Prompt:**

```
Chapter 2 of my Modeling project. The Foundation Document for my
phenomenon is in this Claude Project. Chapter 2 taught: the balance
principle (do the same operation to both sides of an equation); a
general strategy for solving linear equations (simplify, isolate
the variable using the balance principle); three classifications
(conditional — one solution; identity — infinite solutions;
contradiction — no solution); linear inequalities and the flip
rule (when you multiply or divide both sides by a negative,
reverse the inequality sign).

Write the brief's "Linear Model" section in 400–600 words.

1. **The linear relationship.** Pick the SINGLE most important
   linear relationship in your phenomenon. Write it as a linear
   equation. Be explicit:
   - Which variable is on each side.
   - What the coefficient means physically.
   - What the constant term means physically.
   Example for compound interest with simple-interest approximation:
   `A = P + Prt` becomes `A = P(1 + rt)`, a linear relationship in
   t with slope Pr and intercept P. Be specific about your
   phenomenon.

2. **Solve for an unknown.** Pick a specific question your linear
   equation can answer:
   - "Given P = $10,000 and r = 0.05, at what t does A = $15,000?"
   - "If I want to hit a 200-pound bench by age 30, given my 165
     today at age 25, what monthly progression rate does that
     require?"
   Solve it step by step. Show the balance-principle moves
   explicitly — don't skip steps.

3. **Add a constraint as an inequality.** What real-world
   constraint operates on your phenomenon? "Time must be ≥ 0,"
   "Cost must be ≤ budget B," "Distance must be ≤ track length."
   Write the constraint as a linear inequality. Solve it. Apply
   the flip rule if you need to (and name when you did).

4. **Identify the model's limits.** A linear model is the simplest
   possible model. Where does the linear assumption hold in your
   phenomenon, and where does it break? "Linear is fine for the
   first 6 months; after that, the actual phenomenon grows
   slower/faster than linear." This sets up the polynomial and
   quadratic models in Chs 6 and 10.

End with the model's first prediction. Plug in specific numbers
and predict an outcome. Test the prediction against reality (or
your best knowledge of the phenomenon). Note any discrepancy —
the discrepancies are what future chapters will fix.
```

---

**What this produces:** A 400–600 word section with one linear equation, one solved unknown, one inequality constraint, and one tested prediction. The section's most useful output is the named gap between linear-model prediction and reality.

**How to adapt this prompt:**

- *For your own project:* If your phenomenon is fundamentally nonlinear (population growth, projectile motion), the linear model is a local approximation. Be honest about where it's valid.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* Optional sidecar — Claude Code can solve the equation symbolically with SymPy and verify your hand calculation.
- *For a Claude Project:* Append to the building document.

**Connection to previous chapters:** Chapter 1's Foundation Document named variables and units; Chapter 2 uses them in a real equation.

**Preview of next chapter:** Chapter 3 applies the 5-step word-problem strategy to your phenomenon. You'll write a full word problem in your domain and solve it using the strategy — bridging from textbook abstraction to your own model.


---

##  AI Wayback Machine

**Run this:**

```
Who is al-Khwarizmi, and how does their work connect to linear equations and inequalities we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"al-Khwarizmi"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way al-Khwarizmi would have.
- Add a constraint: "Answer including criticisms or limits of al-Khwarizmi's methods."

What changes? What gets better? What gets worse?

## Prompts

Use these prompts with Claude to generate interactive D3 v7 versions of the
figures in this chapter. Each produces a standalone HTML file you can open
in a browser and modify freely.

**Prerequisites:** Load `brutalist/CLAUDE.md` and `brutalist/DESIGN.md` into
your Claude project context before using these prompts. They define the stack,
naming conventions, color system, and typography the figures use.

---

### Figure 2.1 — Two number lines stacked vertically

Create a standalone D3 v7 HTML figure for "Two number lines stacked vertically". Use a horizontal bar chart with 5 labeled categories with approximate values from 0 to 100. Marks: bars or rectangular panels, direct labels, and concise value labels. Channels: position for sequence or category, length for quantitative emphasis when bars are used, color for the primary highlighted item only, and direct text labels for accessibility. Use a zero baseline for quantitative bars. Include title, desc, role="img", aria-labelledby, ResizeObserver redraw, dark mode CSS variables, and reduced-motion safeguards. Deliver as one HTML file with inline CSS and the D3 7.9.0 CDN.

> Reference implementation: `d3/02-solving-linear-equations-and-inequalities-fig-01.html`
