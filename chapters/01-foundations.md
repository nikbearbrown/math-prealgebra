---
book: prealgebra-bundle
chapter: 01-foundations
voice: Attenborough × Feynman v1.1
source: OpenStax *Elementary Algebra 2e*, Chapter 1 (CC-BY 4.0). Modules m82451–m82461.
status: draft — voice-anchored at workshop level (root style/VOICE.md), no per-book voice samples
---

# Suggested titles

1. The Number Line Is Older Than Algebra
2. Foundations: What the Number Line Knows
3. The Spine of Arithmetic

---

**TL;DR.** Algebra rests on three things that look small until you build on them: a number line that holds every number you'll ever use, a notation that lets you talk about numbers you don't yet know, and a small set of properties that govern how the symbols are allowed to move. Get those right and the rest of the book follows.

---

## 1. Chapter opening

A January morning in northern Vermont. The thermometer outside the kitchen window reads negative eight. Inside, the dial of the wall thermostat reads sixty-eight. You stand at the door in socks and consider what to wear.

Seventy-six. That is the number you actually want. It is the gap between where you are and where you are going. It is not on either thermometer, but you can find it by counting: from negative eight, climb to zero, that is eight steps; from zero, climb to sixty-eight, that is sixty-eight more; eight plus sixty-eight is seventy-six. You do this without thinking. You have just done arithmetic on the number line, with a negative number on one end, in your head, before coffee.

The thermometer outside your window is a number line stood on its head. So is the measuring tape in the toolbox. So is the running balance in your bank account. So is the elevation profile on a hiking app, where the trail dips below sea level for a quarter mile before climbing again. Same line. Different labels.

This chapter is about that line — what lives on it, how the things that live on it combine, and what rules a person has to know to talk about those combinations without ambiguity. It is the foundation chapter. It is the boring one in the introduction of every algebra book ever written. It is also the one whose mistakes echo through every chapter that follows. A weak grip on the number line, on order of operations, on the properties of real numbers — and every later proof, every later word problem, every later graph carries the wobble forward.

So we begin here, slowly, with the line.

### Learning objectives

By the end of this chapter, you should be able to:

- **Locate** any rational number on a number line, and **name** its opposite and absolute value.
- **Apply** the order of operations to evaluate an arithmetic or algebraic expression at given values.
- **Identify and use** the commutative, associative, identity, inverse, and distributive properties to rewrite an expression in an equivalent form.
- **Translate** an English phrase into an algebraic expression — and back.
- **Distinguish** rational from irrational numbers, and **place** examples of each on the number line.

Action verbs only. *Locate. Apply. Identify. Translate. Distinguish.* If a learning objective uses *understand* or *be familiar with*, the objective is hiding from itself.

### Prerequisites

You should be comfortable with addition, subtraction, multiplication, and division of whole numbers — the operations and the times tables, not the theory. If "seven times eight" requires more than a pause, the rest of this chapter will be slow going; spend a week with flash cards before continuing. Comfort with simple fractions like one-half and three-quarters helps too, though we will rebuild fractions on the line as we go.

### Why this chapter matters

Most algebra failures in the chapters ahead are not algebra failures. They are sign errors — students who add when they should subtract because they lost track of a negative. They are order-of-operation errors — students who multiply before exponentiating because they confused the convention. They are property errors — students who distribute the negative across one term but not the next. Every one of those is a foundations error.

A student who has internalized the contents of this chapter can recover from a sign error in the next chapter without panic. A student who has not will compound mistakes. The leverage is not in mastering the hard chapters; it is in not skimming this one.

---

## 2. Concept 1 — The number line: where every number lives

A carpenter pulls a steel tape from the spool. The first inch is marked, then the half, then the quarter, then the eighth, then the sixteenth — each one a smaller comb of teeth between the larger ones. The tape stops at twenty-five feet. The lake outside the workshop window is colder than freezing — a thermometer staked into the ground reads the air at fifteen below. A check has just cleared at the bank: the running balance, which had been one hundred and eighty dollars, is now negative forty-three.

Three different objects. One mathematical structure underneath them.

The number line is the oldest visual idea in mathematics. The Babylonians had it. The Greeks had it without negatives. The Hindu mathematician Brahmagupta, writing in the seventh century, had it with negatives — he called them *debts*, which is exactly right. The line keeps showing up because it captures, in one picture, two things human beings need to track: *how much* and *which way*.

### The line, building outward

Start with what you can count. One, two, three, four, and so on — fingers held up, tally marks on a wall. These are the **counting numbers**, also called the **natural numbers**, written

$$1, 2, 3, 4, 5, \ldots$$

The three dots — the *ellipsis* — mean *and so on, forever*. There is no largest counting number. If someone hands you one, you can always add one more.

Add zero to the counting numbers and you get the **whole numbers**:

$$0, 1, 2, 3, 4, 5, \ldots$$

Zero is younger than the counting numbers. The Romans did fine without it. The mathematicians of medieval India developed it as a placeholder, and Europe adopted the idea reluctantly, in part because it raised theological questions. *Nothing*, as a number, is a strange thing to commit to writing.

Now mark zero on a horizontal line. Mark equal steps to the right. Each step is one whole number. The line points to the right, but the line does not stop at zero. The same steps reflect to the left, into territory you can label *negative*. **Negative numbers** are how a temperature can be colder than freezing; how a checking account can be overdrawn; how the basement floor can sit below the floor of the lobby. They are not a fudge. They are the line on the other side of zero.

The whole numbers together with their negatives form the **integers**:

$$\ldots, -3, -2, -1, 0, 1, 2, 3, \ldots$$

*Integer* comes from the Latin for *whole*, *intact*. An integer is a number with no fractional crumbs.

### Opposites and the additive zero

Two numbers that sit at the same distance from zero, but on opposite sides, are called **opposites**. Three and negative three are opposites. So are seventeen and negative seventeen. So are a thousand and negative a thousand. So is zero and itself — zero is its own opposite.

The opposite of $a$ is written $-a$. So $-7$ is the opposite of $7$. And $-(-7) = 7$, because the opposite of "seven steps to the left" is "seven steps back to the right." Two negatives walk you home.

Why does the opposite matter? Because adding a number and its opposite always returns you to zero:

$$a + (-a) = 0.$$

That is not a coincidence. It is the *definition* of the opposite. Once you have a number line and a starting point at zero, the opposite of $a$ is whatever number, when added to $a$, returns you to where you started.

### Absolute value: distance, freed from direction

Now ask a different question. *How far* is $-7$ from zero? The answer is seven. Not negative seven — *distance is never negative*. You can walk seven blocks east or seven blocks west; in either case you have walked seven blocks. The fact that one direction is labeled "positive" and the other "negative" is bookkeeping; the *distance* is the same.

This is what **absolute value** records. We write $|a|$ for the absolute value of $a$, and we read it as *the distance from $a$ to zero on the number line.*

$$|7| = 7 \quad |-7| = 7 \quad |0| = 0$$

Absolute value strips off the sign. The Latin root *absolutus* means *freed from* or *unconditional*. The absolute value is the magnitude freed from the question of direction.

A small subtlety: $-|5|$ is *not* the same as $|-5|$. The first is *the negative of the absolute value of five*, which equals $-5$. The second is *the absolute value of negative five*, which equals $5$. The bars do their work first, then the negative sign acts on the result.

[FIGURE: A horizontal number line marked from -10 to 10 with integer ticks. Two arcs above the line span from 0 to -7 and from 0 to 7, both labeled "7" — illustrating that |-7| and |7| are both equal to 7 because they describe the same distance.]

### Adding integers — walking on the line

To add a positive number, walk to the right. To add a negative number, walk to the left. To start, plant yourself at zero.

What is $-3 + 5$? Start at zero. Walk three steps left, to $-3$. Now walk five steps right. You land at $2$. So $-3 + 5 = 2$.

What is $-7 + (-4)$? Start at zero. Walk seven steps left, to $-7$. Now walk *four more steps left* (because the second number is also negative). You land at $-11$. So $-7 + (-4) = -11$.

What is $9 + (-12)$? Start at zero, walk nine right, then twelve left. You overshoot zero by three, landing at $-3$. So $9 + (-12) = -3$.

Here is the pattern. When the two numbers have the same sign — both positive or both negative — you walk in the same direction both times, and the magnitudes add. When they have opposite signs, you walk in opposite directions, the magnitudes subtract, and the *sign of the result* matches the one whose magnitude was larger. That is not a rule to memorize; it is what walking on a line does.

### Subtraction: addition of the opposite

Subtraction is the same operation as addition, but you take the opposite of the second number first. That is the rule to internalize:

$$a - b = a + (-b).$$

So $5 - 8 = 5 + (-8) = -3$. And the trickiest case, $5 - (-3)$, becomes $5 + 3 = 8$. *Subtracting a negative is adding a positive*, because the opposite of $-3$ is $3$, and once you flip the sign you are just adding.

That last fact is where the bumper sticker "two negatives make a positive" comes from. It is an oversimplification, but for subtraction of a negative number, it is correct.

### Worked example — walking off a problem

> **Problem.** Compute $-8 + 5 - (-3) + (-12)$ by interpreting each step as a walk on the number line.

> *Step 1.* Start at $0$.
> *Step 2.* $0 + (-8)$: walk eight left. You are at $-8$.
> *Step 3.* $-8 + 5$: walk five right. You are at $-3$.
> *Step 4.* $-3 - (-3)$ becomes $-3 + 3$: walk three right. You are at $0$.
> *Step 5.* $0 + (-12)$: walk twelve left. You are at $-12$.
>
> **Answer:** $-12$.
>
> *General lesson:* every signed-arithmetic problem can be solved by walking. Only when the line gets crowded — fractions, decimals, irrationals — does the walk get awkward, and we trade the picture for procedure.

### The trade-off

The number line is a *physical* model. You can point to it, walk along it, draw arrows on it. That makes addition and subtraction of integers nearly automatic — students who picture the line stop making sign errors.

The trade-off arrives when the operations get more complex. Multiplying $-3$ by $-4$ on a number line is awkward — *what does it mean to walk negative four times?* — and the picture starts to mislead. By the time you reach fractions and irrationals, the line is still a useful intuition pump but no longer the calculation engine. The *picture* of the number line keeps you honest about what numbers are. The *procedures* of arithmetic do the actual work.

That trade-off — visual intuition for procedural power — repeats throughout mathematics. Geometry buys you proof, algebra buys you generality. The number line is the visual that you carry with you while the symbols do the heavy lifting.

### Scale shift — the line, the very large, the very small

The number line in your head is finite. You can picture maybe ten ticks left and ten ticks right. The number line in the universe is not. Astronomers measure distances in *light-years* — the distance light travels in a year, about six trillion miles — and the diameter of the observable universe is about ninety-three billion light-years. Each of those distances sits at a specific point on the number line you have just been walking on. It is the same line.

In the other direction, a hydrogen atom is about one angstrom across — that is, about one ten-billionth of a meter. The point that represents the diameter of a hydrogen atom in meters sits between zero and any positive integer; it is a tiny crumb, but it is a crumb at a specific location, and the line knows where.

The number line is the only mathematical object that holds all of human measurement at once.

### Common misconceptions

- *"Negative ten is bigger than negative three because ten is bigger than three."* On the number line, $-10$ sits to the *left* of $-3$, so $-10 < -3$. Larger magnitude in the negative direction means smaller value, not larger. This trips up nearly every student exactly once.
- *"$|-5|$ equals $-5$ because the bars don't change anything."* The bars change everything. They strip the sign. $|-5| = 5$, always.
- *"Two negatives always make a positive."* True for *multiplication* of two negatives, and for *subtraction of a negative*. False as a general slogan. $-3 + (-4) = -7$, which is still negative. The slogan is a partial truth.

---

## 3. Concept 2 — Variables, expressions, and the order of operations

A recipe card on the counter. Halfway down it reads:

> *Combine 3 + 4 × 2 cups of flour with the wet ingredients.*

Two cooks read this. The first computes left to right: three plus four is seven, seven times two is fourteen. Fourteen cups of flour. The second knows the convention: multiplication first, then addition. Four times two is eight, plus three, is eleven. Eleven cups. They have just baked two completely different cakes. The recipe writer meant only one of them. Which?

The math does not, on its own, tell you. *Three plus four times two* is ambiguous on the page. The rules that resolve the ambiguity are conventions — agreements between writers and readers — not truths about numbers. Most of arithmetic is fine without them. Algebra is impossible without them.

This section is about three things that have to come before solving any equation: how we use letters to stand for numbers, how we read expressions that combine several operations, and how we keep track of what is and is not the same kind of thing.

### Variables: a letter standing in for a number

Suppose Greg is twenty years old and Alex is twenty-three. You know that Alex is three years older than Greg. When Greg was twelve, Alex was fifteen. When Greg is thirty-five, Alex will be thirty-eight. The *difference* between their ages is three years; the *ages themselves* keep changing.

In algebra, the names for these two kinds of quantities are **variables** (the things that change) and **constants** (the things that do not). If $g$ stands for Greg's age in years, then $g + 3$ stands for Alex's age — at every age Greg can be. The single expression $g + 3$ captures every row in the table:

| Greg's age | Alex's age |
|---|---|
| 12 | 15 |
| 20 | 23 |
| 35 | 38 |
| $g$ | $g + 3$ |

Letters most commonly used for variables are $x, y, a, b, c$. The letter is just a name. The *number it stands for* is what matters. When you assign a value — when you say *"let $g = 20$"* — you have *evaluated* the variable, and the expression containing it becomes a specific number: $g + 3 = 23$.

The leverage of this is enormous. One expression, infinitely many cases. *The reason algebra is more powerful than arithmetic is that algebra can talk about every number at once.*

### Expressions versus equations

An **expression** is a mathematical phrase. It does not, by itself, claim anything to be true. $3 + 4$ is an expression. So is $g + 3$. So is $3x^2 - 7x + 2$.

An **equation** is a complete sentence. It claims that two expressions name the same number:

$$3 + 4 = 7$$
$$g + 3 = 23$$
$$3x^2 - 7x + 2 = 0$$

Equations are the things you *solve*. Expressions are the things you *simplify* or *evaluate*. This chapter is mostly about expressions; equations show up in the next chapter.

### Why an order of operations is needed

Return to the recipe ambiguity: $3 + 4 \times 2$. There are exactly two reasonable readings: do the addition first and get $14$, or do the multiplication first and get $11$. The math does not decide. *Some* convention has to.

The convention used by every algebra textbook is **PEMDAS**:

1. **P**arentheses first.
2. **E**xponents next.
3. **M**ultiplication and **D**ivision, left to right.
4. **A**ddition and **S**ubtraction, left to right.

Under PEMDAS, $3 + 4 \times 2 = 3 + 8 = 11$. The multiplication binds tighter than the addition.

A subtle point that costs students a lot of partial credit: *multiplication and division are not separate steps*. They sit on the same rung, evaluated left to right. $12 \div 3 \times 2$ is *not* twelve divided by six, which would give two; it is twelve divided by three (giving four), then times two, giving eight. Same for addition and subtraction: $10 - 4 + 3$ is *not* ten minus seven, giving three; it is ten minus four (giving six), then plus three, giving nine. The mnemonic *PEMDAS* hides this; the truth is *P-E-MD-AS*, with multiplication-and-division and addition-and-subtraction as paired tiers.

The British use *BIDMAS* (Brackets, Indices, Division, Multiplication, Addition, Subtraction) and the implication looks different — division before multiplication — but it is the same rule. They are paired tiers in both.

### A worked example

> **Problem.** Evaluate $3x^2 - 2(x - 1)$ when $x = 4$.

> *Step 1 — substitute.* Replace each $x$ with $4$:
>
> $$3(4)^2 - 2(4 - 1)$$
>
> *Step 2 — parentheses first.* The inside of the rightmost parentheses is $4 - 1 = 3$. The expression becomes
>
> $$3(4)^2 - 2(3).$$
>
> *Step 3 — exponents next.* $4^2 = 16$.
>
> $$3(16) - 2(3).$$
>
> *Step 4 — multiplication and division, left to right.* $3 \times 16 = 48$ and $2 \times 3 = 6$.
>
> $$48 - 6.$$
>
> *Step 5 — addition and subtraction.*
>
> $$42.$$
>
> **Answer:** $42$.
>
> *General lesson:* substitute first, then peel from the inside out. Each line of work should change exactly one thing. If two things change at once, an error is hiding in the leap.

### The trade-off

PEMDAS is a convention, not a discovery. Nothing in the integers themselves says "multiplication binds tighter than addition." We *agreed* that it does, and now every expression you write means the same thing whether you read it in San Francisco or São Paulo. That is the gain: universal communication. Every algebra book in every language uses the same convention; every spreadsheet, every programming language uses a closely related one (though languages disagree on edge cases like exponentiation, and Python distinguishes `**` and `^` in ways that surprise mathematicians).

The cost is memorization. Students have to learn an arbitrary tier system — and learn it *by heart*, because hesitation breeds error. Worse, the system is just irregular enough to bite people. Multiplication and division are paired, but the *initial letter ordering* in PEMDAS suggests they are not. Subtraction is left-associative — $10 - 4 - 3 = 3$, not $9$ — but the mnemonic does not say so.

The trade-off is worth taking. The cost of *no* convention would be that no one could write an algebraic expression and trust that the next reader would compute the same number. But the cost is real, and it is paid in the partial-credit column of every algebra exam.

### Like terms — when can you combine?

After substituting and simplifying, you sometimes end up with multiple expressions that look almost the same. *Like terms* are terms that share the same *variable part* — the same letters raised to the same powers. Constants are like terms with each other.

$$3x \text{ and } 5x \text{ are like terms — same variable, same power.}$$
$$3x \text{ and } 5x^2 \text{ are not like terms — different powers.}$$
$$7y \text{ and } 4y \text{ are like terms — same variable.}$$
$$7y \text{ and } 4z \text{ are not like terms — different variables.}$$

When you combine like terms, you add or subtract their *coefficients* — the numerical part — and leave the variable part alone:

$$3x + 5x = 8x.$$

Why does this work? Because $3x$ means *three of $x$*, and $5x$ means *five of $x$*; together you have *eight of $x$*. It is the same logic as *three apples plus five apples is eight apples*. You cannot combine $3x$ with $5x^2$ for the same reason you cannot combine *three apples and five oranges* — they are different items, and the sum is just *three apples plus five oranges*, no further simplification possible.

### Translating English to algebra

A number of word problems in this and later chapters require you to take a sentence in English and write it as an algebraic expression. The trick is to identify which *operations* the words name.

| English | Algebra |
|---|---|
| *the sum of $x$ and $7$* | $x + 7$ |
| *seven less than $x$* | $x - 7$ |
| *seven minus $x$* | $7 - x$ |
| *the product of $x$ and $7$* | $7x$ |
| *the quotient of $x$ and $7$* | $x / 7$ |
| *twice a number* | $2n$ |
| *five less than twice a number* | $2n - 5$ |
| *the difference of $x$ and $y$, divided by $2$* | $(x - y)/2$ |

The two sneaky ones are *less than* and *more than*. They reverse the order. *Seven less than $x$* is $x - 7$, not $7 - x$. The number you are taking *from* comes first; the amount you take *off* comes second. Read the phrase aloud, decide what the larger or starting quantity is, and write *that* on the left.

### Common misconceptions

- *"PEMDAS means do all multiplication before all division."* No. Multiplication and division are paired and evaluated left to right. So is addition and subtraction.
- *"$5x$ and $5x^2$ are like terms because they both have $x$."* No. The exponent matters. Different exponents, different terms.
- *"You can substitute $x = 4$ before clearing parentheses."* You can — but if the parentheses contain other variables, you have to substitute every occurrence consistently. *Substitute every $x$ at once*, then proceed by PEMDAS.

---

## 4. Concept 3 — The properties of real numbers: the rules that make algebra legal

Quick: what is $19 \times 6$?

If you are like most adults, you did not multiply nineteen by six the way you were drilled in fourth grade. You computed $20 \times 6 = 120$ and then subtracted $6$, getting $114$. That mental shortcut — *replace the awkward number with a friendlier one, then correct* — is the **distributive property** doing work without being named.

This last concept is the most abstract of the chapter, and also the one that pays the most. Every legal manipulation in algebra is licensed by one of a small handful of properties. Once you know the properties by name, you stop wondering whether a given step is allowed; you check it against the list.

There are five families of properties to know.

### Commutative — order does not matter (for $+$ and $\times$)

For any real numbers $a$ and $b$:

$$a + b = b + a$$
$$ab = ba$$

You can add five and three in either order; you get eight. You can multiply seven and four in either order; you get twenty-eight. *Commutative* shares a Latin root with *commute* — to move back and forth — and the property says exactly that: you can move the numbers back and forth.

Subtraction and division are *not* commutative. $5 - 3 = 2$, but $3 - 5 = -2$. $12 / 4 = 3$, but $4 / 12 = 1/3$. The order matters; you cannot swap.

### Associative — grouping does not matter (for $+$ and $\times$)

For any real numbers $a$, $b$, and $c$:

$$(a + b) + c = a + (b + c)$$
$$(ab)c = a(bc)$$

If you are adding three numbers, you can add the first two together first, or the last two first; you get the same answer. The parentheses move; the result does not.

Again, subtraction and division break the property. $(10 - 4) - 3 = 3$, but $10 - (4 - 3) = 9$. The grouping matters.

### Identity — the number that does nothing

For any real number $a$:

$$a + 0 = a$$
$$a \cdot 1 = a$$

Zero is the *additive identity*: adding it changes nothing. One is the *multiplicative identity*: multiplying by it changes nothing. The word *identity* is precise here — the number remains identical after the operation. (And note: zero and one are not interchangeable. Add one to a number and it changes; multiply a number by zero and you get zero, which is a violent change. Zero is the identity for *addition only*; one is the identity for *multiplication only*.)

### Inverse — undoing the operation

For any real number $a$:

$$a + (-a) = 0$$

For any *nonzero* real number $a$:

$$a \cdot \frac{1}{a} = 1.$$

Every number has an *additive inverse* — its opposite — that, when added, returns you to the additive identity zero. Every nonzero number has a *multiplicative inverse* — its reciprocal — that, when multiplied, returns you to the multiplicative identity one.

The exception is zero. *Zero has no multiplicative inverse* — there is no number you can multiply by zero and get one, because zero times anything is zero. This is why dividing by zero is undefined; *division by $a$ is multiplication by $\frac{1}{a}$*, and $\frac{1}{0}$ does not exist.

### Distributive — the engine

For any real numbers $a$, $b$, and $c$:

$$a(b + c) = ab + ac.$$

This is the property that connects the two operations. Multiplication, applied to a sum, distributes across the sum. Each term inside the parentheses gets multiplied by the factor outside, and the results are added.

Why is this *the engine* of algebra? Because it is the property that lets you rewrite a product as a sum *or* a sum as a product. Read left to right, it is *expansion*: $3(x + 4) = 3x + 12$. Read right to left, it is *factoring*: $3x + 12 = 3(x + 4)$. Every expansion in this book and every factoring in chapter 7 is the distributive property in one direction or the other.

The mental shortcut from the start of this section — $19 \times 6 = (20 - 1) \times 6 = 120 - 6 = 114$ — is the distributive property applied to a difference, which works the same way: $a(b - c) = ab - ac$. The arithmetic gets easier because you have rewritten a hard product as a friendlier sum-or-difference of easier products.

### A worked example using all five properties

> **Problem.** Simplify $3(2x + 4) - 2x$ and name the property used at each step.

> *Step 1 — distributive property:*
>
> $$3(2x + 4) - 2x = 3 \cdot 2x + 3 \cdot 4 - 2x = 6x + 12 - 2x.$$
>
> *Step 2 — commutative property of addition*, to bring like terms together:
>
> $$6x + 12 - 2x = 6x - 2x + 12.$$
>
> *Step 3 — combine like terms* (which is itself the distributive property in reverse: $6x - 2x = (6 - 2)x = 4x$):
>
> $$6x - 2x + 12 = 4x + 12.$$
>
> **Answer:** $4x + 12$.
>
> *General lesson:* almost every simplification is the distributive property and combining like terms, with the commutative and associative properties quietly rearranging things in the background.

### The trade-off

The properties make algebra *legal*. Without them, every manipulation would have to be justified from first principles every time, and algebra would be unworkable. With them, you can string together many small moves — distribute, commute, combine, distribute again — and trust that each one preserves equality.

The cost is that the *names* of the properties hide the *thinking*. A student who writes "by the distributive property" at every step has not learned anything; they have learned to label. The properties are most useful when you can both *invoke them by name* (because you can check legality) *and* see *why* the move makes the problem easier (because you can choose moves wisely). The shortcut that lets a person compute $19 \times 6$ in their head is not the distributive property as a rule; it is the distributive property as an *insight*.

The reflexive note: these "properties" are not laws of nature. They are properties *of the real numbers under the operations of addition and multiplication*. In other mathematical systems they break. Matrix multiplication is not commutative — $AB$ and $BA$ are usually different matrices. The cross product of vectors is not associative. In modular arithmetic, every nonzero number has an inverse only when the modulus is prime. The properties of the real numbers are a *very nice* package, and you will spend the rest of this book exploiting them. But they are not the only package, and treating them as the only package limits what kinds of mathematics you can later see.

[FIGURE: A two-column comparison. Left column: "Real numbers under + and ×" with bullets — commutative ✓, associative ✓, identity ✓, inverse ✓ (except 0 for ×), distributive ✓. Right column: "2×2 matrix multiplication" with bullets — commutative ✗ (AB ≠ BA in general), associative ✓, identity ✓, inverse ✓ (only for invertible matrices), distributive ✓. Pedagogical purpose: show that the properties are properties of a *system*, not laws of nature.]

### Common misconceptions

- *"The distributive property works for multiplication across multiplication."* It does not. $a(bc) \ne (ab)(ac)$. The property distributes multiplication across *addition* (or subtraction), not across multiplication.
- *"$0$ has a multiplicative inverse, it's just $\frac{1}{0}$."* No. $\frac{1}{0}$ is undefined, full stop. Zero is the only real number without a multiplicative inverse.
- *"The commutative property lets me rearrange anything."* It lets you rearrange *terms in addition* and *factors in multiplication*. It does *not* let you rearrange terms in subtraction or division. $5 - 3 \ne 3 - 5$.

---

## 5. Integration / Synthesis

A contractor needs to cut a sixteen-foot board into three pieces. Two of the pieces are to be the same length. The third is to be nine inches longer than each of the first two. The saw blade is one-eighth of an inch thick, and each cut consumes that much wood as kerf. Two cuts are needed. How long is each of the equal pieces?

This is the kind of problem the chapter exists for. It uses every concept we have built.

### Setting up — Concept 2 in action

Let $x$ be the length, in inches, of each of the equal pieces. The third piece is $x + 9$ inches. There are two cuts, and each cut wastes $\frac{1}{8}$ inch.

The total length of the original board, in inches, is $16 \times 12 = 192$. That total has to account for everything: the three pieces *and* the waste from the cuts.

$$x + x + (x + 9) + 2 \cdot \frac{1}{8} = 192.$$

The two-cut waste, $2 \cdot \frac{1}{8}$, simplifies to $\frac{1}{4}$.

$$x + x + (x + 9) + \frac{1}{4} = 192.$$

### Simplifying — Concepts 2 and 3 working together

Combine like terms — that is the commutative and distributive properties at work. The three $x$'s sum to $3x$:

$$3x + 9 + \frac{1}{4} = 192.$$

The constants $9$ and $\frac{1}{4}$ combine to $9.25$ (or, as a fraction, $\frac{37}{4}$):

$$3x + \frac{37}{4} = 192.$$

To isolate $3x$, subtract $\frac{37}{4}$ from both sides — the additive inverse property:

$$3x = 192 - \frac{37}{4} = \frac{768}{4} - \frac{37}{4} = \frac{731}{4}.$$

Divide both sides by $3$ — the multiplicative inverse property:

$$x = \frac{731}{4 \cdot 3} = \frac{731}{12} \approx 60.92 \text{ inches.}$$

### Checking — Concept 1 keeps us honest

Does this answer make sense on the number line? Each equal piece is about $60.92$ inches, which is just over five feet. The third piece is nine inches longer, about $69.92$ inches, just under six feet. Adding three pieces: about $60.92 + 60.92 + 69.92 \approx 191.76$ inches. Plus a quarter inch for the cuts: $192.01$. Close enough; the rounding error in $60.92$ vs. the exact $\frac{731}{12}$ accounts for the discrepancy.

That last check matters. The answer came from algebra, but the *sanity check* came from estimating where the result sits on the number line. Numbers that came out hugely positive or negative would have signaled an error in the setup.

### What this shows about the design of algebra

The three concepts of this chapter were not chosen arbitrarily.

- The **number line** anchors what counts as a number. Without it, when the answer comes out as $\frac{731}{12}$, you have no way to know if that is reasonable.
- **Variables and order of operations** let you set up the problem at all. Without $x$, you would be stuck guessing at lengths until one combination worked.
- **The properties of real numbers** license every step of simplification. Without them, you would not know that combining $x + x + x = 3x$ is legal, or that you can subtract $\frac{37}{4}$ from both sides without changing what is true.

This is the philosophical structure of algebra. *Numbers, names for unknown numbers, and the legal moves that connect them.* Each chapter ahead will introduce more techniques — solving equations, graphing, factoring, working with rational expressions — but every technique will rest on these three pieces.

---

## 6. Exercises

### Warm-up

1. **(LO 1, easy)** On a number line, locate $-\frac{7}{2}$, $|-5|$, $0$, and $|-(-3)|$. Then list them from least to greatest.

2. **(LO 2, easy)** Evaluate $12 \div 4 + 3 \times 2 - 5$ using PEMDAS. Show each step.

3. **(LO 3, easy)** State which property is used in each of the following:
   (a) $7(x + 2) = 7x + 14$
   (b) $5 + 3 = 3 + 5$
   (c) $a + 0 = a$
   (d) $4 \cdot \frac{1}{4} = 1$

### Application

4. **(LO 2 and 3, medium)** Simplify $5(3a - 2) + 4(a + 1) - 7$. Name the property used at each step.

5. **(LO 4, medium)** Translate to an algebraic expression: *the difference between three times a number and seven, divided by two.* Then evaluate your expression for $n = 5$.

6. **(LO 4, medium)** Evaluate $m^2 - 4n$ for $m = -3$ and $n = 2$.

7. **(LO 1, medium)** Compute $-8 + 5 - (-3) + (-12)$. Show your work as a sequence of moves on a number line, naming each move.

### Synthesis

8. **(LO 1 and 4, harder)** A bank account starts at \$250. Three transactions occur, in this order: a deposit of \$80, a withdrawal of \$135, and a returned-check fee of \$30 charged twice. Write a single algebraic expression for the final balance. Evaluate it. Locate the result relative to zero on a number line, and state in words whether the account is overdrawn.

9. **(LO 2 and 3, harder)** Simplify
$$\frac{2}{3}(6x - 9) + \frac{1}{4}(8x + 12).$$
Show each step and name the property used.

10. **(LO 4, harder)** A taxi service charges \$3.50 plus \$2.20 per mile. Write an expression $C(d)$ for the cost of a trip of $d$ miles. Evaluate for $d = 7.5$. Then write a single expression for the total cost of two trips — one of $d$ miles and one of $2d$ miles — and simplify it using the distributive property.

### Challenge

11. **(LO 2, hard)** Construct an arithmetic expression that gives a different answer if you (incorrectly) apply addition before multiplication. Then add parentheses so that the *incorrect-order* answer becomes the correct answer. What does this exercise tell you about the role of parentheses in PEMDAS — and about the role of conventions in mathematics more generally?

12. **(LO 3, hard, points toward chapter 5 and beyond)** The integers under addition and multiplication satisfy commutative, associative, and distributive properties. Find a familiar non-mathematical operation — making a sandwich, giving driving directions, dressing for the cold — that is *not* commutative. Describe the operation precisely enough that someone could test the failure of commutativity by swapping the order of two specific steps and observing the different result.

---

## 7. Chapter summary

You came in with arithmetic. You leave with three things you did not have before.

You can *locate* any rational number on a number line, name its opposite and absolute value, and add or subtract integers by walking on the line. You know that $-(-a) = a$ and that $|a|$ is always nonnegative. You know what the integers, the rationals, and the reals are, and that the real number line holds all of them — though some of them, the irrationals, cannot be written as exact fractions.

You can *evaluate* an expression by substituting values for variables and applying the order of operations. You know that PEMDAS is a convention, not a discovery — that multiplication and division share a tier and are evaluated left to right, and that addition and subtraction share a tier and are evaluated left to right. You can combine like terms, and you know that two terms are *like* only when their variable parts match exactly.

You can *identify and use* the five families of properties — commutative, associative, identity, inverse, distributive — and you know that the distributive property, alone among them, connects multiplication to addition and is therefore the engine of expansion and factoring. You know that the properties hold for the real numbers, and that they do not all hold for every mathematical system.

The single most important idea: *the rules of algebra are the properties of the real numbers, plus the convention of order of operations.* Every legal move you will make in the chapters ahead is one of those properties or a careful reading of that convention.

The most common mistake to watch for: *sign errors and order-of-operations errors compound*. A student who drops a negative sign in step three of a four-step problem will probably also miscombine like terms in step four, and the original sign error will be untraceable by the time the answer comes out wrong. The defense is to write each step on its own line, change one thing per line, and check at every transition.

What you should now be able to teach someone else: why $-(-5) = 5$, why $3x + 5x = 8x$ but $3x + 5x^2$ does not simplify, why $a(b + c) = ab + ac$ is the engine that the rest of algebra runs on, and why dividing by zero has no answer.

---

## 8. Connections forward

Chapter 2 begins where this chapter ends. You can *simplify* expressions; you cannot yet *solve* equations. An equation is the claim that two expressions name the same number. Solving one means finding the value of the variable that makes the claim true.

The reason chapter 2 will not feel like a new subject is that every move in solving a linear equation is one of the properties from this chapter. When you isolate $x$ by adding the same number to both sides, you are using the additive inverse property to clear a constant. When you divide both sides by three, you are using the multiplicative inverse property to clear a coefficient. When you combine $5x - 2x$ on one side, you are using the distributive property in reverse. *Solving equations is not new arithmetic; it is the properties applied with a goal.*

Bring the number line with you. When the answer to chapter 2's equation comes out as $x = -7$, you should picture exactly where on the line that sits and what it would mean in the original problem. The answer is never just a number; it is a position on the line, and the problem is what made that position meaningful.

---

**What would change my mind:** If the historical and pedagogical record showed that PEMDAS itself causes more student errors than it prevents — that a different convention (for example, strict left-to-right evaluation with explicit parentheses required for any non-default order) would yield better learning outcomes — I'd reconsider whether this chapter teaches PEMDAS as the natural way to read expressions or names it as the historically contingent convention it actually is. I currently lean toward the second framing but teach the first.

**Still puzzling:** Why does the distributive property feel structurally different from the other four? It is the only one that connects two different operations, and the only one that does the heavy lifting in expansion and factoring. Whether that asymmetry is a deep fact about how addition and multiplication interact, or just a notational artifact of how we write down numbers, I am not sure.

---

**Tags:** number-line, integers, real-numbers, order-of-operations, distributive-property, elementary-algebra, openstax, foundations, properties-of-real-numbers, variables

---

*This chapter is a voice rewrite of OpenStax* Elementary Algebra 2e *Chapter 1, modules m82451 through m82461, used under CC-BY 4.0. Source content — facts, examples, sequencing of arithmetic operations, treatment of properties — derives from OpenStax. Voice, scene work, framing, trade-off analysis, and pedagogical commentary are original to this rewrite.*
---

## LLM Exercise — Chapter 1: Foundations (Modeling One Phenomenon Project)

**Project:** Mathematical Modeling of One Phenomenon — across the semester, build increasingly sophisticated models (linear → systems → polynomial → factored → rational → radical → quadratic) of a single real-world situation you pick now.
**What you're building this chapter:** the foundation — pick the phenomenon, identify its variables and units, and write the descriptive (pre-mathematical) model.
**Tool:** **Claude Project** "Modeling [Your Phenomenon]." Every later chapter adds a section to a single document inside this Project.

---

**The Prompt:**

```
I'm starting a semester-long Mathematical Modeling project for my
algebra course. I'll pick one real-world phenomenon now and build
increasingly sophisticated mathematical models of it across all 10
chapters. By Chapter 10 I should have a quadratic model with a real
parabola.

Help me set this up. Ask me ONE question at a time, waiting for my
answer.

1. Pick the phenomenon. Pick ONE from this list (or propose a
   sharper one in the same shape):
   - Compound-interest savings growth (one account growing over
     time).
   - Mortgage amortization (monthly payment, balance, interest
     vs. principal split).
   - Projectile motion (a ball thrown, a basketball shot, a
     rocket launch).
   - Personal fitness progression (lifts, mile pace, recovery
     time).
   - Recipe scaling and cost (yield, ingredient cost, batch
     economics for cooking or coffee).
   - Cell phone bill with data overage (base plan + per-GB
     overage).
   - Photographic exposure (aperture, shutter, ISO trade-offs).
   - A gaming phenomenon you understand (XP curves, drop rates,
     respawn times).
   - Sports analytics (free throw percentage and distance, pace
     and recovery, shot probability and angle).
   The phenomenon must (a) involve at least two measurable
   variables, (b) plausibly have linear, polynomial, AND quadratic
   behavior at different scales, (c) be something you actually
   care enough to model 10 chapters in a row about.

2. The variables. Name 3–5 measurable variables in the phenomenon.
   For each: the symbol you'll use (consistent across chapters);
   the units; the typical range. Example for compound interest:
   P (principal, dollars, $0–$100,000); r (annual rate, decimal,
   0.01–0.10); t (time in years, 0–50); A (final amount, dollars).

3. The relationships you've already noticed (in plain English).
   What goes up when what else goes up? What's the most surprising
   relationship in the phenomenon — the one you don't fully
   understand?

4. The single question this whole modeling project is going to
   answer by Chapter 10. State it sharp enough that the answer is
   a specific number, decision, or curve. Examples:
   - "What monthly savings amount, at 5% interest, lets me reach
     $100K by age 35?"
   - "Given my 200-pound bench at 30, what's my realistic max
     and the age at which I hit it?"
   - "What's the optimal launch angle for the longest free throw
     given my arm strength?"

After all four answers, write a 400–600 word **Foundation
Document** as a markdown document. It should:

- Open with the phenomenon in one sentence.
- Define each variable with symbol, units, and typical range.
- State the relationships in English (no math yet).
- State the project's central question.
- Apply Chapter 1's properties of real numbers — name where the
  commutative, associative, or distributive properties will
  matter when the math gets real (e.g., "the cost of N units of
  X plus M units of Y is the same in either order — that's
  commutative addition").
- Use Chapter 1's number-line framing — what's the range of the
  phenomenon's variables in real numbers? Are any irrational?
  Are any constrained to integers (count of objects) or
  positives (lengths, times)?
- End with the first acceptance test: a single specific instance
  of the phenomenon that any later model must explain.
```

---

**What this produces:** A 400–600 word Foundation Document — the project's anchor. Every later chapter adds to this document, building toward the Chapter 10 final.

**How to adapt this prompt:**

- *For your own project:* The phenomenon needs to be one you care about. A bored student modeling a phenomenon they picked at random will produce work indistinguishable from an exercise; a student modeling something they actually want to understand will go deep.
- *For ChatGPT / Gemini:* Works as written.
- *For Claude Code:* Wrong tool for setup.
- *For a Claude Project:* Essential. Build the Project around this Foundation Document — every later chapter loads it as context.

**Connection to previous chapters:** This is the project's opening.

**Preview of next chapter:** Chapter 2 builds the first real mathematical model — a linear equation describing one relationship in your phenomenon. You'll solve it for an unknown and use it to answer a specific question about your phenomenon.


---

## AI Wayback Machine

**Aryabhata** was Indian mathematician of the 5th century who introduced the place-value system and a precise estimate of π.

**Run this:**

```
Who is Aryabhata, and how does their work connect to pre-algebra foundations we covered in this chapter? Keep it to three paragraphs. End with the single most surprising thing about their career or ideas.
```

→ Search **"Aryabhata"** on Wikipedia.

**Now make the prompt better.** Try one of these:

- Ask it to solve a specific problem the way Aryabhata would have.
- Add a constraint: "Answer including criticisms or limits of Aryabhata's methods."

What changes? What gets better? What gets worse?
