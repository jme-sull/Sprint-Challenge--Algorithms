#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Runtime is O(n), because for any given n, the while loop executes n times. This means that the runtime is linear.


b) Runtime is O(n*log(n)), because the inner loop increments by multiplication and the outer loop increments by addition, and both loops increment until they reach n.


c) Runtime is O(n) because the "loop" (not a loop but operates like one) decrements by subtraction, and does so the same number of times as there are bunnies.

## Exercise II

To solve this problem, pick any f in range of 0 to n and throw an egg. If the egg breaks, choose a lower f, if the egg doesnt break, choose a higher f. This has a runtime complexity of 0(log n)


