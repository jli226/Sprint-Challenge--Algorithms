#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)
Linear time - O(n) it's reliant only on n. So as n gets bigger so too would the run time

b)
Polynomial time - O(n^2) there are two loops that are fully reliant on n, it would be O(n squared). Again, as n gets bigger, so would the run time.

c)
Linear time -O(n) the loop runs n times, which is one.

## Exercise II

use binanry search

f is number of floor the egg breaks n is n-story of the building

1. middle = (highest_floor - lowest_floor) /2 // find the middle floor drop an egg from it.
2. if middle == f // If the egg breaks, eliminates floors above.
3. elif middle < f // If the egg doesn't break, you can eliminate floors lower.
4. repeat the above process with the remaining floors until find the breaking floor.
