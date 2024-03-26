"# zkML-Q1-2024" 

Lesson 1:

Homework 1:

Question 1

Multiplicative inverses
For the set S = {0,1,2,3,4,5,6}
What is
a) 3 x 5
b) The multiplicative inverse of 3 ?


Assumptions: set S Z*7 i.e. a finite field of integers mod prime p (where p=7) with multiplicative inverses

a) 3 x 5 = 15 is 1 mod 7

b) To find, use the notes for Fermat's little theorem

This is useful for finding a multiplicative inverse

a^(-1) is a^(p-2)(mod p)

Let p = 7 and a = 2. 

Compute the (multiplicative) inverse of a i.e. (multiplicative) inverse of 2 (for this set):
a^(p-2) = 2^(7-2) = 2^5 = 32 is 4 mod 7

This is easy to verify: 2 x 4 = 8 [= (7x1) r 1] is 1 mod 7.

So answer to b, let a =3, then:
a^(p-2) = 3^(7-2) = 3^5 = 243 [= (7*34=238) r 5] is 5 mod 7 

verify: 3 x 5 = 15 is 1 mod 7 (so, should have spotted it from answer to Q1)

NOTE: multiplicative operation used to get identity i.e. 1 (mod 7) ... in this particular case

Question 2

Polynomials

For the polynomial x^3 - 2x^2 - 2x - 3
Find a positive root
What is the degree of this polynomial ?
Rewrite this in the form
(x - a). Q(x)

For now, educated guess, let x = 3.
3^3 - 2.3^2 - 2.3 - 3 = 27 - 2.9 - 2.3 - 3 = 27 -18 -6 -3 = 0 ergo 3 is (one possible) root
polynomial is of degree = 3 (spot: x^3)
rewrite:
a is a known root:
(x - 3)

workings:
(x-3).x^2 = x^3 - 3.x^2

x^3 - 2x^2 - 2x - 3 = (x^3 - 3.x^2) + (x^2 - 2x - 3) = (x-3).x^2 + (x^2 - 2x - 3)

(x-3).x = x^2 - 3.x

x^2 - 2x -3 = (x^2 - 3.x) + (x - 3) = (x-3).x + (x-3)

put it together:

x^3 - 2x^2 - 2x - 3 = (x-3).x^2 + (x-3).x + (x-3) = (x-3)(x^2 + x + 1)

check:
(x-3)(x^2 + x + 1) = x^3 + x^2 + x - 3.x^2 - 3.x - 3 = x^3 + (1-3)x^2 + (1-3)x - 3 = x^3 - 2x^2 - 2x - 3 

so answer to (x - a). Q(x) is (x-3)(x^2 + x + 1)