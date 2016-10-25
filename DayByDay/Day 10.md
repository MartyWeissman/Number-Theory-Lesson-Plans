# Day 10,  October 25, 2016.
## Modular dynamics.

**Read before class:**  Chapter 6

## Introduction

Truth in Diophantine equations and truth in congruences.  Review of reduction.

Now, living in a modular world, we study dynamics.  What happens if you begin with a number, and repeat a process over and over and over again?  

Example:  Mod 7.  Begin with x.  Replace x by x^2 + 1.  Repeat.  What pattern do you find?
0,1,2,5,5,5,5.  3,3,3,3,.  4,3,3,3.  6,2,5,5,5...

Example:  Mod 8.  Begin with x.  Multiply by 6.  Repeat.  What pattern do you find?  0-->0, 1-->6-->4-->0, 2--> 4 --> 0,...

## Multiplicative dynamics.

Multiplication by a, mod p.  Have class consider p = 13.  Do multiplication by 4 on the board.  Note coincidence with book cover at the end.  Ask for observations -- note that the dynamics yield cycles, all of the same length.

Proof:  (1)  Every element belongs to a cycle.  (2) Every cycle has the same length as 1.  (3)  The cycle length is the smallest exponent for which a^e = 1 mod p.

Corollary:  Fermat's Little Theorem.  
Corollary (contrapositive):  p is *not prime* if a^(p-1) is not 1 mod p, and 1 <= 1 <= p-1.

Computation:  How to compute 2^90 mod 91 *quickly* by Pingala's algorithm.

One other property of primes:  the ROO property.  Read before section.

## Conclusion

Generalization:  The totient and the Fermat-Euler theorem.  Coming soon!  
