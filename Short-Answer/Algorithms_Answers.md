#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) Linear time O(n) the loop is only running linear based on n. it's reliant only on n. So as n gets bigger so too would the run time.

b) Polynomial time O(n \* n \* nk), for a given n. The for loop is dependent on n, the while loop is dependent on n, and multiplication is nk. Since the while loop is nest within the for loop,
you multiply the complexities, which give roughly `O(kn^3)`, where k is a constant.

c) `O(n)`, Linear time This is a recursive function that is just running like a loop. Its going to start at whatever value bunnies is until its -1 so its linear 0(n)

## Exercise II

use binanry search

f is number of floor the egg breaks n is n-story of the building

1. middle = (highest_floor - lowest_floor) /2 // find the middle floor drop an egg from it.
2. if middle == f // If the egg breaks, eliminates floors above.
3. elif middle < f // If the egg doesn't break, you can eliminate floors lower.
4. repeat the above process with the remaining floors until find the breaking floor.
