# Day 15,  November 10, 2016.
## The Legendre Symbol and Zolotarev's Lemma.

**Read before class:**  Chapter 8

## The Legendre Symbol

We have talked about "squareness mod p" and proved Euler's criterion.  Legendre introduced a notation related Euler's criterion:  "a on p" is defined to be 1, -1, or 0 according to whether a is a nonzero square, a nonsquare, or zero mod p.  We have proven four things about "a on p" so far:  Euler's criterion, multiplicativity, (-1 on p) and (-2 on p).

Today we relate the Legendre symbol to the sign of a permutation.

## The sign of a permutation:  cycle interpretation.

Def:  odd-length cycles have sign 1 and even-length cycles have sign -1.  Sign(pi) equals the product of the signs of the its cycles.

A permutation is called even if it has sign 1, odd if it has sign -1.

Transpositions have sign -1.

Zolotarev:  The sign of "multiplication by a mod p" equals (a on p).

Proof:  Note (p-1) = \ell c where ell is the length of a cycle and c is the number of cycles.  Note that a^\ell = 1 and no smaller positive power of a equals 1.  

Case 1:  c is even.  In this case, (p-1)/2 = \ell (c/2) and so a^( (p-1)/2) = (a^\ell)^(c/2) = 1, so (a on p) = 1.  Also, sgn = (sgn of l-cycle)^c = 1.  So ok.

Case 2:  c is odd.  In this case, \ell is even, since (p-1) is even.  We have a^( (p-1)/2 ) = (a^(\ell / 2))^c) = (-1)^c = (-1). So (a on p) = -1.  Also, sgn = (sgn of l-cycle)^c = (-1)^c = -1.  So ok.

## Two other interpretations of signs.

Building permutations out of transpositions.  From cycles to functions.  How to build.  The effect of a transposition on a cycle diagram.  Every time you compose with another transposition, the sign switches.  

Corollary, sign( \pi \circ \rho) = sign(\pi) \circ sign(\rho).

## Conclusion

Next week, we'll use this permutation interpretation to prove quadratic reciprocity.  Before we go, let's see the statement of quadratic reciprocity and how to use it.  Example:  (7 / 103) and (7/101) and (23 / 37).   
