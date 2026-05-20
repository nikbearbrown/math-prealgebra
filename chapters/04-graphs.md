---
book: prealgebra-bundle
chapter: 04-graphs
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 4 (CC-BY 4.0). Modules m82479–m82488.
status: draft
---

# Suggested titles

1. The Picture of an Equation
2. Graphs: Reading Lines at a Glance
3. Slope, Intercepts, and What a Line Says

---

**TL;DR.** A linear equation in two variables has infinitely many solutions; the graph is the picture of all of them. Two numbers — the *slope* and the *y-intercept* — capture the line completely, and from them you can read the equation's behavior in one look. This chapter is about seeing equations.

---

## 1. Chapter opening

A hiker stands at a trailhead in the Adirondacks holding a phone. The screen shows an elevation profile: a thin line beginning at the lower-left and climbing toward the upper-right. The horizontal axis reads *distance from trailhead, miles*. The vertical reads *elevation, feet*. The line starts at $(0, 1{,}200)$ and rises steadily to $(2, 3{,}400)$ before flattening into a ridge.

She looks at the line and decides to bring a windbreaker. She has read, in a single glance, three things the elevation table on the back of the map could not have told her so quickly: how steep the climb is, how long it will take, and whether there is a flat section to rest on. The picture is faster than the numbers.

The line on the screen is the graph of an equation. *Elevation as a function of distance.* The first two miles are roughly $y = 1100 x + 1200$ — elevation rising eleven hundred feet for every mile of horizontal distance, starting at twelve hundred feet. Two numbers — *eleven hundred* and *twelve hundred* — describe the climb completely. The slope and the starting value.

This chapter is about that translation. How a relationship between two quantities — pace and distance, price and quantity, time and account balance — becomes a line on a coordinate grid; how the line's *slope* and *intercept* read off as the rate of change and the starting value; how, given a line, you can write its equation, and given an equation, you can sketch its line in three seconds.

### Learning objectives

By the end of this chapter you should be able to:

- **Plot** points in the rectangular (Cartesian) coordinate plane and identify the four quadrants.
- **Verify** that an ordered pair is a solution to a linear equation in two variables, and **find** solutions by completing a table of values.
- **Graph** a linear equation in two variables by plotting points or by using the intercepts.
- **Calculate** the slope of a line from two points using $m = \dfrac{y_2 - y_1}{x_2 - x_1}$.
- **Read** the slope and y-intercept of a line directly from the slope-intercept form $y = mx + b$.
- **Write** the equation of a line given (a) slope and y-intercept, (b) slope and a point, or (c) two points.
- **Recognize** parallel lines (same slope) and perpendicular lines (negative reciprocal slopes).
- **Graph** a linear inequality in two variables by graphing the boundary line and shading.

### Prerequisites

Chapters 1, 2, and 3. The number line is now becoming a number *plane*; everything you know about the line still applies, doubled. You should be able to solve any linear equation in one variable and translate any word problem of moderate complexity. The new work is the coordinate plane and the geometry of lines.

### Why this chapter matters

Three reasons. First, a graph compresses information. The same data that takes a paragraph to describe takes one picture to see. Second, a graph reveals structure that algebra hides. Whether two quantities scale together, grow apart, or hold constant — these are visible at a glance, but invisible in a wall of equations. Third, the graph is the bridge from algebra to every later mathematics: calculus is the study of how graphs *change*, statistics is the study of how scattered points cluster around a line, and engineering is the study of how to design a graph to behave a particular way.

---

## 2. Concept 1 — The coordinate plane and the graph of an equation

A naval officer in 1637 needed a way to describe where a ship was. *Two miles east and three miles north of the lighthouse* fixed the position. Two numbers, one for each direction. The lighthouse was the origin; *east* and *north* were the two reference directions. Any point on the ocean could be named by its pair of distances.

That same year, René Descartes published *La Géométrie*, in which he formalized the same idea for mathematics. Two perpendicular number lines — one horizontal, one vertical — sharing a common origin. Any point in the plane named by a pair of numbers $(x, y)$, the first measuring how far right or left of the origin, the second how far up or down. The plane is now called the **rectangular** or **Cartesian** coordinate plane, after Descartes.

### The conventions

The horizontal axis is the **x-axis**; the vertical is the **y-axis**. They meet at the **origin**, the point $(0, 0)$. The x-axis is positive to the right, negative to the left; the y-axis is positive up, negative down. The plane is divided into four **quadrants**, numbered counterclockwise from the upper right (Quadrant I, where both coordinates are positive) through Quadrants II, III, and IV.

An **ordered pair** $(x, y)$ locates a unique point. The order matters: $(3, 5)$ and $(5, 3)$ are different points. The first number is always the horizontal coordinate (the x-coordinate, or *abscissa*); the second is always the vertical (the y-coordinate, or *ordinate*).

[FIGURE: A Cartesian coordinate plane with x and y axes labeled, origin marked, four quadrants labeled with Roman numerals I-IV, and four points plotted: (3, 5), (-2, 4), (-3, -1), (4, -2) — one in each quadrant. Pedagogical purpose: visualize the four quadrants and confirm that ordered pairs locate unique points.]

### Equations in two variables

A linear equation in *one* variable, like $3x + 5 = 17$, has one solution. A linear equation in *two* variables, like $2x + y = 7$, has infinitely many solutions. Each solution is an ordered pair $(x, y)$ that makes the equation true.

To verify: is $(2, 3)$ a solution to $2x + y = 7$? Substitute: $2(2) + 3 = 7$. Yes. Is $(0, 7)$ a solution? Substitute: $2(0) + 7 = 7$. Yes. Is $(1, 6)$? $2(1) + 6 = 8$. No.

To *generate* solutions: pick any value of $x$, solve for $y$. From $2x + y = 7$, solving for $y$ gives $y = 7 - 2x$. Now plug in any $x$:

| $x$ | $y = 7 - 2x$ | $(x, y)$ |
| --- | --- | --- |
| $-1$ | $9$ | $(-1, 9)$ |
| $0$ | $7$ | $(0, 7)$ |
| $1$ | $5$ | $(1, 5)$ |
| $2$ | $3$ | $(2, 3)$ |
| $3$ | $1$ | $(3, 1)$ |

Five solutions. The equation has infinitely many — one for every real number you choose for $x$. Plot the five solutions on the coordinate plane and notice: they fall on a straight line. Plot a sixth, a seventh, a hundredth: they all fall on the same line.

The **graph** of an equation in two variables is the set of all points $(x, y)$ that satisfy the equation. For a linear equation, the graph is always a straight line.

### Why a line?

The picture is not coincidence. *Every* equation of the form $ax + by = c$ (with $a$ and $b$ not both zero) has a graph that is a straight line. The reason is that the equation imposes a *constant rate of trade-off* between $x$ and $y$: increase $x$ by one, and $y$ must decrease by exactly $a/b$ to keep the left side equal to $c$. A constant rate of change traces a straight line. We will name and measure that rate in Concept 2.

### Special cases — vertical and horizontal lines

A **horizontal line** has equation $y = c$ for some constant $c$. Every point on the line has the same y-coordinate. The line $y = 3$ passes through $(0, 3), (1, 3), (-5, 3), \ldots$ — every point with y-coordinate 3.

A **vertical line** has equation $x = c$. Every point on the line has the same x-coordinate. The line $x = -2$ passes through $(-2, 0), (-2, 1), (-2, -7), \ldots$.

Notice: the equation $y = 3$ has only one variable visible. But it is still a two-variable equation; the missing $x$ is implicit, and what the equation is saying is *for every value of $x$, $y$ equals $3$*. The graph is therefore the entire horizontal line at height 3.

### A worked example — graphing by plotting points

> **Problem.** Graph $y = 2x - 1$.

> *Step 1.* Make a table of solutions. Pick easy values of $x$, compute $y$:
>
> | $x$ | $y = 2x - 1$ |
> | --- | --- |
> | $-1$ | $-3$ |
> | $0$ | $-1$ |
> | $1$ | $1$ |
> | $2$ | $3$ |
>
> *Step 2.* Plot the four points $(-1, -3), (0, -1), (1, 1), (2, 3)$.
>
> *Step 3.* Draw a straight line through them, extending in both directions with arrows.
>
> The line crosses the y-axis at $(0, -1)$ and rises two units for every one unit to the right. We will name those quantities — *y-intercept* and *slope* — in Concept 2.

### The trade-off

The graph is *picture-fast*: a glance tells you whether the relationship is increasing, decreasing, steep, shallow, positive at the origin, negative at the origin. Algebra cannot do that as quickly. The trade-off is precision. A graph drawn by hand will show a line *near* $y = 2x - 1$ but you cannot read off, from a graph, that the slope is *exactly* $2$ and the intercept *exactly* $-1$. The numbers come from the equation; the picture comes from the graph; you need both.

### Common misconceptions

- *"$(3, 5)$ is the same as $(5, 3)$."* Not in coordinates. The first is three right and five up; the second is five right and three up. Different points.
- *"Plotting two points is enough to draw a line."* Two points *determine* a line, but if either point is wrong, the entire line is wrong. Plot at least three points and confirm they are collinear before drawing.
- *"$x = 3$ is a point."* No — it is a *line* (vertical, passing through every point with x-coordinate 3). The point with x-coordinate 3 is not specified until you give a y-coordinate as well.

---

## 3. Concept 2 — Slope and the slope-intercept form

A roof pitch. A wheelchair ramp. A skier estimating the difficulty of a run. *Steepness* is a property everyone reads from a picture, intuitively, before they have any vocabulary for it. The mathematical name for steepness is **slope**, and the formula that captures it makes the intuitive measurement exact.

### Slope as rate of change

The **slope** of a line measures how much $y$ changes per unit change in $x$. If the line passes through two points $(x_1, y_1)$ and $(x_2, y_2)$, the slope is:

$$m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{\text{change in } y}{\text{change in } x} = \frac{\text{rise}}{\text{run}}.$$

The letter $m$ for slope is conventional, possibly from the French *monter* — to climb — though the historical record is unsettled.

A worked computation: the slope of the line through $(2, 3)$ and $(5, 9)$ is

$$m = \frac{9 - 3}{5 - 2} = \frac{6}{3} = 2.$$

The line rises six units for every three units to the right, or equivalently, two units up for every one to the right.

The slope's *sign* tells you the line's direction: positive slope tilts upward as you move right; negative slope tilts downward. A horizontal line has slope zero ($y$ never changes). A vertical line has *undefined* slope ($x$ never changes, so the formula divides by zero).

### Slope is the same anywhere on the line

Pick any two points on a non-vertical line; the slope formula gives the same answer. This is the *defining* property of a straight line: its rate of change does not change. That is what makes lines worth a chapter of their own; many later objects you will study (curves, surfaces) have *varying* rates of change, and the calculus of chapter ten of a college algebra book will treat exactly that complication.

### Slope-intercept form: y = mx + b

The most useful form of a line's equation is

$$y = mx + b$$

where $m$ is the slope and $b$ is the **y-intercept** — the y-coordinate of the point where the line crosses the y-axis. From this form, you can sketch the line in seconds: plot $(0, b)$, then use the slope to step to a second point, then draw the line.

A worked translation: the line $y = -3x + 5$ has slope $-3$ and y-intercept $5$. To graph: start at $(0, 5)$. Slope $-3 = -3/1$ means *down 3, right 1*. Step to $(1, 2)$. Step again to $(2, -1)$. Draw the line.

### Three forms, one line

The same line can be written in three useful forms:

- **Slope-intercept:** $y = mx + b$. Best when you want to read slope and intercept directly.
- **Point-slope:** $y - y_1 = m(x - x_1)$. Best when you have a slope and one point.
- **Standard form:** $ax + by = c$. Best when both intercepts are needed quickly.

Convert among them by algebraic manipulation. The line through $(2, 7)$ with slope $4$, in point-slope form, is $y - 7 = 4(x - 2)$. Distribute and simplify to $y = 4x - 1$ (slope-intercept). Subtract $4x$ from both sides to get $-4x + y = -1$, or $4x - y = 1$ (standard form). Same line, three dresses.

### A worked example — graphing from slope-intercept form

> **Problem.** Graph $y = -\dfrac{2}{3}x + 4$.

> *Step 1.* Identify $m = -\dfrac{2}{3}$ and $b = 4$. The y-intercept is $(0, 4)$.
>
> *Step 2.* Plot $(0, 4)$.
>
> *Step 3.* Use the slope to step to a second point. Slope $-\dfrac{2}{3}$ means *down 2, right 3*. Step from $(0, 4)$ to $(3, 2)$.
>
> *Step 4.* Draw the line through the two points, extending in both directions.

### The trade-off

Slope-intercept is fast, readable, and almost always the form to use. The trade-off is that *vertical lines have no slope-intercept form*. The line $x = 3$ cannot be written as $y = mx + b$ — its slope is undefined. So the form $y = mx + b$ describes every line *except* vertical lines, and you have to remember that exception. Standard form $ax + by = c$ describes every line, including vertical ($a = 1, b = 0, c = 3$ gives $x = 3$), at the cost of being harder to read.

### Common misconceptions

- *"Slope is rise plus run."* No — *rise over run*, division. Steepness is a ratio, not a sum.
- *"A line with slope zero is undefined."* No — slope zero means the line is horizontal. *Undefined* slope means the line is vertical (the formula divides by zero).
- *"$y = mx + b$ where $b$ is the *x*-intercept."* No — $b$ is the y-intercept. To find the x-intercept, set $y = 0$ and solve for $x$.

---

## 4. Concept 3 — Writing equations of lines, and parallel/perpendicular

To *graph* a line, you start with the equation. To *write* the equation, you start with information about the line — points it passes through, slopes it has, lines it is parallel or perpendicular to. This concept reverses Concept 2's direction: from geometry to algebra.

### Three building blocks

Three pieces of information are enough to determine a line uniquely. Any two of the following will do:

- A slope.
- A point on the line.
- An intercept.

### Equation from slope and y-intercept

If you have $m$ and $b$, the line is $y = mx + b$. Done.

### Equation from slope and a point

If you have slope $m$ and one point $(x_1, y_1)$ — but not necessarily the y-intercept — use the point-slope form:

$$y - y_1 = m(x - x_1).$$

Distribute to get slope-intercept form.

> **Problem.** Find the equation of the line with slope $3$ passing through $(2, 5)$.

> Point-slope: $y - 5 = 3(x - 2)$.
>
> Distribute: $y - 5 = 3x - 6$.
>
> Add $5$: $y = 3x - 1$.

### Equation from two points

If you have two points $(x_1, y_1)$ and $(x_2, y_2)$, first compute the slope, then use point-slope with either point.

> **Problem.** Find the equation of the line through $(1, -2)$ and $(4, 7)$.

> Slope: $m = \dfrac{7 - (-2)}{4 - 1} = \dfrac{9}{3} = 3$.
>
> Point-slope using $(1, -2)$: $y - (-2) = 3(x - 1)$, i.e., $y + 2 = 3x - 3$.
>
> Solve for $y$: $y = 3x - 5$.

Check using the other point: $y = 3(4) - 5 = 7$. $\checkmark$

### Parallel lines

Two non-vertical lines are **parallel** if and only if they have the *same slope* and *different y-intercepts*. Geometrically, parallel lines never meet — and the reason is exactly that they rise at the same rate, so the vertical gap between them stays constant.

### Perpendicular lines

Two non-vertical lines are **perpendicular** if and only if their slopes are *negative reciprocals* — that is, if their product is $-1$.

$$\text{Lines are perpendicular} \iff m_1 \cdot m_2 = -1.$$

If one line has slope $\frac{2}{3}$, a line perpendicular to it has slope $-\frac{3}{2}$. Flip the fraction; flip the sign.

The geometric reason: rotating a line $90°$ in the plane maps a slope of $m$ to a slope of $-1/m$. The proof uses the Pythagorean theorem, which we met in chapter 3 — the same theorem turns out to govern the geometry of lines.

A horizontal line (slope $0$) and a vertical line (undefined slope) are perpendicular, even though the negative-reciprocal formula breaks down (you cannot take the reciprocal of zero). They are the boundary case; the geometric perpendicularity is what is real, and the algebraic formula merely captures it for non-vertical lines.

### A worked example combining everything

> **Problem.** Find the equation of the line through $(3, 4)$ that is perpendicular to the line $y = -\frac{1}{2}x + 7$.

> *Slope of the given line:* $m_1 = -\dfrac{1}{2}$.
>
> *Slope of perpendicular:* $m_2 = -\dfrac{1}{m_1} = -\dfrac{1}{-1/2} = 2$.
>
> *Use point-slope* with $(3, 4)$ and slope $2$:
>
> $$y - 4 = 2(x - 3)$$
> $$y = 2x - 6 + 4 = 2x - 2.$$
>
> *Check.* The slope of $y = 2x - 2$ is $2$. The slope of the original is $-\dfrac{1}{2}$. Their product: $2 \times -\dfrac{1}{2} = -1$. $\checkmark$ The line passes through $(3, 4)$: $y = 2(3) - 2 = 4$. $\checkmark$

### The trade-off

Three forms, two perpendicularity conditions, and the special cases of horizontal and vertical lines — this is a lot of small machinery. The trade-off is that *every* line in the plane is now describable, both forward (equation to graph) and backward (graph or geometric condition to equation). The cost is the bookkeeping of which form is best in which situation.

The reflexive note: parallel and perpendicular as defined here are *Euclidean* relations. On the surface of a sphere, "parallel" lines do not stay equidistant — meridians of longitude all converge at the poles. Euclidean geometry's two-thousand-year reign as *the* geometry was challenged in the nineteenth century by Bolyai, Lobachevsky, and Riemann; the lines we draw in this chapter are the lines of the local, flat plane, and that is exactly the right setting for almost every problem you will solve.

### Common misconceptions

- *"Perpendicular lines have opposite slopes."* No — *negative reciprocal*. Slope $3$ is perpendicular to slope $-\frac{1}{3}$, not to slope $-3$.
- *"Parallel lines have the same equation."* No — they have the same slope but *different* y-intercepts. The same equation describes the same line, not parallel lines.
- *"You cannot write the equation of a vertical line."* You can; it has no slope-intercept form, but its standard form is $x = c$. Use the form that fits.

---

## 5. Integration / Synthesis

A small business owner notices a pattern in her monthly heating bills.

| Month | Outdoor avg temp (°F) | Heating cost (\$) |
| --- | --- | --- |
| October | $55$ | $80$ |
| December | $25$ | $260$ |
| February | $15$ | $320$ |

The owner wants to predict next October's heating cost if forecasters say the average outdoor temperature will be $50°$F. Build a linear model.

### Concept 1 — plot the points

Treat outdoor temperature as $x$ and heating cost as $y$. The three data points are $(55, 80), (25, 260), (15, 320)$. Plot them on a coordinate plane.

Are they collinear? Compute the slope between successive pairs:

- From $(55, 80)$ to $(25, 260)$: $m = \dfrac{260 - 80}{25 - 55} = \dfrac{180}{-30} = -6$.
- From $(25, 260)$ to $(15, 320)$: $m = \dfrac{320 - 260}{15 - 25} = \dfrac{60}{-10} = -6$.

Same slope. The three points lie on a single line. (For real-world data, perfect collinearity would be suspicious — actual heating costs vary with humidity, wind, occupancy, and equipment efficiency. Here we will treat the line as a clean model.)

### Concept 2 — slope-intercept form

Slope is $-6$. Cost falls six dollars for every degree warmer. To find the y-intercept, use point-slope with any of the three points. Take $(55, 80)$:

$$y - 80 = -6(x - 55) = -6x + 330$$
$$y = -6x + 410.$$

Slope-intercept form: $y = -6x + 410$.

The y-intercept is $410$. *At an outdoor temperature of zero degrees, the model predicts a monthly heating bill of \$410.* That is the *meaning* of the y-intercept in this context.

The slope is $-6$. *Each degree of warmer outdoor temperature reduces the heating bill by six dollars.*

### Predicting next October

Plug $x = 50$:

$$y = -6(50) + 410 = -300 + 410 = 110.$$

The model predicts a heating bill of $\$110$ for an October with average outdoor temperature $50°$F.

### What this shows

Three observations.

*First*, two numbers — slope $-6$ and intercept $410$ — capture an entire relationship. If you wrote this on the back of a napkin and handed it to someone, they could reconstruct the table, the line, and any prediction within range.

*Second*, the model has *limits*. At an outdoor temperature of $-100°$F, it predicts a bill of $\$1{,}010$ — but no real building's heating cost is exactly linear in outdoor temperature across that range. At $200°$F, the model predicts a *negative* heating bill, which is meaningless. Linear models are *local approximations*; they are most reliable inside the range of the data that built them and least reliable far outside it. In statistics, this is called the danger of *extrapolation*.

*Third*, the entire process — plot, find slope, find intercept, predict — used every concept in the chapter. The plotting was Concept 1. The slope and y-intercept were Concept 2. Reading the perpendicular slope or the parallel comparison would have been Concept 3. The arithmetic was chapter 1. The setup was chapter 3.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** Plot $(2, 3)$, $(-1, 4)$, $(-2, -3)$, $(0, -2)$, $(3, 0)$ on a coordinate plane. State which quadrant or axis each lies in.

2. **(LO 2, easy)** Verify: is $(3, -4)$ a solution to $2x + y = 2$?

3. **(LO 4, easy)** Find the slope of the line through $(2, 3)$ and $(5, 9)$.

4. **(LO 5, easy)** State the slope and y-intercept of $y = -2x + 7$.

### Application

5. **(LO 3, medium)** Graph $y = \dfrac{1}{2}x - 3$ by plotting at least three points.

6. **(LO 5, medium)** Find the x- and y-intercepts of $3x + 4y = 12$, and use them to graph the line.

7. **(LO 6, medium)** Write the equation of the line with slope $-2$ that passes through $(1, 5)$.

8. **(LO 6, medium)** Write the equation of the line through $(0, -3)$ and $(2, 1)$.

### Synthesis

9. **(LO 7, harder)** Determine whether the lines $y = 3x - 4$ and $-6x + 2y = 10$ are parallel, perpendicular, or neither. Justify with slopes.

10. **(LO 6 + 7, harder)** Find the equation of the line that passes through $(2, -1)$ and is perpendicular to $y = \dfrac{2}{3}x + 5$.

11. **(LO 6, harder)** A taxi service charges \$3.50 plus \$2.20 per mile (chapter 3, exercise 10). Write a linear equation for the total cost $C$ as a function of miles $d$. Identify the slope and y-intercept and interpret each in context.

### Challenge

12. **(LO 4 + 5, hard)** A line passes through $(a, b)$ and $(c, d)$ where $a \ne c$. Write the equation of the line in slope-intercept form, and verify (by substituting) that both points satisfy your equation. Then state, in one sentence, what changes if $a = c$.

13. **(LO 8, hard, points to chapter 5)** Sketch the solution region for the inequality $2x + y \le 6$. *Hint: graph the line $2x + y = 6$ first; then decide which side of the line satisfies the inequality by testing a single point not on the line, like $(0, 0)$.* In chapter 5 we will solve systems of *two* such inequalities; here, do one.

---

## 7. Chapter summary

You came in able to translate word problems into equations. You leave able to *picture* the equations.

You know that the rectangular coordinate plane is two perpendicular number lines, that an ordered pair $(x, y)$ locates a unique point, and that the four quadrants are numbered counterclockwise from the upper right. You know that a linear equation in two variables has infinitely many solutions, and that the graph — a straight line — is the picture of all of them.

You can graph a line three ways: by plotting points, by using the intercepts, or by using the slope-intercept form. You know that two numbers — the slope $m$ and the y-intercept $b$ — describe the line completely. You can compute the slope from any two points using $m = \dfrac{y_2 - y_1}{x_2 - x_1}$. You can read the slope and y-intercept directly from $y = mx + b$.

You can write the equation of a line three ways: from slope and y-intercept (use $y = mx + b$), from slope and a point (use point-slope $y - y_1 = m(x - x_1)$), or from two points (compute the slope, then use point-slope). You know that parallel lines have the same slope, and that perpendicular lines have negative reciprocal slopes — flip the fraction, flip the sign.

You know that vertical lines have undefined slope and are written as $x = c$, and that horizontal lines have slope zero and are written as $y = c$. Both are the special cases that the slope-intercept form does not handle.

The single most important idea: *a line is its slope and its intercept*. Every fact about the line — where it crosses the axes, which way it tilts, how steep it is, whether it is parallel or perpendicular to another — follows from those two numbers.

The most common mistake to watch for: confusing slope-zero (horizontal) with undefined-slope (vertical). The terms sound similar; the lines are at right angles to each other. When in doubt, sketch the line and ask whether $x$ or $y$ is changing.

What you should be able to teach someone else: how to read a graph for slope and intercept in one glance, how to write the equation of a line through two given points, and why perpendicular lines have negative reciprocal slopes.

---

## 8. Connections forward

Chapter 5 introduces the natural next question: what if you have *two* linear equations that must hold simultaneously? Each equation describes a line. The pair of lines either crosses at one point, runs parallel and never crosses, or describes the same line and crosses everywhere. Those three outcomes — one solution, no solution, infinitely many solutions — will look familiar; they are the same three outcomes you saw for one-variable equations in chapter 2 (conditional, contradiction, identity). Geometry and algebra produce the same taxonomy.

Chapters 6 through 10 leave linearity behind. You will graph parabolas, hyperbolas, square-root curves — shapes that do not have a constant slope. The slope at a point on a curve becomes a *local* slope, and answering "what is the slope at this exact point?" leads, ultimately, to differential calculus. But the foundation for all of that is the slope of a *line*, which you now own.

Bring the picture with you. Whatever equation arrives, sketch it. The picture often resolves what the algebra obscures.

---

**What would change my mind:** If a careful study showed that students who learn slope from a *purely algebraic* definition (rate of change in $y$ per unit increase in $x$) develop better long-term mathematical understanding than those who learn it from rise-over-run, I'd reconsider whether the geometric framing is pedagogically primary. Current consensus favors the geometric introduction; the empirical question is whether it generalizes well to non-linear functions in calculus.

**Still puzzling:** Why does the slope formula $m = (y_2 - y_1)/(x_2 - x_1)$ fail for vertical lines, while the geometric notion of perpendicularity does not? The algebraic representation has a hole that the underlying geometry does not. Whether a different parametrization of slope (using angle from horizontal, perhaps) would close that hole without introducing new problems, I am not sure.

---

**Tags:** coordinate-plane, cartesian, slope, slope-intercept-form, linear-equations, graphs, parallel-lines, perpendicular-lines, openstax, elementary-algebra

---

*Voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 4 (modules m82479–m82488), used under CC-BY 4.0. Source content (coordinate-plane conventions, slope formula, slope-intercept and point-slope forms, parallel/perpendicular criteria, intercept method) derives from OpenStax. Voice, scenes, and pedagogical commentary are original.*
---

## LLM Exercise — Chapter 4: Graphs (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon.
**What you're building this chapter:** the graphical representation of your phenomenon — coordinate-plane plot, slope-intercept equation, parallel/perpendicular relationships.
**Tool:** **Claude Project** for prose + **Claude Code** for actual graph generation (matplotlib, Plotly, or even Excel). Save the chart as an image alongside the document.

---

**The Prompt:**

```
Chapter 4 of my Modeling project. Prior sections (Foundation, Linear
Model, Word Problem) are in this Claude Project. Chapter 4 taught:
the coordinate plane (Cartesian, x and y axes); slope (rise/run, or
the change in y per unit change in x); slope-intercept form
(y = mx + b, where m is slope and b is y-intercept); writing the
equation of a line from a point and slope, or from two points;
parallel lines (same slope, different y-intercepts) and
perpendicular lines (slopes whose product is -1).

Write the brief's "Graphing the Phenomenon" section in 400–600
words.

1. **Plot the phenomenon.** Generate 6–10 data points from your
   linear model. Plot them on the coordinate plane. Use Claude
   Code (or a spreadsheet) to produce an actual chart with axis
   labels, units, and a title. Save the chart as an image
   committed to the project folder.

2. **Compute the slope.** Pick two of your data points. Compute
   the slope using the rise/run formula. Verify it matches your
   Chapter 2 linear model's coefficient. Note the slope's units
   (e.g., dollars per year, miles per hour gain per year of
   training).

3. **Write the slope-intercept equation.** Express your linear
   model in y = mx + b form. State explicitly:
   - What does m mean in your phenomenon's context?
   - What does b mean? (Sometimes b is the starting value;
     sometimes it's a parameter that depends on initial
     conditions.)

4. **The eyeball test.** Look at the chart. Does the linear trend
   actually fit the phenomenon? Or is the linear model the wrong
   shape — concave up, concave down, S-curve, oscillating? Name
   what you see. The visual mismatch (if any) names what the
   polynomial/quadratic models in later chapters need to fix.

5. **Parallel and perpendicular cases.** Pick one realistic
   scenario in your phenomenon where:
   - Two different parameter sets would produce PARALLEL lines
     (same slope, different intercept — e.g., two people with the
     same growth rate but different starting balances).
   - Two parameter sets would produce PERPENDICULAR lines
     (slopes m1 × m2 = -1 — e.g., one variable's increase
     directly trades against another's decrease).

End with the equation of the line in two alternate forms (point-
slope and standard form) plus one specific prediction the line
makes that you can test against reality.
```

---

**What this produces:** A 400–600 word section + an actual chart of the phenomenon. The chart's visual fit (or misfit) is the most important single output — it tells you whether the linear model is adequate or needs the polynomial/quadratic extensions coming in Chs 6 and 10.

**How to adapt this prompt:**

- *For your own project:* If your phenomenon's "data" is qualitative or sparse, generate plausible synthetic data and plot it. The visual analysis still works.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* This is the right chapter for it. A 10-line matplotlib script produces a real chart. Save the chart as PNG in the project folder.
- *For a Claude Project:* Append the analysis; reference the chart by filename.

**Connection to previous chapters:** Chapter 2's linear equation is now visual; Chapter 3's word problem can be re-solved graphically.

**Preview of next chapter:** Chapter 5 adds a second equation — now your phenomenon has two constraints simultaneously (budget + time, two competing options, two related variables). You'll solve the system using substitution and elimination, and identify the intersection point as a real-world event.


---

## AI Wayback Machine

**René Descartes** was introduced the coordinate system in 1637 that lets algebra and geometry talk to each other.

**Run this:**

```
Who is René Descartes, and how does their work connect to graphs we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"René Descartes"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way René Descartes would have.
- Add a constraint: "Answer including criticisms or limits of René Descartes's methods."

What changes? What gets better? What gets worse?
