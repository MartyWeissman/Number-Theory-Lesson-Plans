# Day 20,  December 1, 2016.
## Finishing class.

## Fermat's Xmas Theorem

Claim:  If $p = 1$ mod $4$, then $p$ can be expressed as the sum of two squares.  First proven by Euler, 1752.

Lemma:  (Minkowski's thm)  If the area of the circle is at least 4 times the area of a parallelogram in a grid, then the circle contains a non-origin grid-point.  Take overlap point.  Unfold to get two points P and Q.  P = Q + 2 \lambda.  Q' = -Q in the circle.  Midpoint M = (P+Q')/2 = \lambda in the grid and in the circle.  

Thm:  (Fermat XMas Thm)  Suppose p = 1 mod 4.  Let u be an integer satisfying u^2 = -1 mod p.  Consider the lattice of points (x,y) satisfying x = uy mod p.  This is a grid of parallelograms, corners (0,0), (u,1), (p,0), (p+u,1).  Area = p.  Put a circle of area 4p at the origin.  Radius^2 = 4p / pi.  

Then there's a lattice point.  It satisfies x^2 + y^2 <= (4/pi) p and x = uy mod p.  Thus x^2 = - y^2 mod p.  So x^2 + y^2 is a multiple of p.  So x^2 + y^2 = p.  Done!

## 2 Million Dollars

### The Riemann Hypothesis.
Heuristic:  If t >= 2, then t has a 1/log(t) chance of being prime.  
Implication:  The number of primes between 2 and x is about \sum_2^x 1/log(t).  This is approximately equal to the integral.
Gauss used this to approximate the number of primes.
E.g.:  There are 78498 primes up to 1 million.  Gauss counted 78501 (off by 3).  The approximation gives 78627, pretty close!
We can make "approximately" precise by making statements about the error.  Two ways to think about it:  relative and absolute.

Relative:  Consider Approx / True, and compare to 100%.  Theorem (PNT, Hadamard and Vallee Poussin, 1896):  limit of Approx / True = 1, as x approaches infinity.

Absolute:  Consider abs(Approx - True) and compare to 0.  Conjecture:  Error <= 1/8 pi * sqrt(x) log(x).  ($1000000)

### BSD.

Consider an equation of the form y^2 = x^3 + a.  
Question 1:  How many rational numbers (x,y) satisfy this equation?  Answer:  maybe finite, maybe infinite!

Question 2:  How many solutions to y^2 = x^3 + a are there mod p?  Answer:  between 0 and p^2.  On average, about p.  (Error <= 2 sqrt(p) by Hasse).

Link:  Statistics in Q2 relate to answer in Q1.  Consider the product (a_p + 1) / p, where a_p = number of solutions mod p.  Each term is pretty close to 1, so the product may converge.  

Conjecture (BSD):  The product grows without bound if and only if E has infinitely many rational solutions.

## Conclusion

Evaluations of Joe and myself.
