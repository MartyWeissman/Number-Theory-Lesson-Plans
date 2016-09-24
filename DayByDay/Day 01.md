# Day 1, September 22, 2016

## The Euclidean Algorithm

**Read before class:**  Skim Chapter 0. 

## Hook problem

(N.B.  Students don't yet have their coursepack, and so they haven't seen this problem from Chapter 1.)  

Problem:  You can hop 133 units left and right, and you can skip 85 units left and right.  If you start at zero, where can you go?  Can you travel from zero to one?  What's the smallest (nonzero) number you can get to, if you start at zero?

Students typically try a few approaches:
0.  Some students may have seen the Euclidean algorithm and recognize its utility here.  Have them wait... the point is to discover the Euclidean algorithm from scratch.
1.  Some will follow the problem literally, hopping and skipping (on paper) and *following their nose*.
2.  Many try setting up an equation like 133x + 85y = 1.  This has two problems:  it is underdetermined (one equation in two variables), and it doesn't deal with the problem that x and y must be integers.  So the *formulaic approach* doesn't work.
3.  A few students may list multiples of 133 and multiples of 85, in two rows/columns, and will search for a pair which differ by one.  This is a good *brute-force strategy*.
4.  Hopefully, a few students end up finding the *strategy of compound moves*.  One might say something like "If I can hop 133 and skip 85, then I can move back and forth by 48."  This leads to the solution of jumps,leaps,etc., given in the text.

I typically identify these four strategies by name, since all four are useful problem-solving strategies to recognize and they will come back later in the course.

## Course introduction and adminitration

Course website:  on Canvas.  Read everything there!  Chapter 1 will be posted just after class, and the coursepack should be at the Bay Tree Bookstore today/tomorrow.  Purchase it for around $40-45.

Expectations:  Timeliness.  Participation.  Consideration for each other.

Discussions begin Wednesday with Joe.  (Ask Joe to stand).  Attendance at discussions is mandatory and there will be a quiz in almost every one.  

Team homeworks and teamwork in discussion section.

## Related problem

Hopping 91 and skipping 49.  Can you go from 0 to 1?  Where can you go?  

This one goes more quickly, and leads to a more formal demonstration of the Euclidean algorithm (no more hops and skips).  

## GCD

Demonstration that the Euclidean algorithm leads to the GCD (in the strong sense).  

Comparison of the weak and strong definitions of GCD.  The Mantra.

Ask three students to come up with distinct 2-digit prime numbers:  p,q,r (but don't tell me!)  Have them compute x = pq and y = qr, and tell these numbers to me.  I'll compute q = GCD(x,y) with the Euclidean algorithm at the board.

----------------------

## History

Discussion of Euclid, Liu Hui, Aryabhata.  Why history?

A short discussion of the "mutual subtraction algorithm" in ancient Chinese texts, for reducing fractions.  Carry out example of reducing 49/91 with this algorithm -- this was the example used in the *Nine Chapters*.

## Solubility of LDE

Existence of solutions, as a theorem.

## Conclusion

We have used the Euclidean algorithm to demonstrate the existence of solutions to linear Diophantine equations.  Next time, we will find *all* solutions to LDEs and this will bring in the LCM.  Read Chapter 1 by next week.
