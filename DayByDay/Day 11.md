# Day 11,  October 11, 2016.
## The Totient and the Fermat-Euler Theorem.

**Read before class:**  Chapter 6 up to p.177.

## Primality Testing

Recall Fermat's Little theorem:  If p is prime and GCD(a,p) = 1, then a^(p-1) = 1 mod p.
What is the hypothesis?  What is the conclusion?  Does it hold for non-prime p?  Does it hold if GCD(a,p) is not 1?

Using FLT as a primality test.  The example of 561.  Here's a Pingala table:

exponent n: 560 280 140 70  35  34  17  16  8 4 2 1
2^n mod 561:  1   1  67 166 263 412 359 460 256 16  4 2

So FLT holds, but there is something else in the table that violates primality.  Namely, 67 * 67 = 1, mod 561.  This violates the (ROO) property of primes.

The Miller-Rabin test for primality:  Test whether p is prime in the following steps:
1.  Choose a random base b (between 2 and p-1).
2.  Make a Pingala table for powers of b, up to b^(p-1).
3.  If you see a violation of FLT or of ROO, then p is not prime.  STOP.
4.  Repeat t times.
5.  If you do not see a violation of FLT or of ROO, then p is probably prime.  The chance that p is prime is about 1 / 4^t.
6.  If p < 341 trillion, you can just use the bases b = 2,3,5,7,11,13,17.  If p isn't prime, then one of these bases will see it.

## Totients and the generalization of FLT.

Definition of the totient.
Proof of Euler's generalization.  Exhibit of dynamics mod 10.  Computation of phi(10).

Review of multiplicative functions.  Computation of phi.

Computation of big exponents.

## Conclusion

Chinese remainder theorem.  Proof of multiplicativity of phi.
