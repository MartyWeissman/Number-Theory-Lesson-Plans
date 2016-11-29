# Day 19,  November 29, 2016.
## Squares, sums of squares, origins and consequences of reciprocity.

**Read before class:**  Chapter 8

## The statement of reciprocities.

Quesiton:  Is $x$ a square mod $p$?  We can answer this question thanks to reciprocity.  Audience-provided problem.

Deeper questions:  How do you *find* a square root of $x$ mod $p$, if one exists?  Tonelli-Shanks (1891, 1973) algorithm, and Cipolla algorithm (1907).  We won't get there.

What about squares mod $m$, when $m$ is not prime?  1.  If GCD(a,b) = 1, then $x$ is a square mod $ab$ if and only if $x$ is a square mod $a$ and mod $b$.  Proof by Chinese remainder theorem.  

Next:  the lifting algorithm.  If $x$ is a square mod $p$, then $x$ is a square mod all powers of $p$ (if $p$ is odd, prime).  Example:  approximation.  Square roots of $2$ as a real number.  Square roots of $2$ mod $7$, to square roots mod $49$.  

## Fermat and sum of squares

The structure of a reciprocity law.  Reciprocities for variable $x$.  Is $x$ square mod $p$?  Is $p$ congruent to BLANK mod BLANK?  Example for $-3$.

Earlier reciprocities due to Fermat, 1654 letter to Pascal.

Can $p$ be expressed as the sum of two squares?  Yes, iff $p = 1$ mod $4$.  (Fermat to Mersenne, XMas 1640)
Can $p$ be expressed as $x^2 + 2 y^2$?  Yes, iff $p = 1,3$ mod $8$.
Can $p$ be expressed as $x^2 + 3y^2$?  Yes, iff $p = 1$ mod $3$.

One direction, via QR.  The other direction:
Claim:  If $p = 1$ mod $4$, then $p$ can be expressed as the sum of two squares.  First proven by Euler, 1752.

Lemma:  (Minkowski's thm)  If the area of the circle is at least 4 times the area of a parallelogram in a grid, then the circle contains a non-origin grid-point.  Take overlap point.  Unfold to get two points P and Q.  P = Q + 2 \lambda.  Q' = -Q in the circle.  Midpoint M = (P+Q')/2 = \lambda in the grid and in the circle.  

Thm:  (Fermat XMas Thm)  Suppose p = 1 mod 4.  Let u be an integer satisfying u^2 = -1 mod p.  Consider the lattice of points (x,y) satisfying x = uy mod p.  This is a grid of parallelograms, corners (0,0), (u,1), (p,0), (p+u,1).  Area = p.  Put a circle of area 4p at the origin.  Radius^2 = 4p / pi.  

Then there's a lattice point.  It satisfies x^2 + y^2 <= (4/pi) p and x = uy mod p.  Thus x^2 = - y^2 mod p.  So x^2 + y^2 is a multiple of p.  So x^2 + y^2 = p.  Done!

## Conclusion
