the basic idea of a limit is that we want to study the behavior of a function near a certain point without being influenced by its behavior at that point. 

if a function f is defined on an open interval around a point c (except possibly at c itself) and the values f(x) are arbitrarily close to a number L for all x-values sufficiently close to (but not equal to) c. 

here we use the Greek letter ("epsilon") to represent a (usually a very small) positive real number.

we use this number to create a "target" around the value y = L in the form of the open interval (L-E, L+E): we look for values of x near c such that the function value f(x) lands in the target and we say that the limit exists if:

no matter how small a target we are aiming for, we we can always find x-values in an open interval (a,b) containing c that all hit the target. 

![[Screenshot 2026-01-04 at 5.56.10 PM.png]]

example.

let E > 0. we want to find an open interval (a,b) containing x=1 such that for all x-values in this interval (excpet x=1 itself), the function values f(x) are inside the target (7-E, 7+E)

7-E < f(x) < 7+E

since we are excluding x=1, we can use the rule for f(x) for all x=/ 1:

7 - E < 3x+4 < 7+E

subtracting 4 gives, 3-E < 3x < 3+E
and dividing by 3 gives 1-(E/3) < x < 1+(E/3)

we have now proven the limit: for our choice of E, we found an interval (1-E/3, 1+E/3) of x-values, containing x=1, such that for every x-value in this interval except x=1, the function f(x) = 3x+4 lands in the E-target (7-E, 7+E) around 7. 

 if you take another look at the interval we found in the previous example, you'll notice that it has a very nice property: It not only contains the point x=1, but it is *centered* there-we travel the same distance of E/3 to both the left and right end points. 

 often useful to rewrite the definition given above such that you are looking for this distance, usually represented by the Greek letter & (delta).
 
 ![[Screenshot 2026-01-04 at 6.09.05 PM.png]]
