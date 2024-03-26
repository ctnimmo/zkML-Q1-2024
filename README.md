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