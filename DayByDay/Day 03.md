# Day 3,  September 29, 2016.
## Prime decomposition.

**Read before class:**  Start Chapter 2

## Introduction

Last time, we finished the study of GCD and LCM, and connected them to the solution of LDE.  We had an existence theorem for solutions to ax+by = c.  This generalizes to more variables, which you might see in the exercises.  I also mentioned that GCD(a,b) = 1 happens pretty often... when this happens, we say that a and b are coprime.  

Today, we start looking at prime numbers, starting with the definition.

## Activity

Sieving activity, to get primes up to 100.

How many divisions do we need to test whether a number like 997 is prime?

We can use a large class for parallel processing.  Assign students the numbers 2,3,5,7,11,13,17,19,23,29,31.  Ask them whether their prime divides 997.  If nobody says yes, then 997 is prime.  Some algorithms are easy to parallelize and some are not.

## Theory

Easy result:  every number can be factored into primes.

Consequence:  Euclid's proof of the infinitude of primes.

Question:  Could a number be factored into primes in two different ways?

What if I told you that 43 * 73 = 23 * 133.  Would this be surprising?  Why?

Euclid's lemma and the solubility of LDE.

If a prime divides a product, the prime divides a factor.

Proof that if (p1)(q1) = (p2)(q2), then the primes on either side are equal.

## Decomposition

The general form of prime decomposition.

The proof of uniqueness of decomposition.  First, prove that if ep = 0, then fp = 0.  Next prove that if ep = 1, then fp = 1.  Etc., informal proof by induction.

## Conclusion

Once we have uniqueness of prime decomposition, we can transform questions about multiplication and divisibility into questions about addition and comparison.  We can re-interpret a|b in terms of an inequality of the exponents.  Time-permitting, we can re-examine the GCD LCM identity.
