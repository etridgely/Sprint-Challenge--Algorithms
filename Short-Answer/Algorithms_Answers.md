#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Linear - O(n)
All that matters is the size of n, so it's linear.

b)  Polynomial - O(n^c)
There are two loops.  The complexity will increase as n increases, extending the loops runtime. Therefore, it's polynomial.

c) Linear - O(n)
Tricky.  At first, I thought it could be exponential.  Upon review, all that matters is how large bunnies is. That will dictate how many times it will loop through recursively.  0(n).

## Exercise II

We don't know what floor the eggs will break.  To solve this in the quickest time period possible, let's use a binary search tree.  We can randomly go to a floor 'r'.  When we arrive at floor r, we drop an egg.  If the egg breaks, we know we need to go down a few floors until it doesn't.  If the egg doesn't break, then we know we need to go up a few floors.  Rinse and repeat.  We'll quickly find which floor is 'f', the floor where eggs break.

Since it's a binary search tree, the runtime complexity is logarithmic, O(log n), which has terrific runtime complexity.
