---
book: prealgebra-bundle
chapter: 05-systems-of-linear-equations
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 5 (CC-BY 4.0). Modules m82489–m82499.
status: draft
---

# Suggested titles

1. Two Equations, One Truth
2. Systems: Where the Lines Cross
3. The Geometry of Simultaneous Constraints

---

**TL;DR.** A system of linear equations is two or more equations that must hold at the same time. A solution is an ordered pair that satisfies *every* equation in the system. Geometrically, you are finding the intersection of two lines; algebraically, you are reducing two equations in two unknowns to one equation in one unknown by substitution or elimination.

---

## 1. Chapter opening

Two cyclists agree to meet on a stretch of straight rural road between their two homes. The road is fifty miles long. Aiya leaves her house — at mile zero — at noon, riding east at eighteen miles per hour. Boris leaves his house — at mile fifty — at noon, riding west at twelve miles per hour. *Where on the road do they meet, and at what time?*

This problem has two unknowns (the meeting position and the time elapsed) and two pieces of information (Aiya's motion and Boris's motion). Each piece of information becomes one equation. Together they form a *system*. The solution is the single moment in space and time when both motions are consistent.

Aiya's position, in miles east of mile zero, after $t$ hours is $a(t) = 18t$. Boris's position, in miles east of mile zero, after $t$ hours is $b(t) = 50 - 12t$ — he started at mile fifty and is moving west. They meet when their positions are equal: $18t = 50 - 12t$. Solve: $30t = 50$, so $t = 5/3$ hours = $1$ hour $40$ minutes. Position: $18 \times 5/3 = 30$ miles east of Aiya's house, or twenty miles west of Boris's. They meet at $1{:}40$ p.m. at mile thirty.

The trick was reducing two unknowns to one. Aiya's equation alone has infinitely many solutions; Boris's alone has infinitely many; *together*, they have exactly one. The intersection of the two lines on the time-versus-position graph is the single point that both equations describe.

This chapter is about that intersection. Two equations in two unknowns. Three ways to find the solution — graphing, substitution, elimination — and one taxonomy: a system has either one solution, no solutions, or infinitely many.

### Learning objectives

By the end of this chapter you should be able to:

- **Verify** that an ordered pair is a solution of a system of two linear equations.
- **Solve** a system of two linear equations by **graphing**, **substitution**, or **elimination**.
- **Classify** a system as **consistent and independent** (one solution), **inconsistent** (no solution, parallel lines), or **dependent** (infinitely many solutions, identical lines).
- **Choose** the most convenient method based on the form of the equations.
- **Set up and solve** systems for applications — mixture, money, motion, and geometric.
- **Graph** the solution region of a system of two linear inequalities.

### Prerequisites

Chapters 2, 3, and 4. You should be able to solve a single linear equation, set up word problems, and graph a line from any of its forms. The new work is *combining* two equations into one solution.

### Why this chapter matters

Almost no real problem has only one variable. A budget has dollars and time. A diet has calories and protein. A circuit has voltage and current. A flight plan has fuel and distance. Most of practical mathematics is the algebra of *several* unknowns balanced against *several* constraints, and the smallest nontrivial case — two of each — is the entire content of this chapter. Master the two-by-two case and the three-by-three (and the n-by-n that linear algebra studies) feels like more of the same.

---

## 2. Concept 1 — What a system is, and the three outcomes

In chapter 4, you learned that a single linear equation in two variables has infinitely many solutions, all lying on one line. A system of two such equations asks: *which ordered pairs lie on both lines at once?* The answer depends on how the two lines sit relative to each other.

### The three geometric outcomes

**Case A: The two lines cross at one point.** Exactly one ordered pair satisfies both equations. The system is **consistent** (it has a solution) and **independent** (the two equations carry different information). This is the typical case.

**Case B: The two lines are parallel and distinct.** They have the same slope, different y-intercepts, and never meet. No ordered pair satisfies both. The system is **inconsistent** (no solution).

**Case C: The two lines are identical.** Same slope, same y-intercept — different-looking equations describing the same line. Every ordered pair on the line satisfies both. The system is **consistent** and **dependent** (infinitely many solutions).

This taxonomy mirrors the conditional/contradiction/identity taxonomy of single linear equations from chapter 2 §3, and for the same reason: a system reduces to a single linear equation in the elimination or substitution method, and that single equation falls into one of those three categories.

[FIGURE: Three small coordinate planes side by side. Left plane shows two lines crossing at one point, labeled "(A) one solution — consistent, independent." Middle plane shows two parallel lines, labeled "(B) no solution — inconsistent." Right plane shows two identical lines (drawn as one), labeled "(C) infinitely many solutions — consistent, dependent." Pedagogical purpose: place the three outcomes side-by-side so the geometric distinction is visually unmistakable.]

### Verifying a candidate solution

To verify $(x, y)$ is a solution of a system, substitute into *both* equations. The pair must satisfy both.

> **Example.** Is $(2, 1)$ a solution of $\begin{cases} x + y = 3 \\ 2x - y = 3 \end{cases}$?
>
> First equation: $2 + 1 = 3$. $\checkmark$
> Second equation: $2(2) - 1 = 3$. $\checkmark$
>
> Yes, $(2, 1)$ is a solution.

### Solving by graphing

Graph each line on the same coordinate plane. The intersection point is the solution.

This method is *visual*, *intuitive*, and *limited*. If the solution involves non-integer coordinates, a hand-drawn graph reads them only approximately. If the lines are nearly parallel, the intersection is hard to locate by eye. Graphing is excellent for *seeing* what kind of system you have (one solution / parallel / identical), but for *exact* answers you should use substitution or elimination.

> **Example.** Solve $\begin{cases} y = x + 1 \\ y = -x + 5 \end{cases}$ by graphing.
>
> First line: y-intercept $1$, slope $1$. Plot $(0, 1)$, $(1, 2)$, $(2, 3)$.
> Second line: y-intercept $5$, slope $-1$. Plot $(0, 5)$, $(1, 4)$, $(2, 3)$.
>
> Both lines pass through $(2, 3)$. That is the solution.

### The trade-off

Graphing makes the *kind* of system visible — students who graph regularly stop confusing inconsistent with dependent. But graphing does not produce exact non-integer answers, and it requires drawing two lines accurately. The algebraic methods of Concept 2 are more precise; they trade the picture for symbolic exactness.

### Common misconceptions

- *"If the two equations look different, the system has one solution."* Not necessarily — the equations $y = 2x + 3$ and $4x - 2y = -6$ look different but describe the same line; the system is dependent, infinitely many solutions.
- *"No solution means the system has zero variables."* No — it means no ordered pair satisfies both equations. The variables are still there; the constraints are simply incompatible.
- *"Graphing is always the easiest method."* Only if the solution involves easy integer coordinates. For most real systems, substitution or elimination is faster and more accurate.

---

## 3. Concept 2 — Substitution and elimination

Two algebraic methods solve any consistent system exactly, and one of them is almost always more convenient than the other. The choice depends on the form of the equations.

### Substitution

The idea: solve one equation for one variable, then substitute the resulting expression into the other equation. The substitution turns a two-variable problem into a one-variable problem, which you solved in chapter 2.

**Best when** one equation is already (or easily) solved for one variable.

> **Example.** Solve $\begin{cases} y = 2x - 3 \\ x + y = 6 \end{cases}$ by substitution.
>
> *Step 1.* The first equation already has $y$ isolated.
>
> *Step 2.* Substitute $2x - 3$ for $y$ in the second equation:
>
> $$x + (2x - 3) = 6.$$
>
> *Step 3.* Solve: $3x - 3 = 6$, so $3x = 9$, $x = 3$.
>
> *Step 4.* Back-substitute. Plug $x = 3$ into either original equation. Using the first: $y = 2(3) - 3 = 3$.
>
> *Step 5.* Verify in both originals.
> First: $y = 2x - 3 \Rightarrow 3 = 2(3) - 3 = 3$. $\checkmark$
> Second: $x + y = 6 \Rightarrow 3 + 3 = 6$. $\checkmark$
>
> **Answer:** $(3, 3)$.

### Elimination

The idea: add or subtract the two equations to eliminate one of the variables. If the coefficients of one variable are not already opposites, multiply each equation by a suitable constant to make them so.

**Best when** the equations are in standard form $ax + by = c$, especially if no variable has coefficient $1$.

> **Example.** Solve $\begin{cases} 3x + 2y = 12 \\ 5x - 2y = 4 \end{cases}$ by elimination.
>
> *Step 1.* The y-coefficients are $+2$ and $-2$ — already opposites.
>
> *Step 2.* Add the equations:
>
> $$8x + 0 = 16, \quad x = 2.$$
>
> *Step 3.* Back-substitute. Plug $x = 2$ into either original. First: $3(2) + 2y = 12 \Rightarrow 2y = 6 \Rightarrow y = 3$.
>
> *Step 4.* Verify both originals.
> $3(2) + 2(3) = 12 \checkmark$, $5(2) - 2(3) = 4 \checkmark$
>
> **Answer:** $(2, 3)$.

A more typical elimination example, where you must scale first:

> **Example.** Solve $\begin{cases} 2x + 3y = 7 \\ 5x + 4y = 14 \end{cases}$.
>
> Eliminate $x$. Multiply the first equation by $5$ and the second by $-2$:
>
> $$10x + 15y = 35$$
> $$-10x - 8y = -28$$
>
> Add: $7y = 7$, so $y = 1$. Back-substitute: $2x + 3(1) = 7 \Rightarrow x = 2$.
>
> **Answer:** $(2, 1)$. Verify in both originals.

### Choosing the method

| Form of system | Best method |
| --- | --- |
| One equation has $y$ (or $x$) isolated | Substitution |
| One coefficient is $1$ or $-1$ | Substitution |
| Both equations in standard form | Elimination |
| Coefficients of one variable are already opposites or equal | Elimination |
| Approximate / visual answer wanted | Graphing |

### Inconsistent and dependent systems — what the algebra looks like

When the algebra of substitution or elimination produces a *false* statement like $0 = 5$, the system is **inconsistent**: no solution.

When the algebra produces a *true* statement like $0 = 0$, the system is **dependent**: infinitely many solutions, every point on the common line.

> **Inconsistent example.** $\begin{cases} y = 3x + 2 \\ -3x + y = 5 \end{cases}$.
> Substitute the first into the second: $-3x + (3x + 2) = 5 \Rightarrow 2 = 5$. False. No solution. *(The two lines are parallel — same slope $3$, different y-intercepts.)*

> **Dependent example.** $\begin{cases} y = 2x + 1 \\ 4x - 2y = -2 \end{cases}$.
> Substitute: $4x - 2(2x + 1) = -2 \Rightarrow 4x - 4x - 2 = -2 \Rightarrow -2 = -2$. True. Infinitely many solutions. *(Both equations describe the same line.)*

The recognition rule, again: when the variables disappear, the resulting constant statement classifies the system. True ⇒ dependent. False ⇒ inconsistent.

### The trade-off

Substitution is conceptually clean but algebraically messy when fractions appear. Elimination is conceptually a bit more abstract — *why* should adding two equations give us new information? — but algebraically tidier. The honest answer is that practitioners flip between them, often within the same problem, picking whichever isolates a variable fastest.

The deeper point: both methods reduce the system to a single linear equation in one variable. Both methods preserve the solution set at every step. Both methods are corollaries of the addition and multiplication properties of equality from chapter 2 — applied not to one equation but to a pair.

### Common misconceptions

- *"Substitution and elimination give different answers."* They do not, when applied correctly. If they appear to, find your error.
- *"Once I find $x$, I can stop."* No — the solution to a system of two equations in two variables is an *ordered pair*. Both $x$ and $y$ are part of the answer.
- *"After elimination, if both variables disappear, there's no solution."* Only if the resulting statement is false. If it is true, the system is dependent.

---

## 4. Concept 3 — Setting up systems for applications

The five-step strategy from chapter 3 still applies. The new piece is *naming two unknowns* and writing *two equations* — one for each constraint.

### Translation: two unknowns, two equations

> **Example: a money problem.** A pile of $25$ coins is made up of nickels and dimes worth a total of \$1.85. How many of each?

> *Name.* Let $n$ = number of nickels and $d$ = number of dimes.
>
> *First constraint:* total number of coins is $25$:
> $$n + d = 25.$$
>
> *Second constraint:* total value is $\$1.85$, and a nickel is worth $\$0.05$, a dime $\$0.10$:
> $$0.05n + 0.10d = 1.85.$$
>
> *Solve.* Substitute $d = 25 - n$ into the second:
> $$0.05n + 0.10(25 - n) = 1.85$$
> $$0.05n + 2.50 - 0.10n = 1.85$$
> $$-0.05n = -0.65$$
> $$n = 13.$$
>
> Then $d = 25 - 13 = 12$.
>
> *Verify.* $13 + 12 = 25 \checkmark$. $0.05(13) + 0.10(12) = 0.65 + 1.20 = 1.85 \checkmark$.
>
> **Answer:** *13 nickels and 12 dimes.*

### Mixture and uniform-motion applications

The mixture template from chapter 3 takes a cleaner form here, because *amount* and *value* now each get their own variable.

> **Example: a mixture problem.** A chemist has a 25% acid solution and a 50% acid solution. She wants $200$ mL of $40\%$ acid. How many mL of each does she combine?

> Let $a$ = mL of $25\%$ solution, $b$ = mL of $50\%$ solution.
>
> *Volume constraint:* $a + b = 200$.
>
> *Acid constraint:* $0.25a + 0.50b = 0.40 \times 200 = 80$.
>
> Substitute $b = 200 - a$ into the acid equation:
> $$0.25a + 0.50(200 - a) = 80$$
> $$0.25a + 100 - 0.50a = 80$$
> $$-0.25a = -20$$
> $$a = 80.$$
>
> Then $b = 120$.
>
> *Verify.* $80 + 120 = 200 \checkmark$. $0.25(80) + 0.50(120) = 20 + 60 = 80 \checkmark$.
>
> **Answer:** *80 mL of 25% solution and 120 mL of 50% solution.*

### Boat-with-current — finally tractable

Recall the chapter 3 challenge: *a boat travels 36 miles downstream in 2 hours and 36 miles upstream in 3 hours. Find the boat's speed in still water and the current's speed.*

Let $b$ = boat's speed in still water (mph), $c$ = current speed (mph).

Downstream: speed = $b + c$, distance = $36$, time = $2$. So $b + c = 18$.
Upstream: speed = $b - c$, distance = $36$, time = $3$. So $b - c = 12$.

Add the two equations: $2b = 30$, so $b = 15$. Then $c = 3$.

**Answer:** *boat 15 mph in still water, current 3 mph.* Verify: downstream speed $18$ mph, $36/18 = 2$ hours. Upstream speed $12$ mph, $36/12 = 3$ hours. $\checkmark$

The setup that produced a quadratic equation in chapter 3 (synthesis problem with one unknown speed) becomes a clean system of two linear equations when you allow yourself two unknowns. *More variables can mean simpler algebra.* That is one of the lessons of this chapter.

### A brief preview of inequality systems

A *system of two linear inequalities* has a solution set that is a *region* of the plane — the intersection of two half-planes. To graph it: graph each boundary line (dashed if strict inequality, solid if non-strict), shade each side that satisfies its inequality, and the overlap is the solution.

> **Example.** Sketch the solution region for $\begin{cases} y \le 2x + 3 \\ y > -x + 1 \end{cases}$.

> Boundary 1: line $y = 2x + 3$, drawn solid (because $\le$). Shade *below* the line.
> Boundary 2: line $y = -x + 1$, drawn dashed (because $>$, strict). Shade *above* the line.
> Overlap: the region below the first line and above the second.

Systems of inequalities arise in linear programming — a technique for finding optimal allocations of scarce resources, used in scheduling, manufacturing, transportation, and finance. The full theory is the subject of a later course; here you only need to be able to graph the region.

### The trade-off

Two-equation systems handle two-unknown problems cleanly. The trade-off is computational cost: setting up two equations and solving the system takes more time than a one-equation problem. The gain is that two unknowns can be carried separately, and the *meaning* of each variable is preserved through the solving — easier to interpret the answer in context.

The reflexive note: not every two-unknown problem is a *linear* system. The chapter 3 round-trip problem, with its constraint of total time fixed, produced a *quadratic*. Chapter 8 will produce *rational* equations from systems involving rates of work. The two-equation, two-unknown structure is universal; the *type* of equations changes as the problem complicates.

### Common misconceptions

- *"With two unknowns, I need three equations."* No — two unknowns require two independent equations. A third would be redundant or inconsistent.
- *"I can use either substitution or elimination — it shouldn't matter."* It always works, but one is usually faster. Choose based on form.
- *"Adding the two equations always gives me a useful result."* Only if doing so eliminates a variable. Otherwise, scale one or both equations first.

---

## 5. Integration / Synthesis

A small business sells two products — handmade candles and ceramic mugs. Each candle takes 30 minutes of labor and \$4 of materials. Each mug takes 45 minutes of labor and \$6 of materials. The owner has 60 hours of labor budgeted for next week and \$640 for materials. *If she wants to use exactly all of her labor and exactly all of her materials, how many of each should she make?*

This problem combines all three concepts.

### Concept 1 — set up a system

Let $c$ = number of candles, $m$ = number of mugs.

*Labor constraint* (in hours; convert minutes): each candle takes $30/60 = 0.5$ hours, each mug takes $45/60 = 0.75$ hours. Total labor used: $0.5c + 0.75m = 60$.

*Materials constraint*: $4c + 6m = 640$.

System:

$$\begin{cases} 0.5c + 0.75m = 60 \\ 4c + 6m = 640 \end{cases}$$

### Concept 2 — solve

The fractions in equation 1 are awkward. Multiply equation 1 by $4$ to clear them:

$$2c + 3m = 240.$$

Now the system is

$$\begin{cases} 2c + 3m = 240 \\ 4c + 6m = 640 \end{cases}$$

Use elimination. Multiply the first by $-2$:

$$-4c - 6m = -480.$$

Add to the second:

$$0 = 160.$$

False. The system is *inconsistent*.

### What does that mean here?

The labor and materials constraints are not compatible. Look at the ratios: the second equation is exactly twice the first equation's left-hand side ($4c + 6m = 2 \cdot (2c + 3m)$), but the right-hand sides do not match the same ratio. If the materials budget were $\$480$ instead of $\$640$, the system would be dependent (infinitely many solutions, every $(c, m)$ on the labor line would also use all the materials). With \$640, the materials budget is incompatible with the labor budget at the given product specs.

The owner cannot use exactly all of both. She must choose: use all the labor and have leftover materials, or use all the materials and run out of labor partway through.

### What this shows

The classification matters. An inconsistent system in this context is not an algebra failure — it is an *operational* finding that the budget and product mix are misaligned. The math has identified a real-world constraint mismatch.

If the owner instead asked, *"What is the most candles and mugs I can make subject to my labor and materials limits?"* — the constraints become inequalities (*at most*), and the question becomes a linear programming problem. The optimum sits at a corner of the feasible region, the intersection of two boundary lines. That is one application of the brief inequality preview at the end of Concept 3.

The deeper lesson: a two-equation system can have one solution, no solution, or infinitely many — and which case obtains is itself an answer to a question about the original problem.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** Verify whether $(3, -1)$ is a solution of $\begin{cases} 2x + y = 5 \\ x - y = 4 \end{cases}$.

2. **(LO 2, easy)** Solve by substitution: $\begin{cases} y = 3x - 2 \\ x + y = 6 \end{cases}$.

3. **(LO 2, easy)** Solve by elimination: $\begin{cases} x + y = 7 \\ x - y = 1 \end{cases}$.

### Application

4. **(LO 2, medium)** Solve: $\begin{cases} 2x + 3y = 1 \\ 5x - y = 11 \end{cases}$.

5. **(LO 3, medium)** Solve and classify: $\begin{cases} 4x - 2y = 6 \\ -2x + y = -3 \end{cases}$.

6. **(LO 3, medium)** Solve and classify: $\begin{cases} y = 4x + 1 \\ -8x + 2y = 7 \end{cases}$.

7. **(LO 5, medium)** A jar holds $40$ coins, all dimes and quarters, totaling \$7.30. Find the number of each. Use a system of equations.

### Synthesis

8. **(LO 5, harder)** A boat travels $48$ miles downstream in $3$ hours and the same distance upstream in $4$ hours. Find the boat's speed in still water and the current's speed.

9. **(LO 5, harder)** A chemist has a $20\%$ alcohol solution and a $50\%$ alcohol solution. She wants $300$ mL of $35\%$ alcohol. How many mL of each does she combine?

10. **(LO 5, harder)** \$10{,}000 is invested in two accounts: one paying $3\%$ annual simple interest, the other $5\%$. The total annual interest is \$430. How much is in each account?

### Challenge

11. **(LO 4, hard)** A system of two linear equations in two unknowns is given by $\begin{cases} 2x + 3y = 6 \\ ax + 4y = 8 \end{cases}$. Find the value(s) of $a$ for which the system is *dependent* (infinitely many solutions). Find the value(s) for which it is *inconsistent* (no solution). What can you say about all other values of $a$?

12. **(LO 6, hard)** Sketch the solution region of $\begin{cases} x + y \le 6 \\ x \ge 0 \\ y \ge 0 \end{cases}$. List the coordinates of the corner points (vertices) of the region. *This is a small linear-programming problem; the corners are the candidate optima for any linear objective function defined on the region.*

13. **(LO 5, hard, points to chapter 8)** Sarah and Maya can complete a project together in $4$ hours. Sarah, working alone, can complete it in $6$ hours. How long would Maya take working alone? *Hint: rates of work add. If you find your equation involves $\frac{1}{x}$, that is a rational equation — chapter 8.*

---

## 7. Chapter summary

You came in able to graph a single line and write its equation. You leave able to handle *two* lines at once.

You know that a system of two linear equations in two variables has one of three possible solution sets: one ordered pair (lines cross at a point — consistent and independent), no ordered pairs (lines are parallel — inconsistent), or infinitely many (lines are identical — consistent and dependent). You can verify a candidate solution by checking it in both equations. You can solve a system three ways: by graphing (visual, approximate), by substitution (best when one equation isolates a variable), or by elimination (best when both are in standard form).

You know that the algebra of substitution or elimination tells you the system's classification: if the variables disappear and the resulting statement is false, the system is inconsistent; if the resulting statement is true, the system is dependent.

You can set up systems for two-unknown applications: money problems, mixtures, motion in a current, work-rate, geometric. You know that giving yourself two variables instead of one can simplify the algebra dramatically — the chapter 3 round-trip problem produced a quadratic; the analogous two-unknown setup in this chapter produces clean linear systems.

You can sketch the solution region of a system of two linear inequalities — graph each boundary line, shade each side, take the overlap.

The single most important idea: *two equations describe two lines, and the system asks where those lines meet*. Geometry and algebra say the same thing. The geometric picture (lines crossing, parallel, or identical) is the algebraic taxonomy (one solution, none, infinitely many) wearing different clothes.

The most common mistake to watch for: stopping after finding one variable. The solution is an ordered pair; both numbers are required.

What you should be able to teach someone else: how to choose substitution vs. elimination based on a quick look at the equations, why an inconsistent system means parallel lines and a dependent system means identical lines, and how to set up a system for a money or mixture problem.

---

## 8. Connections forward

Chapters 6 through 10 leave linear systems behind, but they keep the structural lesson: complex problems often resolve into multiple simpler equations that must hold simultaneously. A factoring problem (chapter 7) is, ultimately, two simpler equations of the form *(factor) = 0*. A rational equation (chapter 8) often resolves into a system of constraint plus domain restriction. A quadratic equation (chapter 10) has *two* solutions (typically), and graphing the parabola often involves finding two specific x-values where $y = 0$.

The skill of *setting up* multi-variable problems — naming each unknown, writing one equation per constraint, solving the resulting system — is one you will use for the rest of mathematical life. The setup is independent of whether the equations turn out to be linear or not.

Bring the geometric picture with you. *Two equations, the intersection of their solution sets.* Whether linear or not, that is what a system means.

---

**What would change my mind:** If careful empirical work showed that students taught substitution and elimination *together*, with explicit method-selection criteria from day one, performed worse on transfer tasks than students taught one method to fluency before introducing the other, I'd reconsider whether the parallel presentation in this chapter is pedagogically optimal. Current evidence is mixed; my prior is that exposure to both, with explicit selection guidance, helps more than it confuses.

**Still puzzling:** Why does the elimination method *feel* more abstract than substitution to students who have already met the addition property of equality? Adding two equations is just applying the addition property to both sides simultaneously, but the *productivity* of that move — that adding equations can eliminate a variable — surprises every student. Whether the surprise is intrinsic or a teaching artifact, I am not sure.

---

**Tags:** systems-of-equations, substitution, elimination, consistent-independent-dependent, linear-programming, mixture-problems, intersection-of-lines, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 5 (modules m82489–m82499), used under CC-BY 4.0. Source content (graphing/substitution/elimination methods, classification of systems, mixture and money applications, systems of inequalities) derives from OpenStax. Voice, scenes, and pedagogical commentary are original.*
---

## LLM Exercise — Chapter 5: Systems of Linear Equations (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon.
**What you're building this chapter:** a system of two linear equations describing simultaneous constraints in your phenomenon — solved both algebraically (substitution + elimination) and graphically (the intersection).
**Tool:** **Claude Project** + **Claude Code** for the graphical solution.

---

**The Prompt:**

```
Chapter 5 of my Modeling project. Prior sections in this Claude
Project. Chapter 5 taught: a system of linear equations (two-or-
more equations with the same variables); the three possible
outcomes — one solution (consistent + independent — lines cross at
one point), no solutions (inconsistent — parallel lines), infinite
solutions (consistent + dependent — same line); substitution
method (solve one equation for a variable, sub into the other);
elimination method (multiply equations to make coefficients match,
add or subtract to eliminate a variable).

Write the brief's "Two-Constraint Model" section in 400–600 words.

1. **Identify a second constraint.** Your phenomenon almost
   certainly has more than one linear constraint operating
   simultaneously. Examples:
   - Compound interest: two competing investments at different
     rates and balances; find when they converge.
   - Fitness progression: training intensity vs. recovery time;
     both linear in some range.
   - Cell-phone bill: data usage vs. budget; both linear up to
     the data cap.
   - Cooking: recipe scaling vs. ingredient budget; both linear
     per batch.

   Write a SECOND linear equation that, combined with your
   Chapter 2 model, captures a real two-constraint situation in
   your phenomenon.

2. **Solve by substitution.** Solve the system using substitution.
   Show every step. The substitution should produce a solution
   (a specific x, y pair).

3. **Solve by elimination.** Solve the same system using
   elimination. Show every step. You should get the same answer
   as substitution.

4. **Graph the intersection.** Plot both equations on the same
   coordinate plane (use Claude Code or a spreadsheet). The
   intersection point should match the algebraic solution. Verify
   visually.

5. **Interpret the intersection.** What does the intersection
   point mean physically? "After 18 months, both accounts have
   $12,500." "At 25 hours of training, my pace is 8:00 and my
   recovery is 3 days." The interpretation is the point of the
   whole exercise.

6. **The three-outcomes lens.** Could your phenomenon ever produce
   one of the other two outcomes (no solutions = the two
   constraints can never be met simultaneously; infinite solutions
   = the two equations are actually the same constraint)? Name
   one realistic case for each, even if your specific setup gives
   one solution.

End with one decision the intersection enables. The model is
useful when it changes what someone would do.
```

---

**What this produces:** A 400–600 word section + a chart with two lines and their intersection. The interpretation of the intersection point is where the section earns its keep.

**How to adapt this prompt:**

- *For your own project:* If your phenomenon really has only one linear constraint, force a second one by introducing a related variable (cost vs. time, or two competing options).
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* Graphing both lines + finding the intersection programmatically is a 15-line script. Useful for confirming algebra.
- *For a Claude Project:* Append.

**Connection to previous chapters:** Ch 4's slope-intercept analysis on one line gets applied to two lines that cross.

**Preview of next chapter:** Chapter 6 starts the nonlinear arc. Polynomials enter — your linear model gets an upgrade to quadratic or cubic if the phenomenon's behavior genuinely curves. Exponent rules and FOIL come into the modeling toolkit.


---

## AI Wayback Machine

**Carl Friedrich Gauss** was developed Gaussian elimination in 1809 — the algorithm at the heart of every modern linear-system solver.

**Run this:**

```
Who is Carl Friedrich Gauss, and how does their work connect to systems of equations we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"Carl Friedrich Gauss"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way Carl Friedrich Gauss would have.
- Add a constraint: "Answer including criticisms or limits of Carl Friedrich Gauss's methods."

What changes? What gets better? What gets worse?
