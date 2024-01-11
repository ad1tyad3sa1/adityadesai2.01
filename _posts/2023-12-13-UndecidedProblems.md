---
toc: true
comments: false
layout: base
title: Undecided Problems 
description: Blog/Hacks
type: hacks
courses: { compsci: {week: 4} }
---

# Undecidable Problems and Popcorn Hack Summaries

## Undecidable Problems:

## Definition:

Some problems are inherently unsolvable by algorithms, even with infinite time. These are known as undecidable problems.

# Characteristics:

Decidable problems have algorithms that provide correct answers for all inputs, while undecidable problems lack such algorithms.
Undecidable problems may have instances solvable by algorithms, but there's no universal algorithm for all cases.

## Popcorn Hack #1 - Consequences of Undecidable Problems:

Scenario:
A tool to detect "unreachable code" claims to find and delete 100% of such code.
Question:
What are the consequences of this problem being undecidable?
Answer:
B: The tool can correctly determine unreachable code most of the time but won't be accurate in all cases.

- Halting Problem: A classic undecidable problem addressing whether a program, given any input, will eventually halt or run indefinitely.
Turing's Proof Through Contradiction:
Assume a halting algorithm exists, then create a "Reverser" that contradicts its results when applied to itself.
Contradiction arises, proving the nonexistence of a universal halting algorithm.

## Popcorn Hack #2 - Halting Problem Summary:
Question:
What best summarizes the Halting Problem?
Answer:
A: The Halting Problem is a decision problem seeking to determine whether a given algorithm will halt or run indefinitely for all possible inputs.
Undecidable Problems Examples:
Post Correspondence Problem (PCP):

---------------------------------------------------------

Definition:
Involves arranging tiles with strings to match on the top and bottom.
Undecidability:
No algorithm can determine sequences for all sets of tiles.
Rice's Theorem:

Definition:
States any non-trivial property about a program's behavior is undecidable.
Undecidability:
No algorithm can always answer questions about a program's behavior.
Collatz Conjecture:

Definition:
A mathematical hypothesis about the behavior of positive integers.
Undecidability:
Proving or disproving the conjecture remains an unsolved problem.
Tiling Problem:

Definition:
Determines if a given shape can be tiled without gaps or overlaps.
Undecidability:
Proving whether an arbitrary shape can be tiled is undecidable.
Entscheidungsproblem:

Definition:
Originally posed by David Hilbert, inquires about a general algorithm to determine truth or falsity in mathematics.

Undecidability:
No algorithm can decide the truth or falsity of statements in arithmetic.

---------------------------------------------------------
## Popcorn Hack #3 - Alternative Examples of Undecidable Problems:

Question:
Which option is not an example of an undecidable problem?
Answer:
D: Bubble sorting (Bubble sorting is a sorting algorithm, not an undecidable problem.)

