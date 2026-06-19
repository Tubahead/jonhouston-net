---
title: Infinity
---

## Definitions

### Set

A **set** is a container that you can put things in.

For example:

- The set of students in a classroom
- The set of books on a shelf
- The set of natural numbers

### Cardinality

**Cardinality** is the number of objects in a set.

For finite sets, this is straightforward.

For example, the set `{apple, banana, orange}` has a cardinality of 3.

But with infinite sets, things get stranger.

### Natural Numbers

The **natural numbers** are the counting numbers:

```text
1, 2, 3, 4, 5, ...
```

### Rational Numbers

The **rational numbers** are numbers that can be written as fractions.

Their decimal places either end or repeat forever.

Examples:

```text
1/2 = 0.5
1/3 = 0.333...
3/4 = 0.75
```

### Real Numbers

The **real numbers** include both rational and irrational numbers.

Irrational numbers cannot be written as fractions. Their decimal places do not end and do not repeat in a pattern.

Examples:

```text
π
√2
0.101001000100001...
```

## Theorems

## Cardinality Without Counting

You do not need to be able to count the members of a set in order to know that one set has a higher cardinality than another.

You just need a way to match the members of one set to the members of another set.

If every member of one set can be matched with every member of another set, then the two sets have the same cardinality.

If one set has members left over, then that set is bigger.

## Theorem 1: The Rational Numbers and the Natural Numbers Have the Same Cardinality

The set of rational numbers and the set of natural numbers have the same cardinality.

This seems strange because there appear to be many more rational numbers than natural numbers.

After all, between 1 and 2 alone there are infinitely many fractions.

But the question is not whether there are a lot of rational numbers.

The question is whether we can list them.

If we can make a numbered list of all the rational numbers, then the rational numbers have the same cardinality as the natural numbers.

## Proof Idea

Every rational number can be written as a fraction.

Each fraction has:

- A numerator, or top number
- A denominator, or bottom number

So we can imagine rational numbers as pairs of numbers:

```text
(1,1)  (2,1)  (3,1)  (4,1)  (5,1)
(1,2)  (2,2)  (3,2)  (4,2)  (5,2)
(1,3)  (2,3)  (3,3)  (4,3)  (5,3)
(1,4)  (2,4)  (3,4)  (4,4)  (5,4)
(1,5)  (2,5)  (3,5)  (4,5)  (5,5)
```

In each pair, take the first number as the numerator and the second number as the denominator.

So `(3,2)` represents:

```text
3/2
```

Now we list the fractions by moving through the grid diagonally.

First list all fractions where the numerator and denominator add up to 2.

Then list all fractions where they add up to 3.

Then 4.

Then 5.

And so on forever.

For example:

```text
1.  1/1

2.  2/1
3.  1/2

4.  3/1
5.  2/2
6.  1/3

7.  4/1
8.  3/2
9.  2/3
10. 1/4
```

If we keep going like this, every rational number will eventually appear on the list.

Therefore, every rational number can be paired with a natural number.

So the set of rational numbers and the set of natural numbers have the same cardinality.

## Theorem 2: The Real Numbers Have a Higher Cardinality Than the Natural Numbers

The set of real numbers has a higher cardinality than the set of natural numbers.

## Proof Idea

Suppose the real numbers had the same cardinality as the natural numbers.

If that were true, then we should be able to make a complete numbered list of all the real numbers between 0 and 1.

Such a list might look like this:

```text
1.  .0028765435...
2.  .0038989765...
3.  .0039999996...
4.  .0066666652...
5.  .0898989895...
6.  .1000000009...
7.  .7114598567...
8.  .7222222434...
9.  .8000000000...
10. .9999911222...
11. ...
```

Now make a new number by changing the first digit of the first number, the second digit of the second number, the third digit of the third number, and so on.

For example, the new number might be:

```text
.1147019513...
```

This is clearly a real number between 0 and 1.

Since our list is supposed to contain all the real numbers between 0 and 1, this new number should be somewhere on the list.

But it cannot be the first number, because it differs from the first number in the first digit.

It cannot be the second number, because it differs from the second number in the second digit.

It cannot be the third number, because it differs from the third number in the third digit.

In the same way, it cannot be the fourth number, the tenth number, the 10,000th number, or the 1,113,456,469,655,202nd number.

Our new number will never appear on the list.

But that means the original list was not actually a complete list of all the real numbers.

Therefore, we cannot make a complete numbered list of the real numbers.

So the real numbers have a higher cardinality than the natural numbers.

## Questions

1. Do you think we have discovered something about the universe when we found out there is more than one type of infinity, or are we merely inventing new kinds of things? Is infinity really out there in the world, or is it only in our heads?

2. There are a lot of atoms in the universe, but there are not infinitely many atoms. We have never really experienced infinity before. Do you think we can actually understand infinity? What are some of the ways we have tried to come to grips with the infinite?

3. The first of Hilbert’s famous questions was whether there was some set of numbers bigger than the natural numbers but smaller than the real numbers. Kurt Gödel’s incompleteness theorem famously showed that there are things in math that are true but that we can never prove are true. Do you think we should still trust math?

4. The concept of infinity leads to all sorts of paradoxes, such as Zeno’s paradox. Should we still trust the concept of infinity?

5. When our reasoning leads us to really weird conclusions, should we still trust reason?