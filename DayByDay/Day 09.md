# Day 9,  October 20, 2016.
## Algebra in modular arithmetic.  Introduction to dynamics.

**Read before class:**  Chapter 5.  Beginning, to page 153.

## Introduction

In the world of numbers, mod m, there are only m numbers.  These numbers can be represented by 0,1,...,m-1, the "natural representatives".  "Sameness" is given by congruence mod m.  The operations in this modular world are addition, subtraction, and multiplication.  Familiar properties hold:  commutativity, associativity, identity (0 and 1), and the distributive law.  Such a world of numbers is called a "ring".  Other examples of rings include Z, Q, R, C.

Additive inverses exist, mod m.  Let's see them for natural representatives.

Once one has these properties, one can solve many equations using familiar methods.  You can always "do the same thing to both sides" of an equation/congruence, but remember that you can only "do" addition, subtraction, and multiplication.  NOT division, in general.  And remember that "doing things" to equations should be thought of as a deductive process... "*If* x+3 = 5, *then* x = 2."

So one can solve x+7 = 5, mod 10.  But what if one tries to solve 2x = 4, mod 10?  

## Multiplicative inverses

Let's solve 13x = 1 mod 20.  

Theorem:  Existence of multiplicative inverses.
Corollary:  Working mod p, when p is prime.
Solving equations, mod p.  Cancellation principle.
Study:  Which numbers are their own additive inverse?  mult inverse?
ROO principle.

Introduction to dynamics.  Additive dynamics and cycle lengths.  Prime modulus.  Composite modulus.

Multiplicative dynamics.  Bad example.  Restricting to Phi(n).

## Conclusion

Next week -- modular dynamics to cryptography.  Read Chapter 6.
