
# Concrete Mathematics 

## Finding closed forms for recurrences 

### Technique for recurrences of the type f(n) = a f(n−1) + b 
f(n) = −4f(n−1) + 3 for n > 1.  (1)
f(1) = 1
The idea is to make a substitution to replace f by a function g that grows exponentially. Let g(n) = f(n) − d for some as yet undetermined constant d, 
so that f(n) = g(n) + d. Substitute into the recurrence in (1) to get

g(n) + d = −4(g(n−1) + d) +3 = −4g(n−1) + 3 − 4d,

which simplifies to g(n) = −4g(n−1) + 3 − 5d. Now choose d so that 3 − 5d = 0, i.e., d=3/5; 
then g(n) = −4g(n−1), g(1) = f(1) − d = 2/5, and we can replace (1) with

g(n) = −4g(n−1) for n>1 
g(1) = 2/5               (2)

But (2) is trivial: it has the closed form g(n) = 2/5 (−4)^n−1. It follows that

f(n) = g(n) + d = 2/5 . (−4)^n − 1 + 3/5 = 3 − (((−1)^n) . 2^(2n−1))/5

