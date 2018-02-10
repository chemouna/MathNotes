
# Primes

## Prime Signature
The prime signature of a number is the multiset of exponents of its prime factorisation.
For example, all prime numbers have a prime signature of {1}, the squares of primes have a prime signature of {2}, 
the products of 2 distinct primes have a prime signature of {1,1} and the products of a square of a prime and a 
different prime (e.g. 12,18,20,... ) have a prime signature of {2,1}.

### Rules derived from prime signatur
Given a number with prime signature S, it is
- A prime number if S = {1}
- A square if gcd S is even
- A square-free integer if max S = 1
- A powerful number if min S ≥ 2
- An Achilles number if min S ≥ 2 and gcd S = 1
- k-almost prime if sum S = k.

