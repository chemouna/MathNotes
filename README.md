# MathNotes

### Computing Square root


### Pascal's triangle
 

#### Pascal's simplices.


#### Pascal's pyramid

## Combinatorics

### Inclusion–exclusion principle
the inclusion–exclusion principle is a counting technique which generalizes the familiar method of obtaining the number of elements in the union of two finite sets
|A union B|= |A|+|B| - |A Intersect B|
l
### Binomial coefficient
(n) is often read aloud as "n choose k", because there are {\displaystyle {\tbinom {n}{k}}} {\tbinom {n}{k}} ways to choose a subset of size k elements, disregarding their order, from a set of n elements.
(k)
-  it gives the number of ways, disregarding order, that k objects can be chosen from among n objects


### Catalan Numbers
In combinatorial mathematics, the Catalan numbers form a sequence of natural numbers that occur in various counting problems, often involving recursively defined objects.

The Catalan numbers on nonnegative integers n are a set of numbers that arise in tree enumeration problems of the type, "In how many ways can a regular n-gon be divided into n-2 triangles 
if different orientations are counted separately?

- The only Catalan numbers Cn which are odd are those for which n = 2^k − 1. All others are even.

Applications:
 - Cn is the number of Dyck words of length 2n. A Dyck word is a string consisting of n X's and n Y's such that no initial segment of the string has more Y's than X's 

 - Re-interpreting the symbol X as an open parenthesis and Y as a close parenthesis, Cn counts the number of expressions containing n pairs of parentheses which are correctly matched 

 - Cn is the number of different ways n + 1 factors can be completely parenthesized (or the number of ways of associating n applications of a binary operator). 

 - Successive applications of a binary operator can be represented in terms of a binary tree. It follows that Cn is the number of rooted ordered binary trees with n + 1 leave 

 - Cn is the number of monotonic paths along the edges of a grid with n × n square cells, which do not pass above the diagonal. A monotonic path is one which starts in the lower left corner, finishes in the upper right corner, and consists entirely of edges pointing rightwards or upwards. Counting such paths is equivalent to counting Dyck words: X stands for "move right" and Y stands for "move up".  

 - Cn is the number of noncrossing partitions of the set {1, ..., n}. A fortiori, Cn never exceeds the nth Bell number. Cn is also the number of noncrossing partitions of the set {1, ..., 2n} in which every block is of size 2.

- Cn is the number “mountain ranges” can you form with n upstrokes and n downstrokes that all stay above the original line 

- A robot is on the origin of a number line. It either walks to the right or left 1 unit in 1 step. But it cannot go to the negative numbers. The number of ways the robot can go back to the origin in 2n steps is Cn. 


The easiest way fto think about them is that the nth Catalan number C_n is the number of paths from one corner of an NxN lattice to the other without crossing the diagonal, This way, it's easy to see that the Catalan 
numbers also count the number of Dyck words (strings of balanced parentheses) of length n, replace every move to the right with a "(" and every move up with a ")".


### Rearrangement inequality
- The intuition is pretty simple, you want your multiplications to have the smallest overall impact; the biggest number is the one you will want to "sabotage" the most, so you multiply it with the smallest. 
  Then repeat with what's left...
 
