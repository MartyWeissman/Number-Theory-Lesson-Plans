# Day 16,  November 17, 2016.
## The many faces of sign.

**Read before class:**  Chapter 8

## Recollection of Zolotarev's Lemma.

Recall that we're studying signs of permutations and squareness mod p.  These are connected by Zolotarev's lemma.

We have seen two interpretations of the sign of a permutation.  Transpositions and cycle-lengths.  Let's connect them.

Before/after notation and cycle diagrams and cycle notation.

Composition of permutations

Sign of (transposition \circ permutation)
Sign as the parity of the number of transpositions.
The homomorphism property of sign.

## Inversions/derangements

We can also count the inversions in a permutation.  Between 1 and n-choose-2.

Theorem:  The sign is (-1)^(Inv(sigma)).  

## Conclusion

Goal:  Three permutations of (0,1,...,pq - 1).  \alpha, \beta, \gamma. Sign(\alpha) = (p/q) and Sign(\beta) = (q/p) and Sign(\gamma) = (-1)^(p-1/2 q-1/2).  And \gamma \circ \alpha = \beta.

Chinese remainder theorem:  Every element of S can be uniquely represented by [a,b] modulo [p,q].

\alpha sends [a,b] to aq + b
\beta sends [a,b] to a + bp.

\gamma sends aq + b to a + bp.
