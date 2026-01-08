Algebraic Rules for Sequences:
Assume that lim n -> infinity an = L, lim n -> infinity b n = M
	sums: lim n -> infinity a n + b n  = L + M
	 constant multiples: lim n -> infinity  c a n = cL
	 products: lim n-> infinity a n * b n = LM
	 quotients: lim n -> inifinity a n/b n = L/M (as long as M is not 0)

*Other ideas from 21A that apply:*

Thm (Sandwich or Squeeze): If {a n}, {b n}, and {c n} are sequences with a n <_ b n <_ c n and lim n -> infinity a n = lim n -> infinity c n = L, then lim n -> infinity b n = L as well. 

Ex. 
a n = ((-1)^n) 1/n : -1, 1/2, -1/3, 1/4

use sandwich thm to find the limit

c n = 1/n: 1, 1/2, 1/3, 1/4 = 0

b n = ((-1)^n) 1/n : -1, 1/2, -1/3, 1/4, ...

a n = -1/n: -1, -1/2, -1/3, -1/4 = 0

Since -1/n <_ (-1)^n 1/n <_ 1/n  with lim n-> infinity +-1/n = 0, lim n->infinity (-1)^n 1/n = 0 by Sandwich Theorem. 

in exams, if you are using sandwich theorem, state you are using the sandwich theorem

a n = (-1)^(n+1) 1/n
a 1 = (-1)^2 1 = 1
a 2 = (-1)^3 (1/2) = -1/2

Thm: If lim n->inifinity a n = L and f is continuous function, then lim n->infinity f(a n) = f(L)

If a n = f(n), when f is a function, then lim n->infinity f(n) = lim x->infinity f(x).
-this sets up L'Hospital's Rule for sequences 
lim n->infinity lnn/n --> infinity/infinity. L'H lim n-> infinity 1/n/1 = 0

This couldn't be applied to a n = (-1)^n since f(x) = (-1)^x is not a real-world function

**Common**

screen shot proof from 31 minutes ish from zoom recording. 



All of these sequences converge (have a limit)
what about sequences that diverge?

ex. a n = (-1)^n+1 : 1, -1, 1, -1, 1, -1, ...

insert ss from 3:47

-all of the points at -1 miss the epsilon target around 1


if one part of the a sequences converges to one limit, and the other part converges to another, they the overall sequence diverges. 

the sequence is nondecreasing if a sub n+1 >_ a n and nonincreasing if a sub n+1 <_ a n.
- monotonic if either of these apply

Thm: a monotonic and bounded sequence must converge

Ex. a n = 1/n: 1, 1/2, 1/3, 1/4, ..... converges
a n = (-1)^(n+1): 1, -1, 1, -1, 1 ... bounded but not monotonic
a n = n: 1, 2, 3, 4 ... not bounded but it is monotonic

monotonic means forever increasing/decreasing. 

a n = (-1)^n 1/n: -1, 1/2, -1/3 ...
- not monotnic but still converges. 
- 
