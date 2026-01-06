course introduction & sequences

Thomas's Calculus: Early Transcendentals (any edition)

all lecture's are recorded, come to class anyway

*sequences*

a sequence is an infinite list of numbers
	a1, a2, a3, ..., an

formally, this is a function whose domain is positive integers
	 n 1 2 3 4
	 a n 

eg. 
	 12, 13, 16, 18, 20, ... --> accumulation of +2 every iteration, repeated addition is multiplication 
	a n = 10 + 2n
		n=1: 10+2 = 12
		n=2 10+4 = 14 ...

(repeated multiplication is an exponential) 

some cases n=1 is better, some cases n=0. 

Q: Do the terms of a sequence approach a number as n gets very large?

Ex: a n = 1/n; 1, 1/2, 1/3, 1/4, ... list of numbers looks like they're approaching 0. 

Def: A sequence {a n} converges to a limit L if given E>0, we can find a number N such that if n>N, then a n is in the interval (L-E, L+E)

Idea: E establishes a target around L that we want the sequence to hit. 
	a n = 1/n, L=0, say E=1/2
			 |
		     |
		     | __ __ __ __ __ __
		     |
		     |
input graph from lecture...

for a general E:  we want 1/n < E
so we solve for n>1/E,
so we take N to be the integer greater than 1/E

establish a E target, and we want the terms of the sequence to be inside that target. 

this means that we can always ignore the beginning of the sequence

all limit ideas from Math 21A can be applied to sequences

eg. 